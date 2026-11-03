# Microsoft 365 Administration – Home Lab

## Project Overview

**Objective:** Build practical experience administering a Microsoft 365 environment, simulating common IT support and systems administration tasks found in a real business.

This project focuses on learning how to manage users, licences, groups, shared mailboxes, SharePoint permissions, account security and employee onboarding/offboarding.

The environment will be built using a Microsoft 365 trial tenant.

**Platform:** Microsoft 365 Business Premium  
**Duration:** 30-day trial  
**Difficulty:** Beginner  
**Status:** In Progress

---

## 1. Environment Setup

- [ ] Sign up for a Microsoft 365 Business Premium trial.
- [ ] Create and configure the Microsoft 365 tenant.
- [ ] Familiarise yourself with the Microsoft 365 Admin Centre.
- [ ] Explore the Microsoft Entra Admin Centre.
- [ ] Explore the SharePoint Admin Centre.
- [ ] Familiarise yourself with the Microsoft 365 Defender portal.
- [ ] Record the tenant configuration and initial setup.

**Evidence to document:**
- Screenshot of Microsoft 365 Admin Centre.
- Screenshot of Microsoft Entra Admin Centre.
- Brief explanation of each administration portal and its purpose.

---

## 2. User and Licence Management

**Objective:** Understand how to create, manage and administer employee accounts.

- [ ] Create three test users representing different employees.
- [ ] Assign appropriate Microsoft 365 licences.
- [ ] Review the available licence options and service plans.
- [ ] Update user profile information.
- [ ] Reset a user's password.
- [ ] Block a user's sign-in.
- [ ] Unblock a user's sign-in.
- [ ] Delete a test user.
- [ ] Explore the deleted users recovery process.

**Evidence to document:**
- Screenshot of created users.
- Screenshot showing licence assignments.
- Document the steps involved in creating a user.
- Document the password reset procedure.
- Explain the difference between blocking sign-in and deleting an account.

---

## 3. Groups and Shared Mailboxes

**Objective:** Learn how organisations manage access and communication through Microsoft 365.

### Groups

- [ ] Create a security group.
- [ ] Create a Microsoft 365 group.
- [ ] Add and remove members.
- [ ] Review group ownership and membership settings.
- [ ] Understand the difference between security groups and Microsoft 365 groups.
- [ ] Investigate how groups can be used to manage access to organisational resources.

### Shared Mailboxes

- [ ] Create a shared mailbox (e.g. support@yourtenant.onmicrosoft.com).
- [ ] Assign users Full Access permissions.
- [ ] Assign Send As permissions.
- [ ] Test access to the shared mailbox.
- [ ] Remove a user's access.
- [ ] Document when a shared mailbox is preferable to an individual user mailbox.

**Evidence to document:**
- Screenshots of group creation and membership.
- Screenshot of shared mailbox configuration.
- Document the difference between Full Access and Send As permissions.

---

## 4. SharePoint Administration and Permissions

**Objective:** Understand how organisations store, share and control access to documents.

- [ ] Create a SharePoint team site.
- [ ] Create a document library.
- [ ] Create folders for different departments.
- [ ] Upload sample documents.
- [ ] Add users to the SharePoint site.
- [ ] Configure site permissions.
- [ ] Configure document library permissions.
- [ ] Test access using different user accounts.
- [ ] Remove a user's permissions.
- [ ] Investigate permission inheritance.
- [ ] Document the difference between Owners, Members and Visitors.

**Suggested scenario:**

Create a company SharePoint site with separate folders for:

- Human Resources
- Finance
- IT Support

Configure permissions so that different employees have access to the appropriate resources.

**Evidence to document:**
- Screenshot of the SharePoint site.
- Screenshot of document library permissions.
- Explain how permission inheritance works.
- Document how you restricted access to sensitive documents.

---

## 5. Joiner Process (Employee Onboarding)

**Objective:** Simulate the onboarding of a new employee into an organisation.

### Scenario

A new employee has joined the company and requires access to the systems and resources necessary to perform their role.

### Checklist

- [ ] Receive an onboarding request.
- [ ] Verify the employee's details and required access.
- [ ] Create their Microsoft 365 user account.
- [ ] Configure their display name and profile information.
- [ ] Assign the appropriate Microsoft 365 licence.
- [ ] Generate temporary login credentials.
- [ ] Require a password change at first sign-in.
- [ ] Configure MFA registration.
- [ ] Add the employee to the appropriate security groups.
- [ ] Grant access to the relevant SharePoint site.
- [ ] Grant access to shared mailboxes if required.
- [ ] Verify that the employee can sign in.
- [ ] Test access to their assigned resources.
- [ ] Record completion of the onboarding process.

**Evidence to document:**

Write a short Joiner Procedure explaining each step, the reason behind it and how you verified successful onboarding.

---

## 6. Leaver Process (Employee Offboarding)

**Objective:** Simulate the secure removal of an employee's access when they leave an organisation.

