# Grafico: The Non-Profit Annual Report Generator

## 1. Introduction

## 1.1 Purpose
Grafico is a cloud-based application that creates an annual report document using data provided by the user. 

## 1.2 Intended Audience
The intended audience is Nonprofit administrators, not technical users who need to create annual reports.

## 1.3 Intended Use
Manual report creation is tedious and time-consuming. Grafico automates the process of aggregating data, generating charts/graphs, and formatting the report document. This saves users time and effort.

Manual report creation lacks consistency. When reports are created manually, there may be inconsistencies in formatting, data accuracy, branding etc. Grafico provides consistent, standardized reports each time.

## 1.4 Scope

# 3. System Features and Requirements
### 3.1 Functional Requirements
- Data Integration
  - Ability to connect to various data sources such as databases, cloud storage, financial systems, HR systems, etc.
  - Options for uploading/inputting supplemental data not in other systems
  - Automated data validation and error checking
  - Customizable automated data refresh/import on a scheduled basis
- Visualizations
  - Options for different chart and graph types based on the data
  - Drag-and-drop positioning of visuals
  - Formatting options for colors, labels, sizing etc.
  - Dynamic updating of visuals when data changes
  - Exporting of visualizations as images/files
- Document Authoring
  - Use of pre-built report templates
  - Drag-and-drop positioning of visuals into templated layouts
  - Inserting and formatting of text, tables, images
  - Collaboration tools for commenting, reviews
  - Version history for document rollback
- Formatting & Branding
  - Style themes for consistent formatting, colors, fonts
  - Cover pages with logos, headers, footers
  - Table of Contents generation
  - Application of brand assets and guidelines
- Outputs & Distribution
  - Export report in formats like PDF, Word, PowerPoint
  - Print to physical printer
  - Emailing distribution of reports
- Permission controls over access
  - User Access Controls
  - Role-based permissions for access
  - Audit trail of accesses and changes

### 3.2 External Interface Requirements
Are there any UX and UI requirements that you must keep in mind as you build?

### 3.3 System Features
What features are required for the software to work?

### 3.4 Nonfunctional Requirements



## Front-end functionality
The user must be able to register and create an account first. Then create an annual report from existing templates through an modern, simple, and easy-to-use interface.

### Features
- A user must be able to Sign Up
- Sign up -> Collect information: contact information, unique username.
- User account
In the user account, the user should be able to edit his/her profile and manage reports
The user must be able to create, save, edit, delete a report

- The user must be able to share the report
The user must be able to share the generated report to social networks

### Sitemap and website structure

#### Landing page
The front page should be the form, the user should not have to click on another link to access the generator. Upon saving or generating the report, he will be prompted to login if not logged in.

### User account
The user account page is split in 02 sections. The profile section and reports management section.

### Sections
#### Section 1: Company Info and Mission Statement
- A word from the CEO or President
- Mission statement

#### Section 2: Accomplishments and activities
- Accomplishments
An accomplishment object is made of 02 fields
A text area and an image area
- Infographics (Maybe Google Charts)

#### Section 3. Personal Profiles

#### Section 4. Financials
- Funding Areas
- Consolidated Statements of Financial Position
- Consolidated Statements of Activities

#### Section 5. Donors List
List of donors

#### Section 6. How donors can help

#### Section 7. Pictures
