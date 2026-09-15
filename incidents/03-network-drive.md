# Incident 03 – Network Drive Access Issue

## Scenario

A user was unable to access the department's network drive. Internet access was working normally, but the network location could not be reached.

## Troubleshooting

1. Checked the user's Active Directory account and confirmed that the account was active.
2. Verified that the user had the correct group membership and permissions for the network drive.
3. Checked the file server and confirmed that it was online and functioning normally.
4. Confirmed that other users could access the network drive.
5. Checked the user's computer and confirmed that it had network connectivity, a valid IP address and working internet access.
6. Tested connectivity to the file server. Ping and DNS resolution were working correctly.
7. Tested the SMB connection and found that it was unsuccessful.
8. Checked the firewall configuration and found that TCP port 445 was blocked by an incorrect firewall rule.
9. Corrected the firewall rule to allow SMB traffic to the file server.
10. Asked the user to test the network drive again.
11. The user confirmed that the network drive was accessible and that files could be read and written successfully.

## ServiceNow

* Incident created and documented in ServiceNow.
* Status changed from **New → In Progress → Resolved**.
* Troubleshooting actions documented.
* Resolution code: **Solution provided**.
* Resolution notes and close notes added.

## Root Cause

An incorrect firewall rule on the user's computer was blocking SMB traffic on TCP port 445.

## Resolution

The firewall rule was corrected to allow SMB traffic to the file server. The user confirmed that the network drive was accessible and working normally.

## Screenshot

![Resolved network drive incident](SCREENSHOT_FILENAME)

