# Active Directory - Basic Help Desk Guide

## What is Active Directory?

Active Directory (AD) is a Microsoft directory service used to manage users, computers, groups and access within a Windows domain.

For a Help Desk technician, basic Active Directory tasks may include:

- Finding user accounts
- Checking account status
- Resetting passwords
- Unlocking accounts
- Checking group membership
- Finding computers in the domain
- Checking basic permissions

## Main Active Directory Objects

### User

A user account represents a person who needs access to company resources.

Example:

Username: j.smith  
Department: IT  
Status: Enabled

### Computer

A computer object represents a Windows device joined to the company domain.

Example:

Computer: PC-LUBLIN-001  
Operating System: Windows 11  
Domain: COMPANY.LOCAL

### Group

Groups are used to organize users and manage access to resources.

Example:

Group: Helpdesk

Members:
- j.smith
- a.brown

## Common Help Desk Tasks

### Password Reset

A user may contact the Help Desk because they forgot their password.

Basic procedure:

1. Verify the user's identity according to company policy.
2. Find the user account in Active Directory.
3. Reset the password.
4. Ask the user to sign in again.
5. Document the action in the ticket.

### Account Unlock

A user account can become locked after multiple incorrect login attempts.

Basic procedure:

1. Verify the user's identity.
2. Find the user account in Active Directory.
3. Check the account status.
4. Unlock the account if appropriate.
5. Ask the user to try logging in again.
6. Document the action in the ticket.

## Security

Help Desk technicians should follow company security procedures when handling:

- Passwords
- User accounts
- Permissions
- Group membership

Never change permissions or reset accounts without following the company's verification and authorization procedures.