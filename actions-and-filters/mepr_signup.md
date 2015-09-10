---
layout: page
title: mepr_signup
permalink: /actions-and-filters/mepr_signup/
---

## Type

This is an **action**.

## Description

This *action* triggers when a member signs up and their initial transaction completes. This action is identical to the [mepr_{$signup_type}_signup action]({{ '/actions-and-filters/mepr__signup' | prepend: site.baseurl }}) but will trigger regardless of the type of signup. The current valid signup types you can register actions for are 'free', 'non-recurring' and 'recurring'.

## Parameters

This *action* is passed one parameter:

- __$txn__ - The transaction associated with the current member signup.

## Source

This action is located in the 'process_signup_form()' function in 'memberpress/app/controllers/MeprCheckoutCtrl.php'