[![Deploy to Salesforce](https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png)](https://githubsfdeploy.herokuapp.com)

# Maica Post-Install Permission Deployment
Due to Salesforce packaging limitations related to Master-Detail relationships with standard objects, certain Permission Sets and Permission Set Groups required by the Maica managed package cannot be included directly in the package. This repository provides a post-install deployment process to create these permissions in your target org.

These permissions ensure that your users have the correct access to key objects and functionalities introduced by the Maica solution, including Booking Items, Connections, Service Bookings, Appointments, Participant Notes, Invoices, and more.

## Permission Sets
The following Permission Sets define granular Create, Read, Edit, and Delete access for core custom objects:

### Booking Item Access

- Maica - Booking Item - Create Access

- Maica - Booking Item - Read Access

- Maica - Booking Item - Edit Access

- Maica - Booking Item - Delete Access

### Connection Access

- Maica - Connection - Create Access

- Maica - Connection - Read Access

- Maica - Connection - Edit Access

- Maica - Connection - Delete Access

### Service Booking Access

- Maica - Service Booking - Create Access

- Maica - Service Booking - Read Access

- Maica - Service Booking - Edit Access

- Maica - Service Booking - Delete Access

These modular permissions can be assigned directly or combined through groups for role-based access control.

## Permission Set Groups
The following Permission Set Groups are also included and combine object permissions with functional access for common user roles:

- Maica - Create Billable Participant Notes & Object Permissions

- Maica - Global - Create Appointment & Object Permissions

- Maica - Global - Create Participant Notes & Object Permissions

- Maica - Global - Create Shift & Object Permissions

- Maica - Manage Invoices & Object Permissions

- Maica - Manage Service Booking & Object Permissions

- Maica - Service Agreement - Manage Budget & Object Permissions

- Maica - Sync NDIS Funding & Object Permissions

Each group includes the relevant Create/Edit/Delete access and is designed for use in standardised user role profiles across healthcare and support delivery teams.

## System Permissions
The repository also includes a general system-level permission set:

- Maica - System Permissions

This set includes:

- ManageCustomPermissions

- ViewRoles

- ViewSetup
