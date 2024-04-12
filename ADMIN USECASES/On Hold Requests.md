**Use Case: On Hold Requests**

**Actor:** Admin

**Trigger Point:** Admin accesses the system dashboard to review requests that are on hold.

**Description:** This use case describes the process of an admin managing requests that have been placed on hold within the system.

**Pre-Conditions:**

1\. Admin is authenticated and logged into the system.

2\. Requests have been placed on hold and are available in the system for review.

**Post-Conditions:**

1\. Admin successfully reviews and manages requests that are on hold.

2\. On hold requests are either approved, rejected, or taken off hold based on admin's actions.

**Normal Flow:**

1. Admin accesses the system dashboard.
1. Admin selects the "On Hold Requests" card.
1. The system displays a list of purchase requisitions that are on hold.
1. Admin reviews the details of each requisition in the list, including request number, name, location, date, total cost, priority, and status.
1. Admin may use the filter button and search bar to narrow down the list based on username, date, or other criteria.
1. Admin may scroll through the list using the number scroll at the bottom.
1. Admin selects a specific requisition from the list to view more details or take action.

**Alternative Flow:**

1\. If admin needs to search for a specific request:

- Admin uses the search bar in the second card to search by username or date.
- Admin filters the list based on specific criteria using the filter button.

2\. If admin requires further information about a request:

- Admin clicks on the request from the list to view additional details.
- Admin accesses attached documents or comments for more context.

3\. If admin needs to approve an on-hold request:

- Admin reviews the request details and clicks on the "Approve" button.
- System updates the status of the request to "Approved" and notifies the requester.

4\. If admin needs to reject an on-hold request:

- Admin reviews the request details and clicks on the "Reject" button.
- Admin provides a reason for rejection and confirms the action.
- System updates the status of the request to "Rejected" and notifies the requester.
