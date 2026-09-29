 Flows
 Happy Birthday Email Flow

Type: Scheduled-Triggered Flow

Object: Customer Account

Conditions:
- `Date_of_Birthday_is_today__c = True`
- `Email_ID__c` is not null

Action:
- Send the configured `Happy Birthday Email Alert`.
