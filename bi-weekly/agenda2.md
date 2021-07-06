# DIF All hands - open call

[![hackmd-github-sync-badge](https://hackmd.io/uMfiml4_QfmJFmgSZhmxdw/badge)](https://hackmd.io/uMfiml4_QfmJFmgSZhmxdw)



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
           *  Good Health Pass [Report and Interop Profile](https://wiki.trustoverip.org/display/HOME/GHP+Blueprint+Public+Review+Process) out now-- draft requested before 17 June
           *  [GCCN annoucement](https://www.lfph.io/2021/06/08/gccn/)
       *  WACI-PEx update 
       *  Identiverse (conference) update 



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
        - Universal Resolver 
        - DID Registration
  * **Claims & Credentials** (Daniel, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md) 
      * Workitem Status: WACI-PEX
          * next week restructure PR (going in) 
          * work continues apace, please open issues if anything is unclear and attend monday meetings!
      * Workitem Status: PE (Maintenance) + Credential Manifest
      * Workitem Status: VC Marketplace
          * Plugathon and interop-profile for participating companies
          * blog post (series) explaining the plugathon project forthcoming
  * **DID Auth** (Oliver, Kyle, Kristina) call under OIDF
      * A/B Connect WG is hub of all this-- in DIF Calendar
      * SIOP V2
          * Progress on SIOP properties: https://hackmd.io/@dwaite/Hyg0vTZFd 
          * [Stop using SIOP umbrella term?](https://bitbucket.org/openid/connect/issues/1239/we-should-stop-using-siop-as-an-umbrella)
      * OIDC4VP
          *  [DIF PE to OIDC4VP](https://bitbucket.org/openid/connect/pull-requests/20)

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
    - Identity Hubs
        - JOSE and CBOR agreement
        - Joel from 3Box/Ceramic gave an informative presentation on DAG-JOSE (JOSE-style tooling for IPFS)
        - Brooklyn from FISSION gave an informative presentation on Cryptree (a merkle-based file-system-like thing)
        - Implementers call (today) 10am PST 
*  **Sidetree WG** (Troy, Daniel) [meeting minutes](https://github.com/decentralized-identity/sidetree/blob/agenda/agenda.md)
    *  Adding update new form of equivalent ID 
        *  have more anchoring data in it 
            *  enables short IDs (7 digit short) / phone number lenght
* **KERI WG** (Sam, Charles) - [meeting page](https://github.com/decentralized-identity/keri/blob/master/agenda.md)
    * py implementation's use case and driving design decisions 
    * design process for TELs (txn logs/microledgers for VCs, smart contracts, or other verifiable data objects)
    * discussion of new, more detailed proposal did:indy:xxx:keri "tunnel" (re-registering indy DIDs as KERI AIDs and vice versa)
* **Product Managers** - [meeting page](https://github.com/decentralized-identity/product-managers/blob/main/agenda.md)
    * Keith Kowal proposed as a new chair for the group 💪
    * Credential payloads discussion
        * [Slides](https://github.com/decentralized-identity/product-managers/files/6607771/DIF.PM.Update.June.21.pdf) and [Recording](https://us02web.zoom.us/rec/share/wnkcrIpwjA_fqUdTjSdi-AxquhjEpkRl_aYr4KOgnRGuyD4FfBraMRwBTk5SliPc.4NoaZNFIxICZfk2b)
    * Events
        * User experience in SSI potential half day un-conference: July 22nd
        * Open Skills Network Conference - July (https://www.openskillsnetwork.org/)
        * ASU Digital Trust Summit today/tomorrow: https://uto.asu.edu/events/digital-trust-summit/agenda#DTS3
    * [eIDAS Update](https://ec.europa.eu/info/strategy/priorities-2019-2024/europe-fit-digital-age/european-digital-identity)
    * Potential demo from Lucas Czarnecki - credential design
* **Finance & Banking** - [meeting page](https://www.notion.so/dif/Meetings-a243fc1d22e2458b87381ef41b9bffb8)
    * Chris Kamier (Sustany) proposed as a new chair 
* **Travel and Hospitality** - [meeting page](https://www.notion.so/dif/HOSPITALITY-TRAVEL-SIG-242105321e1747f8bce776bf634a55b3)
    * Four weekly sub-group meetings: (Selected use cases to be taken to PoC given appropriate interest)
        * [Verifiable Credentials & Offers](https://www.notion.so/Verifiable-Credentials-Offers-fa83440a49af4f508188b8279afc6d6e)
        * [Travel Change & Disruption](https://www.notion.so/Travel-Change-Disruption-2067e043fc434c2386fa2a35a5d4bae2)
        * [KYC / Customer Profile / Loyalty](https://www.notion.so/KYC-Customer-Profile-Loyalty-bd412ae7bb494170b3cae0c71674be41)
        * [Government Sanctioned Credentials](https://www.notion.so/Government-Sanctioned-Credentials-346c7d18fad149a99b10ff1e46bb1b53)
    * Investigating adoption and/or development of H&T schemas to support documented use cases
    *  Good Health Pass Collaborative - to extend the interoperability blueprint focus beyond Interational air travel.
* **APAC/ASEAN**
* **Africa**



3. **Additional items**
    - F2F meeting timing: 
        - Considerations:
            - IIW33: Oct 12-14
            - mini-IIWs: July 22 and Aug 4
        - commnets: 
            - mid august onwards +1
            - september +1 - 7 or 14 are tuesdays, 1Sept (Wed)
    - Asia event
        - asia time-zone friendly meeting 
        - China/Asia session as part of F2F?
            - Or, hold second F2F with EU/APAC hours (sorry, america)?
            - Or, ALTERNATE US/EU and EU/APAC F2Fs (+2 from the Europeans, hehe)
        - middle-of-the-night sessions day before or after F2F? (//IIW)
        - Discuss what would be good for them? 
        - community to be more appreciative and get different regiouns involved 
            - reuse material (if possible)
    - 
