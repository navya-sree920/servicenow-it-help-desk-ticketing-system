
# ServiceNow IT Help Desk Ticketing System

## Project Overview
A ServiceNow application designed to simplify IT support request management through employee self-service, automated ticket assignment, and manager dashboards.

## Objectives
- Allow employees to submit IT support tickets through the Service Catalog.
- Automatically route tickets to the appropriate support team.
- Assign tickets to designated support personnel.
- Track ticket status and priority.
- Provide managers with dashboards and reports for monitoring support requests.

## Key Features

### Employee Self-Service
Employees can submit tickets with their name, email, department, category, priority, short description, and detailed issue description.

### Automated Ticket Routing
Flow Designer routes tickets based on category:

| Category | Assignment Group | Assigned To |
|---|---|---|
| Hardware | Hardware Team | John Smith |
| Software | Software Team | Alice Brown |
| Network | Network Team | David Lee |
| Access | Access Team | Emily Wilson |
| Other | Other Support Team | Michael Brown |

### Ticket Lifecycle
Tickets move through the following statuses:
- New
- In Progress
- Resolved
- Closed

### Manager Dashboard
The dashboard includes:
- Total Tickets
- Open Tickets
- Critical Tickets
- Tickets by Status
- Tickets by Priority
- Tickets by Department

## Technologies Used
- ServiceNow App Engine Studio
- Service Catalog and Record Producer
- Flow Designer
- Custom Tables and Forms
- ServiceNow Data Visualization and Dashboards

## Workflow
1. An employee submits an IT support request.
2. A ticket record is created in the custom IT Help Desk Ticket table.
3. Flow Designer identifies the ticket category.
4. The ticket is assigned to the appropriate group and support person.
5. The manager monitors ticket statistics through the dashboard.

## Testing
- Verified employee ticket submission through the Service Catalog.
- Tested automatic assignment for ticket categories.
- Confirmed ticket data appears in the manager dashboard.

## Learning Outcomes
- Building custom applications using App Engine Studio.
- Creating record producers and employee-facing forms.
- Automating business processes using Flow Designer.
- Designing dashboards for IT service management.

## Future Enhancements
- Role-based access testing.
- Knowledge Base integration.
- Email notifications for ticket updates.
- SLA tracking and escalation rules.

## Author
ServiceNow Application Development Project
