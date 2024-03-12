Here is the basic info for creating a Vlan for printers and accces points for CISCO Catalyst 9300. 





Explanation:

We create two VLANs: VLAN 100 for printers and VLAN 200 for access points.
We then assign the ports connected to printers to VLAN 100 and ports connected to access points to VLAN 200.
Make sure to replace GigabitEthernet1/0/1-24 and GigabitEthernet1/0/25-28 with the actual range of ports you want to assign to each VLAN. 
Also, replace switch_ip_address with the actual IP address of your switch. Additionally, replace admin with your actual username if it's different.


Always ensure that you have a backup of your configuration and that you understand the impact of the changes
you're making before applying them to a production environment.

