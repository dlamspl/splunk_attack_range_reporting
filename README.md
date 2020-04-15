# Splunk attack range reporting
A Splunk App for Attack Range Reporting. Provides dashboards for insights on your attack range simulations. 


Splunk attack range repo can be found [here](https://github.com/splunk/attack_range)

## What is it ?
It is a Splunk app that provides dashboards that enable a user of Splunk attack range to have better view of what simulations run, relevant security content from other Splunk apps and overview of the available Atomic Red tests.

## Compatibility and dependencies
v1.0.0 of the app is compatible with the below

+ Splunk 8.0.x
+ [Splunk Analytic Story execution v1.0](https://github.com/splunk/analytic_story_execution)
+ [Splunk Security Content v1.0.x](https://splunkbase.splunk.com/app/3449/)
+ [Security essentials v3.1.x](https://splunkbase.splunk.com/app/3435/)

### Dependencies
v1.0.0 of the app has the following depencencies

+ [Punchcard - Custom Visualization](https://splunkbase.splunk.com/app/3129/)
+ [Security essentials v3.1.x](https://splunkbase.splunk.com/app/3435/)
+ [Status Indicator - Custom Visualization](https://splunkbase.splunk.com/app/3119/)

## What does it look like ?

Main dashboard is showing simulations run, users, hosts, MITRE ATT&CK tactics and techniques, tests executed and potential mapping with analytic stories. 

![Main Dashboard](appserver/static/docs/img/ar_main_dashboardv1.0.png?raw=true "Main Dashboard")
