## MBE - User Deactivation Serverless

This AWS Lambda project is designed to automatically manage inactive users in the system.

### 🔧 Purpose
- Automatically **deactivates users** who have not logged in for **more than 6 months**.

### ⏱️ Execution
- Runs as a **scheduled/background thread** on a **weekly basis**.

### ✅ Key Actions
- Scans for users with **over 6 months of inactivity**.
- **Deactivates** those users in the system.
- **Updates** all **related database tables** accordingly.
- **Sends notification emails** to administrators about the deactivated users.

### [Click here](https://franconnect.atlassian.net/wiki/spaces/CO/pages/11763220494) to know more.
