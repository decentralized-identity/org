# DIF bi-weekly - open call

[![hackmd-github-sync-badge](https://hackmd.io/sdTB8He_TASbNSJOSUdfvQ/badge)](https://hackmd.io/sdTB8He_TASbNSJOSUdfvQ)



[**Website** ](https://identity.foundation ) | [Mailing list](https://lists.identity.foundation/) | [Old minutes](https://docs.google.com/document/d/1vVSGCxZ_YTluSUnwyUNwV74pd6cjLBL-n2ydht_5NyA/edit#) | [Meeting recordings](https://docs.google.com/spreadsheets/d/1wgccmMvIImx30qVE9GhRKWWv3vmL2ZyUauuKx3IfRmA/edit#gid=2039757024)


_For this call, you are encouraged to turn your video on. This is a good way to build rapport given we are a large, disparate group experiencing a lot of churn._

_This document is live-edited DURING each call, and stable/authoritative copies live on our github repo under /agenda.md. Please note that we might not notice a pullrequest in time, but you are free to propose agenda items for future meetings via hackmd._

<details>
<summary> Meeting information </summary>

* To participate - This is an open call, feel free to join and contirubute
* Time: bi-weekly Wednesdays, 11:00-12:00 ET
* [Calendar entry](https://calendar.google.com/event?action=TEMPLATE&tmeid=OWtzNWZuanA4bWRnYmF0ZnVxaDR0MnQ2cGVfMjAyMDA5MjFUMTgwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL)
* [Zoom room](https://us02web.zoom.us/j/81262437540?pwd=UW5ZZkxxTGZXc1RpbFVXTW5JNkdDUT09), Meeting ID: 812 6243 7540, Password: 212121 
</details>

# Meeting - 31 March 2021 - (1100 ET)

### Agenda

1. **Welcome and introductions**
    * Summer time zone misery is over. 
* 2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md) 
        * Machine readable governance framework straw man (Telegramsam)
        * Trust frameworks at ToiP (Sankarshan)
        * The interoperability interop meeting 
            * SVIP plugathon report-out 
                * [Slides and demo/videos from SVIP event last week](https://docs.google.com/presentation/d/1MeeP7vDXb9CpSBfjTybYbo8qJfrrbrXCSJa0DklNe2k/edit?usp=sharing)
                - [VC-HTTP-API](https://github.com/w3c-ccg/vc-http-api) specification used in recent SVIP plugathon (more detailed documentation forthcoming)
                - [CHAPI test suite](https://github.com/w3c-ccg/chapi-interop-test-suite) recently updates as well
        * Recently-launched public website for tracking cross-agent testing in the [Aries test harness](http://aries-interop.info/)
        * [Guided tour](https://www.youtube.com/watch?v=cWPiJrVKj-U) of iGrant.io's Aries Testing Journey and their open-sourced [Aries Interop Playground](https://hackmd.io/K5BWQ_rvSTKJ-BxeWINYfw?edit)
        * [Interop Testing Survey](https://forms.gle/KTwPkfcJujZEKuzk8) in support of DIF Member Gataca's [Verifier Universal Interface](https://gataca-io.github.io/verifier-apis/) (done through the interop program of ESSIF-LAB)
        * Cross-Industry plug-a-thon? Smaller than profiles
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * Review and discussion of DID WG test suite: https://github.com/w3c/did-test-suite/
        * Timeline and what the current ["CR"](https://docs.google.com/presentation/d/1nSLk3cwJ8CanDoMLsO_JS3-ltBEeM8HZVXSsAZbrIl4/) state means 
        * Policies of DID Spec Registries from last few DID WG calls:
        * [JackT] Updates on "VerifiableCondition" https://github.com/Gimly-Blockchain/verifiable-conditions
   * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
       * Presentation Exchange 
           * **Ratification of v1.0.0: "Workgroup-approved Status"**
           * next steps 
       * Credential Manifest
           * Still going through some scoping / requirement engineering.
           * Should CM support to output multiple credentials.
           * Presentation of current resolutions
       * VC marketplace
           * Moving it into Spec-up format
           * Filling the determined UC Categories with more content.
       * quick overview [UVI](https://gataca-io.github.io/verifier-apis/) (Essiflab)
    * **DID Auth** (Oliver, Kyle, Kristina) half hibernated state
        *  DIF-OIDF joint meetings - follow along on the [bitbucket](https://bitbucket.org/openid/connect/issues) issues if the timing doesn't work for you!
            *  Special calls on SIOP taking place under OIDF. (incl. in DIF calendar)
            *  On 29th April SIOP/DIF will be represented by Kristina at the OIDF workshop.
    *  **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        *  PRs
            - [170](https://github.com/decentralized-identity/didcomm-messaging/pull/170) - Restructure to solve image display issues.
            - [172](https://github.com/decentralized-identity/didcomm-messaging/pull/172) - Fix inconsistencies with to/next attributes in a forward message. 
            - [171](https://github.com/decentralized-identity/didcomm-messaging/pull/171) - media type discussion
            - [167](https://github.com/decentralized-identity/didcomm-messaging/pull/167) - accept property
            - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
                - [Encrypted Attachments](https://hackmd.io/jx8W0boDSzmLe2r6LKQU5w) 
        - Issues
            - [165](https://github.com/decentralized-identity/didcomm-messaging/issues/165) - cty of JWM
            - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. - awaiting PR
    *  **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
        *  Confidential Storage Specification Refactoring
    *  **KERI WG** (Sam, Charles) - [meeting page](https://github.com/decentralized-identity/keri/blob/master/agenda.md)
    *  **Product Managers** - [meeting page](https://github.com/decentralized-identity/product-managers/blob/main/agenda.md)
        *  Events & conferences 
            * GS1 US Digital Innovation Conference (March 30th / sign up by March 26th) [Details](https://web.cvent.com/event/5c5e5d0e-08b5-49f9-8f5e-c115c031b729/summary)
        *  DHS SVIP Interoperability update (10 mins) 
            * [Deck](https://docs.google.com/presentation/d/1MeeP7vDXb9CpSBfjTybYbo8qJfrrbrXCSJa0DklNe2k/edit#slide=id.p1)
            * [Transmute post](https://medium.com/transmute-techtalk/interoperability-is-not-a-choice-387d57c6dc32)
    *  **Healthcare** 
        * delayed meetings until April
    * **Finance & Banking** - [meeting page](https://www.notion.so/dif/Meetings-a243fc1d22e2458b87381ef41b9bffb8)
        * Alex David, Global Business Development Manager @ Raon

3. **Additional Agenda items**
    * Wallet Security WG is looking for Chairs (interim)
    * **[IIW is coming up](https://internetidentityworkshop.com/)** 
        * Use this coupon code for **20%** off: **DIF_XXXII_20**
    * DIF Governance Operating Addendum
        * SC election is coming up
    * [Documentation Corps](https://docs.google.com/document/d/1AczRHKJOx4hNMr6TmCDcN4XfXB1Pm6213BbQqPcKXJc/edit) 



# Meeting - 17 March 2021 - (1100 ET)

### Agenda

1. **Welcome and introductions**
    * [Presentation Exchange](https://identity.foundation/presentation-exchange/) v1.0.0!! 
    * +1 summer time zone misery 😭
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md) 
        * Justin Richter & Adrian Gropper on  newest [GNAP core spec](https://www.ietf.org/archive/id/draft-ietf-gnap-core-protocol-04.html)
            * GNAP = Grant Negotiation and Authorization Protocol
                * _Defines a mechanism for delegating authorization to a piece of software, and conveying that delegation to the software. This delegation can include access to a set of APIs as well as information passed directly to the software._
            * Naïve version: everyone is their own AS 
            * "Token factory" verion
            * Fancy version 
        * NGI report on disposible identites - postponed
        * Discussion on Micro-Grant/Implementation-Bounty setting by DIF for the community. (ideation and planning)
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        *  discussion on multisig and delegation in DID methods
            *  review of https://github.com/Gimly-Blockchain/verifiable-conditions
            *  discussion on advanced verification methods involving smart contracts, etc.
        *  new did:solid method (but not related to Solid) but identitydotcom
        *  Solana blockchain discussion
        *  member run universal resolver: https://did.civic.com/
        *  Universal Registrar discussion
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * **[Presentation Exchange](https://identity.foundation/presentation-exchange/) - v1.0.0 status** - WOW! 
        *  Credential Manifest
            *  Extract Styling Spec
        *  VC Marketplace
            *  How will the VCM handle registration crawling
        *  LDAP VC method status
    *  **DID Auth** (Oliver, Kyle, Kristina) half hibernated state
        *  DIF-OIDF joint meetings - follow along on the [bitbucket](https://bitbucket.org/openid/connect/issues) issues if the timing doesn't work for you!
            *  Special calls on SIOP taking place under OIDF. (incl. in DIF calendar)
        *  On 29th April SIOP/DIF will be represented by Kristina at the OIDF workshop.
    *  **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        *  - PRs
            - [171](https://github.com/decentralized-identity/didcomm-messaging/pull/171) - media type in envelope
            - [157](https://github.com/decentralized-identity/didcomm-messaging/pull/157) - JSON-LD Context (conflicts)
            - [166](https://github.com/decentralized-identity/didcomm-messaging/pull/166) - Curve P-384
            - [167](https://github.com/decentralized-identity/didcomm-messaging/pull/167) - accept property
            - [161](https://github.com/decentralized-identity/didcomm-messaging/pull/161) - Attachments WIP
                - [Encrypted Attachments](https://hackmd.io/jx8W0boDSzmLe2r6LKQU5w)
        - Issues
            - [165](https://github.com/decentralized-identity/didcomm-messaging/issues/165) - cty of JWM
            - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages. - awaiting PR
        - Discussion
            - Peer DID Method 2 - [pull 26](https://github.com/decentralized-identity/peer-did-method-spec/pull/26)
    * **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
        * [Secure Data Storage Features](https://hackmd.io/qClYLUPkQ7uf0r3_4O7BUQ)
            * EDV Client Features
            * EDV Server Features
            * HUB Features
            * Decentralized Twitter (Dewitter) Requirements List
                * Assumptions, Principles, Requirements, and Other Considerations
    * **KERI WG** (Sam, Charles) - [meeting page](https://github.com/decentralized-identity/keri/blob/master/agenda.md)
        * Keri is moving from a first-cut "promiscuous mode" proof of concept to the next stage of development: securing an internal interface for local events to protect a controller's authoritative key event log from external events and receipts contaminating it.
            * partly, this entails designing a query mechanism for communicating requests for key events that manages the multisig escrow and the duplicity-detection log
            * key threads to follow on github are the [Query Mode discussion](https://github.com/decentralized-identity/keri/issues/109) (a whopper!), the broader [roadmapping thread](https://github.com/decentralized-identity/keri/issues/108), and a conceptual/mental-model alignment thread on how the concept of the transaction-event log "TEL" is [evolving](https://github.com/decentralized-identity/keri/issues/118) as KERI gets more complex and starts layering on security, duplicity-detection, multi-sig, etc.
    * **Product Managers** - [meeting page](https://github.com/decentralized-identity/product-managers/blob/main/agenda.md)
         * Discussion on Wallet Security WG
         * Product intros:
             * GlobaliD
             * Serto
    * **Healthcare** 
        * delayed meetings until April
    * **Finance & Banking** - [meeting page](https://www.notion.so/dif/Meetings-a243fc1d22e2458b87381ef41b9bffb8)
        * no meeting since last bi-weekly
3. **Additional Agenda items**
    * Wallet Security - soon a WG, attend next week's meeting to close all outstanding comments on the charter. 
    * Hospitality & Travel SIG still [chartering](https://docs.google.com/document/d/1uYlz3oVBDz-HKEtyO5CsCM1g3uhPxryy/edit) and holding exploratory meetings to tease technical requirements out of use cases founding members have been working on
    * **DIF Grants/Bounties/founded challenges** 
        * [Proposal](https://docs.google.com/document/d/1MQllNfFvC3PiVi5jo_kT6OCq9w3_GoEGWjZb-0pwuys/edit) for managing it




# Meeting - 3 March 2021 - (1100 ET)

### Agenda

1. **Welcome and introductions**
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md) 
        * Revocation Mechanisms - Mike Lodder and Revocable BBS+
            * Non-Private Methods, Pseudonymous Methods, Anonymous Methods, Indy Style, Merkle trees w/circuit proofs, RSA, Bilinear Maps Accumulators, 
            * Revocation is just difficult mathematically to scale
            * Mike is also working on a bearer-token/passwordless auth system as well
        * Manu gave a presentation (earlier today) about the W3C / CCG long term plans 
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * Updates on progress on DID Core in W3C DID WG - Discussion around data model and representations, e.g. see
        * Controller, verification methods, authorization in DID Core - See issues in DID Core
        * Presentation by Jack about EOS chain and larger EOSIO ecosystem
            * Detailed discussions about multi-sig verification methods and delegation methods
            * Consensus that a new **cryptosuite** should be defined (as a work item in W3C CCG or DIF)

    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * [Presentation Exchange](https://identity.foundation/presentation-exchange/) aims to reach WG approved level next week
            * Next Monday - it will reach WG approved status unless last issues are raised
        * [Credential Manifest](https://github.com/decentralized-identity/credential-manifest) - how issuers differ from verifiers in their publication needs and mechanisms
        * [VC Marketplace](https://github.com/decentralized-identity/vc-marketplace) - VC business-model/marketplace-use-case sandbox/discussion group! Detailed discussions not just about payment and incentivization but also discovery mechanisms, semantic definition/propagation
    *  **DID Auth** (Oliver, Kyle, Kristina) half hibernated state
        *  DIF-OIDF joint meetings - follow along on the [bitbucket](https://bitbucket.org/openid/connect/issues) issues if the timing doesn't work for you!
            *  Special calls on SIOP taking place under OIDF. (incl. in DIF calendar)
        *  SIOP "laundry list" by Kyle
            *  selfissued.me was a limitation
    *  **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        *  PRs
            - [166](https://github.com/decentralized-identity/didcomm-messaging/pull/166) - recommending P-384 over P-256 in DIDComm handshake/channel-security
            - [157](https://github.com/decentralized-identity/didcomm-messaging/pull/157) - JSON-LD Context
            - [160](https://github.com/decentralized-identity/didcomm-messaging/pull/160) - Remove old queue reference/TODOs
        - Issues
            - [162](https://github.com/decentralized-identity/didcomm-messaging/issues/162) - Rewrapping forwarded messages.
            - [159](https://github.com/decentralized-identity/didcomm-messaging/issues/159) - Which keys are used for encryption.
        - Discussion Topics
            - Peer DID Method 2: https://github.com/decentralized-identity/peer-did-method-spec/pull/26
            - P384 discussion lead by Troy
    - **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        - [**Sidetree v1.0.0**](https://identity.foundation/sidetree/spec/) 
        - ION dashboard demo
        - Open PRs
        - Tag spec v1.0. Agreed to tag EOD today.
        - Spec followup: need to add references.
        - Discussion of v1.1 (time permitting)
    - **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
         * Discussion about [Identity Hub Requirements](https://hackmd.io/qClYLUPkQ7uf0r3_4O7BUQ?view)
         * Once it is done then the focus is on EDV Specs 
     * **Product Managers** 
         * DIF updates - Wallet Security WG
         * Key Management (part 2), part 1 [summary here](https://whimsical.com/dif-product-manager-topics-GTPeiBy3qQ7DBNTSqDZiZ5)

    * **Healthcare** 

    * **Finance & Banking** 
        * General planning for 2021
        * Wallet Security WG's relationship to the SIG
        * Discussion on wallets for the Banking sector
        * AOBs
        *  __"portable KYC paper from EEA"__
            *  reached out to the group
            *  reworded [problem statement](https://github.com/sustany/dvg/wiki/Problem-Statement-Framing)

3. **Additional Agenda items**
    * **Wallet Security kickoff** - [register](https://forms.gle/A391WWLYWxMHZ7qt6) for next week or listen to recording
    - __Biweekly Topic: Travel and Hospitality SIG Proposal__
        * Some new members will be taking input on their [draft charter](https://drive.google.com/file/d/133WJ3RrviGBl7ppPNgo-dilZu9Xq3osY/view?usp=sharing) for a SIG looking at what industry-specific problems and power structures could gain from decentralized identity solutions for customer information and data flows. [**Register here**](https://forms.gle/87na2GD58v9PSbmd8) - 11th March, Thursday, 10 am ET.
    *  __DIF Africa call kickoff__ 
        *  Takes place tomorrow at 8am GMT+1
    *  __#documentation-corps__ <- slack channel 
    *  __IIW is coming up April 20-22__




# Meeting - 17 February 2021 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * Last week: Intro to the Revocation Topic (first in a series- Martin Riedel gave a very even-handed overview of pros and cons of the three main types of status-check mechanism, and gave examples of each. Future sessions will cover proposed new mechanisms by DIF members, and some might even be led by guest-host Andreas Freitag, who is looking at how to evaluate them objectively against something like the DID-Rubric!
        * Today: Recently registered DID Methods- DID:Orb and DID:Tezos, with a discussion of how to design and specify and register future methods
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * Updates on Fuzzy Encryption project (C++ implementation released!), KERI (WG Charter pending SC approval)
        * DID-Dillo project- lightweight in-browser DIDKit build for resolving DIDs locally with UR fallback. 300kb microbrowser can run on a flipphone!
        * Helpful overview of DID Method registration process, multi-signature and verification method mechanics
        * Universal Registrar/Resolver & DIDComm: interesting work item afoot   
        * DID-Core update: Daniel Burnett gave a report 3 weeks ago at [interop WG](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md#agenda---3-feb-2021---useu-time-0600-pt---update-on-did-core-and-enterprise-ethereum-alliance-d-burnett-and-did-interop-fundamentals-markus-sabadello-and-guests), and Markus will give a more recent one next week

    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Gabe Cohen has had to step down from chairship, but will still be involved in specific work items. His colleague Daniel McGrogan has been nominated.
        * Presentation Exchange is in final-final [editorial](https://identity.foundation/presentation-exchange/), and ready for review! 
        * VC Marketplace is still accepting use-case proposals, get in touch if you're interested in their VC business-model/marketplace-use-case sandbox/discussion group! Detailed discussions not just about payment and incentivization but also discovery mechanisms, semantic definition/propagation, etc, so bring your questions and use-cases and [get involved](https://github.com/decentralized-identity/vc-marketplace)!
        * [Credential Manifest](https://github.com/decentralized-identity/credential-manifest) still booting up and scoping, not too late to get involved if you're interested in how issuers differ from verifiers in their publication needs and mechanisms
        * Poke around the new work item [Schema Forms](https://github.com/decentralized-identity/schema-forms)- not an official work item, mostly just Daniel Buchner open-sourcing a open-ended project for JSON Schema form definition

    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * DIF-OIDF joint meetings - follow along on the [bitbucket](https://bitbucket.org/openid/connect/issues) issues if the timing doesn't work for you!

    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * Major open PRs: [#157 - JSON-LD Context](https://github.com/decentralized-identity/didcomm-messaging/pull/157) 
        * PRs merged or closed: [DID-use-cases #messaging](https://w3c.github.io/did-use-cases/#messaging), [Editorial PR #160](https://github.com/decentralized-identity/didcomm-messaging/pull/160)
        * Issues discussed: [159 - Which keys are used for encryption](https://github.com/decentralized-identity/didcomm-messaging/issues/159), [did-core #599](https://github.com/w3c/did-core/issues/599)
        * Ongoing work items on sample implementation of [DIDComm-rs](https://github.com/decentralized-identity/didcomm-rs) & extension spec+implementation of [DIDComm-bluetooth](https://github.com/decentralized-identity/didcomm-bluetooth)
        * Coming soon- extensions for the [DID Spec registry](https://www.w3.org/TR/did-spec-registries/#service-properties)... or... [not](https://github.com/w3c/did-spec-registries/issues/125)?

    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * home stretch of WG-internal "spec v1" PRs and discussions-- only [7 open issues tagged "v1"](https://github.com/decentralized-identity/sidetree/issues?q=is%3Aissue+is%3Aopen+label%3A%22Spec+v1%22) left! will be calling for wide review in a week
        * new Sidetree-based DID method: [did:orb](https://trustbloc.github.io/did-method-orb/) was discussed on interop 2 hours ago, check Slack for the recording!

    * **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
         * use-cases discussion for better defining identity hub/EDV boundary and division of labor
             * Replication Discussion
                 * [notes](https://lists.identity.foundation/g/sds-wg/wiki/25267)
         * second half of use-case list tomorrow 
    
    * **Product Managers** - KMS and UX
        * Next session: round 2

    * **Healthcare** - FHIR-->LD VC translation
  =

    * **Finance & Banking** - Guest presentation on AML
        * next meeting is a working session

3. **Additional Agenda items**
    - Wallet Security WG
        - [Draft charter](https://docs.google.com/document/d/18H2hVjHZEBjbnzod8tLogJIEzySdecbk9d-QBJaqHP0/edit) 
            - Questions:
                - Should there be consideration for SaaS wallet as well as standalone?
VC file formats: https://lists.w3.org/Archives/Public/public-credentials/2021Feb/0000.html
                - Does the WG is focusing on best practices or evaluation? 
                - Adding a use case index as a part of the WG? (similar to VC EDU) - https://docs.google.com/document/d/1vjrvwmvHOYmJd_Dqwk_TfGjKLTiTe9fzX9J4QqCUcf0/edit#
                - Who would be interested to co-chair? 
                - mailing list - https://lists.identity.foundation/g/wallet-security
     - #DIF-Gov update - operating addendum iterated and ready to go, but implementation details such as appointment/election calendar and transitions still to be worked out. Come friday if such details interest you!


# Meeting - 3 February 2021 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
    -  Hakan Yildiz (TU Berlin)
    -  Michael Herman (Trusted Digital Web)
    -  Paul Bastian (Bundesdruckerei)
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * Origianal Context:
            * Mitre, Carin, and Common [press release](https://www.businesswire.com/news/home/20210114005294/en/Broad-Coalition-of-Health-and-Technology-Industry-Leaders-Announce-Vaccination-Credential-Initiative-to-Accelerate-Digital-Access-to-COVID-19-Vaccination-Records)
        * Discussions
            - eparation of concerns where for protocols and data models
                - authorization and messaging as yin and yang?
                - diversion through didcomm
        - Dan Brunett: DID-core presentaion and ETH Entr. Alliance
        - Markus: potential multi VC format representation
        
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * Integration between [ACA-py](https://github.com/hyperledger/aries-cloudagent-python/)/[Veramo](https://github.com/uport-project/veramo)/[aries-framework-go](https://github.com/hyperledger/aries-framework-go/) and [Universal Resolver](https://github.com/decentralized-identity/universal-resolver/).
            * DID write operations in Aries-framework-go, in Veramo, in Universal Registrar
            * Discussion around "trusted endpoints" for DID methods
        * discussion on DID CRUD operations, including architectures, interfaces, implementations (such as Universal Resolver/Registrar, ACA-py, aries-framework-go, Veramo, DIDKit)
            * Introduction to DIDKit
            * Discussion on architectures of DID registration software
            * Discussion around government-approved cryptography, and adoption of DIDs.
        * Consider proof-of-control
        * KERI WG charter is being finalized 

    
    
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Presentation Exchange is waiting for the last PR
        * 

    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * 

    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * DID Registry DIDComm service types
        - DID Use Cases
            - Extended discussion: https://github.com/w3c/did-use-cases/pull/126
            - New PR: https://github.com/w3c/did-use-cases/pull/139
            - New PR Preview: https://pr-preview.s3.amazonaws.com/w3c/did-use-cases/pull/139.html#messaging
        - PRs
            - [140](https://github.com/decentralized-identity/didcomm-messaging/pull/140)
        -  DIDCom V2 Library - Rust (donated by Jolocom
            -  https://github.com/decentralized-identity/didcomm-rs
        - Walkthrough and Q&A
            - [Localization](https://hackmd.io/Bcomd6hqTVOVh7oWjlo6kQ)
            - [Attachments](https://hackmd.io/zPQHVHtpTiShXG64TYHyiQ)

    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * ion v1
        * issue reviews and editorial PRs for spec v1
        * fyi: new Sidetree-based DID method: [did:orb](https://trustbloc.github.io/did-method-orb/) 

     * **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
         * discussion:
             * Replication Discussion
                 * [notes](https://lists.identity.foundation/g/sds-wg/wiki/25267)

3. **Additional Agenda items**
    - Wallet Security WG
        - [Draft charter](https://docs.google.com/document/d/18H2hVjHZEBjbnzod8tLogJIEzySdecbk9d-QBJaqHP0/edit) 
            - Question:
                - Should there be consideration for SaaS wallet as well as standalone?
VC file formats: https://lists.w3.org/Archives/Public/public-credentials/2021Feb/0000.html
                - Does the WG is focusing on best practices or evaluation? 
                - Adding a use case index as a part of the WG? (similar to VC EDU) - https://docs.google.com/document/d/1vjrvwmvHOYmJd_Dqwk_TfGjKLTiTe9fzX9J4QqCUcf0/edit#
                https://github.com/w3c-ccg/vc-ed-use-cases/issues
                https://w3c.github.io/did-use-cases/#featureBenefitGrid
                    - substances (drugs) related secure signatures (Adrian’s mention of DEA licensing for writing prescriptions in the US)
                    - education ^^ 
                - Are there dependencies? Is there a timeline or hard deadline? 
                - Is the wallet only for SSI or also could be used for finance too? 
                - eg: https://en.wikipedia.org/wiki/FinTS
                - Who would be interested to co-chair? 
                - mailing list - https://lists.identity.foundation/g/wallet-security



# Meeting - 20 January 2021 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
    - Thank you for everyone making DIF F2F Virtual such a success! 
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * Kaliya presented her new [paper](https://docs.google.com/document/d/1sipXx9f_hBC8D0S1qZNMAhehblRW8pab-B4TX7CF0lw/edit0)
            *  Scene by Scene reviwe
            *  call to action:
                *  Scenes that need the most love: 8, 9, 10
        *  [Veramo](http://veramo.io/) intro - modular Javascript framework for verifiable data
            *  Consensys will donate the work to DIF, once the right location is found. 
        
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * preparation for F2F
        * [list](https://github.com/decentralized-identity/identifiers-discovery#work-items) of current work items 
            * discussion on did:peer's status
            * KERI implementations are moving ahead
            * Tomislav Markovski (Streetcred) donated [DID:key implementation in RUST](https://github.com/decentralized-identity/did-key.rs)
            * DID syntax discussion
    
    
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Accepted work items: 
            * [Credential Manifest](https://github.com/decentralized-identity/claims-credentials/blob/main/work_items/credential_manifest.md) `Weekly Thu 1PM EST`
            * [VC Marketplace](https://github.com/decentralized-identity/claims-credentials/blob/main/work_items/vc_marketplace.md) `Weekly Tue 8AM EST`
        * Presentation Exchange status update
            * `Comments on the Draft are welcome through 03:59 UTC/GMT on 2021-01-22`
        * Spherity (Aledander Yenkalov) presentation 
        * DIF F2F preparation

    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * OIDF meeting after DIF F2F
        * Kristina presented at F2F about the effort OIDF will do on SIOP.

    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * preparation for DIF F2F 
        * Jolocom DIDcomm Demo (Ivan)
        * DIDcomm bluetooth first meeting 
        * NFC discussion? 

    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * [Deactivate resolution/metadata](https://github.com/w3c/did-core/issues/468)
        * [Equivalence property notes on implications](https://github.com/w3c/did-core/pull/542)
        * discussion:
            * Align with did core PR
                1. deactivate result missing context
                2. Empty controller in all resolution results
                3. Return HTTP 200 instead of 410 for deactivate
                    * https://github.com/decentralized-identity/sidetree/pull/1000#issuecomment-762442040

     * **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
         * discussion:
             * Example capabilities for operations

3. **Additional Agenda items**
    - Thank you again for F2F
    - What was your (honest) opinion about gatherTown + Zoom
        - Went great (opinion) 
        - gather.town sponsored IIW event
        - networking was good, but for event hosting its not the best
            - 

# Meeting - 6 January 2021 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        *  Microsoft Authenticator func
        *  tionality presentation (not live demo) and discussion around consent 
        *  Year in review session
            *  Where Interop Happens
            *  Adrian presentation
  
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * new .NET implementation 
        * goal to create new work item proposal/approval process
        * preparation for F2F started

    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * New work items:
            * [Credential Manifest - work item](https://github.com/decentralized-identity/claims-credentials/pull/2)
                * Presentation exchange meetings will be Credential Manifest meetings from now on.
            * [VC Marketplace - work item](https://github.com/decentralized-identity/claims-credentials/pull/1)
        * Presentation Exchange, nearing 0.1.0 release.
            *  [**call for review on this version - Until 22nd of January**](https://lists.w3.org/Archives/Public/public-credentials/2020Dec/0148.html)
            *  blog article in preparation
            *  last issues have been raised 
        * Aries RFCs and their Integration of PE and CM specifications.
        * Aries-GO plans full support of BBS+ and PE and the end of Q1/2021
        * Status on Schema Work

    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * Asia specific AB connect wg calls at OIDF.
        * Tobias & Kristina lead the work there 
        * Special topic calls within OIDF 
            * 
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * DID core usecases added 
        - PR/Issues: 
            - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
            - [134](https://github.com/decentralized-identity/didcomm-messaging/issues/134) - `reply_*` headers and the support of DIDs without endpoints
            - [135](https://github.com/decentralized-identity/didcomm-messaging/issues/135) - Size (byte length) Specification for DIDComm Messages
            - [140](https://github.com/decentralized-identity/didcomm-messaging/pull/140) - Anonymous From
            - [141](https://github.com/decentralized-identity/didcomm-messaging/pull/141) - expires_time semantics
        - Support DID Methods without endpoint support
        - Interop testing? 
        - DIDComm Bluetooth discussion (Wed - Jan 6th, 12pm ET)
        - ACK - inclusion and status
        - [139](https://github.com/decentralized-identity/didcomm-messaging/pull/139) - Proposed Reply Header Text





    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * Sidetree.js (Orie / Transmute)
            * https://github.com/transmute-industries/sidetree.js
        * Element DID method
            * http://staging.element.transmute.industries/ < blockexplorer / staging testnet
            * https://element-did.com/ < older version on a previous version of sidetree.
        * Photon DID method (based on Amazon QLDB + ipfs)
        * Ion DID Method (Daniel / Microsoft)
        * SecureKey
            * GoLang implementation in progress - https://github.com/trustbloc/sidetree-core-go
        * Issue review:
            * [965](https://github.com/decentralized-identity/sidetree/issues/965) - algorithm to use for hashing suffix data


    * **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
        * new name: *Confidential Data Store Specification*
        * Discussion on identifiers
            * Items added to EDV, therefore, they need identifiers for retrieval. "content addresssable identifier" is not best match
        
    * Glossary group 
        * might come back to life with new work item(s)
            * Updates? 

3. **Additional Agenda items**
    * __DIF F2F Virtual meeting - January 19, Tuesday.__
        * [Sign up](https://www.eventbrite.com/e/dif-face-to-face-virtual-2-tickets-131061150429)
        * [Agenda discussion](https://docs.google.com/spreadsheets/d/1hVnwrnU7QOp_rA7AcK2NTQkflSAg0zvQ3-We2DqyRpk/edit?ts=5fea38e1#gid=445783158)
        * Testing/learning [graphical conference tool](https://gather.town/app/OhVftM5pgOzKTV7t/DIF%20F2F) 
    * Reminder: Better GitHub Tracking: Teams, WGs, WIs
        * Reach out to the Chairs of WGs (where WG charter for IPR has been signed) with your Github handle to be added to the Github teams 


## Meeting - 9 December 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        *  Introduction to [Spec Map](https://github.com/manicprogrammer/vc-spec-rel/) with researcher Michael Ruminer, talking about how to maintain it going forward
        *  BBS+ in Aries overview with Stephen Curran
        *  eSSIF & eSSIF-Lab interop deep dive
            *  Interop specifications discussion-- how to align with existing API standards?

    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * [Method Spec Registry analytics](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md#meeting---30-nov-2020---1400-et-recording) and some possible directions for DIF-based efforts to structure DID Method comparison/review
            * Sam suggested to do analytics of DID method usage through Universal Resolver
            * Sophie suggested that authors/implementers should be asked to supply contact information
            * Juan mentioned journalists, researchers, and consultancies would all benefit from a common repository for neutral, factual information as well as self-assessments against the DID Rubric
        * Discussion around accessibility/usability of DID technology
            * it felt hard to get back to the topic and find the inside knowledge that's required to use DIDs.
            * Sophie agreed that it was hard to find things, there are too many documents and some broken links.
            * Eric suggested it would be good to have third-party journalistic review of DID methods.
        * Key roll-over and recovery
            * repo in IDWG for lists recovery methods we know about.
            * For the Confidential Storage (SDS) WG, key recovery is pretty much out of scope. 
            * There is essentially only a limited set of options (menmonic devices, secret sharing).
            * Biometrics must not be used as a primary private key ("you can't rotate biometrics"). Biometrics can be used to unlock a private key, i.e. as an authorization capability.
            * Universal Wallet Conceptual Clarifications 
            * Universal Registrar problem

    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Update around [WACI](https://github.com/hellobloom/wallet-credential-interactions/pull/5)
        * Inform about VC Marketplace Workitem: Candidates:
            * In addition to existing: *KILT, Civic*
        * Credential Ontology and Tooling: What should the output to the group be: JSON Schemas, JSON-LD Contexts, Overlab with CCG Vocubulary. Workitem + Affinidi. Getting people at the table.
        * Recovation Workitem TBD (discuss with Gabe.)

    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * blog article about OIDF collaboration
        * [OIDC workshop on Dec 15th inclusing SIOP/DIF](https://openidentityexchange.org/networks/87/events.html?id=1031)
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](https://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * Current status on 1st complete draft? 
        * DIDComm.org Progress
            * https://github.com/decentralized-identity/didcomm.org
            * https://didcomm.org / https://www.didcomm.org  (works)
        * DID Use Cases
            * [Original]( https://github.com/w3c/did-use-cases/pull/100)
            * [Nader](https://github.com/w3c/did-use-cases/pull/122)
                - [Preview](https://pr-preview.s3.amazonaws.com/creatornader/did-use-cases/pull/122.html#messaging)
            - Needs New PR.
            - Expansion of messaging into protocols?
        * Issues:
            - [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
            - [131](https://github.com/decentralized-identity/didcomm-messaging/pull/131) - from/to DID Query Parameters
        * Bluetooth Transport - possible work item?
            - [status/questions](https://hackmd.io/animo/didcomm-bluetooth-transport)
        *  

    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * SIP 1 status
            * Expected by the end of the month.
        * Canonical and equivalent identifiers status
        * Finalize rules for evaluation of operations and dropping of files
        * Spec / reference implementation inconsistencies
    * **SDS WG** (Kaliya, Dmitry, Tobias) - [meeting page](https://github.com/decentralized-identity/confidential-storage/blob/master/agenda.md)
        * new name: *Confidential Data Store Specification*
        * Discussion: Storage Operations, and Authorization Structure
    * Glossary group 
        * might come back to life with new work item(s)
            * Updates? 

3. **Additional Agenda items**
    * Question about DID Method certification or U.R. data: Markus mentioned that this is an ongoing conversation, most recently discussed at the 30Nov ID [WG meeting](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md#meeting---30-nov-2020---1400-et-recording).
    * __DIF F2F Virtual meeting - January 19, Tuesday.__
        * [Sign up](https://www.eventbrite.com/e/dif-face-to-face-virtual-2-tickets-131061150429)
    * Better GitHub Tracking: Teams, WGs, WIs
        * Reach out to the Chairs of WGs (where WG charter for IPR has been signed) with your Github handle to be added to the Github teams 
    * [MyData conference](https://online2020.mydata.org/tickets/) next two days!
        * DIF Member Domi Labs aG will be [talking about](https://www.linkedin.com/posts/domi-labs_event-digital-digitaltransformation-activity-6742433961647063040-EpvN) their work in the European Commission's Data Portability Services Incubator (DAPSI)
    * [Thoughtful Biometrics](https://thoughtfulbiometrics.org/) conference, featuring many DIF companies and independent researchers, will be in early February. In addition to the obvious authentication, security, ethics, and government/digital-ID topics, there will also be a technical focus on biometrics for less well-known use-cases, such as [key recovery](https://medium.com/decentralized-identity/dif-id-wg-starting-work-on-cryptographic-secret-recovery-204117b6a2ab?source=friends_link&sk=15e09af545daa6dc86fae39ee9ea632e).
    * Announcement from DID Auth WG: there will be a SIOP/DIF presentation at the Open Identity Exchange December workshop at 1500-1700 GMT.  information [here](https://openidentityexchange.org/networks/87/events.html?id=1031)

## Meeting - 25 Nov 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
2. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * BBS+ presentation by Tobias (Mattr)
            * answering questions about his IIW [presentation](https://www.youtube.com/watch?v=AVnCVzW0rkI)
            * Discussion questions
                * To what degree is this a VC "format", and to what degree is it a VP upgrade?
                * What standards need to change/upgrade for these additional values ("proofValue", "subjectAuthenticationMethod", etc.) to be widespread? Consequences for core VC spec, LD-Proof spec, etc?
                * How are domains and linked secrets related, in the Aries universe? Are systems outside of the Aries world using domain-based indirection?
                * How big is the "lift" (or level of effort) for Aries systems post-[RFC 47](https://github.com/hyperledger/aries-rfcs/blob/master/concepts/0047-json-ld-compatibility/README.md)?  How big for non-Aries systems already using LD-VCs today?  How big for JWT-native systems? 
                * [If time allows] Could we talk more about "Just-in-time Issuance" and "Trusted Witness" solutions?
        * ESSIF-LAB and Odyssey Momentum
            * tbd
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * Questions around DID deactivation and resolution metadata
            * Can you verify a credential that was signed by a DID that has been deactivated?
            * older versions of a DID document - *version_id* and *version_time* parameters.
            * But support for those parameters is optional.
            * Sidetree's "checkpoint" feature
        * MIME types of DID documents - [issue](https://github.com/w3c/did-core/issues/208
        * Update on issues with [WebID](https://tcwiki.azurewebsites.net/index.php?title=Authentication_UX)
            * Potentially DIF should work on getting WebID into browsers
            * Opportunity for smooth iteration
            * WebAuthn is an option?
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](https://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Bloom Presentation: [The Wallet Credential Interactions Spec Proposal](https://specs.bloom.co/) by Jace Hensley
        * Next steps: Credential Schemas
        * Workitem Status: Presentation Exchange
            * Go Implementation Workday
            * JSONPath / Ontology Discussion Recap
            * [Open Issues](https://github.com/decentralized-identity/presentation-exchange/issues)
        * Workitem Status: Credentials Manifest calls
    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * blog article about OIDF collaboration
    * **DIDcomm** (Sam, Tobias, Oliver) - [meeting page](hhttps://github.com/decentralized-identity/didcomm/blob/main/agenda.md)
        * First Complete Draft - reads correctly from beginning to end Nov 30th.
        * DIDComm.org Progress
            * https://github.com/decentralized-identity/didcomm.org
        * DIDcomm usecase to DID Core https://github.com/w3c/did-use-cases/pull/100
        * Issues:
            * [117](https://github.com/decentralized-identity/didcomm-messaging/pull/117) - forward secrecy
            * [124](https://github.com/decentralized-identity/didcomm-messaging/pull/124) - mime types
            * [127](https://github.com/decentralized-identity/didcomm-messaging/pull/127) - structured headers
            * [128](https://github.com/decentralized-identity/didcomm-messaging/pull/128) - to header semantics
            * [129](https://github.com/decentralized-identity/didcomm-messaging/pull/129) - post quantum
            * [126](https://github.com/decentralized-identity/didcomm-messaging/issues/126) - DIDDocs for Peer DIDs
    * **Sidetree** (Daniel,Troy, Tobias) - [meeting page](https://docs.google.com/document/d/12l4wNkgkDn0tXxTPKB502gRXHa1hd7m0_KyebfRqMAo/edit)
        * SIP 1 status [issue](https://github.com/decentralized-identity/sidetree/pull/928)
            * PR for renamed files and properties
        * Canonical and equivalent identifiers status
        * Spec / reference implementation inconsistencies
    * **SDS WG** (Kaliya, Dmitry, Tobias)
        * EDV and Hub Use Cases
            * Demos of what people are using it for now (navigator api, etc)
            * Present/talk about why people are investing in EDVs / being in this group. (Is there overlap between people's use cases?)
            * For example, primary EDV use case: Wallet backup / portability. Is that true for the group?


3. **Additional Agenda items**
    * DIF-wide strategic goals for 2021 (Juan) + [opinion poll](https://forms.gle/jkeC7tTvPr5Ux4vH7)
------------------------


## Meeting - 11 Nov 2020 - (1100 ET) 
 
### Agenda

1. **Welcome and introductions**
3. **Additional Agenda items**
    * DIF F2F Virtual ~mid January 
        * [planning doc v1](https://docs.google.com/document/d/1GcTbLMixs_iaVAJpkNHEZl_c4LH9bH_vrNbe-2cL0GY/edit#)
    * Technical Steering Committee at DIF  (max 10 min)
        * One WG Chair's point: sometimes WGs have difficult decisions about deduplication of efforts or recommendations-- would be good to have "higher authority" with which to consult for tricky judgment calls
        * Frees up Steering Committee for more internal, structural, governance, and business topics
3. **Groups**
    * **Interop WG** (Kaliya, Pamela, Juan) - [meeting page](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md)
        * [The What and Why of the DIF general-purpose Document-Loader](https://youtu.be/-yUbMDft5O0)  - by Orie Steele
        * [W3C-CCG Edu Creds Task Force & Tooling/Sandbox Intro](https://youtu.be/AEb02JGCArM) (Overview of CCG LD tooling) -  Kim H Duffy 
        * Kaliya book presentation and the Domains of Identity [book](https://g.co/kgs/T6T8LQ)
        * Gold-Button Interop (MyData panel next month by A. Gropper)
        * **Next call about BBS+** agenda and "homework links" [here](https://github.com/decentralized-identity/interoperability/blob/master/agenda.md#agenda---18-nov-2020---useu-time-0600-pst)
    * **Identifiers & Discovery** (Markus, Sam) - [meeting page](https://github.com/decentralized-identity/identifiers-discovery/blob/main/agenda.md)
        * [DID WG meeting review during TPAC](https://docs.google.com/presentation/d/1RoE8E4y8S1j65EJaXZ8oihkduNbjTXXvdwtkzw961Xw/)
            * privacy violating properties
            * Abstract Data Model (ADM)
            * language that describes how to add and register new representations
            * Work on "security" and "privacy" in DID Rubric: https://github.com/w3c/did-rubric/pull/10
            * Video Recording of Markus's TPAC resolutions/action items overview [here](https://us02web.zoom.us/rec/share/kupVdGlwe30wjuPFmHBfUG_toosS9Hv-2rl1pReIMWVrODDkJATa7MErNGk0FoQD.J2Ho-Tz_5ZYq3n8D)
        * Fuzzy vault - C++? 
        * Updates on current work items did:peer, KERI, Universal Resolver, .well-known DID configuration, DID parameters, secret recovery mechanisms
        * KERI:
            * "mini conference" on API design in about a month's time
            * additional KERI meeting the hour before the current meeting time for use-cases and spec-authoring discussions to preserve the weekly meeting for #techTalk
    * **Claims & Credentials** (Gabe, Wayne, Martin) - [meeting page](hhttps://github.com/decentralized-identity/claims-credentials/blob/main/AGENDA.md)
        * Credential Manifest 
            * Reuse existing Presentation Exchange call time and shift focus towards Credential Manifest.
            * Review Daniel Status
        * IIW recap
        * Affinidi presentation in C&C [Recording](https://us02web.zoom.us/rec/share/3IYGkxbiCJG9acGTsoie_TQYWu8nKacNUcHEZPFx6yyMTjgp4-R_LsrE4SODrlAF.5dwcWpUCRYgI0BAs)
        * Presentation Exchange Status
            * [Multiple Schema identifiers](https://github.com/decentralized-identity/presentation-exchange/pull/149)
            * [Holder Binding between credentials](https://github.com/decentralized-identity/presentation-exchange/pull/123)
    * **DID Auth** (Oliver, Kyle) *half hibernated state*
        * blog article about OIDF collaboration
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
        * Working through issues
    * **SDS WG** (Kaliya, Dmitry, Tobias)
        * GNAP Presentation by Justin Richer
            * [Filling in the GNAP - Justin Richer](https://justinsecurity.medium.com/filling-in-the-gnap-a032453eaf8c)
            * [OAuth 3](https://oauth.net/3/)
        * Spec Rename Update/Announcement (spoiler: Confidential Data Store)
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

