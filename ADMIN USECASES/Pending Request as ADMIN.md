**Use Case: Pending Request as ADMIN**

**Description:**

This use case outlines the process of an ADMIN managing a pending request within a system. The ADMIN has the authority to either accept, reject, or modify the request based on certain criteria.

**Trigger Point:**

The trigger point occurs when a pending request is received in the system and needs to be processed by the ADMIN.

**Pre-conditions:**

1\. The ADMIN is logged into the system.

2\. A pending request is available for review and action.

**Post-conditions:**

1\. The pending request is either accepted, rejected, or modified by the ADMIN.

2\. Any necessary updates or changes to the request are recorded in the system.

**Normal Flow:**

1\. The ADMIN logs into the system and navigates to the Purchase requisitions dashboard, and selects a specific pending request

2\. The system displays a list of pending requests with relevant details including:

- Request number
- Creation date
- Required delivery date 
- Request type
- Priority
- Location
- Department
- Requestor details
- Note

3\. The ADMIN selects a pending request from the list to review in detail.

4\. The system displays the detailed information of the selected request including:

- Request details (as mentioned in the first panel)
- Order list panel showing items' details such as name, category, quantity, unit, price, total cost, and status.
- The admin reviews the requesting cost, total cost at bottom of the order line.
- Comments panel for any additional notes or messages related to the request.
- Attach documents section for any relevant files or documents attached to the request.

5\. The ADMIN reviews the request details and evaluates whether it meets the required criteria.

6\. If satisfied, the ADMIN clicks the "Accept" button.

- The system updates the status of the request to "Accepted".
- An acknowledgment notification is sent to the requestor.

7\. If the request does not meet the criteria or requires modification, the ADMIN clicks the "Modify Request" button.

- The system allows the ADMIN to make necessary changes to the request details.
- After modifications, the ADMIN can choose to accept the modified request.

8\. If the request is considered inappropriate or cannot be fulfilled, the ADMIN clicks the "Reject" button.

- The system updates the status of the request to "Rejected".
- A notification is sent to the requestor informing them of the rejection along with the reason if provided.

9\. The ADMIN may add any relevant comments regarding the decision made.

10\. The system saves all actions taken by the ADMIN and updates the request status accordingly.

**Alternative Flow:**

1\. If the ADMIN needs to consult with another department or higher authority before deciding, they can choose to forward the request for review before taking any action.

2\. In case of technical issues or discrepancies in the request details, the ADMIN may escalate the issue to the technical support team for resolution before proceeding with any action.
