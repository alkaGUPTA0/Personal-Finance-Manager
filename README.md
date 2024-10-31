# Personal-Finance-Manager
An advanced tool designed to manage personal finances, providing a secure and organized approach to tracking expenses, budget management, and transaction analysis. Key features include:

Secure Data Encryption: Employs a simple encryption scheme to protect transaction data, ensuring that sensitive information is stored securely. This feature provides confidentiality for transaction categories, amounts, and dates.

Budget Limit & Alert System: Users can set a customizable budget limit, and the program automatically monitors spending. When an expense exceeds 20% of the budget limit, a priority-based alert is triggered, highlighting categories with high spending for proactive budget control.

Sorted Transaction Viewer: Transactions are inserted into a binary search tree (BST), allowing efficient sorting by transaction amount. Users can view all transactions in sorted order, making it easy to spot large expenses and monitor spending trends.

Expense Summary Report: The system provides a detailed report of expenses across different categories, calculating the total spent and comparing it to the set budget limit. If spending exceeds the budget, it warns the user, enabling better financial decision-making.

Undo Last Transaction: For flexibility in data management, a stack-based undo feature allows users to remove the most recent transaction. This helps in quickly adjusting records when needed without going through detailed modifications.

Persistent File Storage with Encrypted Data: Users can save transactions to a file with encrypted fields for offline storage, ensuring data remains confidential. The program also allows reloading data from saved files, supporting continuity across sessions.
