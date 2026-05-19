# Expense Claim System

This system is designed to help employees submit and get reimbursement for their expenses in a structured and efficient way. It starts when an employee creates an expense claim using a web or mobile application. The employee enters the details of the expense, such as amount, date, and purpose, and submits the claim for approval.

Once submitted, the claim goes through an approval process. A manager reviews the request and decides whether to approve or reject it. This step ensures that all expenses follow company policies and are legitimate. If the manager approves the claim, it moves to the next stage for payment processing.

Behind the scenes, several application services support this process. For example, a login system (SSO with Azure AD) ensures that only authorized users can access the system. The expense data is stored securely, and approval workflows help automate the decision process. The system also connects to an ERP system, which handles accounting and payment operations.

After approval, the finance team processes the reimbursement. The payment details are recorded, and the employee receives the money. The system keeps track of all transactions in a database for reporting and auditing purposes.

The technology layer supports all of this by providing servers, databases, and network infrastructure to run the applications reliably. Overall, the system reduces manual work, improves accuracy, and speeds up the reimbursement process for employees.
