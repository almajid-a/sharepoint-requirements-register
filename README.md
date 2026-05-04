# SharePoint Requirements Register System

## Overview

This project presents a SharePoint-based Requirements Register designed to support structured requirement tracking, stakeholder linkage, and iterative project development.

It was developed as part of the ITBA BPMN Template initiative and evolved from an initial setup into a more structured and reusable system aligned with business analysis practices.

---

## Problem

Many student and project teams lack a simple, structured way to manage requirements, stakeholders, and iteration progress using accessible tools.

Common challenges include:
- Unstructured requirement tracking
- Limited visibility of stakeholders
- No clear iteration or prioritization structure
- Inconsistent organization across projects

---

## Solution

This project provides a SharePoint List-based system that enables:

- Structured requirement tracking
- Stakeholder linkage using lookup fields
- Iteration-based organization
- Clear prioritization and status management
- Multiple views to support different perspectives

The goal is to create a reusable and understandable solution that can be applied in both academic and organizational contexts.

---

## Target Users

- Business Analysis students  
- Project teams  
- Internal organizational teams using SharePoint  

---

## Key Features

- Requirement ID tracking (R-01, R-02, etc.)
- Status management (Draft, Completed, etc.)
- Iteration tracking (I-01, I-02)
- Priority classification
- Stakeholder linkage via lookup fields
- Notes and references for traceability
- Multiple views:
  - List view  
  - Board view  
  - Calendar view  

---

## List Structure

The SharePoint List includes the following key fields:

- Requirement ID  
- Requirement Title  
- Description  
- Status  
- Iteration  
- Due Date  
- Priority  
- Owner  
- Stakeholders (Lookup)  
- Related Process / BPMN Reference  
- Requirement Type  
- Notes  

Detailed structure is available in the `/docs` folder.

---

## Setup Instructions

To recreate this solution:

1. Create a new SharePoint List  
2. Add columns based on the structure described in `/docs/list-structure.md`  
3. Configure views:  
   - List view for standard tracking  
   - Board view for status-based grouping  
   - Calendar view based on due dates  
4. Create or link a Stakeholder Register list  
5. Configure lookup relationships between lists  

---

## Documentation

Additional documentation is available in the `/docs` folder:

- overview.md — background and context  
- list-structure.md — detailed column definitions  
- setup-guide.md — step-by-step configuration  

---

## Screenshots

See the `/screenshots` folder for examples of the working solution, including:

### List View Overview
![List View Overview](screenshots/list-view-overview.png)

### List View Detail
![List View Detail](screenshots/list-view-detail.png)

### Board View
![Board View](screenshots/board-view.png)

### Calendar View
![Calendar View](screenshots/calendar-view.png)

### Requirement Form
![Requirement Form](screenshots/requirement-form.png)

---

## Project Context

This solution was developed alongside a BPMN Template project that focuses on improving process modeling consistency and clarity.

The Requirements Register supports this work by providing a structured way to manage requirements and track iterative improvements.

---

## Future Improvements

- Export as reusable SharePoint template  
- Integration with BPMN modeling workflows  
- Enhanced automation using Power Automate  
- Improved reporting and dashboards  

---
