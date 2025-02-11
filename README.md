[![Deploy to Salesforce](https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png)](https://githubsfdeploy.herokuapp.com)

# Maica Client Care - Post Install

### Includes:
1. 'Maica - System Permissions' Permission Set

### Maica - System Permissions
**This Permission Set contains the following required permissions**:
- Create/Read/Update/Delete access to Funding/Funding Item
- Create/Read/Update/Delete access to Service Booking/Booking Item
- Customize Application System Permission

This needs to be assigned to all of your Maica users.

This Permission Set is not part of the Maica Managed Package but is manually installed via [this link](https://github.com/VerticAU/MaicaClientCare-PostInstall) as shown in this online demonstration video. The reason we need to do it this way is due to the Salesforce restriction that prevents us from including System Permissions and objects with a Master-Detail relationship to a standard object (Contact) to a package's Permission Sets.