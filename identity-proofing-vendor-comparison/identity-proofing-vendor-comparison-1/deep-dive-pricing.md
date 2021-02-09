# Deep dive: pricing

Given the variety of products from these vendors and the way that the information was provided, it’s hard to do a direct comparison -- but we can try by making a couple of assumptions and establishing some constants:

1. For the vendor with a set-up fee \(Experian\), the cost is amortized over 2 years and 10,000 claims per month.
2. For the vendors that provided approximate costs:
   1. Sentilink said $0.25 / verification: we will create a moderate cost range of $0.15 - $0.45 / verification.
   2. Socure said mid-to-high single digit cents / query: we will create this as a range of $0.04 - $0.09 / query.
3. Not all queries will result in a verified identity; we will stipulate that a best-case scenario for all vendors other than ID.me is 95%, and that the worst-case scenario is 80%. 
4. \*Because ID.me has a virtual in-person proofing step that none of the other vendors have, we will stipulate that their best-case scenario for achieving a verified identity is 99%, and that their worst case is 85%.

Below are the results of calculating average cost per query \(i.e., cost per new UI claim\) for the 6 vendors whose pricing information we have

|  | Low average cost per query | High average cost per query |
| :--- | :--- | :--- |
| **Cognito** | $0.56 | $0.94 |
| **Ekata** | $0.10 | $0.25 |
| **Experian** | $0.11 | $0.28 |
| **ID.me**  | $3.96 | $3.40 |
| **SentiLink** | $0.12 | $0.43 |
| **Socure** | $0.09 | $0.29 |

