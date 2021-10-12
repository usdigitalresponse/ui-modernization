# Recommendation 2: Increase accountability for ensuring rightful claimants make it through the system

An unknown number of legitimate claimants are being prevented from receiving the benefits for which they are eligible. This marks a failure of the UI system that has not received as much attention as it deserves.

There is currently no way to tell the difference between someone who gave up because they were a criminal and knew they couldn’t pass the step, and someone who gave up because they didn’t understand or have the required documentation to move on. 

But we can--and should--tell a different story: one that gives as much weight to how easy these systems are for the rightful claimants to pass through as it does to how good they are at catching criminal actors.

### Recommendation 2.1: Do not count incomplete applications as fraud

It is currently in the interest of both identity proofing vendors and the UI agencies that contract them to conflate unstarted and incomplete applications with fraud. The vendors’ performance looks more impressive if they don’t counter the perception that everyone who doesn’t get positively identified is fraudulent. UI agencies, under intense scrutiny from the public and US DOL, are able to look more effective. 

But, again: The fact that someone was stopped from receiving benefits does not mean that they were rightly stopped. Agencies and vendors should be careful with their language and not [imply that unstarted or incomplete applications are fraud](https://des.az.gov/sites/default/files/media/newsrelease-10-12-2020-DES-Partners-with-ID-me-to-Further-Prevent-Unemployment-Fraud-through-Advanced-Identity-Verification-System.pdf).

The agencies should work with the vendor(s) that provide their identity verification solutions to ensure that the unstarted and incomplete applications are tracked and reported separately from those whose incomplete or completed applications had a positive indicator of fraud detected. That data from the vendor should be made available on a user-by-user basis to the UI agency so they can connect it to their own claimant data and break it down by race. 

Distinguishing this “false” rejection rate from the overall rejection rate of these systems is a key step toward improving benefits participation rate.

### Recommendation 2.2: Usability test the complete experience

While the document+biometric verification products will have gone through usability testing within the vendor's company, UI agencies should usability test the end-to-end experience themselves or in partnership with the vendor.

Whether the identity proofing is included in the initial application, triggered by a change on the account, or requested as part of a backlog-clearing process, it exists in a context beyond what the vendor could've usability tested independently: e.g., surrounding website interface, digital notification or physical letter asking them to complete the identity proofing process. Here are some key questions to ask about the experience:

* How is someone notified that they need to go through additional identity verification? 
  * Does it make clear what people should do if they don’t have a photo ID or have difficulty going through the vendor’s process?
  * What methods are used, and are those effective for the population in question? (Have you considered using SMS?)
  * Has the notification content been usability tested in all languages? (Do people understand what is being asked of them, and the importance of them following through?)
* Is the claimant reminded to start the process if they don’t ever begin? (They should be.)
* How long does someone have to complete the identity proofing process? Does the data support this time period? (California increased the period [from 10 to 30 days](https://edd.ca.gov/About_EDD/pdf/news-21-03.pdf).)
* What languages is the vendor’s user experience available in?
* If someone starts but does not finish the application:
  * Is there a clear way from the vendor’s user experience for someone to get direct agency help if they are unable to provide what the process requires?
  * Is the claimant reminded to complete the process if they begin but do not finish? (They should be.)

By conducting their own usability testing, UI agencies have the opportunity to make sure that the experience has been tested by a representative sample of people based on the demographics of the population seeking UI benefits. If anything is found to be unclear, the agencies should work either on their own or with the vendor to ensure that the experience or communication is improved.

### Recommendation 2.3: Ask your doc+bio verification vendor for performance measures by skin type classifications

[In a 2018](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf) study co-authored by researchers at the MIT Media Lab and Microsoft Research, lighter-skinned men were more than 40x less likely to be misclassified than darker-skinned women in common face recognition software. A [response by IBM](https://www.ibm.com/blogs/research/2018/02/mitigating-bias-ai-models/) to that paper said that they made significant improvements to their system, but lighter-skinned men were _still_ 13x less likely to be misclassified than darker-skinned women. 

The [NIST Face Recognition Vendor Test](https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8280.pdf?campaign_id=158\&emc=edit_ot\_20200625\&instance_id=19710\&nl=on-tech-with-shira-ovide\&regi_id=57534\&segment_id=31845\&te=1\&user_id=8703e060a3dae05ab6bb2ba72268174a) found that when image quality is low and you're trying to match a photo to one of many possibilities (1:N), "false negatives are generally higher in people born in Africa and the Caribbean, the effect being stronger in older individuals." 

If these patterns are at all present in the 1:1 matching use case between a selfie (which isn't necessarily going to be high quality or well-lit) and an ID photo, it would contribute to racial disparities in benefits participation rates.

Ultimately, more information is needed on how false rejection rate differs by skin type. [onfido](https://onfido.com),\* a company with a document+biometrific verification product, has been transparent about how its [false _acceptance_ rate differs by continent](https://onfido.com/resources/blog/creating-an-open-world-with-fair-identity-verification), but there doesn't appear to be data on false rejection rate by skin type from _any_ of the major players in the space. 

UI agencies should ask the vendor they are using for document+biometric verification for these performance metrics, and if there is any discrepancy between performance for different skin types, they should ask how the vendor is planning to improve. [Jumio](https://www.jumio.com),\* another company that provides this product, published "[5 Practical Ways to Reduce AI Bias in Online Identity Verification](https://www.jumio.com/reduce-ai-bias-online-identity-verification/)," which is a succinct and useful list to reference.

\*** Note:** USDR is neither affiliated with nor endorses any vendors. Additionally, at the time of this publication, neither onfido nor Jumio has been evaluated as part of USDR's [ID Proofing Vendor Comparison](https://usdr.gitbook.io/unemployment-insurance-moderinzation/identity-proofing-vendor-comparison/identity-proofing-vendor-comparison-1), but that shouldn't be seen as an indicator of their suitability for UI agencies' needs. 
