---
title: "Do my community users need to be unique across all salesforce Orgs?"
categories:
  - Blog
  - Salesforce
tags:
  - Experience Cloud
  - Licenses
  - Users
---

First of all, why does Salesforce have a requirement for uniqueness of user names across all orgs? Simple answer is that back before MyDomain was commonplace, everyone logged in using login.salesforce.com. Therefore Salesforce needed to know what org the username belonged to so they could handle the login process.


For community users they will not login via login.salesforce.com therefore there is no reason to require uniqueness across all orgs - only in the org the experience site exists in. 


There are some caveats around partner license types - check out https://help.salesforce.com/s/articleView?id=sf.networks_licenses_limitations.htm&type=5 for more details