### Scenario

An employee has left the company. Their access must be revoked, while important business information and communications are retained.

### Checklist

- [ ] Receive and verify the employee departure request.
- [ ] Confirm the employee's final working date.
- [ ] Block the user's sign-in.
- [ ] Revoke active sign-in sessions.
- [ ] Review and remove group memberships where appropriate.
- [ ] Review and revoke SharePoint permissions.
- [ ] Remove access to shared mailboxes and other resources.
- [ ] Review mailbox retention and data handover requirements.
- [ ] Convert the mailbox to a shared mailbox where appropriate.
- [ ] Assign mailbox access to an authorised colleague if required.
- [ ] Remove or reassign relevant licences in accordance with retention requirements.
- [ ] Delete the account only when authorised and appropriate.
- [ ] Document the completed offboarding process.

**Evidence to document:**

Create a Leaver Procedure explaining how you would securely offboard an employee, including the reasoning behind each action.

Include a walkthrough demonstrating the process using one of your test accounts.

---

## 7. Password Management and Multi-Factor Authentication

**Objective:** Understand identity security and common account support procedures.

### Password Management

- [ ] Reset a test user's password.
- [ ] Generate a temporary password.
- [ ] Configure the requirement to change the password at next sign-in.
- [ ] Investigate password reset permissions and administrator roles.
- [ ] Document the procedure for handling a password reset request.

### Multi-Factor Authentication (MFA)

- [ ] Explore MFA configuration in Microsoft Entra.
- [ ] Enable or configure an appropriate MFA policy.
- [ ] Register MFA for a test user.
- [ ] Test the sign-in process with MFA.
- [ ] Investigate how to handle a user who loses access to their authentication method.
- [ ] Document the process of troubleshooting MFA issues.

**Evidence to document:**
- Screenshot of MFA configuration.
- Screenshot of successful MFA registration (without exposing security information).
- Document how MFA improves account security.
- Write a short troubleshooting guide for common MFA issues.

---

## 8. Documentation and Troubleshooting

**Objective:** Develop the ability to document IT procedures clearly and resolve common user issues.

Create short troubleshooting guides for the following scenarios:

- [ ] User cannot sign in to Microsoft 365.
- [ ] User has forgotten their password.
- [ ] User cannot access a shared mailbox.
- [ ] User cannot access a SharePoint document library.
- [ ] User is not receiving MFA prompts.
- [ ] User has insufficient permissions to access a resource.

For each scenario, document:

1. Problem description.
2. Initial checks.
3. Troubleshooting steps.
4. Resolution.
5. Verification that the issue has been resolved.

---

## 9. Final Project Documentation

- [ ] Write a project overview.
- [ ] Document the Microsoft 365 environment.
- [ ] Include screenshots demonstrating completed tasks.
- [ ] Document the Joiner Procedure.
- [ ] Document the Leaver Procedure.
- [ ] Include a password reset and MFA walkthrough.
- [ ] Include a SharePoint permissions walkthrough.
- [ ] Add troubleshooting guides.
- [ ] Review the README for accuracy and clarity.
- [ ] Publish the completed project on GitHub.

### Suggested Repository Structure

```text
microsoft-365-home-lab/
│
├── README.md
│
├── documentation/
│   ├── environment-setup.md
│   ├── user-management.md
│   ├── groups-and-mailboxes.md
│   ├── sharepoint-permissions.md
│   ├── joiner-procedure.md
│   ├── leaver-procedure.md
│   └── password-and-mfa.md
│
├── troubleshooting/
│   ├── sign-in-issues.md
│   ├── password-reset.md
│   ├── shared-mailbox-access.md
│   ├── sharepoint-access.md
│   └── mfa-issues.md
│
└── screenshots/
    ├── admin-centre/
    ├── user-management/
    ├── sharepoint/
    ├── security/
    └── onboarding-offboarding/
```

---

## 10. Skills Developed

By completing this project, I aim to demonstrate practical familiarity with:

- Microsoft 365 Administration
- Microsoft Entra ID
- User and Licence Management
- Security Groups and Microsoft 365 Groups
- Shared Mailbox Administration
- SharePoint Administration
- Access Control and Permissions
- Employee Onboarding and Offboarding
- Password Management
- Multi-Factor Authentication (MFA)
- IT Documentation and Troubleshooting

---

## Project Completion Criteria

The project is considered complete when:

- [ ] All core administration tasks have been performed successfully.
- [ ] A complete Joiner Procedure has been documented.
- [ ] A complete Leaver Procedure has been documented.
- [ ] A practical leaver walkthrough has been completed.
- [ ] Password reset and MFA procedures have been demonstrated.
- [ ] SharePoint permissions have been configured and tested.
- [ ] Screenshots and supporting documentation have been uploaded to GitHub.

**Important:** This is a personal learning lab, not a production environment. All accounts and data are fictional. Never publish passwords, recovery codes, MFA secrets, tenant credentials or other sensitive information in the repository.
