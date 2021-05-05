# Deep dive: platform “bundling”



Alloy and Experian are different from the other vendors in that they explicitly and transparently leverage other companies’ technology as identity proofing platforms. Both take information that others have already interpreted and use that as an input to their own risk interpretation. Additionally, Idemia itself uses Experian.

Alloy has a platform that can combine multiple risk assessments about the same piece of data. For example, Alloy can interpret in parallel the fraud risk data sent by both SentiLink and Ekata about a particular Name + Address combination. Alloy has agreements with more than 65 partners in total that can be mixed and matched when setting up an identity proofing system. This immense flexibility \(and overlap with the vendors evaluated in this paper\) and the fact that no pricing information was made available make it hard to come to any conclusion about Alloy.

Experian’s approach is slightly different. They build some of the infrastructure themselves, and they rely on other companies for specific pieces of the puzzle: Acuant provides their document verification; EmailAge by LexisNexis gives them a risk assessment specifically about the longevity of an email address and the domain to which it belongs. Experian bundles the vendors and features into 2 or 3 offerings, as distinct from Alloy’s a la carte approach.

UI agencies themselves could also build their own platform by using different vendors at different steps of the process. \(If you wanted multiple products to provide synthetic identity detection on PII, it would likely be more effective and less risky to achieve that through Alloy--with the caveat that their pricing is unknown.\) For example:

1. Use your existing method to determine validity of SSN / Name / DOB combination
2. If that combination is valid, collect and use additional PII \(address, mother’s maiden name, email, phone, etc.\) and evaluate it with one vendor’s synthetic identity detection product.
3. If step 2 indicates a particular fraud risk, have that individual go through a document + biometric verification step.

