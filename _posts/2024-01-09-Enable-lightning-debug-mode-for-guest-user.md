---
title: "How can I enable lightning debug mode for an Experience site guest user?"
categories:
  - Blog
  - Salesforce
  - Experience
tags:
  - LWC
  - debug
---
If you have a need to enable debug mode for a guest user you will notice that the guest user does not appear in the list.

In order to turn on debug mode for the guest user you will need to use the developer console and set the field UserPreferencesUserDebugModePref to be true.
See example below:

```apex
update new User(Id = '<<GuestUserId>>', UserPreferencesUserDebugModePref=true);
```

