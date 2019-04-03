# PDQ-Inventory-Firewall-Fix

Run the following command to the end client inorder to allow access to the $Admin share

`netsh advfirewall firewall set rule group="File and Printer Sharing" new enable=Yes`

More Details: https://support.pdq.com/knowledge-base/1053
