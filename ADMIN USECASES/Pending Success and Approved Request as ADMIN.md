**Use Case: Pending Success and Approved Request as ADMIN**

**Actor:** Admin 

**Description:**

This use case describes the process followed by an ADMIN to manage a pending request that has been successfully reviewed and approved within the system. The ADMIN has the authority to create a Request for Quotation (RFQ), cancel the request, or modify it based on specific requirements.

**Trigger Point:**

The trigger point occurs when a pending request has been successfully reviewed and approved, requiring further action from the ADMIN.

**Pre-conditions:**

1\. The ADMIN is logged into the system.

2\. A pending request has been reviewed and approved by the relevant authority.

**Post-conditions:**

1\. The pending request is processed further based on the action taken by the ADMIN.

2\. Any necessary updates or changes to the request are recorded in the system.

**Normal Flow:** 

1\. The ADMIN logs into the system and navigates to the dashboard displaying pending requests that have been successfully reviewed and approved.

2\. The system presents a list of approved requests with relevant details, including:

- Request number
- Creation date
- Required delivery date
- Request type
- Priority
- Location
- Department
- Requestor details
- Note

3\. The ADMIN selects a specific approved request from the list to proceed with further action.

4\. The system displays the detailed information of the selected request, including:

- Request details (as mentioned in the first panel)
- Order list panel showing items details such as name, category, quantity, unit, price, total cost, and status.
- The admin reviews the requesting cost, total cost at bottom of the order line.
- Comments panel for any additional notes or messages related to the request.
- Attach documents section for any relevant files or documents attached to the request.

5\. The ADMIN evaluates the request and determines the next course of action.

6\. If additional quotes are required from vendors, the ADMIN clicks the "Create RFQ" button.

- The system generates a Request for Quotation (RFQ) based on the request details.
- The RFQ is sent to relevant vendors for pricing and quotations.

7\. If the request needs to be modified for any reason, the ADMIN clicks the "Modify Request" button.

- The system allows the ADMIN to make necessary changes to the request details.
- After modifications, the ADMIN can proceed with further actions as necessary.

8\. If the request is no longer required or cannot be fulfilled, the ADMIN clicks the "Cancel" button.

- The system updates the status of the request to "Cancelled."
- A notification may be sent to the requestor informing them of the cancellation.

9\. The ADMIN may add any relevant comments regarding the action taken.

10\. The system saves all actions performed by the ADMIN and updates the request status accordingly.

**Alternative Flow:**

1\. If the ADMIN encounters any discrepancies or issues with the approved request, they may choose to consult with the relevant department or higher authority before proceeding with any further action.

2\. In case of urgent modifications or cancellations, the ADMIN may directly contact the requestor or relevant stakeholders to expedite the process.
