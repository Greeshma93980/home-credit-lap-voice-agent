# Home Credit LAP Voice Agent — Testing
## Objective
To test the Retell AI voice agent's handling of customer identity, loan eligibility, callback requests, and loan-transfer requests.
## Test Cases1. Successful Qualification
Input:Customer confirms identity and provides eligible answers for all seven required fields.
Expected result: Agent explains that a senior loan expert will follow up about interest rates and next steps.
Actual result: Tested — agent provided a follow-up response.

2. Callback Request
Input:Customer says they are busy and requests a callback.
Expected result:Agent asks for a suitable callback time and ends the current call politely.
Actual result:Tested — customer provided a preferred callback time.

3. Loan Transfer Request
Input: Customer mentions an existing property loan or asks for EMI reduction.
Expected result: Agent routes the conversation to the loan-transfer specialist handling step.
Actual result: Tested — agent responded with loan-transfer specialist guidance.

4. Agricultural Property
Input:Customer says the property is agricultural.
Expected result:Agent ends the eligibility assessment politely.
Actual result:Pending confirmation.

 5. Cash-Only Income
Input: Customer confirms that income is received only in cash.
Expected result: Agent ends the eligibility assessment politely.
Actual result: Not yet tested.

## Conclusion
Testing covers the main conversation paths. Additional tests should verify every disqualifying condition and confirm that the agent does not repeat questions or qualify customers with missing information.
