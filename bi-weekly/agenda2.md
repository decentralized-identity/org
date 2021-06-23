# DIF all hands - open call


[**Website** ](https://identity.foundation ) | [Mailing list](https://lists.identity.foundation/) | [Old minutes](https://docs.google.com/document/d/1vVSGCxZ_YTluSUnwyUNwV74pd6cjLBL-n2ydht_5NyA/edit#) | [Meeting recordings](https://docs.google.com/spreadsheets/d/1wgccmMvIImx30qVE9GhRKWWv3vmL2ZyUauuKx3IfRmA/edit#gid=2039757024)


_For this call, you are encouraged to turn your video on. This is a good way to build rapport given we are a large, disparate group experiencing a lot of churn._

_This document is live-edited DURING each call, and stable/authoritative copies live on our github repo under /agenda.md. Please note that we might not notice a pullrequest in time, but you are free to propose agenda items for future meetings via hackmd._

<details>
<summary> Meeting information </summary>

* To participate - This is an open call, feel free to join and contirubute
* Time: every 4th Wednesdays, 11:00-12:00 ET
* [Calendar entry](https://calendar.google.com/event?action=TEMPLATE&tmeid=OWtzNWZuanA4bWRnYmF0ZnVxaDR0MnQ2cGVfMjAyMDA5MjFUMTgwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL)
* [Zoom room](https://us02web.zoom.us/j/81262437540?pwd=UW5ZZkxxTGZXc1RpbFVXTW5JNkdDUT09), Meeting ID: 812 6243 7540, Password: 212121 
</details>

# Meeting - 23 June 2021 - (1100 ET)

### Agenda

1. **Welcome and introductions**
    - New format, less meeting more update 
2. **Groups**

| ID | CC | DIDAuth | DIDcomm | SDS | Sidetree | KERI | WalletSec |Crypto|
|---|---|---|---|---|---|---|---|---|
|**Interop**|**Prod managers**|**H&T SIG**|**Finance SIG**|**APAC/ASEA**|**Africa**| | | |


   * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
       *  [IDUnion](https://idunion.org/?lang=en), [BMWi Schaufenster](https://www.digitale-technologien.de/DT/Navigation/DE/ProgrammeProjekte/AktuelleTechnologieprogramme/Sichere_Digitale_Identitaeten/Programm/programm.html), and new [interop targets](https://blog.identity.foundation/setting-interoperability-targets/) w/Hakan Yildiz
       *  Why do you need DIDs for SSI, with guest David Chadwick *(Verifiable Credentials Ltd., UK)*
           *  [CCG Thread](https://lists.w3.org/Archives/Public/public-credentials/2021Jun/0023.html) on VCs with non-DID identifiers: a recurring issue in this group!
           *  x509 as issuer ; "DID" for holder to express a key (did:key like encoding from [IETF RFC](https://datatracker.ietf.org/doc/html/rfc7519))
           *  "Protocols for VCs should not presume DIDs"
       *  [Good Health Pass](https://www.goodhealthpass.org/) Blueprint by Drummond Reed, Global Covid Certificate Network by Lucy Yang.
           *  Good Health Pass [Report and Interop Profile](https://wiki.trustoverip.org/display/HOME/GHP+Blueprint+Public+Review+Process) out now-- draft requested before 17 Jun!!
           *  [GCCN annoucement](https://www.lfph.io/2021/06/08/gccn/)
       *  WACI-PEx update (TBD)
 * **Identifiers & Discovery** (Markus, Alen) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
     * "controller" property in DID documents and verification methods.
         * "controller" on the top level seems clear, but on the "verificationMethod" is less clear.
         * "verificationMethod" can only have a single "controller", but verification methods can in fact be "controlled" by multiple entities (e.g. see the next topic - Verifiable Conditions)
         * See e.g. https://github.com/w3c/did-core/issues/697
         * practice we always have `did_document.id === did_document.verificationMethod[N].controller`
     * Updates from Verifiable Conditions - https://github.com/w3c-ccg/verifiable-conditions
       * We discussed https://github.com/w3c-ccg/verifiable-conditions/issues/3
       * Preference for second option ("Manu's proposal")
   * Review of [transform-keys DID parameter](https://github.com/decentralized-identity/did-spec-extensions/blob/master/parameters/transform-keys.md)
       * Outdated in various ways (e.g. matrix parameters, "publicKey" property), needs to be updated to match latest DID Core
   * Discussion on DHS request for comments on mDL:
       * [Minimum Standards for Driver's Licenses and Identification Cards Acceptable by Federal Agencies for Official Purposes; Mobile Driver's Licenses
](https://www.federalregister.gov/documents/2021/04/19/2021-07957/minimum-standards-for-drivers-licenses-and-identification-cards-acceptable-by-federal-agencies-for)
           * [Proposed Rules](https://www.govinfo.gov/content/pkg/FR-2021-04-19/pdf/2021-07957.pdf)
           * [Update](https://www.federalregister.gov/documents/2021/06/16/2021-12616/public-meeting-and-extension-of-comment-period-on-request-for-information-minimum-standards-for)
  * **Claims & Credentials** (Daniel, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md) 
      * Workitem Status: WACI-PEX
      * Workitem Status: PE (Maintenance) + Credential Manifest
      * Workitem Status: VC Marketplace
  * **DID Auth** (Oliver, Kyle, Kristina) call under OIDF
      * A/B Connect WG is hub of all this-- in DIF Calendar
      * SIOP V2
          * Progress on SIOP properties: https://hackmd.io/@dwaite/Hyg0vTZFd 
      * OIDC4VP

  * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
      * Discussion Topics
          * [Q3 Done Plan](https://hackmd.io/d9AYc6uWScOCWMrFLp-iwA)
              * Get the DIDComm v2 ecosystem “mature enough” to be adoptable by end of Q3 2021.
          *  Keys by Value or By ID
              *  [191](https://github.com/decentralized-identity/didcomm-messaging/issues/191) Issue
        - Sender Key/ID Encryption
            - Do we need to?
            - How is that done?
        -  Alternative Transport
            - Bluetooth (Timo at Animo)
            - NFC (Daniel at SICPA)
        - DIDComm v2 library interface comparison (pack and unpack interface comparison)
            - DIDComm-rs - Rust - Jolocom (who?) Ivan
            - did-jwt/veramo - Typescript - Oliver
            - Go - Securekey - Baha
    - PRs
        - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments
        - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
        - [185](https://github.com/decentralized-identity/didcomm-messaging/pull/185) - kid and skid headers
            - keys vs key refs
        - [195](https://github.com/decentralized-identity/didcomm-messaging/pull/195) - anoncrypt warning (updated)
        - [198](https://github.com/decentralized-identity/didcomm-messaging/pull/198) - typ/cty language
        - [200](https://github.com/decentralized-identity/didcomm-messaging/pull/200) - threading
        - [202](https://github.com/decentralized-identity/didcomm-messaging/pull/202) - refactor attachments
        - [206](https://github.com/decentralized-identity/didcomm-messaging/pull/206) - advanced sequencing
        - [205](https://github.com/decentralized-identity/didcomm-messaging/issues/205) - APU/APV values
- **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
    - 27th EDV Dedicated Call
        - Discussed Derek's batch API PR
        - Issue review (details captured in issues)
            - Deletion Semantics
            - Vault Deletion
            - Revisited JWE vs CWE format
        - Discussed Issue 
            - [Data Vault Configuration stored as?](https://github.com/decentralized-identity/edv-spec/issues/18)
            - [URL to a data vault vs privacy](https://github.com/decentralized-identity/edv-spec/issues/19 )
            - [Max structured document size](https://github.com/decentralized-identity/edv-spec/issues/22)
            - [change owner/controller of the data vault](https://github.com/decentralized-identity/edv-spec/issues/23 )
            - [Proposal update "edvs" route name](https://github.com/decentralized-identity/edv-spec/issues/36)
        - Opened Issues 
            - [correlation of server-visible information](https://github.com/decentralized-identity/edv-spec/issues/58)
            - [default root zcaps for EDVs](https://github.com/decentralized-identity/edv-spec/issues/59)
    - 
