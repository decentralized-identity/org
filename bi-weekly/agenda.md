# DIF bi-weekly - open call

[![hackmd-github-sync-badge](https://hackmd.io/sdTB8He_TASbNSJOSUdfvQ/badge)](https://hackmd.io/sdTB8He_TASbNSJOSUdfvQ)



[**Website** ](https://identity.foundation ) | [Mailing list](https://lists.identity.foundation/) | [Old minutes](https://docs.google.com/document/d/1vVSGCxZ_YTluSUnwyUNwV74pd6cjLBL-n2ydht_5NyA/edit#)

_For this call, you are encouraged to turn your video on. This is a good way to build rapport given we are a large, disparate group experiencing a lot of churn._

_This document is live-edited DURING each call, and stable/authoritative copies live on our github repo under /agenda.md. Please note that we might not notice a pullrequest in time, but you are free to propose agenda items for future meetings via hackmd._

<details>
<summary> Meeting information </summary>

* To participate - This is an open call, feel free to join and contirubute
* Time: bi-weekly Wednesdays, 11:00-12:00 ET
* [Calendar entry](https://calendar.google.com/event?action=TEMPLATE&tmeid=OWtzNWZuanA4bWRnYmF0ZnVxaDR0MnQ2cGVfMjAyMDA5MjFUMTgwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL)
* [Zoom room](https://us02web.zoom.us/j/313879009?pwd=dHZiSFlFUEYwVk91dEptaTAraTlBZz09), Meeting ID: 313 879 009, Password: 743522 
</details>

## Meeting - 11 Nov 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Additional Agenda items**
    * DIF F2F Virtual ~mid January 
        * [planning doc v1](https://docs.google.com/document/d/1GcTbLMixs_iaVAJpkNHEZl_c4LH9bH_vrNbe-2cL0GY/edit#)
    * Technical Steering Committee at DIF  (max 10 min)

3. **Groups**

    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * [The What and Why of the DIF general-purpose Document-Loader](https://youtu.be/-yUbMDft5O0)  - by Orie Steele
        * [W3C-CCG Edu Creds Task Force & Tooling/Sandbox Intro](https://youtu.be/AEb02JGCArM) (Overview of CCG LD tooling) -  Kim H Duffy 
        * Kaliya book presentation and the history of identity
        * Gold-Button Interop
        * Next call about BBS+ 
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * [DID WG meeting review during TPAC](https://docs.google.com/presentation/d/1RoE8E4y8S1j65EJaXZ8oihkduNbjTXXvdwtkzw961Xw/)
            * privacy violating properties
            * Abstract Data Model (ADM)
            * language that describes how to add and register new representations
            * Work on "security" and "privacy" in DID Rubric: https://github.com/w3c/did-rubric/pull/10
        * Fuzzy vault - C++? 
        * Updates on current work items did:peer, KERI, Universal Resolver, .well-known DID configuration, DID parameters, secret recovery mechanisms
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](hhttps://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Credential Manifest 
            * Reuse existing Presentation Exchange call time and shift focus towards Credential Manifest.
            * Review Daniel Status
        * IIW recap
        * Presentation Exchange Status
            * [Multiple Schema identifiers](https://github.com/decentralized-identity/presentation-exchange/pull/149)
            * [Holder Binding between credentials](https://github.com/decentralized-identity/presentation-exchange/pull/123)
    * **DID Auth** (Oliver, Kyle) *half hibernated state*
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://docs.google.com/document/d/1BpTm5SmgfOJcEsXfizO0ZmH1r7imTJDGKudAZtYsm0M/edit?usp=sharing)
        * Spec milestones
            * First Complete Draft reads completely by end of November
            * Next Complete Draft - Eliminate all TODOs
        * https://github.com/w3c/did-use-cases/pull/100
        * Switching to HackMD note taking from next week
        * Mime Types
            * [PR 124](https://github.com/decentralized-identity/didcomm-messaging/pull/124)
            * [Strategy Sheet](https://docs.google.com/spreadsheets/d/1VZz8J2Uz4nab-SY4pvhKd1_eipoEo9kGiqU5iaMYVsY/edit#gid=0)
        * PR/Issues:
            * Pick an issue you think can be closed
            * Pick an issue that shouldn’t be, and comment on what is needed next on the issue.
    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
    * **SDS WG** (Kaliya, Dmitry, Tobias)
        * GNAP Presentation by Justin Richer
            * [Filling in the GNAP - Justin Richer](https://justinsecurity.medium.com/filling-in-the-gnap-a032453eaf8c)
            * [OAuth 3](https://oauth.net/3/)
        * Spec Rename Update/Announcement (spoiler: Confidential Storage)
        * Special Topic Discussion: Integrating Hubs & Vaults in the spec


## Meeting - 28 Oct 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Additional Agenda items**
    * Impressions from IIW #31 
        * Sessions
            * OIDC connect propocols - "credential providers"/ Mattr, only for issuance
            * The new SIOP - OIDC way
                * comment: DIDcomm way is also very intersting
                * the two ways are complimentary
            * Scaling using zKP rollups + hiding state info
    * best sessions
3. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * last call of contributions on Transcommunity map
        * Crowd-sourcing an #IIW31 *Interop-relevant* Reading List
        * working draft [here](https://github.com/decentralized-identity/interoperability/blob/master/assets/iiw31guide.md)
        * host a special meeting focused on 
            * coordinate on JSON-LD/ZKP/BBS+ work(s)
            * cross ledger revocation
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page]
        * From IIW: did:indy https://hackmd.io/@icZC4epNSnqBbYE0hJYseA/S1eUS2BQw
        * From IIW: Opt-in discovery rather than passive discovery by Daniel Hardman
        * Websites and browser interactions 
        * Implementation updates
            * Implementing .well-known 
            * Python implementation of Fuzzy Vault is available now: https://github.com/decentralized-identity/fuzzy-encryption/tree/master/src/python
            * WASM bundle
        * Current topics in DID Core spec
        * Updates on current work items did:peer, KERI, Universal Resolver, .well-known DID configuration, DID parameters, secret recovery mechanisms
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * No major updates due to IIW
    * **DID Auth** (Oliver, Kyle) *half hibernated state* -
        * DIF - OIDF liaison agreement and collaboration 
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://docs.google.com/document/d/1BpTm5SmgfOJcEsXfizO0ZmH1r7imTJDGKudAZtYsm0M/edit?usp=sharing)
        * Milestones
            * First Complete Draft - reads correctly from beginning to end Oct 30th
            * Next Complete Draft - Eliminate all TODOs
        * DIDComm.org Progress
            * Repo exists
        * IIW Recap
            * DIDComm WG Update
            * DIDComm Mediators
            * Mark Miller talk - https://youtu.be/NAfjEnu6R2g
            * D Web - 
        * MIME Types for DIDComm PR 124 (Daniel Hardman)
        * PR/Issues:
            * Future Encoding
                * [PR 122](https://github.com/decentralized-identity/didcomm-messaging/pull/122)
                * [PR 121](https://github.com/decentralized-identity/didcomm-messaging/pull/121) - Queue Transport to return-route extension
                * [PR 123](https://github.com/decentralized-identity/didcomm-messaging/pull/123) - Outline adjustments
                * [PR 117](https://github.com/decentralized-identity/didcomm-messaging/pull/117) - Perfect Forward Secrecy details (Not updated yet)
    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * property renaming status 
        * Follow-ups
            * remove `verificationMethod` enum value in public key `purpose`
            * Align remove-public-keys and remove-services on use of `ids` property
            * Question: how do you change the purposes using patches?
        * Controller in patches
        * Compact JWS -> JSON JWS
        * Output the DID document according to the latest did-core spec (rename publicKey to verificationMethod)S
        * SIP 1
        * SIP 2
        * Canonical and equivalent identifiers status
        * Common protocol parameter format 
    * **SDS WG** (Kaliya, Dmitry, Tobias)
        * SDS meeting this week will feature Justin Richer talking about GNAP (formerly OAuth.XYZ) for people researching cutting-edge authorization/authentication 
4. **Discussion topics**
    * on Fridays we host DIF governance calls, feel free to join 


### Proposals
-proposals here-

### Attendees
- 

