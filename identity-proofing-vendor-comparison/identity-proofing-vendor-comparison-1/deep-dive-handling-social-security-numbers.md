# Deep dive: handling Social Security numbers

UI agencies already have in place methods to determine whether a provided SSN / Name / DOB combination is real \(i.e., not synthetic\). That functionality can remain in place alongside any new identity proofing mechanisms, as long as there is clear communication between pieces of the system. 

There are 2 ways that vendors determine the validity of a provided Social Security Number \(Ekata doesn’t handle SSNs at all\). The second method is more “official,” but both Cognito and Socure believe their method to be effective.

1. Cognito and Socure have systems that search for prior use of a SSN / Name / DOB combination, e.g., through DMV records or credit files. A drawback of this approach \(depending on the details of the vendor’s implementation\) is that it is possible for synthetically created identities to have credit files. Additionally, the vendors that rely heavily on credit bureau sources will systematically be less likely to prove the identities of those with less access to credit. Via both Cognito and Socure, Alloy has this functionality. 
2. Experian, ID.me, and SentiLink have systems that check against the Social Security Administration Death Master File, which will not have any synthetic identities in it. All three vendors use additional methods to detect synthetic identities. However, it is updated at most weekly and is not a comprehensive record of all deaths in the country; a notable exception is that it excludes state death records. Via SentiLink, Alloy has this functionality. 

Note: Two vendors, SentiLink and Experian, have access to the SSA's new eCBSV product, which _for their financial customers only_ allows them to effectively query the SSA directly and thus know with near-certainty that the SSN / Name / DOB match, and belong to a live human. Unfortunately, the SSA does not currently allow for other uses of this API, despite how useful and effective it would be for the UI identity theft detection scenario. 

