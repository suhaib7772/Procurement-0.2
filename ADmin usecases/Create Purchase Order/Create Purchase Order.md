**Use Case: Create Purchase Order for Specific Request**

**Actor:** Admin

**Description:** This use case details the process of an admin creating a purchase order for a specific request, including filling out necessary details, reviewing order lines, and specifying payment and shipping information.

**Trigger Point:** Admin receives a request for goods or services that require procurement and decides to create a purchase order for it.

**Pre-Conditions:**

1\. Admin is authenticated and logged into the system.

2\. Admin has access to the purchase order creation functionality.

3\. A specific request for goods or services is identified and documented in the system.

4\. Supplier details are available and selected for the procurement.

**Post-Conditions:**

1\. A purchase order is created and saved in the system with the details provided.

2\. The purchase order is available for further processing, such as approval or modification.

3\. Payment and shipping information are associated with the purchase order for future reference.

**Normal Flow:**

1\. Admin accesses the specific request in the system that requires procurement.

2\. Admin fills out the purchase order form with the following details:

- Creation date
- Required delivery date
- Request type
- Priority
- Location
- Department
- Supplier details
- Attachments (if any)

3\. Admin reviews the order lines provided in the request, including:

- Line 
- Name
- Category
- Quantity
- Unit
- Price
- Total cost
- Status

4\. Admin ensures accuracy and completeness of the purchase order details.

5\. Admin proceeds to the top right panel and decides whether to create the purchase order or delete the request:

- If ready to proceed, admin clicks on the "Create PO" button.
- If changes are required or the request is no longer valid, admin clicks on the "Delete" button.

6\. If "Create PO" is selected, the system generates a unique purchase order number and saves the order details.

7\. Admin verifies that the purchase order is created successfully and accessible in the system.

**Alternative Flow:**

1\. If additional information is needed for the purchase order:

- Admin communicates with the requester or supplier to gather necessary details.
- Admin updates the purchase order form accordingly.

2\. If the request needs modification or cancellation:

- Admin clicks on the "Delete" button in the top right panel.
- System removes the request and associated purchase order from the system.

3\. If there are issues with the order lines or supplier details:

- Admin reviews and rectifies any discrepancies or errors in the order lines or supplier information.
- Admin ensures all necessary attachments are included before proceeding with creating the purchase order.

4\. If the payment or shipping terms need customization:

- Admin enters the specific payment terms, payment mode, and any additional intercoms details in the bottom card of the form.
