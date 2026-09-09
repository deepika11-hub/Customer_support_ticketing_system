
# Customer Support Ticketing System

A Salesforce-based Customer Support Ticketing System designed to manage customers, support tickets, support agents, resolutions, ticket categories, and customer feedback.

## Project Objective

The system provides an end-to-end support ticket management process, from ticket creation and agent assignment to resolution and customer feedback. It also provides management with reports and dashboards for monitoring ticket performance, priorities, agents, resolution time, and customer satisfaction.

## Key Features

- Support Ticket Management
- Customer Management
- Support Agent Management
- Ticket Assignment
- Ticket Status Tracking
- Resolution Management
- Customer Feedback and Ratings
- Duplicate Ticket Prevention
- Validation Rules
- Role-Based Security
- Automated Ticket Status Updates
- Email Notifications and Reminders
- Reports and Management Dashboard

## Salesforce Components

### Objects

- Support Ticket
- Support Agent
- Resolution
- Ticket Category
- Customer Feedback
- Account – Customer Company
- Contact – Customer

### Validation Rules

- Ticket Title Required
- No Future Creation Date
- Resolution Date Valid
- Resolution Time Positive
- Feedback Rating Required

### Record Types

- Internal Ticket
- Customer Ticket
- Technical Resolution
- Billing Resolution

### Automation

#### Screen Flows
- Create Support Ticket
- Assign Ticket to Support Agent

#### Record-Triggered Flows
- Ticket Created → Status = New
- Resolution Completed → Ticket Status = Resolved
- Customer Feedback Submitted → Ticket Status = Closed

#### Scheduled Automation
- Daily High-Priority Ticket Reminder
- Customer Satisfaction Survey
- Overdue Ticket Reminder

## Apex

- `SupportTicketDuplicateTrigger`
- `WeeklyTicketPerformanceBatch`
- `WeeklyTicketPerformanceScheduler`
- `OverdueTicketReminderScheduler`
- `DailySupportSummaryScheduler`

## Lightning Web Components

### Support Dashboard
Displays:
- Open Tickets
- Ticket Status Summary

### Ticket Management
- Create New Ticket
- Track Ticket Status

### Resolution Component
- Update Resolution Details
- View Resolution History

### Customer Feedback
- Submit Feedback
- View Feedback Ratings

## Reports

- Tickets by Category
- Tickets by Priority
- Open Tickets
- Resolved Tickets
- Agent Performance
- Customer Feedback

## Dashboard

The Customer Support Dashboard provides:

- Total Tickets
- Open Tickets
- Pending Tickets
- Resolved Tickets
- Average Resolution Time
- Customer Satisfaction Rating
- Tickets by Category
- Tickets by Priority
- Agent Performance

## Technologies Used

- Salesforce CRM
- Apex
- SOQL
- Lightning Web Components (LWC)
- Salesforce Flow
- Salesforce Reports
- Salesforce Dashboards

## Project Outcome

This project demonstrates the implementation of an end-to-end Salesforce CRM solution using declarative automation, Apex development, Lightning Web Components, security configuration, reporting, and dashboarding.

## Author

**Deepika M**
