**Use Case: Request for Quotation (RFQ)**


**Actor:** Admin

**Description:**

This use case outlines the process followed by users within a procurement web application to create, submit, and manage Request for Quotations (RFQs). The application provides a user-friendly interface with modules for viewing all RFQs, submitting new RFQs, managing open RFQs, closing RFQs, and saving RFQs for future reference.


**Trigger Point:**

The trigger point occurs when the user needs to procure goods or services and requires quotations from suppliers to proceed with the procurement process.

**Pre-conditions:**

1\. The Admin has access to the procurement web application.

2\. The Admin is authenticated and logged in.

3\. The Admin has the necessary permissions to create and manage RFQs.

4\. Supplier information is available in the system.

**Post-conditions:**

1\. RFQs are created and saved in the system.

2\. Suppliers receive RFQs and provide quotations.

3\. The Admin reviews and evaluates received quotations.

4\. The status of RFQs is updated accordingly (approved, pending, rejected, on hold).

**Normal Flow:**

1\. The Admin navigates to the RFQ management section of the procurement web application.

2\. The top module displays five cards: All RFQs, Submit RFQs, Open RFQs, Close RFQs, and Save RFQs.

3\. The Admin selects the "Submit RFQs" card to create a new RFQ.

4\. The system presents a form with fields to input RFQ details:

- RFQ Number (automatically generated)
- Supplier Count
- RFQ Name
- Requestor
- Quote Deadline
- Status (defaulted to "pending")

5\. The Admin fills in the required details for the RFQ.

6\. After filling in the details, the Admin submits the RFQ.

7\. The system saves the RFQ and sends notifications to selected suppliers with RFQ details and the deadline for submitting quotations.

8\. Suppliers receive the RFQ and provide quotations within the specified deadline.

9\. The Admin receives and reviews quotations from suppliers.

10\. Based on the received quotations, the user takes appropriate actions:

- If satisfied with a quotation, the user marks the RFQ as "approved."
- If none of the received quotations meet requirements, the user may mark the RFQ as "rejected" and initiate a new RFQ process.
- If further information or negotiation is required, the user may put the RFQ "on hold."

11\. The system updates the status of the RFQ accordingly.

12\. The Admin may close the RFQ once the procurement process is complete.

**Alternative Flow:**

1\. In urgent procurement scenarios, the Admin may directly contact suppliers outside the system to request quotations and manually input them into the system.

2\. If received quotations do not meet requirements or quality standards, the may extend the submission deadline or request revised quotations from suppliers.

3\. The Admin may choose to save RFQs for future reference without submitting them immediately. They can later retrieve and submit them as needed.
