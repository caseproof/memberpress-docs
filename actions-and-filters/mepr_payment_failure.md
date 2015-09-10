---
layout: page
title: mepr_payment_failure
permalink: /actions-and-filters/mepr_payment_failure/
---

## Type

This is a **filter**.

## Description

This *filter* allows you to modify the url that the member is redirected to after their signup completes.

By default the checkout url is going to be the "Thank You" page. But using this filter a developer could add additional pages to the checkout process.

## Parameters

This *filter* is passed one parameter:

- __$txn__ - The transaction associated with the payment failure.

## Source

This action is located in the 'process_payment_form()' function in 'memberpress/app/controllers/MeprCheckoutCtrl.php'