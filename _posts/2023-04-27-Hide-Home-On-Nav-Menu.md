---
title: "Hide the Home option on Experience Cloud Navigation menu"
categories:
  - Blog
  - Salesforce
tags:
  - Experience Cloud
  - css
---
Within an experience cloud navigation menu it is not possible to remove the Home Option.
You may get a request from a client that they do not want the hope option to display - this can be easily hidden using the custom CSS below.


```css
.forceCommunityThemeNav .comm-navigation__top-level-item.mainNavItem:first-child{
    display: none;
    visibility: hidden;
}
```