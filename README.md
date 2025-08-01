# 🚨 ServiceNow Urgent Incident Notification Workflow

---

## 🛠️ Technologies Used

- **ServiceNow Personal Developer Instance (PDI) - Yokohama Release**
- **Draw.io** (for architecture diagramming)

---

## 🏢 System Overview

A fictional transportation app company—renowned for its reliable network infrastructure, supporting ride-hailing services across hundreds of cities worldwide—recently faced a major service disruption. Due to a malfunctioning notification workflow, a critical network outage in a major city data center went unnoticed for 2 hours, causing widespread disruption and loss.

**Incident Details:**
- ❗ Critical network outage was not flagged due to failed notifications.
- 💸 Resulted in significant revenue loss and regulatory scrutiny.
- 🕒 A Critical priority incident was created, but no email notifications were sent to the Network Operations team.
- ⚠️ The system was expected to alert engineers within minutes of such incidents.

**Project Objective:**  
Fix the system so that urgent network incidents trigger immediate email notifications to IT engineers, preventing SLA breaches.

---

## 👩‍💻 Your Role

As a **junior ServiceNow admin** on the IT Operations team, you are tasked with closing a critical gap in the incident management system that supports the network infrastructure.

---

## 📝 Implementation Steps

1. **Identified Gaps**
   - Analyzed the scenario and the existing notification trigger.
   - Verified correct trigger and table selection.
   - Discovered bottleneck in the notification conditions.

2. **Refined Notification Conditions**
   - Removed outdated conditions.
   - Added:  
     - `Priority is Critical`  
     - `Assignment group is Networking Operations`

3. **Enhanced Notification Content**
   - Updated the action record to ensure email notifications include:
     - 🎯 Targeted, descriptive titles
     - 📝 Ticket number and detailed description of the issue

---

## 🗺️ Architecture Diagram

Visual representation of the complete system flow (created in Draw.io):

<img width="1704" height="694" alt="System Architecture Diagram" src="https://github.com/user-attachments/assets/f160aa56-618a-4229-b2c6-aa03cf96d5a0" />

---

## 🤖 Hypothetical AI Enhancement Scenario

Your company operates globally across multiple time zones. Critical incidents often occur outside business hours when senior engineers aren't available. The current escalation process follows a rigid hierarchy that doesn't account for engineer expertise, current availability, or incident complexity, leading to prolonged resolution times.

**How AI Agents Could Enhance Incident Routing:**  
Given the global nature of this company, there should ideally be 24/7, 365-day availability of resources to provide solutions. For AI agents to truly enhance incident routing, they must have access to key data points such as employee schedules, work hours, mean time to resolution, Microsoft Teams status, and performance reviews. The agent would then filter these elements by geographic region and create a rating system to identify top performers with the fastest resolution times across all regions.

When an incident is submitted during standard business hours in a user’s region, the AI agent would route it to the highest-rated, most available employee—determined by Teams status—according to the rating system, and continue this process until an appropriate resource is found. If the incident arises outside of standard business hours, it would automatically be routed to the closest region where business hours are active, applying the same logic.

Once the agent assigns an incident, it would automatically update the Microsoft Teams status of the selected employee with a “busy with incident” tag. Over time, the agent would leverage historical regional data and daily tracking to build a kind of “muscle memory,” continually improving its routing decisions.

---

## 📬 Contact

For questions or contributions, please open an issue or contact [@Edana87](https://github.com/Edana87).