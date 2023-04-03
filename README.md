# PagerDuty + Mammoth Cyber Integration Benefits
* Escalate Mammoth Cyber generated security alerts according to your PagerDuty settings.
* Create high and low urgency incidents based on the severity of the event from the Mammoth Cyber alert level.

# How it Works
* You can use Mammoth Cyber cloud's monitoring funcitonality to generate security alerts based on who accessed which data and how often. Those security alerts can be sent to PagerDuty.
* You should create incident response workflows in PagerDuty to properly handle the security alerts sent from the Mammoth Cyber cloud.

# Requirements
* Mammoth Cyber integrations require an Admin role for account authorization. If you do not have this role, please reach out to an Admin or Account Owner within your organization to configure the integration.

# Support

If you need help with this integration, please contact Mammoth Cyber support desk: https://appaegis.atlassian.net/servicedesk/customer/portal/1

# Integration Walkthrough
## In PagerDuty

### Integrating With a PagerDuty Service
1. From the **Configuration** menu, select **Services**.
2. Either create a new service to handle the security alerts from Mammoth Cyber cloud, or identify an existing servie to use.

## In Mammoth Cyber
* Login to your Mammoth Cyber account as an administrator.
* Select "Monitor" from the menu bar on the left and then the "Alert" option under it.
* Click the "Alert Settigns" button at the upper right corner.
* The "Alert setting" page will appear. Pick a alert level you want to configure PagerDuty with, click the "PagerDuty" button.
* Your PagerDuty login will show up, you need to login with an admin role.
* Pick the service corresponding to the alert handling.

# How to Uninstall
In the "Alert setting" page, uncheck the PagerDuty option, to disable the integration.
