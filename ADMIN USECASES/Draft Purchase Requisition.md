**Use Case: Draft Purchase Requisition Management**

**Actor:** Admin

**Use Case Description:** This use case outlines the process followed by the admin to manage draft purchase requisitions within the procurement system. The admin has the authority to review, approve, reject, or modify draft purchase requisitions submitted by requestors.

**Trigger Point:** The trigger point occurs when a requestor creates a draft purchase requisition and submits it for approval.

**Pre-conditions:**

1\. The admin is logged into the procurement system.

2\. There is at least one draft purchase requisition awaiting approval.

3\. The requestor has filled in all necessary details in the requisition form.

4\. The requestor has submitted the draft purchase requisition for approval.

**Post-conditions:**

1\. The admin takes appropriate action on the draft purchase requisition.

2\. The status of the requisition is updated based on the admin's decision.

3\. Comments and attached documents, if any, are saved and associated with the requisition.

**Normal Flow:**

1\. The admin accesses the draft purchase requisition management section of the procurement system.

2\. The system displays a list of draft requisitions awaiting approval.

3\. The admin selects a specific draft requisition from the list to review.

4\. The system presents the details of the selected requisition in the first panel, including:

- Request number
- Creation date
- Required delivery date
- Request type
- Priority
- Location
- Department
- Requestor details
- Note

5\. At the top right panel, the system indicates that the requisition needs admin approval and provides three buttons: create RFQ, cancel, and modify request.

6\. The admin reviews the requisition details and evaluates whether they meet the organization's requirements.

7\. If the requisition is satisfactory, the admin clicks the "Accept" button to approve it.

8\. The system updates the status of the requisition to "Approved" and saves the admin's decision.

9\. If modifications are required, the admin clicks the "Modify Request" button to make changes to the requisition.

10\. The system allows the admin to edit the requisition details as necessary.

11\. After making modifications, the admin resubmits the requisition for approval.

12\. If the requisition is not acceptable, the admin clicks the "Reject" button.

13\. The system updates the status of the requisition to "Rejected" and saves the admin's decision.

14\. The admin may add comments regarding the rejection in the comments panel at the bottom.

15\. The system saves the comments and updates the requisition status accordingly.

**Alternative Flow:**

1\. If the admin encounters any differences or issues with the requisition, they may choose to consult with the requestor or other relevant stakeholders before making a decision.

2\. In case of urgent modifications or approvals, the admin may directly contact the requestor or relevant department to expedite the process.

3\. If additional documents or information are required to evaluate the requisition, the admin may request the requestor to provide them before proceeding with approval or rejection.
