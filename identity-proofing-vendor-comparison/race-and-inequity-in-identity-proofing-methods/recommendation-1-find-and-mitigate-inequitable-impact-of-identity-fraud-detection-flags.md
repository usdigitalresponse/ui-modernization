# Recommendation 1: Find and mitigate inequitable impact of identity fraud detection flags

There are several common mechanisms by which people get caught up in fraud detection systems in a way that disproportionately targets POC. Below are some common problem areas and how to resolve them.

### Recommendation 1.1: Systems should not use IP Address Geolocation as a binary signal for fraud but instead as part of risk score

IP addresses are used to geolocate web traffic. For UI agencies, traffic coming from, e.g., out of state can be suspicious. However, there are several limitations to this approach that ultimately amount to the fact that IP addresses are not particularly trustworthy as a binary fraud detection mechanism; they should be used as [part of a risk score](https://usdr.gitbook.io/unemployment-insurance-moderinzation/identity-proofing-vendor-comparison/identity-proofing-vendor-comparison#risk-score). 

* IP Address databases might simply be out of date
* Black and Latinx adults are [25% less likely](https://www.nelp.org/publication/from-disrepair-to-transformation-how-to-revive-unemployment-insurance-information-technology-infrastructure/) than White adults to own a laptop or desktop computer. Without a desktop computer to file (a situation that also disproportionately happens to those who are housing insecure), you might be using devices from friends or relatives or a library (if open), or using your cell phone -- all of which means your location may change from week to week, and your apparent location may change even more.

### Recommendation 1.2: Audit and fix system’s English bias in name-matching

Many UI systems were built with just English names in mind, which does not reflect the linguistic and cultural diversity of the United States. Systems need to be able to handle:

* Short first and family names without error
* Long first and family names without truncation
* Non-Roman characters (spaces, hyphens, apostrophes, accents) without error

In addition to being able to accurately store names with the above characteristics, the identity fraud detection process needs to have some flexibility in how it interprets and cross-references names across pieces of the application. It needs to account for mistakes that the system made with someone’s name (e.g., truncated after 10 characters in part A but truncated after 15 characters in part B) as well as for cultural considerations (e.g., [someone might have “Graciela” on their birth certificate but “Grace” on their driver’s license](https://www.newamerica.org/pit/reports/unpacking-inequities-unemployment-insurance/a-focus-on-fraud-over-accessibility-the-punitive-design-of-ui), or sometimes put a second surname in a middle name field instead of the last name field). 

### Recommendation 1.3: Update threshold for number of claims filed from same address

One common flag for UI fraud is many people filing from the same address. However, [“\[f\]amilies of color and families with foreign-born members are more likely to live in multigenerational households,” ](https://www.americanprogress.org/issues/poverty/news/2020/04/15/483248/criminal-records-create-cycles-multigenerational-poverty/)meaning they are more likely to be flagged on suspicion of fraud. Further, the addresses of homeless shelters and other social service agencies can be used in the absence of permanent housing. This should be taken into account when determining a threshold for flagging claims.

Additionally, UI agencies should:

* Ensure they are looking at all parts of the address (e.g., including apartment or floor number) when comparing addresses for multiple claims filed. Otherwise, those who live in multi-family housing units will disproportionately be targeted.
* Proactively “clear” addresses known to be used by those who are housing insecure and thus could have many claims filed 

### Recommendation 1.4: Ensure there is a clear alternative to digital document verification

Many States’ identity verification solutions require claimants to provide photo IDs corroborating their identity. This is important for a robust determination that someone is who they say they are (per NIST IAL2 standards), but it does raise some concerns.

Document verification processes can cause a number of issues from the name mismatch described above -- or a complete break in the process because someone doesn’t have the right (or any) documentation. People who are [poor](https://www.washingtonpost.com/politics/courts_law/getting-a-photo-id-so-you-can-vote-is-easy-unless-youre-poor-black-latino-or-elderly/2016/05/23/8d5474ec-20f0-11e6-8690-f14ca9de2972\_story.html), [formerly incarcerated](https://www.pbs.org/newshour/nation/leaving-prison-without-a-government-id-can-block-access-to-housing-jobs-and-help), or [Black](https://www.npr.org/2012/02/01/146204308/why-millions-of-americans-have-no-government-id) are less likely than their richer, White counterparts to have a valid ID.

In any document verification step, there must be a clear way for a claimant to get in touch with a representative of the agency to find an alternative method for proving they are who they say they are. Otherwise, people without IDs are categorically going to be denied benefits in a racially skewed outcome.
