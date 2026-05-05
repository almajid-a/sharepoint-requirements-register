# CSV Setup Guide (Microsoft Lists in Teams)

This guide explains how to create the Stakeholder Register and Requirements Register using the provided CSV templates.

---

## Overview

The CSV files in the `/data` folder are blank templates with headers designed to help recreate the list structure efficiently.

Based on testing, importing these CSV files creates columns with expected data types close to the original list. Some configuration may still be required after import.

---

## Setup Order

1. Create the **Stakeholder Register**
2. Create the **Requirements Register**
3. Configure the **Stakeholders lookup column**

---

# Part 1: Create Stakeholder Register

## Import CSV

1. Open Microsoft Teams  
2. Navigate to the desired Team and Channel  
3. Click **+ Add a tab**  
4. Select **Apps**  
5. Search for and select **Lists**  
6. (Optional) Choose whether to post to the channel  
7. Click **Save**  
8. Select **Create new list**  
9. Choose **Import from CSV**  
10. Upload:
    - `stakeholder-register.csv`  
11. Review detected column types  
12. Click **Next**  
13. Name the list:
    - Stakeholder Register  
14. Click **Create**

---

## Add Items (Optional)

1. Click **+ Add new item**  
2. Fill in fields  
3. Click **Save**

---

# Part 2: Create Requirements Register

## Import CSV

1. Click **+ Add a tab**  
2. Select **Apps**  
3. Search for and select **Lists**  
4. Click **Save**  
5. Select **Create new list**  
6. Choose **Import from CSV**  
7. Upload:
    - `requirements-register.csv`  
8. Review detected column types  
9. Click **Next**  
10. Name the list:
    - Requirements Register  
11. Click **Create**

---

## Add Items (Optional)

1. Click **+ Add new item**  
2. Fill in fields  
3. Click **Save**

---

# Part 3: Configure Stakeholders Lookup

## Remove Existing Column

1. Open the Requirements Register  
2. Click the **Stakeholders** column  
3. Select **Column settings → Edit**  
4. Delete the column  
5. Confirm deletion  

---

## Create Lookup Column

1. Click **+ Add column**  
2. Scroll and select **Lookup**  
3. Click **Next**  
4. Set:
   - Name: Stakeholders  
   - Description: (optional)  
5. Under **Select a list as a source**, choose:
   - Stakeholder Register  
6. Under **Select a column**, choose:
   - Title (recommended)  
7. Click **Save**

---

## Arrange Column Position

1. Drag the new **Stakeholders** column to the desired position  

---

## Adjust Form Layout

1. Open an item in the list  
2. Click the **Edit form icon** (pencil icon near the form controls)  
3. Select **Configure layout**  
4. Click **Edit columns**  
5. Drag the **Stakeholders** field to the desired position  
6. Click **Save**

---

# Final Check

Ensure that:

- Both lists are created correctly  
- Column names and types are accurate  
- Stakeholders lookup connects properly  
- Form layout is organized as expected  

---

# Summary

The CSV templates provide a fast and structured starting point for list creation.

After import, minimal configuration is required to finalize relationships, layout, and usability.
