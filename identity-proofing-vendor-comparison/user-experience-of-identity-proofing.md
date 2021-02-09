# User experience of identity proofing

## UX flow

A strong identity proofing system can be achieved either through a single product offering, or multiple products and/or vendors. When you use multiple products \(either from the same vendor or multiple vendors\), you can decide not to have everyone go through all identity proofing steps, and/or leverage information from multiple products at the same time to make a determination. \(It is important not to chain these in such a way that would permit fraudulent identities to slip through via the weakest service.\) 

There are two ways that identity proofing can be integrated into a UI system for applicants to provide the required information:

1. Use the vendor’s API so that the applicant never leaves your application website. This option allows for greatest flexibility and can provide applicants with a more consistent experience.
2. From your application, direct applicants away from your website, through a process on a vendor’s website, and then back to your website again. This option is likely less work for the UI agency to implement.

Identity proofing is ideally part of the initial applicant experience.  This reduces the number of applicants that need additional manual review. However, identity proofing can also be used to manage a backlog. By creating a process that encourages applicants to return to the website to provide more information, backlogged claims can be handled with less manual intervention. \([Indiana did this](https://www.in.gov/dor/fraud-prevention/identity-confirmation/) by sending applicants a letter that directs them to an online identity quiz.\)

When thinking about the backlog, there are also options that don’t require an applicant to provide any additional information. For such non-interactive identity proofing processes, the vendor will compare the applicant-provided data to authoritative data sources and return a confidence level \(risk score\), which indicates how certain they are that the applicant is the person who they claim to be. \([Wisconsin has done synthetic identity detection](https://dwd.wisconsin.gov/news/2020/201019-cloud-collaboration.htm) on applications in their backlog to speed up determinations.\)

Regardless of the way you integrate with a vendor, you should make sure that there are clear ways for someone to get direct agency help if they are unable to provide what the process requires. Doing so is an important piece of reducing the racial inequity gap of UI benefits in two key ways: 

1. People who are [poor](https://www.washingtonpost.com/politics/courts_law/getting-a-photo-id-so-you-can-vote-is-easy-unless-youre-poor-black-latino-or-elderly/2016/05/23/8d5474ec-20f0-11e6-8690-f14ca9de2972_story.html), [formerly incarcerated](https://www.pbs.org/newshour/nation/leaving-prison-without-a-government-id-can-block-access-to-housing-jobs-and-help), or [Black](https://www.npr.org/2012/02/01/146204308/why-millions-of-americans-have-no-government-id) are less likely than their richer, White counterparts to have a valid ID. In any document verification step, there must be a clear way for a claimant to get in touch with a representative of the agency to find an alternative method for proving they are who they say they are. Otherwise, people without IDs are categorically going to be denied benefits in a racially skewed outcome.
2. No UX is perfect, and those with lower digital literacy may need additional support or other lower-tech mechanisms to complete their application and prove they are who they say they are. We note this here because [Black and Latinx adults are 2-3 times less likely](https://nces.ed.gov/pubs2018/2018161.pdf) than their White counterparts to be digitally literate.

## UX metrics

There is currently no way to tell the difference between someone who gave up because they were a fraudster and knew they couldn’t pass the step, and someone who gave up because they didn’t understand or have the required documentation to move on. An unknown number of legitimate claimants are being prevented from receiving the benefits for which they are eligible. This marks a failure of the UI system that has not received as much attention as it deserves.

Success ought to look like ensuring every legitimate claimant is able to access the benefits for which they are eligible; we should not assume that everyone who doesn't complete the application was trying to commit fraud. For more on this idea, [read this OpEd](https://www.governing.com/now/Government-Programs-Should-Measure-How-Well-They-Help-People.html) or see [Race and inequity in identify proofing methods](race-and-inequity-in-identity-proofing-methods/).

