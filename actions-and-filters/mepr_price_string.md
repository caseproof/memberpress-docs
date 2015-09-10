---
layout: page
title: mepr_price_string
permalink: /actions-and-filters/mepr_price_string/
---

## Title

This is a **filter**.

## Description

This *filter* can be used to modify a price string for a given Membership, Subscription or Transaction. The price string basically describes the terms of what the member is purchasing. 

## Parameters

This filter is passed one parameter:

- __$obj__ - Either the MeprProduct (Membership Model), MeprSubscription or MeprTransaction object.
- __$show_symbol__ - this is a boolean value that determines if the currency symbol should be displayed

## Source

This hook is located in the 'format_price_string()' function in 'memberpress/app/helpers/MeprAppHelper.php'
