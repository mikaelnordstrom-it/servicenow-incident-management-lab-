# Incident 02 – Outlook Email Issue

## Scenario

A user reported that Outlook was not receiving new emails, while sending emails still worked.

## Troubleshooting

1. Checked the user's Outlook configuration and confirmed that the Microsoft 365 account was configured correctly.
2. Checked DNS and firewall connectivity. No issues were found.
3. Checked Outlook on the web and confirmed that new emails were being received there.
4. Determined that the issue was isolated to the Outlook client.
5. Checked the Outlook connection status and found that Outlook was set to **Work Offline**.
6. Disabled **Work Offline** to restore the connection to Microsoft 365.
7. Asked the user to test Outlook again.
8. The user confirmed that new emails were being received.

## ServiceNow

* Incident created and documented in ServiceNow.
* Status changed from **New → In Progress → Resolved**.
* Troubleshooting actions documented.
* Resolution code: **Solution provided**.
* Resolution notes and close notes added.

## Root Cause

Outlook was set to **Work Offline**, preventing new emails from being synchronized with Microsoft 365.

## Resolution

Work Offline was disabled in Outlook. The connection to Microsoft 365 was restored and the user confirmed that new emails were being received.

## Screenshot
![Resolved Outlook incident](Skärmbild%202026-09-15%20090621.png)

