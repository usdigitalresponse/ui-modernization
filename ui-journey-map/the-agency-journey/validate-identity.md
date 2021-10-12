# Validate Identity

## Challenge 1: Existing systems were built to detect lying, not theft

Unemployment insurance agencies operate under a “threat model” for improper payments of detecting claimants who lie or otherwise make mistakes on their applications and weekly claims. When substantial federal money began flowing into these systems with the CARES Act, the agencies quickly became targets of criminal digital fraud syndicates. These criminal rings have primarily been using stolen identities to claim others’ legitimate benefits or, in the case of Pandemic Unemployment Assistance, to create fully illegitimate claims. 

### What our partners are saying:

* "There have been more data breaches over the last couple of years where accurate information is highly available to folks. In the past, if you have all the right info for someone, our system wasn’t built for stopping you. In most cases, fraud meant that someone was getting unemployment incorrectly - accurate PII out there has made everything more difficult." -- State B
* "The problem we had previously was that someone who stole someone’s ID has all their information, they would be able to get past the software, so what we found is that our ID verification was only stopping people who were the right person who couldn’t answer the questions right. We were stopping the wrong people." -- State B
* "Right now, there’s been a pretty substantial correction toward making sure that criminal rings can’t come in and file claims on behalf of people." -- State F

### Recommendation: 

1. Agencies should ensure their threat model is up-to-date:  what kind of fraud or theft will your system be susceptible to? (Identity theft to steal others’ benefits, or “benefit theft” to try to get more than you are otherwise eligible for) Agency identity proofing systems shouldn’t rely on Knowledge Based Verification. Look to have a NIST Identity Assurance Level 2 system. To learn more, see USDR’s [Identity Proofing for UI Agencies](https://usdr.gitbook.io/unemployment-insurance-modernization/identity-proofing-vendor-comparison/identity-proofing-vendor-comparison) report

## Challenge 2: Many common identity theft detection practices result in racially inequitable outcomes.

In UI systems, there is a balance between finding fraud and getting benefits out in a timely manner. Right now, a lot of fraud is slipping through and benefits are severely delayed. As we work to shift this balance, we need to ensure that we reduce -- not broaden -- racial inequities in UI.

“By focusing on overpayments, the \[US DOL] is not held accountable for determining other errors created by the state, or even an employer, when it comes to UI payments—such as underpayments—which are also payment inaccuracies. The \[accuracy] map also doesn’t reflect cases in which eligible UI applicants are erroneously denied benefits.” --[Unpacking Inequities in Unemployment Insurance](https://www.newamerica.org/pit/reports/unpacking-inequities-unemployment-insurance/a-focus-on-fraud-over-accessibility-the-punitive-design-of-ui)

### What our partners are saying

* “ID verification, the tools we use have the biggest weight against, have the heaviest burden on, low income people. If the tool is a driver’s license, how much more difficult that becomes for low income people." --State B
* "\[We have] no way to break down fraud vs. not having a driver’s license. We’ve seen an uptick in phone filing because of this.”  -- State B
* "These systems, the larger populations get prioritized because you get the biggest result but it’s not the right way to think about things. We are trying to shift and think about smaller populations but more difficult time getting served and get them served with priority "" -- State F

### Recommendations

1. With the support from US DOL, agencies should find and mitigate inequitable impact of identity fraud detection flags like IP address, multiple uses of the same physical address, and restrictions on characters used in people’s names. [Learn more](https://usdr.gitbook.io/unemployment-insurance-modernization/identity-proofing-vendor-comparison/race-and-inequity-in-identity-proofing-methods/recommendation-1-find-and-mitigate-inequitable-impact-of-identity-fraud-detection-flags)
2. With the support from US DOL, agencies should increase accountability for ensuring rightful claimants make it through the system, like usability testing the entire identity proofing process. The US DOL can set standards and best practices for use. [Learn more](https://usdr.gitbook.io/unemployment-insurance-modernization/identity-proofing-vendor-comparison/race-and-inequity-in-identity-proofing-methods/recommendation-2-increase-accountability-for-ensuring-rightful-claimants-make-it-through-the-system)
3. US DOL should reevaluate KPIs and their relative importance to ensure timeliness and equity are valued and improved upon.
4. US DOL should re-release Replacement Rate data in easily accessible format 

## Challenge 3: People whose identities were stolen have difficulty claiming their rightful benefits

### What our partners are saying

* "With the claimant, because we’ve had so many issues with stolen identities used to file fraudulent claims, when the real claimant goes to file, we have to undo everything that has happened - new username against SSN, if payments got issued, we’ve identified a number of claims beforehand, but some need to be cleaned up so that the payments aren’t charged to the claimant or employer. If the fraudulent claim was issued a debit card, the bank is going to have to cancel that, it’s tied to the SSN. It’s not an easy process, especially with the volumes we’ve been having" --State B

### Recommendation

1. Agencies: when the threat model indicates high likelihood of identity theft as a means to obtain benefits, plan ahead for how the rightful claimant can come in after the criminal and actually receive their benefits without significant delay (even if the stolen benefits haven’t been recouped from the criminal).

## Challenge 4: Every state is implementing updated identity proofing procedures on their own

Additionally, the states acting independently leaves the slower-acting states vulnerable: As states tighten their fraud detection efforts, criminals move to other parts of the system (State A vs. State B, standard UI rather than PUA, or hacking into accounts to change bank info rather than submitting new applications)

### What our partners are saying

* “This has been a failure of imagination at every turn. People have not appreciated the scale and scope of this. We’re getting crucified in the media because of things that are beyond our control. To say this is demoralizing is an understatement.” -- State C
* We would be "better served if national requirement and participation in the common data sharing were required" -- State F
* "Federal prison data that SSA has and NASWA has been trying to get it and build it into integrity center and they can’t get the data sharing agreement figured out with DOL. We should just solve these so individual states aren’t having to do independent efforts that will contribute to fraud nationally" -- State F

### Recommendations

1. Legislature: The Social Security administration should be given resources and a mandate to make its online, live, SSN validation service available to state agencies both directly and through Login.gov.
2. US DOL: should set up a “fusion center” to set up and facilitate an ongoing information exchange, so States can learn from each other about what fraud tactics are being used and how to combat them. As part of the project, define the process (and technologies) that people will use to report identity theft, and that the agency will use to act on that information (including law enforcement involvement)
3. US DOL in partnership with other federal agencies: US DOL should secure the use of the CMS Data Hub to provide a shared eligibility determination service, and as an additional data source for identity validation. This makes the process much more efficient for many who won’t have to manually re-enter information for every new program; however, you’ll have to at the same time ensure that those who aren’t in the partner program still have a pathway to apply. [The Missouri Benefits Enrollment Transformation report](https://dss.mo.gov/docs/civilla-missouri-research-report.pdf) has many transferrable recommendations, pp 28-29 in particular.
4. Federal GSA in partnership with US DOL: DOL should pay for Login.gov use for any states that wish to use it, and provide incentives for states to do so
5. State agencies and US DOL: Programs administered by other agencies may have already done the identity validation you need, or could use the ID proofing that you do. Existing auth systems (e.g., with SNAP or Medicaid)) should be leveraged.
