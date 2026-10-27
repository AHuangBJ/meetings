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

#### Information Asymmetry and Deployment Gaps in RPKI-based Route Origin Validation
- Speaker: Weiqiang Cheng
- Desired Duration: 10 minutes
- Expected outcome: community feedback
- Abstract:This draft analyzes RPKI/ROV deployment gaps and cross-plane information asymmetry, describes operational side effects, and frames the problem space for future work, without proposing new protocols.
- Datatracker Link: [https://datatracker.ietf.org/doc/draft-cheng-sidrops-rpki-rov-gap-analysis/](https://datatracker.ietf.org/doc/draft-cheng-sidrops-rpki-rov-gap-analysis/)


#### Source Pre-validation in RPKI ROV
- Speaker: Mingqing Huang
- Desired Duration: 10 minutes
- Expected outcome: community feedback
- Abstract: This document defines a BCP for source pre-validation: an originating AS checks its intended BGP announcement against its local RPKI cache before sending it to eBGP neighbors. The goal is to reduce the number of self-inflicted invalid routes, improve global routing stability, and encourage wider and more confident deployment of ROV drop policies across the Internet - including the long tail of stub and small regional ASes.
- Datatracker Link: [https://datatracker.ietf.org/doc/draft-huang-sidrops-source-pre-validation/](https://datatracker.ietf.org/doc/draft-huang-sidrops-source-pre-validation/)

#### Export of BGP Prefix Origin Validation in IP Flow Information Export (IPFIX)
- Speaker: Xueyan Song
- Desired Duration: 5 minutes (Friday session)
- Expected outcome: community feedback
- Abstract: The draft defines an IPFIX Information Element to export the RPKI-based BGP Prefix Origin Validation state (valid/invalid/not-found) for the active Loc-RIB route. It gives operators standardized visibility into ROV outcomes alongside flow monitoring, helping detect hijacks/misconfigurations and bridging SIDR operations with existing IPFIX tooling. 
- Datatracker Link: [https://datatracker.ietf.org/doc/draft-liu-sidrops-ipfix-bgp-pov/](https://datatracker.ietf.org/doc/draft-liu-sidrops-ipfix-bgp-pov/)
