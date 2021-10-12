# Vendor analysis

For each of the evaluated vendors, we have done our best to provide accurate information through a combination of research and conversations with company representatives. This section of the document summarizes some of the more important vendor differences to inform your decision making. For all the details, see the appendices:

{% content-ref url="../appendix-i-vendor-evaluation-of-key-considerations.md" %}
[appendix-i-vendor-evaluation-of-key-considerations.md](../appendix-i-vendor-evaluation-of-key-considerations.md)
{% endcontent-ref %}

{% content-ref url="../appendix-ii-vendor-evaluation-of-supplemental-considerations.md" %}
[appendix-ii-vendor-evaluation-of-supplemental-considerations.md](../appendix-ii-vendor-evaluation-of-supplemental-considerations.md)
{% endcontent-ref %}

### Vendor overview

#### Vendors Evaluated

| Name, website, and last date updated in this document                                                                                           | Headquarters      | Founded | User Base                                                              | Best for                                           |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | ------- | ---------------------------------------------------------------------- | -------------------------------------------------- |
| <p><strong>Alloy</strong></p><p><a href="https://alloy.co">https://alloy.co</a></p><p>12/3/2020</p>                                             | New York, NY      | 2015    | Financial services, banking                                            | KYC/AML compliance, fraud prevention               |
| <p><strong>Cognito</strong></p><p><a href="https://cognitohq.com">https://cognitohq.com</a></p><p>11/30/2020</p>                                | Palo Alto, CA     | 2014    | Financial services and marketplaces                                    | KYC compliance; address and age verification       |
| <p><strong>Ekata</strong></p><p><a href="https://ekata.com">https://ekata.com</a></p><p>12/2/2020</p>                                           | Seattle, WA       | 2012    | Online lending, retail banking, ecommerce and marketplaces             | Identity records for dynamic PII                   |
| <p><strong>Experian</strong></p><p><a href="https://www.experian.com">https://www.experian.com</a> </p><p>12/2/2020</p>                         | Dublin, Ireland   | 1996    | Government partners, financial services, online lending                | KYC compliance, fraud prevention, identity records |
| <p><strong>ID.me</strong></p><p><a href="https://id.me">https://id.me</a> </p><p>5/4/2021</p>                                                   | McLean, VA        | 2010    | Government partners, retail, online healthcare                         | Identity records                                   |
| <p><strong>Idemia</strong></p><p>https://www.idemia.com</p><p>5/4/2021</p>                                                                      | France            | 2007    | Government partners                                                    | Identity records                                   |
| <p><strong>IDology</strong></p><p><a href="https://www.idology.com">https://www.idology.com</a></p><p>11/17/2020</p>                            | Tallahassee, FL   | 2003    | Financial services, banking, retail                                    | Identity and age verification                      |
| <p><strong>SentiLink</strong></p><p><a href="http://sentilink.com">http://sentilink.com</a></p><p>11/25/2020</p>                                | San Francisco, CA | 2017    | Retail banking, credit card issuers, all types of lenders, and fintech | Synthetic fraud detection & analytics              |
| <p><strong>Socure</strong></p><p><a href="https://www.socure.com/products/sigma-identity-fraud">https://www.socure.com</a></p><p>12/11/2020</p> | New York, NY      | 2012    | Retail banking, credit card issuers, and remittance providers          | Fraud scoring and analysis                         |

#### A federal alternative: Login.gov

There is an identity proofing vendor that falls outside of the scope of this document, but that is likely to be of interest to readers: [Login.gov](https://www.login.gov), provided by the federal government. The single-sign-on service was launched by the General Service Administration in 2017, providing two-factor authentication, fraud detection, and Identity Assurance Level 2 (IAL2) under [NIST-800-63A](https://pages.nist.gov/800-63-3/sp800-63a.html). It was initially available only to federal agencies, with a FedRAMP Moderate ATO, [with customers including](https://login.gov/partners/our-agency-partners/) the Department of Defense, the Department of Homeland Security, the Department of Energy, and the Department of Transportation. At the end of 2020 they were granted permission by the White House Office of Management and Budget to accept state agencies as customers.

Login.gov is not a drop-in identity proofing vendor. They perform identity proofing, but only as a component of a user registration process within Login.gov. For employment agencies to use Login.gov for identity proofing, they need to replace their entire authentication flow with Login.gov, [integrating it via OAuth 2.0 or SAML](https://developers.login.gov).
