# Identity proofing vendor comparison

## **Vendor considerations & requirements**

There are many players in the commercial identity proofing & fraud detection space that are good candidates for use by UI agencies. In addition to providing key overview data for each company, we have aggregated data that will help UI agencies in making a vendor decision. We have also listed out a number of other non-functional requirements that would be relevant to most implementations.

### Key considerations

In evaluating vendors, we came up with a list of key questions that influence the degree to which the vendor could help ease the identity proofing burden on UI systems:

1. **What is the pricing model, and what is the cost?** If it’s by verification attempt rather than only successful verification, the overall difference in per applicant cost could be 5-20% depending on the vendor’s success rate \(which we don’t really know\). Additionally, if a company has known set-up costs, those are noted.
2. **What is the user experience \(UX\) like during identity proofing at account creation?** I.e., is it an API call that is run in the background without the user noticing and/or a UX provided by the vendor that the user is sent to? Some vendors have a single product that provides an experience that all applicants would have; other vendors have multiple products that can be chained together in the “step-up” method depending on individual results. 
3. **How can it be used to process users in the backlog who have been flagged as potential fraud risks?** The most impactful functionality in this area is whether they have a “batch API” that can be used to help make a determination on many individuals at once, without needing those individuals to take further action. Some vendors need a special workflow set up to send people from the backlog to their site to gather, or re-gather, information.
4. **What methods does it use to verify identity**, per descriptions in the ["Process of Identity Proofing" section](https://usdr.gitbook.io/unemployment-insurance-moderinzation/identity-proofing-vendor-comparison/identity-proofing-vendor-comparison#process-of-identity-proofing)? 
5. **Where do they get the data against which they perform the identity proofing, including SSN?** Every data source has limitations, and so in general, more data is going to result in more people with positively proved identities while continuing to catch those trying to commit fraud. \(On the other hand, more data sources is likely to be reflected in a higher price for that vendor.\)

{% page-ref page="../appendix-i-vendor-evaluation-of-key-considerations.md" %}

### **Supplemental considerations**

If you believe that a vendor is a good match for your needs based on the key considerations above, the following information about the company could help you finalize your decision. Please do not be discouraged by “unknown” answers for some of these questions — that we have been unable to get answers to these questions does not mean that they are unanswerable.

1. What notable \(name-brand\) customers do they have?
2. What special certifications/authorizations does it have?
3. Have other government entities used it?
4. Does this vendor have existing contracts through an available Federal Supply Schedule \(FSS\) through GSA or some other Governmentwide Acquisition Contract \(GWAC\)?
5. Is this vendor under a recognized socioeconomic program or status such as the 8\(a\) program or Service-Disabled Veteran-Owned Small Business \(SDVSOB\)? 

{% page-ref page="../appendix-ii-vendor-evaluation-of-supplemental-considerations.md" %}

### Nonfunctional requirements

While most state unemployment insurance agencies are trying to solve the same set of problems, the technologies and processes that they are working with vary greatly. Each organization will have to determine their own requirements in the following areas:

* Network API and style \(e.g. REST/SOAP/GraphQL\)
* Supported development languages 
* Client libraries
* Security concerns
* Average and 99th percentile response times
* Scalability
* Error rate
* Support \(API docs, consulting services, third-party support, etc.\)
* Licensing, embedding, reuse
* Data storage and access policies \(Do they store PII on their side? Do their employees have access to that data? If so, how are those employees vetted and/or held accountable?\)
* Severability and replaceability \(How is their contract structured? If they store data, is that data accessible in a bulk, machine-readable format?\)
* Hosting model \(SaaS or on-premise?\)

## Vendor analysis



{% page-ref page="../appendix-i-vendor-evaluation-of-key-considerations.md" %}

{% page-ref page="../appendix-ii-vendor-evaluation-of-supplemental-considerations.md" %}

### 

