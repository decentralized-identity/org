# DIF Specification Tooling Guides

|[Brand Guidelines](brand-guidelines.md)|[Style Guide](style-guide.md)|[Working Group Lifecycle](working-group-lifecycle.md)|[Work Item Lifecycle](work-item-lifecycle.md)|[Github Donation](github-donation.md)|*Spec Tooling Guides*|[Code of Conduct](code-of-conduct.md)|
|---|---|---|---|---|---|---|


*DIF Knowledgebase for members, work items, and communications:*

DIF recommends picking the spec-authoring tool most appropriate to the target
audience and/or target Standards Development Organization (SDO).  If your work
item can come to a consensus *up front* about an SDO that it wants to target
from the beginning, we advise the group to work within the format and tooling
preferences of that SDO from the begining.  If no clear SDO can be agreed to
upfront, or if a "DIF-terminal" specification is consensual from the beginning,
we recommend SpecUp, a markdown-based tool maintained as a standing work item of
the DIF technical steering committee.

The tools recommended by DIF are:
1. **[SpecUp](https://github.com/decentralized-identity/spec-up)** is a
   lightweight markdown generator similar to Jekyll, which is itself hosted and
   maintained as a standing DIF work item. 
   - Work items intending to use spec-up for their deliverables should request a
     "spec-up repo" from DIF at time of beginning work, i.e., a repo cloned from
     the [SpecUp repo
     template](https://github.com/decentralized-identity/spec-up)
2. **[BikeShed](https://tabatkins.github.io/bikeshed/)** is a general-purposes
   specification authoring tool with many features and settings, which may be a
   bit overwhelming for more junior/inexperienced audiences.
3. **[ReSpec](https://respec.org/docs/)** is the native specification tool of
   the W3C community, is a more bibliographically-oriented tool. Feature
   requests or questions about advanced configuration topics and customization
   should be directed to the [specification producers mailing
   list][https://lists.w3.org/Archives/Public/spec-prod/] and community group,
   which governs both respec and [spec
   prod](https://w3c.github.io/spec-prod/)/[echidna](https://w3c.github.io/spec-prod/#deploy-to-w3c-using-echidna),
   the github action that powers it.
4. **[XML2RFC](http://xml2rfc.tools.ietf.org/)** is the preferred spec-authoring
   tool for IETF RFCs, but may require a bit of XML familiarity; the dockerized
   version, [`markdown2rfc`](https://github.com/oauthstuff/markdown2rfc), also
   contains the similar go-based tool, `mmark`, can be a more user-friendly
   experience.
   - Unless editors have prior experience with IETF spec tooling, we recommend
     work items intended as IETF internet drafts start work in a DIF repo cloned
     from the [DIF
     fork](https://github.com/decentralized-identity/template-IETF-bound) of the
     `internet-draft-template` by Martin Thomson (a long-time IETF WG chair). It
     contains a dockerized version of `markdown2rfc` and automations for github
     that can be customized (documentation forthcoming). 
   - Note: It is also possible to generate IETF RFCs from markdown files using
        [BikeShed](https://tabatkins.github.io/bikeshed/) in situations where
   user-friendlier tools lack flexibility.

## Educational materials

**SpecUp** education materials are forthcoming. In the meantime, see github
[issues](https://github.com/decentralized-identity/spec-up/issues) at the repo.
There is also a video of tool creator Daniel Buchner giving a [quick
tour](https://www.youtube.com/watch?v=sfMc5Has4s4) of key features.

**ReSpec** educational materials are also forthcoming.  In the meantime, see the
[overview](https://w3c-ccg.github.io/specs.html) and
[video](https://youtu.be/0eQXU6Z-A6Q) created by the W3C
[CCG](https://w3c-ccg.github.io/)-- note that there are also instructions on how
to generate ReSpec from markdown via github automation.

## Acknowledgements for Specs
As DIF is a place for collaboration, acknowledging work funded or done by others
is a gesture to recognize the efforts behind ratified work items. Consider
creating a section for acknowledgments and recognize specific grants, people, or
organizations whose work was invaluable for the delivered work item. 
