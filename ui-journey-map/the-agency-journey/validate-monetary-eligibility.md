# Validate Monetary Eligibility

## Challenge 1: Interstate wage verification

### What our partners are saying

* “If they pick up wages in another state, there is a hold put on the claimants; Send request to ICON & ICON sends request to other state; Really depends on another state; Done by hand, no automation; Takes forever. Because each state has a different process, it causes more delays. Can this process be standardized to flow faster and easier?” --State A

### Recommendations: 

1. US DOL should launch specific initiatives to co-develop solutions with states to share  interstate wage data. Establish a working group that includes states and NASWA to address this. ICON \(the current system\) digitizes requests between states but does not help with tracking or ensuring a timely response. US DOL should further partner with select states to iteratively build and test shared service components and/or reference implementations that will inform country-wide guidelines for UI system improvements 
2. US DOL should update guidance to enable people to receive benefits from home state first, and make adjustments when the data from other states comes in. [Learn more](https://dig.abclocal.go.com/wpvi/pdf/NJ%20Congressional%20Letter%20Final.pdf)

## Challenge 2: Verifying “income” from other benefit programs

### What our partners are saying

* "\[I wish we had a\] Joint case management system \[across benefits programs\]. \[State\] is very fragmented for someone to get services. We want to use tech more efficiently and effectively." --State A
* Our state has “issues knowing if people are receiving other benefits from the state that might make someone ineligible.” --State B

### Recommendation:

1. State agency and/or US DOL: If any data needs to be checked with another agency, then make sure that the other entity is prepared for the incoming requests. Ideally, you will be able to establish an expected response time so you could build your surrounding processes accordingly. Digitizing the request to the other agency is important to making sure it doesn’t get lost, but if the other agency’s underlying process is manual, then the digitization won’t have that much impact on timeliness of claimant’s benefit receipt.

## Challenge 3: Veteran and Federal Government wage validation is often time-consuming and not automated

### Recommendations

1. Agencies that need to check someone’s military veteran status should build their process around the Veteran Confirmation API, rather than using separate manual processes
2. Agencies: For any group of people that may need additional or special verification, make sure there is an accessible, mobile-friendly way to upload documents \(including image files\) to avoid requiring manual/paper process for the population"
3. US DOL should work with OPM to build an API to verify that someone was a civilian employee and what their last pay grade was

## Challenge 4: PUA wage validation

State UI agencies are not set up well to validate wages earned through self-employment because those are definitionally not reported by an employer, which is the standard source of verification for UI systems. To the degree that PUA may persist beyond the pandemic, it’s important to think about improvements to this wage verification system.

### What our partners are saying

* "The IRS should be giving us everything, it’s a federal program, this shouldn’t have been with DOL. We don’t have this information, it was shoehorned into us to the detriment of everyone else." --State B
* “PUA was a perfect storm of good intentions and bad policy. \[...\] Are you trying to break our system?” --State C
* - “When DOL said you guys aren’t giving the right monetary determinations for these people, you need to start doing this. OK great, can you help us figure out how to do this, what would be your advice on how to do this quickly? We want to be in compliance, but it’s human beings doing math.” --State E

### Recommendations

1. Similar in concept to the recommendation for Challenge 2, state UI and US DOL should work with state and federal treasury and IRS to get this data directly and/or leverage the information already gathered for other benefit programs. While APIs/agreements for working with the IRS almost certainly don’t \(yet\) exist, states with income taxes should work with their treasury departments to come up with an efficient process to validate wages
2. US DOL and the executive branch should make and communicate a decision about the future of PUA beyond the pandemic to inform how much state agencies should invest

