# Account Login

**User Account Login:**

As a user, I want to log in using my username and password so that I can access my account and track my habits.

**Acceptance Criteria:**
1. Required Fields
 - The system must require:
	- Username
	- Password

2. Failure Handling
- If login fails (e.g., username or password empty or invalid username/password etc), user is informed clearly and can retry.

**Priority:** High
**Story Points:** 5
**Notes:**
- Consider edge cases like users entering wrong username/password.
- Decide early if username rules include special characters or just alphanumeric. This stuff comes back to haunt you.
- Think about future proofing: will you need 2-factor authentication later? If yes, design with that in mind now.
- Localization might matter if you're collecting country. Don't hardcode assumptions.