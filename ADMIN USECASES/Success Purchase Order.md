**Use Case: Success Purchase Order**


**Actor:** Admin

**Use Case Description:**

` `The admin successfully processes a purchase order for a specific request within the procurement system.

**Trigger Point:**

The admin accesses the purchase order detail view for the specific request.

**Pre-conditions:**

` `The admin has appropriate permissions and access rights to manage purchase orders.

` `The purchase order details for the specific request are available in the system.

**Post-conditions:**

The purchase order is successfully submitted, and relevant stakeholders are notified.

**Normal Flow:**

1\. The admin accesses the purchase order detail view for the specific request.

2\. The system displays a modal confirming the action: "Success: The purchase order has been submitted successfully."

3\. The admin reviews the details provided in the purchase order form, including:

- Purchase order number
- Creation date
- Required delivery date
- Request type
- Priority
- Location
- Department
- Supplier details
- Attachments

4\. The admin confirms the submission by selecting the "Success" button.

5\. The system validates the provided information and submits the purchase order.

6\. Upon successful submission, the system updates the status of the purchase order to "Submitted" and sends notifications to relevant stakeholders.

7\. The admin reviews the order line details, including:

- List
- Name
- Category
- Quantity
- Unit
- Price
- Total cost
- Status

8\. The admin verifies that all order line details are accurate and aligned with the purchase order.

9\. The admin proceeds to review payment and shipping details.

**Alternative Flow:**

1. If the admin identifies errors or discrepancies in the purchase order details during step 3, they select the "Revise" button from the top right panel.
- The system navigates the admin to the purchase order form, allowing them to make necessary revisions.
- The admin resubmits the purchase order after making corrections.
1. If the admin decides to cancel the purchase order during any stage of the process, they select the "Delete" button from the top right panel.
- The system prompts the admin to confirm the deletion.
- If confirmed, the purchase order is removed from the system, and stakeholders are notified.
1. If there are issues with payment or shipping details during step 9, the admin revises the information and resubmits the purchase order accordingly.

