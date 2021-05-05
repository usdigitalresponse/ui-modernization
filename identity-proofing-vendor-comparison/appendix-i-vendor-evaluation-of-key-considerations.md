# Appendix I: Vendor evaluation of key considerations



For more information on each of the considerations, please see [Key Considerations](https://usdr.gitbook.io/unemployment-insurance-moderinzation/identity-proofing-vendor-comparison/identity-proofing-vendor-comparison#key-considerations).

For some of the vendors, the answer is “unknown,” and we continue working to try to find that information. For ease of reading on a variety of screen sizes, the evaluation is split into two charts:

## Part 1

<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left">Pricing</th>
      <th style="text-align:left">UX at account creation</th>
      <th style="text-align:left">Backlog management</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Alloy</td>
      <td style="text-align:left">Unknown</td>
      <td style="text-align:left">
        <p>Step-up process:</p>
        <p>- API for PII collection</p>
        <p>- UX for doc verification</p>
      </td>
      <td style="text-align:left">
        <p>- Has batch API to check PII</p>
        <p>- UX for doc verification</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">Cognito</td>
      <td style="text-align:left">$0.70 - $0.99 / verification</td>
      <td style="text-align:left">API for PII collection</td>
      <td style="text-align:left">Has batch API available but won&#x2019;t be able to verify phone number</td>
    </tr>
    <tr>
      <td style="text-align:left">Ekata</td>
      <td style="text-align:left">$0.10 - $0.25 / query</td>
      <td style="text-align:left">API for PII collection</td>
      <td style="text-align:left">No batch API to check PII</td>
    </tr>
    <tr>
      <td style="text-align:left">Experian</td>
      <td style="text-align:left">$0.10 - $0.25 / query, plus $2,500 or $6,500 set-up fee based on implementation
        detail</td>
      <td style="text-align:left">
        <p>Step-up process:</p>
        <p>- API for PII collection</p>
        <p>- UX for doc verification</p>
        <p>- UX for UI agents to input info provided via phone</p>
      </td>
      <td style="text-align:left">
        <p>- Has batch API to check PII</p>
        <p>- UX for doc verification</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">ID.me</td>
      <td style="text-align:left">$4.00 / verification; $2.00 for subsequent years&#x2019; renewal</td>
      <td
      style="text-align:left">- Complete UX for PII collection and doc verification</td>
        <td style="text-align:left">- UX for PII collection and doc verification</td>
    </tr>
    <tr>
      <td style="text-align:left">Idemia</td>
      <td style="text-align:left">$2.50 to $5.50 / verification</td>
      <td style="text-align:left">
        <p>Step-up process:</p>
        <p>- API for PII collection</p>
        <p>- UX for doc verification</p>
      </td>
      <td style="text-align:left">
        <p>- Has batch API to check PII</p>
        <p>- UX for doc verification</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">IDology</td>
      <td style="text-align:left">Unknown</td>
      <td style="text-align:left">
        <p>Step-up process:</p>
        <p>- API for PII collection</p>
        <p>- UX for doc verification</p>
      </td>
      <td style="text-align:left">
        <p>- API for PII collection</p>
        <p>- UX for doc verification</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">SentiLink</td>
      <td style="text-align:left">~$0.25 / verification</td>
      <td style="text-align:left">API for PII collection</td>
      <td style="text-align:left">Has batch API to check PII</td>
    </tr>
    <tr>
      <td style="text-align:left">Socure</td>
      <td style="text-align:left">Mid-to-high single digit cents / PII query; add&#x2019;l $1/query for
        doc verification</td>
      <td style="text-align:left">
        <p>Step-up process:</p>
        <p>- API for PII collection</p>
        <p>- UX for doc verification</p>
      </td>
      <td style="text-align:left">
        <p>- API for PII collection</p>
        <p>- UX for doc verification</p>
      </td>
    </tr>
  </tbody>
</table>

## Part 2



<table>
  <thead>
    <tr>
      <th style="text-align:left"></th>
      <th style="text-align:left">Identity proofing methods (and product names, if applicable)</th>
      <th style="text-align:left">Data sources</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">Alloy</td>
      <td style="text-align:left">Highly configurable: KBV, 2FA, synthetic identity detection (including
        looking at device &#x201C;fingerprinting&#x201D; and IP address), document
        verification, biometric verification</td>
      <td style="text-align:left">Partnerships with 65+ data vendors including ones we have or will evaluate:
        Acuant, Iovation from TransUnion, Ekata, Socure, Cognito, Sentilink, and
        IDology</td>
    </tr>
    <tr>
      <td style="text-align:left">Cognito</td>
      <td style="text-align:left">
        <p>- Cognito Identity Verification Service: 2FA, synthetic identity detection</p>
        <p>- Blocksore product: 2FA, synthetic identity detection, KBV
          <br />
        </p>
      </td>
      <td style="text-align:left">Credit bureaus and public data sources</td>
    </tr>
    <tr>
      <td style="text-align:left">Ekata</td>
      <td style="text-align:left">Synthetic Identity Detection</td>
      <td style="text-align:left">Public data sources -- does NOT check SSN</td>
    </tr>
    <tr>
      <td style="text-align:left">Experian</td>
      <td style="text-align:left">
        <p>Experian PreciseID: Synthetic Identity detection, KBV, 2FA</p>
        <p>Experian Identity Proofing: Document verification, biometric verification</p>
      </td>
      <td style="text-align:left">Credit file info; SSA Death Master File; marketing data; Motor vehicle
        info from auto dealerships and DMVs; public data sources</td>
    </tr>
    <tr>
      <td style="text-align:left">ID.me</td>
      <td style="text-align:left">Synthetic identity detection, document verification, biometric verification</td>
      <td
      style="text-align:left">Credit bureaus, SSA Death Master File, telco records, public data sources</td>
    </tr>
    <tr>
      <td style="text-align:left">Idemia</td>
      <td style="text-align:left">Idemia Proof: Synthetic identity detection, document verification, biometric
        verification</td>
      <td style="text-align:left">Credit file info; DMV database; &quot;Systems of record&quot;</td>
    </tr>
    <tr>
      <td style="text-align:left">IDology</td>
      <td style="text-align:left">
        <p>ExpectID: Synthetic identity detection</p>
        <p>ExpectID IQ: KBV, synthetic identity detection</p>
        <p>Document Scan Solution: both document verification and biometric verification</p>
      </td>
      <td style="text-align:left">
        <p>Motor vehicle info, voting record, creditor information, utility bills
          <br
          />
        </p>
        <p>Have &#x201C;Consortium Fraud Network&#x201D; for additional commercial
          sources</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">SentiLink</td>
      <td style="text-align:left">Synthetic identity detection</td>
      <td style="text-align:left">Credit bureaus, utility data, SSA Death Master File, selective service
        information</td>
    </tr>
    <tr>
      <td style="text-align:left">Socure</td>
      <td style="text-align:left">
        <p>KYC identity verification module &amp; Sigma Fraud products: synthetic
          identity detection</p>
        <p>DocV product: both document verification and biometric verification
          <br
          />
        </p>
      </td>
      <td style="text-align:left">Credit bureaus, utility data, telco, public data sources</td>
    </tr>
  </tbody>
</table>

