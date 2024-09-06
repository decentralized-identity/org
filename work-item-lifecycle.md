# Work Item Life Cycle


|[Brand Guidelines](brand-guidelines.md)|[Style Guide](style-guide.md)|[Working Group Lifecycle](working-group-lifecycle.md)|*Work Item Lifecycle*|[Github Donation](github-donation.md)|[Spec Tooling Guides](spec-tooling-guides.md)|[Code of Conduct](code-of-conduct.md)|
|---|---|---|---|---|---|---|



*Note: this overview was created by combining section 7 of the underlying JDF
[charter](https://github.com/decentralized-identity/org/blob/master/Org%20documents/Membership%20agreements/DIF%20Project%20Charter%20_4.0.2.pdf)
with the October 2020
[addendum](https://github.com/decentralized-identity/org/blob/master/Org%20documents/Membership%20agreements/Project%20Charter%20Addendum.md)
to be readable as a consolidated overview. It is not an authoritative document,
so if you find any discrepancies, those two linked documents are the
authoritative documents.*

*Please note:* deliverables (code and/or specifications) may be "donated" to DIF
at any point in the process below, which describes **original** work happening
inside DIF.  For instructions on how to effect a donation, see the [Github
Donation](github-donation.md) section.

## Deliverable Development Process.

### 7.1. **Pre-Draft**. 

Any Working Group Participant or Contributor may submit a proposed initial draft
document as a candidate Draft Deliverable of that Working Group. The Working
Group chair will designate each submission as a “Pre-Draft” document.
1. A Pre-Draft MAY BE referred to as a “Straw man” internally
2. Additional “Straw men” can serve as input documents to a Draft Deliverable,
   in part or in whole, and can be submitted after a Draft has been initiated at
   the discretion of the chairs.
3. If a deliverable builds on prior art designed and/or built by a participant
   in the DIF work in a legally significant way, i.e., if one or more input
   documents to the DIF work could constitute a threat to the IP safety of the
   DIF work item, the Working Group MAY request that it be officially donated to
   DIF before acceptance of the work item, such that IP rights (and ongoing
   maintenance) of the legacy work can be brought into the remit of the group.
   Review by the Executive Director and/or the Technical Steering Committee may
   help to clarify the scope or procedure for this donation in case of conflicts
   over this request.

### 7.2. **Draft**. 
Each Pre-Draft document of a Working Group must first be Approved by the Working
Group Participants of that Working Group to become a Draft Deliverable. Once the
Working Group approves a document as a Draft Deliverable, the Draft Deliverable
becomes the basis for all going forward work on that deliverable.

1. **Versioning** of specifications or code *SHALL* apply to every change
   affecting normative statements and/or test vectors.
2. All released versions of a draft *SHALL* be accessible at a static and
   **permanent URL**, tracked by DIF. (This is to minimize risk of editorial
   error or “overwriting” of significant changes).
3. Work items or their groups *MAY* customize the standard **contributor
   guidelines** template. SemVer.org-conformant versioning is the expectation,
   and if other conventions will be used, guidance should be published in the
   governing contributor guidelines document.

### 7.3. **Working Group Approval**.
Once a Working Group believes it has achieved the objectives for its deliverable
as described in the Scope, it will progress its Draft Deliverable to “Working
Group Approved” status.
1. Where protocols or interfaces are being specified, a section explicitly
   defining **test vectors for conformance testing** SHALL be written at time of
   approving a draft or earlier.
2. The WG approval process is a good time to do a final call for significant
   contributors to PR into the deliverable any entries to an "Acknowledgments"
   section of the deliverable (readme.md for code deliverables).  This is
   recommended in cases where non-recurring, equity free forms of funding
   supported the work (i.e. "grants" or other research and public-good support
   including DIF itself). Each supported contributor is responsible for their
   own acknowledgement. For a template, see the `[Acknowledgement
   Template](#Acknowledgement-Template)` section below. If the WG chairs and
   membership cannot come to agreement about specific acknowledgements, this can
   be escalated to the Technical Steering Committee by either party.
3. Before Steering Committee Approval, the approved version should be placed at a 
**permanent link** tracked on DIF’s spec-tracking github repo. [See Presentation 
Exchange v1.0.0 for an example](https://identity.foundation/presentation-exchange/spec/v1.0.0/). 
This includes:
    - In the spec repo, create a subfolder under the `spec` folder named `version_number`
    	- For Presentation Exchange v1.0.0, that results in `spec/v1.0.0/`
    - Copy the WG approved `spec.md` file to the newly-created subfolder
	- For Presentation Exchange v1.0.0, `spec/spec.md` was copied to `spec/v1.0.0/spec.md`
    - In the copied version, ensure the spec's version and specification status are up to date.
        - In the file `spec/v1.0.0/spec.md`, the following updates were made:
	    - Title: Presentation Exchange v1.0.0
	    - Specification Status: DIF Ratified Specification
4. The WG Chair requests SC approval.


### 7.4. **Final Approval**.
Upon a Draft Deliverable reaching Working Group Approved status, the Executive
Director or his/her designee will present that Working Group Approved Draft
Deliverable to the Steering Committee for Approval. Upon Approval by the
Steering Committee, that Draft Deliverable will be designated an “Approved
Deliverable.”
1. Once WG Approval has been achieved, the chairs should use the Technical 
   Steering Committee email list to notify it that SC approval will soon be
   sought; a one-week response time is customary for this review request.
   If the Technical Steering Committee believes there may be cause for the 
   Steering Committee to withhold approval, they should formulate clear and 
   actionable change requests for the group; delaying SC approval to address
   such requests is advised in such cases.
2. Final approval by DIF is referred to as “DIF Ratified Deliverable" or "DIF
   Ratified Specification” internally.
3. The steering committee *MAY* invite **external review** of test vectors and
   normative statements at this point, regardless of whether the Draft will
   proceed to step 7.6 or only to step 7.5

### 7.5. **Publication and Submission**.

The Executive Director will publish the Approved Deliverable in a manner agreed
upon by the Working Group Participants (i.e., Project Participant only location,
publicly available location, Project maintained website, Project member website,
etc.). 

Publicly-available specifications will be added to [DIF's spec tracking repo](https://github.com/decentralized-identity/specs/blob/master/README.md)

The publication of an Approved Deliverable in a publicly accessible manner must 
include the terms under which the Approved Deliverable and/or source code is being 
made available under, as set forth in the applicable Working Group Charter.

### 7.6. **Submissions to Standards Bodies**.
No Draft Deliverable or Approved Deliverable may be submitted to another
standards development organization without Approval by the Steering Committee.
Upon Approval by the Steering Committee, the Executive Director will coordinate
the submission of the applicable Draft Deliverable or Approved Deliverable to
another standards development organization with Joint Development Foundation
Projects, LLC. Working Group Participants that developed that Draft Deliverable
or Approved Deliverable agree to grant the copyright rights necessary to make
those submissions.

## Work Item 
A work item can be considered a DIF work item once the status of the item reaches one
of the stages mentioned in the Deliverable Development Process (above). Each DIF
work item must be concluded and developed under the
https://github.com/decentralized-identity organization's repository to be
considered part of the Deliverable Development Process, making it a DIF work
item. 

Types of Work Item:

### Specification

The most common output of working groups at DIF are specifications, which
unambiguously define and specify distinct protocols, data models, and/or
functional software modules. 

Specifications may also be versioned updates of previously published specifications.

### Profile

A work item that only describes and/or implements a *subset* of one or more 
existing normative specifications, whether standards-track or DIF-terminal 
(such as, say, Presentation Exchange or DIDComm) can be called a "profile", not
a specification, in that all normative and IP-sensitive work is done by an
existing specification, making this a "derivative work" and not needing IPR
protection. It is recommended that detailed profiles of a single DIF work item or
deliverable be donated to the working group that defined that work item to
simplify IP concerns if the contributors defining the profile need to open an
"upstream" PR or issue.  See the profile template [here](https://github.com/decentralized-identity/template-for-profile-workitems/blob/main/single-file-test/spec.md)

#### Interoperability Profiles

A common goal for interoperability efforts is to define a profile of multiple
specifications (protocols and/or data models) that add up to an "end to end"
profile for use by a certain ecosystem or infrastructure. These can, ideally, be
defined without any new IPR-sensitive contributions or ideas, whether in a
non-IPR-protected group like the Interoperability WG or elsewhere and donated to
DIF. There always exists, however, the possibility that the reality is less tidy
than the ideal, and such a multi-spec profile finds itself specifying more than
zero or accepting contributions that seem substantial in retrospect. For this
reason, all working group chairs should review any such donations critically
with this very issue in mind, and, if needed, work with donators to open a work
item in an IPR-protected working group to resolve any ambiguities about the IPR
status of all inputs to a profile if they are not confident that an interop
profile is adequately descriptive and non-normative to constitute an IPR-safe
donation before it goes to the Technical Steering Committee for DIF
ratification.

### Registry

In some cases, an ongoing work item can be created that collects inputs,
such as a directory or registry of links to downstream projects or
governance authorities. To minimize reputational risk or market confusion that
could occur from such open-ended registries bearing an implicit DIF seal of
approval, registry work items must define the process for registering items,
this process should be approved by working group chairs (and at
discretion of same, the DIF steering committee) before being opened up to
outside PRs.  Once approved, editors (i.e. code owners) of a given registry are
encouraged to merge PRs and grow their registry indefinitely within the
guidelines of the approved process, while relying on working group chairs in case of
uncertainty about incoming registrations and, of course, to ensure continuity of
maintenance. See the registry template [here](https://github.com/decentralized-identity/template-for-registry-workitems/blob/main/single-file-test/spec.md)

### Maintained versus Archived Work Items

Regardless of how far it proceeded through the statuses above, any DIF work item
is presumed to be an ongoing work item under active management unless explicitly
marked as "Archived" by the Working Group managing it.  

If open issues are
growing stale or not being handled within a reasonable amount of time, WG chairs
may contact work item leaders to request more consistent management, and if this
is not forthcoming, may move to mark the work item as "Archived".  In leiu of active chairs, the technical steering committee could also intervene in that capacity.

The process for archiving is simple: WG chairs request that DIF staff mark the
repo as archived in github, and that the change be reflected on DIF's website.
It is recommended that a sentence about the new archival status also be added to
the rendered/hosted spec and repo "README.md" file. 

Once archived, WG chairs should check their WG's home repo or other informative
references to ensure that archived work items aren't listed among ongoing work
items.

### Acknowledgement Template

{ENTITY_NAME} received funding from {FUNDING_SOURCE} to contribute to this work
item. {OPTIONAL DETAILS ABOUT SCOPE, CONTRACT NUMBERS, OVERSIGHT, ETC}. This
work item does not necessarily reflect the position or the policy of
{FUNDING_SOURCE} and no official endorsement of the work item or of DIF itself
should be attributed to {FUNDING_SOURCE} on the basis of this support.
