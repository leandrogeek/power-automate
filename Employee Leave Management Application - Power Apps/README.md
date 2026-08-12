
## Leave Management System Using Microsoft Power Apps

The Power Apps-based leave management system helps organizations handle leave applications, approvals, and tracking approval status from one place. It eliminates the need to rely on fragmented tools like SharePoint lists, Teams chats and email threads for managing leave requests, by centralizing everything into a single solution.

---
## Advantages of the Leave Tracker App

Below are the key benefits of the leave tracker system: 

 - Supports multiple devices such as mobile phones, tablets, and more.
 - Ensure secure approvals by routing requests to the appropriate managers. 
 - Easy to set up with minimal configuration complexity.
 - Can be integrated directly into Microsoft Teams or SharePoint pages. 

## Features of the Leave Management App

The leave tracker application consists of three main pages:

 1. Apply Leave
 2. Leave History
 3. Approval Center

### 1. Apply Leave Page

Employees can submit leave requests using the leave application form available on this page.

A view of the Apply Leave page is shown below.

![Sample look of Leave Application form](https://blog.admindroid.com/wp-content/uploads/2026/05/Apply-Leave-Page-at-Leave-Management-App-Using-Power-Apps-1024x572.png)

### 2. Leave History Page

 - Displays all leave requests submitted by the logged-in user, along with their current status.
 - Allows users to cancel leave requests directly from this page.
 - Provides filters to view requests by Leave Type and Status.

Here’s a preview of the Leave History page.

![Leave History page in Leave Management System](https://blog.admindroid.com/wp-content/uploads/2026/05/Leave-history-page-in-Leave-management-system-1024x578.png)

### 3. Approval Center Page

 - Accessible only to managers assigned in Microsoft Entra ID.
 - Displays leave requests from their direct reports.
 - Allows managers to approve or reject leave and handle cancellation requests.

Below is the layout of the Approval Center page.

![Approval Center page in Leave Management System](https://blog.admindroid.com/wp-content/uploads/2026/05/Approval-Center-in-Leave-Management-App-1024x574.png)

For more details, refer to: <https://blog.admindroid.com/leave-management-system-using-power-apps/>

---

## How the Leave Tracker App Works:

Here is the simple workflow of the leave management system using Power Apps.

1. When an employee submits a leave request through the **Apply Leave page**, it is sent to the manager assigned in Microsoft Entra ID for approval.
2. On submission, the status of the leave request will be set to *Waiting for Approval*, and notifications are sent both the users and the respective manager.
3. The manager reviews all incoming leave requests in the **Approval Center** and can either *Approve* or *Reject* them.
4. If the leave request is *Approved* or *Rejected*, the respective employees are notified via email and Teams chat.
5. Employees can track all their leave requests in the **Leave History** page as well, which reflects the latest status updates.
6. If an employee cancels a leave while it is pending, it is immediately removed from the manager’s approval queue and cancelled.
7. If a user cancels an approved leave, they are prompted to enter a cancellation request, which is then sent to the manager for approval. 
8. If a cancellation request is approved by the manager, leave status will be updated to *Cancelled*, and notifications are sent via respective mediums. 

---