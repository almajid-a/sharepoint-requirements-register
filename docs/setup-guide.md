# Setup Guide

This guide explains how to recreate the SharePoint Requirements Register System using Microsoft Lists within Microsoft Teams.

This solution is implemented using Microsoft Lists in Teams, which is backed by SharePoint.

---

## Step 1: Create a List in Microsoft Teams

1. Open Microsoft Teams  
2. Navigate to the desired Team and Channel  
3. Click the "+" (Add tab) at the top  
4. Select **Lists**  
5. Choose **Create a new list**  
6. Select **Blank list**  
7. Name the list:
   - Requirements Register  
8. Click **Create**

---

## Step 2: Add Columns

Add the following columns to match the system structure:

### Core Fields

- Requirement ID  
  - Type: Single line of text  

- Requirement Title  
  - Type: Single line of text  

- Description  
  - Type: Multiple lines of text  

- Status  
  - Type: Choice  
  - Suggested values:
    - Draft  
    - In Progress  
    - Completed  

- Iteration  
  - Type: Choice or text  
  - Example:
    - I-01  
    - I-02  

- Due Date  
  - Type: Date  

- Priority  
  - Type: Choice  
  - Suggested values:
    - Low  
    - Medium  
    - High  

- Owner  
  - Type: Person or text  

- Stakeholders  
  - Type: Lookup (linked to Stakeholder Register, see Step 4)

- Related Process / BPMN Reference  
  - Type: Single line of text  

- Requirement Type  
  - Type: Choice  
  - Suggested values:
    - Functional  
    - Design  
    - Analysis / Enabling  
    - Meta / Enabling  

- Notes  
  - Type: Multiple lines of text  

---

## Step 3: Configure Views

### List View
- Default tabular view for requirement tracking

---

### Board View
1. Click **View options**
2. Select **Create new view**
3. Choose **Board**
4. Group by:
   - Status

Purpose:
- Visualize requirements by status (Draft, In Progress, Completed)

---

### Calendar View
1. Create a new view  
2. Choose **Calendar**  
3. Select:
   - Date field: Due Date  

Purpose:
- Track deadlines and scheduling

---

## Step 4: Create Stakeholder Register (Optional but Recommended)

1. Create a new list named:
   - Stakeholder Register  

2. Add fields such as:
   - Name  
   - Role  
   - Department  

3. In the Requirements Register:
   - Set the **Stakeholders** column as a lookup field  
   - Link it to the Stakeholder Register  

Purpose:
- Enable stakeholder traceability across requirements

---

## Step 5: Populate Sample Data

Add a few example requirements:

- R-01  
- R-02  
- R-03  

Include:
- Different statuses  
- Different priorities  
- Assigned stakeholders  

Purpose:
- Validate structure and views

---

## Step 6: Validate the Setup

Ensure that:

- All fields are correctly configured  
- Board view groups by Status  
- Calendar view reflects Due Dates  
- Lookup field works correctly  

---

## Result

You now have a functional Requirements Register System that supports:

- Structured requirement tracking  
- Stakeholder linkage  
- Iteration-based organization  
- Multiple working views  

This setup can be extended or adapted based on project needs.
