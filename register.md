# Account Registration

**User Account Registration:**

As a new user, I want to register with my name, username, age and country, so that I can create an account and access the habit tracking feature.

**Acceptance Criteria:**
1. Required Fields
 - The system must require:
	- Name
	- Username
	- Age
	- Country
    - Password
    - Confirm Password

2. Username Rules
- Must be unique (no duplicates allowed)
- Must follow format rules (e.g., no special characters except `_` or `.`

3. Age Validation
- Must be a valid number
- Must meet minimum age requirement (e.g., 18+ if applicable)

4. Form Validation
- All fields must be validated before submission
- Clear error messages must be shown for invalid or missing inputs

5. Password Validation
- Password must be 8 characters long with alphnumeric and must contain at least one special characters `_-&@#$`
- Password and confirm password must be same.
6. Failure Handling
- If registration fails (e.g., username taken or invalid email etc), user is informed clearly and can retry.

**Priority:** High
**Story Points:** 5
**Notes:**
- Consider edge cases like users entering fake ages (people will try, always).
- Decide early if username rules include special characters or just alphanumeric. This stuff comes back to haunt you.
- Think about future proofing: will you need email/phone verification later? If yes, design with that in mind now.
- Localization might matter if you're collecting country. Don't hardcode assumptions.
