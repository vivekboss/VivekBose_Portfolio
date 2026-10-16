# 🔑 Password Reset & Account Lockout

## Before You Reset
- [ ] **Verify the user's identity** per company policy (employee ID, manager confirmation, security questions)
- [ ] Never ask for the user's current password
- [ ] Confirm you are authorised to reset this account type

## Steps (Active Directory environment)
1. Open **Active Directory Users and Computers** (or the admin portal).
2. Search for the user account.
3. Check the account status: **locked out**, **disabled**, or **password expired**.
4. **Unlock** the account if locked; find the cause (old password saved on a phone/Outlook/mapped drive is common).
5. **Reset** the password with a temporary one; tick *User must change password at next logon*.
6. Share the temporary password through a secure approved channel.
7. Ask the user to log in and confirm access (also email / Microsoft 365).

## Prevention Tips for Users
- Update saved passwords on all devices after a change
- Use a password manager and strong, unique passwords
- Enable MFA where available

## Document
Who requested, how identity was verified, action taken, time.
