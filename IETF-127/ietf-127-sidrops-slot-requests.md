# Requests for SIDROps agenda time @ IETF 127

## How to make a slot request:

Create a Pull Request appending, at the end of this very file, the request using the format:

---
#### Title Here
- Speaker: Your Name
- Desired Duration: in minutes (including Q&A)
- Expected outcome: The main objective of the presentation, e.g. community feedback, adoption, WGLC, etc.
- Abstract: abstract of the document. 
- Datatracker Link:  link to related document(s) in the Datatracker 
---

### Current Pending Requests

#### Introduction to RPKI Doctors
- Speaker: Job Snijders
- Desired duration: 10 minutes
- Expected outcome: community feedback
- Abstract: Explain objective and approach of RPKI Doctors review team
- Datatracker link: [https://datatracker.ietf.org/group/rpkidoctors/about/](https://datatracker.ietf.org/group/rpkidoctors/about/)

#### Mixed Algorithm Certificate Chains in the RPKI
- Speaker: Job Snijders
- Desired duration: 15 minutes
- Expected outcome: community feedback / call for WG adoption
- Abstract: Discussion on the concept of using mixed signing algorithm certificate chains in the RPKI. Permitting a second (widely supported) signing algorithm in the RPKI allows for smaller signatures in the short term and gaining operational experience towards PQ transitions in the long term.   
- Datatracker link: To be posted

#### BGP Signed Origin Delegation Attestation (SODA)
- Speaker: Shenglin(Forrest) Jiang
- Desired duration: 5 minutes
- Expected outcome: community feedback
- Abstract: Using SODA, a validator performing Route Origin Validation (ROV) can determine whether an ROV-Invalid result reflects an authorized delegation rather than a route hijack.
- Datatracker link: [https://datatracker.ietf.org/doc/draft-jiang-idr-bgp-soda/](https://datatracker.ietf.org/doc/draft-jiang-idr-bgp-soda/)

#### Push Mode Extension for the RPKI to Router Protocol
- Speaker: Liyan Gong
- Desired duration: 10 minutes (Friday Sesion)
- Expected outcome: community feedback
- Abstract: This document defines a push mode extension for RTR that allows RPs to proactively push RPKI data updates to routers, either periodically or event-driven.  
- Datatracker link: [[https://datatracker.ietf.org/doc/draft-gong-sidrops-rtr-push/](https://datatracker.ietf.org/doc/draft-gong-sidrops-rtr-push/)]

#### Considerations for Incremental Validation in RPKI Relying Parties
- Speaker: Yingying Su, Yirong Yu
- Desired Duration: 10 minutes (including Q&A)
- Expected outcome: community feedback
- Abstract: This document describes the operational problem and design space for incremental validation in RPKI Relying Parties (RPs), and discusses general correctness and security considerations for reusing previously computed validation state. The goal is to reduce redundant validation work after incremental repository synchronization. The correctness objective is to produce the same validated payload output as full validation for the same repository snapshot, trust anchor set, validation policy, validation time, and applicable RPKI validation rules. This document does not specify a particular algorithm or cache structure, change RPKI object formats, repository synchronization protocols, or validation semantics, or require RPs to implement incremental validation.
- Datatracker Link: https://datatracker.ietf.org/doc/draft-su-sidrops-rpki-rp-incremental-validation/