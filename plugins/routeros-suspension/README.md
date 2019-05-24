# Suspension plugin for Mikrotik RouterOS
This plugin synchronizes the list of suspended IP addresses from UNMS’ CRM to RouterOS based router. 

This plugin is compatible with UNMS v1.0.0 and higher.

The plugin synchronizes the suspended IPs and the suspension rules (NAT, Firewall) based on the frequency set in the plugin configuration. (This might be improved in the future, for example, this plugin could be triggered by webhooks monitoring the client’s service status.)

Be sure that suspended IPs from UCRM are in the `Monitored IP subnets` in the UNMS.

To all developers: feel free to extend or improve this plugin and share your code with others. You might find a better way how to handle the sync of the suspension rules or sync of the blocked IPs.
