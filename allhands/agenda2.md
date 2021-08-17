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

<h2 id="meeting-july-21">Meeting - 21 July 2021 - (1100 ET) </h2>

### Agenda

1. **Welcome and introductions**
    - New format, less meeting more update 
2. **Groups**

| ID | CC | DIDAuth | DIDcomm | SDS | Sidetree | KERI | WalletSec |Crypto|
|---|---|---|---|---|---|---|---|---|
|**Interop**|**Prod managers**|**H&T SIG**|**Finance SIG**|**APAC/ASEA**|**Africa**| | | |


   * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
       * Chair election - ongoing, please vote (if you are at least somewhat active in the group) using this [link](https://docs.google.com/forms/d/e/1FAIpQLScG2mHq8bS9K8GXgLhjoJ4tbgMtnILMkzIK_CSv-cTRPGcdrw/viewform?vc=0&c=0&w=1&flr=0)
       * John Jordan - the ToIP vision and governance for decentralized identity
       * SSI and "eIDAS 2.0"
           * Martin Boender from Sphereon, Xavier from ValidatedID, Samuel from Gataca, and other guests 
           * EBSI is this about roots of trust or trust frameworks?
               * EBSI: European Blockchain Services Infrastructure
           * eIDAS 1.0 was Defining eIDs in a way that allows crossborder interop, 
               * Only 14/27 member states implemented
               * Protocol-level interactions were never really defined;  wallet controlling one of those eIDs doesn't have requirements or capabilities
               * Adoption stalled in many of those 14 countries- <5% of population in most of the 14 actually have and use these eIDs/eSigs
               * crossborder recognition was public-sector only 
           * the EU digital id & VC-holding wallets and EBSI should be seen as two distinct movements,
           * Memberstates still can chose to adopt, or fork, or betray whatever EBSI does 
               * could be interop nightmare
               *  chaos of independent implementations across EU is what they want to avoid this time around
           *  interop on what layer?
               *  DID layer is easy because did:ebsi; semantics/LD/ontology layer is what the universities are focusing on;
           *  here is the [EBSI documentation homepage](https://ec.europa.eu/cefdigital/wiki/display/EBSIDOC/EBSI+Documentation+Home) that gets updated regularly
       *  Report from the OIDF working groups with David Waite and Kristina Yasuda
           *  history of the past 12 years in identity world
               *  OAuth1, Oauth2, Keybase etc. 
           *  "Different kind of trust, can anchor with more sources of identity."
               *  Original OpenIDI didn't stop blog spam, because spammers could host their own OpenID providers. Could block them, but no reputation. Keybase no way to verify email addresses because no social network, no way to collaborate and share information. Twitter/LinkedIn could hypothetically verified my employment history, Keybase didn't get there. Didn't standardize their cryptography beyond PGP until Zoom bought them
           *  With SIOP, you do self-generated and pairwise keys - ephemeral, not rooted to anything. Like AuthN - doesn't prove relation with other things on internet, becomes Privacy-preserving: unlinkable. Can prove it's me: authentication.
           *   proposal on OpenID connect on verifiable presentations.
           *   Idea of user record in hosted application in single table demolished by authentication over the years.
           *   FIDO, WebAuthN: authenticators registered with account: have to be stored so can use them later.
           *   one of reasons I think that "Sign in with Google" is so attractive is that I expect their Google account to outlast my account - so I don't have to do recovery. 
           *   OIDF Interest in using VP as recovery scheme.
               *    e.g. using American driver license, issued by state, and can present it. Even if no attributes, if it has a pseudonymous identifiers, it enables me to log in. If they have documents, those become verifiable.
               *   If shared at registration time, becomes source of registration for recovery.
               *   to recover, lost trust relationship, restarting process, go through process costing companies a lot. If can use VP, that can help reestablish the trust relationship, can save calling, asking for secret questions, Mom's name, etc. 
           *   OpenID Connect for Verifiable Presentations
               *   Previous term: portable identifiers. For existing hosted provider, is there a way to include/assert DID ownership in challenge with other parties
           *   OpenID Connect Aggregated and Distributed Claims
               *   upstream credentials without defined retrieval mechanism. Potential overlap with Credential Manifest
           *   how to transport VP. Larger demand on transferring VP using any model, not just SIOP. What if Google wants to send a VP on behalf of me, based on access token.
               *   1: embed VP entirely in the id token
               *   2: send back VP from user endpoint
           *   company specific implementations how to to use the spec stack 
       *   NFC support - Passport NFC
   * **Identifiers & Discovery** (Markus, Alen) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
       * new time for UR calls, Wednesday 2 pm CET (8 am ET) as mostly european countries atten it
       * [Alen] EBSI Ledger and Trust 
            * European Blockchain Service Infrastructure
            * List of Trusted Registries
            * Registry Properties
            * Discussion about "Onboarding Service"
            * Discussion LoA, key security, eIDAS
            * Current Status of EBSI
        * [Daniel] Historical key resolution
           * A DID document could point to a hub, which contains a list of historical keys associated with the DID. This list is signed by a current DID controller key.
           * Using DID URLs, it should be possible to point to a specific historical key at a specific point in time, and it can be dereferences publicly by anyone.
           * See https://identity.foundation/identity-hub/spec/#did-relative-urls
           * Discussion around how can this be trusted
           * Advantage: This is method-independent.
           * Discussion on relation between this approach and KERI's Key Event Logs.
           * Discussion on implementing this in the Universal Resolver. 
           * The ID WG could start a new work item which defines the data structure of historical keys, as well as the format of DID URls that point to them.
       * Universal Resolver returning a key in a given format (e.g., JWK(S))
            * Discussions on [transform-keys DID URL parameter](https://github.com/decentralized-identity/did-spec-extensions/blob/master/parameters/transform-keys.md).
            * Specification is incomplete and needs more work. PoC has been implemented in Universal Resolver.
            * Parameter is registered in DID Spec Registries (which is a "note", not a "standard").
            * Discussion on trust boundaries and security implications of transforming keys in a DID document (only public keys!)
            * What are possible values? JWK, JWKS, base58, multibase, PEM, ...?
            * Discussion on this approach vs. use media types as in https://did.key.transmute.industries/.
       * discussion around Solid and DIDs
   * **Claims & Credentials** (Daniel, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md) 
      * Workitem Status: WACI-PEX
      * Workitem Status: PE (Maintenance) + Credential Manifest
      * Workitem Status: VC Marketplace
      * Discussion: Covid Vaccination Pass Story (Snorre Lothar von Gohren Edwin (Diwala))
      * PE issue-triage/discussion OIDF (date time)
  * **DID Auth** (Oliver, Kyle, Kristina) call under OIDF
  * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
      * PRs
        - [198](https://github.com/decentralized-identity/didcomm-messaging/pull/198) - typ/cty language
        - [200](https://github.com/decentralized-identity/didcomm-messaging/pull/200) - threading
        - [209](https://github.com/decentralized-identity/didcomm-messaging/pull/209) - sequencing extension
        - [211](https://github.com/decentralized-identity/didcomm-messaging/pull/211) - attachment format attribute
        - [212](https://github.com/decentralized-identity/didcomm-messaging/pull/212) - ECDH 1PU Draft 4
        - [225](https://github.com/decentralized-identity/didcomm-messaging/pull/225) - thid and pthid
        - [227](https://github.com/decentralized-identity/didcomm-messaging/pull/227) - sender key protection
    - DIDComm v2 library interface comparison (pack and unpack interface comparison)
        - DIDComm-rs - Rust - Jolocom (who?) Ivan
        - did-jwt/veramo - Typescript - Oliver
        - Go - Securekey - Baha
    - SICPA Support
        - Tracking Repo: https://github.com/sicpa-dlab/didcomm-gemini
- **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
    - EDV Dedicated Call
        - Once a data vault has been created, can the owner/controller of the data vault be changed? [22](https://github.com/decentralized-identity/edv-spec/issues/23)
        - Is the Data Vault Configuration stored as a (plain text) Document/resource or aa an EncryptedDocument in its data vault? [32](https://github.com/decentralized-identity/edv-spec/issues/32)
        - What should the allowed action/capability for querying an index be? [37](https://github.com/decentralized-identity/edv-spec/issues/37)
        - All examples must include complete JSON [38](https://github.com/decentralized-identity/edv-spec/issues/38)
        - Is the Data Vault Configuration stored as a (plain text) Document/resource or aa an EncryptedDocument in its data vault? [63](https://github.com/decentralized-identity/edv-spec/issues/18)
    - Identity Hub call
        - Attempt to form a PR-ready opinion about the associations between logical objects. Will the spec allow for both flat and tiered structures across logical objects? Can we specify it in such a way that other structures can be virtually overlayed on top? (ex: using extra optional properties in the DAG-JOSE header area)
        - How might such logical object associations determine how tracking of objects/sync works between instances?
        - Discuss top-level API work/proposals, including DID-relative URLs and object-centric normalization of invocations
-  **Sidetree WG** (Troy, Daniel) [meeting minutes](https://github.com/decentralized-identity/sidetree/blob/agenda/agenda.md)
    *  
* **KERI WG** (Sam, Charles) - [meeting page](https://github.com/decentralized-identity/keri/blob/master/agenda.md)
    *  IPR boundaries are difficult to navigate and understand - substantive contributions are blocked
    * Proposal to map out specifications of common tooling
        * CESR - pointers to relevant KIDs other than 001? possible subspec aligning TF work with KERI work?
            * - IIW [session notes](https://docs.google.com/spreadsheets/d/1ChIF0DeIFqvnM23XuCwwidRk_E7nRhDZg11RbIih_eI/edit#gid=0)
        * how to define “KERI-specific” subset of general-purpose version of CESR-- let’s start descriptively and address that later, though, it’s a big problem
        * input to the CESR spec might be [this straw man](https://hackmd.io/@dhuseby/BkG-4gp2u)
        * CESAR doesn’t work in strictly-typed languages; it was hard to implement in Rust
        * CESAR <> Sam's [CDE](https://hackmd.io/@dhuseby/BkG-4gp2u) encoding mechanism?
        * Roadmap proposal

* **Product Managers** - [meeting page](https://github.com/decentralized-identity/product-managers/blob/main/agenda.md)
    * IIW Special Topic virtual 1/2 day for product managers - July 22nd. I have a special code that is 30% off for all of you in this group - www.eventbrite.com/e/159946001797/?discount=DIFUX_30
    * Specification of eIDAS Toolbox still early. Definition of where this toolbox will be specified seems unclear.
* **Finance & Banking** - [meeting page](https://www.notion.so/dif/Meetings-a243fc1d22e2458b87381ef41b9bffb8)
    * 2. Kevin Tussy, CEO @ Facetec
* **Travel and Hospitality** - [meeting page](https://www.notion.so/dif/HOSPITALITY-TRAVEL-SIG-242105321e1747f8bce776bf634a55b3)
    * [Use Case Developed by Verifiable Credentials & Offers Team](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/d7611300-a440-4f33-8c7b-2b0d2c5da6e8/2021-07-08_Use_Case_-_Discount_Entitlement_-_Final.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210721%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210721T145957Z&X-Amz-Expires=86400&X-Amz-Signature=b94f179b7a75bb7958eb58a4166716777570bed143df5b30b960253a99723965&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%222021-07-08%2520Use%2520Case%2520-%2520Discount%2520Entitlement%2520-%2520Final.pdf%22)
    * [On-Demand Profile Element Sharing With Providers and Others ](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/7b88221e-8b7e-4837-bb37-1aeb51fa129c/2021-07-08_P1_-_Share_Profile_Elements_Use_Case_-_Final.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210721%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210721T150027Z&X-Amz-Expires=86400&X-Amz-Signature=7f8b83e6d56dddf4c3ff6ab64352c41e3ab549c9c9f44956daa8d631826813ab&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%222021-07-08%2520P1%2520-%2520Share%2520Profile%2520Elements%2520Use%2520Case%2520-%2520Final.pdf%22)
    * weekly 4 sub-group meetings 
        * [**Verifiable Credentials & Offers**](https://www.notion.so/Verifiable-Credentials-Offers-fa83440a49af4f508188b8279afc6d6e)
        * [**Travel Change & Disruption**](https://www.notion.so/Travel-Change-Disruption-2067e043fc434c2386fa2a35a5d4bae2)
        * [**KYC / Customer Profile / Loyalty**](https://www.notion.so/KYC-Customer-Profile-Loyalty-bd412ae7bb494170b3cae0c71674be41)
        * [**Government Sanctioned Credentials**](https://www.notion.so/Government-Sanctioned-Credentials-346c7d18fad149a99b10ff1e46bb1b53)
* **APAC/ASEAN**
* **Africa**


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
