# Ticket 08 — Moved to a New Team and Cannot Access Their Files or Folders

**Incident:** INC0012860
**Priority:** Medium
**Submitted by:** Tom Wilson
**Request Type:** Access Modification - Department Transfer

---

## Overview

A manager requested that an employee have access to a different department because they wanted to do a department transfer. The manager requested that this employee have IT Infrastructure tool access and remove the other department the user is transferring from, which is the Engineering department.

![Ticket overview](Screenshots/Ticket_08/01_Ticket_Overview.png)

---

## Investigation

I searched for the user given the provided information in the ticket and confirmed that the exisitng group matches the ticket and that all the information provided macthes the user before changing the user's group.

![Directory — user search](Screenshots/Ticket_08/02_Directory_User_Search.png)

![Adding the IT Infrastructure group](Screenshots/Ticket_08/03_Adding_IT_Infrastructure_Group.png)

---

## Resolution

After confirming that the current information of the user is correct, I went to groups, added the new IT Infrastructure group, and removed the Engineering group after adding the new group.

![Adding the IT Infrastructure group](Screenshots/Ticket_08/03_Adding_IT_Infrastructure_Group.png)

![Engineering group removed](Screenshots/Ticket_08/04_Engineering_Group_Removed.png)

---

## Verification

After that, I verified that the information was updated by asking the manager in Team Chat, and the manager confirmed the issue was resolved.

![Manager confirmed the transfer](Screenshots/Ticket_08/05_Manager_Confirmed_Transfer.png)

---

## Skills Demonstrated

- Active Directory
- Group Membership Management
- Access Provisioning
- Access Revocation
- Manager Communication

## Technologies Used

- ServiceDesk Simulator
- Active Directory
- Team Chat
