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
Here are some potential system features for Grafico's annual report creation software:
- Dashboard
  - Customizable dashboard to view reports and track status
  - Overview of recent reports and activity
  - Access controls to restrict visibility
- Data Integration
  - Connectors to databases, APIs, file uploads
  - Automated scheduled data imports
  - Data validation and error checking
  - Custom SQL and no-code options
- Visualizations
  - Drag-and-drop chart builder
  - Library of chart types - bar, pie, line, scatter, etc.
  - Formatting options - colors, labels, styling
  - Dynamic updates when data changes
  - Drill down interactions
- Document Editor
  - Drag-and-drop report layouts
  - Collaborative editing tools
  - Version history and rollbacks
  - Commenting and annotations
  - Standard text formatting options
- Templates & Branding
  - Library of report templates
  - Branding manager for colors, fonts and assets
  - Cover pages and print layouts
  - Table of contents generation
- Review & Approval
  - User access controls and permissions
  - Automated changelog reports
  - Annotation and comment tools
  - Customizable review workflows 
  - eSignature integration
- Publishing & Distribution
  - PDF, Word, PowerPoint exports
  - Print to local printer
  - Emailing and scheduling
- Access Controls
  - Role-based access permissions
  - Single sign-on integration  
  - Audit logs for access and changes
- Admin Console
  - User, data and settings management
  - Usage monitoring and analytics
  - Customization of fields, attributes
  - Configuration of modules and integrations

### 3.4 Nonfunctional Requirements
Here are some potential non-functional requirements for Grafico's annual report creation software:
- Performance
  - Fast response times for report generation (<5 sec)
- Scalability
  - Cloud-native architecture for elastic scaling
- Availability & Reliability
  - Regular backups
- Security
  - Role-based access control
- Usability
  - Intuitive, responsive UI design
  - Contextual help documentation
  - User testing and feedback incorporated
  - ADA-compliant accessibility support
- Maintainability
  - Modular architecture
  - Well-documented code and APIs
  - Automated testing and CI/CD
  - Monitoring and observability baked in
- Data Governance
  - GDPR and CCPA compliant
  - Right to be forgotten