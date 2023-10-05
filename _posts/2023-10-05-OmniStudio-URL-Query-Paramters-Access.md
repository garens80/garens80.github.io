---
title: "How can I access query parameters from the URL in a Flexcard or Omniscript"
categories:
  - Blog
  - Salesforce
  - OmniStudio
tags:
  - OmniStudio
  - Flexcard
  - Omniscript
---
If you have a need to access the query parameters from a flexcard then you can use the following syntax in each.

## Flexcards
Within a flexcard you can access the parameter value by using Params for example: {Params.test} to get the query parameter named test.

## Omniscripts
Within an omniscript you can simply access the parameter value by using the name - no need to prefix. For example: %test% to get the query parameter named test.
