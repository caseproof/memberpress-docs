---
layout: page
title: mepr_stripe_payment_form
permalink: /actions-and-filters/mepr_stripe_payment_form/
---

## Description

This **_filter_** is used to determine the search path for MemberPress Gateway interfaces. It can be used to modify where these files are found and loaded from.

## Examples

If you wanted to add your own, unique Gateway interface to MemberPress via your own addon, you could utilize this filter to add it to MemberPress.

For example, say you had a plugin named 'payment-central-interface' ... and your payment gateway interface file was in the main directory of this plugin called 'MeprPaymentCentralGateway.php' you could do something like this in your main plugin file:

{% highlight php %}
<?php
define('PCGI_PATH', dirname(__FILE__));

add_action('mepr_stripe_payment_form', 'pcgi_gateway_paths');

function pcgi_gateway_paths($paths) {
  $paths[] = PCGI_PATH;
  return $paths;
}
?>
{% endhighlight %}

As long as your gateway interface file is named 'Mepr.\*Gateway.php' and the classname is identical then your gateway interface should load up just fine.

## Parameters

This hook is passed one parameter:

- __$paths__ - The gateway interface search path to be modified and passed back through the filter.

## Source

  This hook is located in the 'paths()' function in 'memberpress/app/lib/MeprGatewayFactory.php'
