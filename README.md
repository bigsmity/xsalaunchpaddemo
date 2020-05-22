# xsalaunchpaddemo

XSA Fiori Launchpad On-Premise Configuration With Cross-MTA Dependencies and UAA.

https://blogs.sap.com/2020/04/03/xsa-fiori-launchpad-on-premise-configuration-with-cross-mta-dependencies-and-uaa./



launchpaddemoapp2 has been updated to control tile visibility via scopes. To view the tile you must add the role template "launchpaddemoapp2_display" to a role collection and assign this to your user.

If you wish to disable this functionality, simply remove the following line from the site-content.json and manifest.json files in launchpaddemoapp2

"oAuthScopes": ["$XSAPPNAME.view"]




XSA Fiori Launchpad On-Premise Configuration With Cross-MTA Dependencies. (Deprecated: Does not support UAA)

https://blogs.sap.com/2020/02/03/xsa-fiori-launchpad-on-premise-configuration-with-cross-mta-dependencies./
