# Identity resolution

To start with, identity proofing requires that the “self-asserted,” personally identifiable information (PII) provided by the user confirms that it belongs to a single, real person. It resolves this data by comparing it to public databases (e.g., checking the address provided by the user against a voter registration file). 

A step-up in certainty would be to use knowledge-based verification (aka “KBV,” aka “Knowledge-based authentication”) to confirm the resolved identity by asking a question based on information others are unlikely to have (e.g., the system asks the user to provide the amount of their last utility bill). Depending on the specific KBV used, this technique can be a good opportunity to identify those using stolen identities.

Beyond that, more in-depth resolution techniques do not contribute toward an IAL2 designation, but they can be an important part of a solution for detecting fraud via the use of stolen or manufactured identities. 

The more sophisticated forms of identity resolution are referred to as synthetic identity detection. With synthetic identity detection, machine learning (aka “artificial intelligence”) is used to combine the self-asserted data with other information you may have about a user (e.g., IP address, phone’s IMEI) and compare it with additional databases (e.g., telco records, credit header files, utility bills). It is through synthetic identity detection that criminals using stolen identities are typically found.

Some synthetic identity detection systems go even further and perform “network level” detection, e.g.:

* How old is the domain name of the email address provided?
* How many applications have there been from this IP address?
* Have accounts on other sites been created with this combination of name + phone?

**Note: **a Social Security Number can be “resolved” to a person through synthetic identity detection, but it is not considered “validated” with any certainty until the Social Security Administration weighs in.
