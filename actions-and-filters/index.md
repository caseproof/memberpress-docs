---
layout: page
title: MemberPress Actions & Filters
permalink: /actions-and-filters/
---

## Transactions

- filter: [mepr_create_transaction]({{ '/actions-and-filters/mepr_create_transaction' | prepend: site.baseurl }})
- filter: [mepr_update_transaction]({{ '/actions-and-filters/mepr_update_transaction' | prepend: site.baseurl }})
- filter: [mepr_delete_transaction]({{ '/actions-and-filters/mepr_delete_transaction' | prepend: site.baseurl }})
- filter: [mepr_delete_transaction]({{ '/actions-and-filters/mepr_delete_transaction' | prepend: site.baseurl }})
- action: [mepr_txn_transition_status]({{ '/actions-and-filters/mepr_txn_transition_status' | prepend: site.baseurl }})
- action: [mepr_txn_store]({{ '/actions-and-filters/mepr_txn_store' | prepend: site.baseurl }})
- action: [mepr_txn_status\_{$status}]({{ '/actions-and-filters/mepr_txn_status_' | prepend: site.baseurl }})
- action: [mepr_payment_failure]({{ '/actions-and-filters/mepr_payment_failure' | prepend: site.baseurl }})
- action: [mepr_txn_expired]({{ '/actions-and-filters/mepr_txn_expired' | prepend: site.baseurl }})
- action: [mepr_transaction_expired]({{ '/actions-and-filters/mepr_transaction_expired' | prepend: site.baseurl }})

## Subscriptions

- action: [mepr_downgraded_{$type}_sub]({{ '/actions-and-filters/mepr_downgraded__sub' | prepend: site.baseurl }})
- action: [mepr_downgraded_sub]({{ '/actions-and-filters/mepr_downgraded_sub' | prepend: site.baseurl }})
- action: [mepr_sub_created]({{ '/actions-and-filters/mepr_sub_created' | prepend: site.baseurl }})
- action: [mepr_new_{$type}_sub]({{ '/actions-and-filters/mepr_new__sub' | prepend: site.baseurl }})
- action: [mepr_new_sub]({{ '/actions-and-filters/mepr_new_sub' | prepend: site.baseurl }})
- action: [mepr_sub_created]({{ '/actions-and-filters/mepr_sub_created' | prepend: site.baseurl }})
- action: [mepr_upgraded_{$type}_sub]({{ '/actions-and-filters/mepr_upgraded__sub' | prepend: site.baseurl }})
- action: [mepr_upgraded_sub]({{ '/actions-and-filters/mepr_upgraded_sub' | prepend: site.baseurl }})
- action: [mepr_sub_created]({{ '/actions-and-filters/mepr_sub_created' | prepend: site.baseurl }})
- action: [mepr_subscr_transition_status]({{ '/actions-and-filters/mepr_subscr_transition_status' | prepend: site.baseurl }})
- action: [mepr_subscr_store]({{ '/actions-and-filters/mepr_subscr_store' | prepend: site.baseurl }})
- action: [mepr_subscr_statu\_{$status}]({{ '/actions-and-filters/mepr_subscr_status_' | prepend: site.baseurl }})
- action: [mepr_limit_payment_cycles_reached]({{ '/actions-and-filters/mepr_limit_payment_cycles_reached' | prepend: site.baseurl }})

## Members

- filter: [mepr_admin_capability]({{ '/actions-and-filters/mepr_admin_capability' | prepend: site.baseurl }})
- filter: [mepr_logout_url]({{ '/actions-and-filters/mepr_logout_url' | prepend: site.baseurl }})
- filter: [mepr_login_title]({{ '/actions-and-filters/mepr_login_title' | prepend: site.baseurl }})
- filter: [mepr_custom_field_html]({{ '/actions-and-filters/mepr_custom_field_html' | prepend: site.baseurl }})
- filter: [mepr_user_product_signup_date_order]({{ '/actions-and-filters/mepr_user_product_signup_date_order' | prepend: site.baseurl }})
- filter: [mepr_user_formatted_address]({{ '/actions-and-filters/mepr_user_formatted_address' | prepend: site.baseurl }})
- filter: [mepr_logout_url]({{ '/actions-and-filters/mepr_logout_url' | prepend: site.baseurl }})
- filter: [mepr_login_redirect_url]({{ '/actions-and-filters/mepr_login_redirect_url' | prepend: site.baseurl }})
- filter: [mepr_validate_login]({{ '/actions-and-filters/mepr_validate_login' | prepend: site.baseurl }})
- filter: [mepr_process_login_redirect_url]({{ '/actions-and-filters/mepr_process_login_redirect_url' | prepend: site.baseurl }})

## Models

- filter: [mepr_cpt_model_url]({{ '/actions-and-filters/mepr_cpt_model_url' | prepend: site.baseurl }})
- filter: [mepr_get_model_attribute\_{$attribute}]({{ '/actions-and-filters/mepr_get_model_attribute_' | prepend: site.baseurl }})
- filter: [mepr_set_model_attribute\_{$attribute}]({{ '/actions-and-filters/mepr_set_model_attribute_' | prepend: site.baseurl }})

## Controllers

## Views

- filter: [mepr_view_paths_get_string\_{$string}]({{ '/actions-and-filters/mepr_view_paths_get_string_' | prepend: site.baseurl }})
- filter: [mepr_view_paths_get_string]({{ '/actions-and-filters/mepr_view_paths_get_string' | prepend: site.baseurl }})
- filter: [mepr_view_get_string\_{$string}]({{ '/actions-and-filters/mepr_view_get_string_' | prepend: site.baseurl }})
- filter: [mepr_view_get_string]({{ '/actions-and-filters/mepr_view_get_string' | prepend: site.baseurl }})
- filter: [mepr_view_paths]({{ '/actions-and-filters/mepr_view_paths' | prepend: site.baseurl }})

## Emails

- filter: [mepr_email_paths]({{ '/actions-and-filters/mepr_email_paths' | prepend: site.baseurl }})
- filter: [mepr_email_send_params]({{ '/actions-and-filters/mepr_email_send_params' | prepend: site.baseurl }})
- filter: [mepr_email_plaintext_body]({{ '/actions-and-filters/mepr_email_plaintext_body' | prepend: site.baseurl }})
- filter: [mepr_email_html_body]({{ '/actions-and-filters/mepr_email_html_body' | prepend: site.baseurl }})
- filter: [mepr_wp_mail_recipients]({{ '/actions-and-filters/mepr_wp_mail_recipients' | prepend: site.baseurl }})
- filter: [mepr_wp_mail_subject]({{ '/actions-and-filters/mepr_wp_mail_subject' | prepend: site.baseurl }})
- filter: [mepr_wp_mail_message]({{ '/actions-and-filters/mepr_wp_mail_message' | prepend: site.baseurl }})
- filter: [mepr_wp_mail_headers]({{ '/actions-and-filters/mepr_wp_mail_headers' | prepend: site.baseurl }})
- filter: [mepr_transaction_email_vars]({{ '/actions-and-filters/mepr_transaction_email_vars' | prepend: site.baseurl }})
- filter: [mepr_gateway_notification_params]({{ '/actions-and-filters/mepr_gateway_notification_params' | prepend: site.baseurl }})
- filter: [mepr_transaction_email_params]({{ '/actions-and-filters/mepr_transaction_email_params' | prepend: site.baseurl }})
- filter: [mepr_user_email_vars]({{ '/actions-and-filters/mepr_user_email_vars' | prepend: site.baseurl }})
- filter: [mepr_user_notification_params]({{ '/actions-and-filters/mepr_user_notification_params' | prepend: site.baseurl }})
- filter: [mepr_user_email_params]({{ '/actions-and-filters/mepr_user_email_params' | prepend: site.baseurl }})
- filter: [mepr_reminder_notification_vars]({{ '/actions-and-filters/mepr_reminder_notification_vars' | prepend: site.baseurl }})
- filter: [mepr_reminder_email_vars]({{ '/actions-and-filters/mepr_reminder_email_vars' | prepend: site.baseurl }})
- filter: [mepr_reminder_notification_params]({{ '/actions-and-filters/mepr_reminder_notification_params' | prepend: site.baseurl }})
- filter: [mepr_reminder_email_params]({{ '/actions-and-filters/mepr_reminder_email_params' | prepend: site.baseurl }})
- filter: [mepr_subscription_email_vars]({{ '/actions-and-filters/mepr_subscription_email_vars' | prepend: site.baseurl }})
- filter: [mepr_subscription_email_params]({{ '/actions-and-filters/mepr_subscription_email_params' | prepend: site.baseurl }})

## Jobs

- filter: [mepr_get_job_attribute\_{$attribute}]({{ '/actions-and-filters/mepr_get_job_attribute_' | prepend: site.baseurl }})
- filter: [mepr_set_job_attribute\_{$attribute}]({{ '/actions-and-filters/mepr_set_job_attribute_' | prepend: site.baseurl }})
- filter: [mepr_job_paths]({{ '/actions-and-filters/mepr_job_paths' | prepend: site.baseurl }})
- filter: [mepr_jobs_config]({{ '/actions-and-filters/mepr_jobs_config' | prepend: site.baseurl }})

## Gateway Interfaces

- filter: [mepr_gateway_paths]({{ '/actions-and-filters/mepr_gateway_paths' | prepend: site.baseurl }})
- filter: [mepr_paypal_pro_payment_args]({{ '/actions-and-filters/mepr_paypal_pro_payment_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_pro_refund_args]({{ '/actions-and-filters/mepr_paypal_pro_refund_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_website_payments_pro_subscr_start_ts]({{ '/actions-and-filters/mepr_paypal_website_payments_pro_subscr_start_ts' | prepend: site.baseurl }})
- filter: [mepr_paypal_pro_create_subscriptions_args]({{ '/actions-and-filters/mepr_paypal_pro_create_subscriptions_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_pro_update_subscription_args]({{ '/actions-and-filters/mepr_paypal_pro_update_subscription_args' | prepend: site.baseurl }})
- action: [mepr_paypal_pro_payment_form]({{ '/actions-and-filters/mepr_paypal_pro_payment_form' | prepend: site.baseurl }})
- action: [mepr_paypal_express_options_form]({{ '/actions-and-filters/mepr_paypal_express_options_form' | prepend: site.baseurl }})
- filter: [mepr_paypal_pro_send_request_args]({{ '/actions-and-filters/mepr_paypal_pro_send_request_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_pro_send_request]({{ '/actions-and-filters/mepr_paypal_pro_send_request' | prepend: site.baseurl }})
- filter: [mepr_paypal_website_payments_pro_cancel_message]({{ '/actions-and-filters/mepr_paypal_website_payments_pro_cancel_message' | prepend: site.baseurl }})
- filter: [mepr_paypal_pro_update_payment_profile_args]({{ '/actions-and-filters/mepr_paypal_pro_update_payment_profile_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_payment_args]({{ '/actions-and-filters/mepr_stripe_payment_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_refund_args]({{ '/actions-and-filters/mepr_stripe_refund_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_subscription_args]({{ '/actions-and-filters/mepr_stripe_subscription_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_update_subscription_args]({{ '/actions-and-filters/mepr_stripe_update_subscription_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_suspend_subscription_args]({{ '/actions-and-filters/mepr_stripe_suspend_subscription_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_resume_subscription_args]({{ '/actions-and-filters/mepr_stripe_resume_subscription_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_cancel_subscription_args]({{ '/actions-and-filters/mepr_stripe_cancel_subscription_args' | prepend: site.baseurl }})
- action: [mepr_stripe_payment_form]({{ '/actions-and-filters/mepr_stripe_payment_form' | prepend: site.baseurl }})
- filter: [mepr_stripe_create_plan_args]({{ '/actions-and-filters/mepr_stripe_create_plan_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_customer_args]({{ '/actions-and-filters/mepr_stripe_customer_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_request_args]({{ '/actions-and-filters/mepr_stripe_request_args' | prepend: site.baseurl }})
- filter: [mepr_stripe_request]({{ '/actions-and-filters/mepr_stripe_request' | prepend: site.baseurl }})
- filter: [mepr_paypal_std_refund_args]({{ '/actions-and-filters/mepr_paypal_std_refund_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_std_custom_payment_vars]({{ '/actions-and-filters/mepr_paypal_std_custom_payment_vars' | prepend: site.baseurl }})
- filter: [mepr_paypal_std_payment_vars]({{ '/actions-and-filters/mepr_paypal_std_payment_vars' | prepend: site.baseurl }})
- filter: [mepr_paypal_std_subscription_vars]({{ '/actions-and-filters/mepr_paypal_std_subscription_vars' | prepend: site.baseurl }})
- action: [mepr_paypal_standard_options_form]({{ '/actions-and-filters/mepr_paypal_standard_options_form' | prepend: site.baseurl }})
- filter: [mepr_paypal_std_send_request_args]({{ '/actions-and-filters/mepr_paypal_std_send_request_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_std_send_request]({{ '/actions-and-filters/mepr_paypal_std_send_request' | prepend: site.baseurl }})
- filter: [mepr_paypal_std_update_payment_profile_args]({{ '/actions-and-filters/mepr_paypal_std_update_payment_profile_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_cancel_message]({{ '/actions-and-filters/mepr_paypal_cancel_message' | prepend: site.baseurl }})
- filter: [mepr_authorize_payment_args]({{ '/actions-and-filters/mepr_authorize_payment_args' | prepend: site.baseurl }})
- filter: [mepr_authorize_refund_args]({{ '/actions-and-filters/mepr_authorize_refund_args' | prepend: site.baseurl }})
- filter: [mepr_authorize_auth_card_args]({{ '/actions-and-filters/mepr_authorize_auth_card_args' | prepend: site.baseurl }})
- filter: [mepr_authorize_create_subscription_args]({{ '/actions-and-filters/mepr_authorize_create_subscription_args' | prepend: site.baseurl }})
- filter: [mepr_authorize_update_subscription_args]({{ '/actions-and-filters/mepr_authorize_update_subscription_args' | prepend: site.baseurl }})
- filter: [mepr_authorize_cancel_subscription_args]({{ '/actions-and-filters/mepr_authorize_cancel_subscription_args' | prepend: site.baseurl }})
- action: [mepr_authorize_net_payment_form]({{ '/actions-and-filters/mepr_authorize_net_payment_form' | prepend: site.baseurl }})
- filter: [mepr_authorize_send_aim_request_args]({{ '/actions-and-filters/mepr_authorize_send_aim_request_args' | prepend: site.baseurl }})
- filter: [mepr_authorize_send_aim_request]({{ '/actions-and-filters/mepr_authorize_send_aim_request' | prepend: site.baseurl }})
- filter: [mepr_authorize_send_arb_request_args]({{ '/actions-and-filters/mepr_authorize_send_arb_request_args' | prepend: site.baseurl }})
- filter: [mepr_authorize_send_arb_request]({{ '/actions-and-filters/mepr_authorize_send_arb_request' | prepend: site.baseurl }})
- filter: [mepr_paypal_ec_payment_args]({{ '/actions-and-filters/mepr_paypal_ec_payment_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_ec_refund_args]({{ '/actions-and-filters/mepr_paypal_ec_refund_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_express_subscr_start_ts]({{ '/actions-and-filters/mepr_paypal_express_subscr_start_ts' | prepend: site.baseurl }})
- filter: [mepr_paypal_ec_create_subscription_args]({{ '/actions-and-filters/mepr_paypal_ec_create_subscription_args' | prepend: site.baseurl }})
- action: [mepr_paypal_express_options_form]({{ '/actions-and-filters/mepr_paypal_express_options_form' | prepend: site.baseurl }})
- filter: [mepr_paypal_ec_send_request_args]({{ '/actions-and-filters/mepr_paypal_ec_send_request_args' | prepend: site.baseurl }})
- filter: [mepr_paypal_ec_send_request]({{ '/actions-and-filters/mepr_paypal_ec_send_request' | prepend: site.baseurl }})
- filter: [mepr_paypal_cancel_message]({{ '/actions-and-filters/mepr_paypal_cancel_message' | prepend: site.baseurl }})
- filter: [mepr_paypal_ec_update_payment_profile_args]({{ '/actions-and-filters/mepr_paypal_ec_update_payment_profile_args' | prepend: site.baseurl }})

## Checkout

- filter: [mepr_price_string]({{ '/actions-and-filters/mepr_price_string' | prepend: site.baseurl }})
- filter: [mepr_invoice]({{ '/actions-and-filters/mepr_invoice' | prepend: site.baseurl }})
- filter: [mepr_invoice_show_quantity]({{ '/actions-and-filters/mepr_invoice_show_quantity' | prepend: site.baseurl }})
- filter: [mepr_invoice_html]({{ '/actions-and-filters/mepr_invoice_html' | prepend: site.baseurl }})
- action: [mepr_after_password_fields]({{ '/actions-and-filters/mepr_after_password_fields' | prepend: site.baseurl }})
- action: [mepr_user_signup_fields]({{ '/actions-and-filters/mepr_user_signup_fields' | prepend: site.baseurl }})
- filter: [mepr_validate_signup]({{ '/actions-and-filters/mepr_validate_signup' | prepend: site.baseurl }})
- action: [mepr_track_signup]({{ '/actions-and-filters/mepr_track_signup' | prepend: site.baseurl }})
- action: [mepr_process_signup]({{ '/actions-and-filters/mepr_process_signup' | prepend: site.baseurl }})
- action: [mepr_{$signup_type}_signup]({{ '/actions-and-filters/mepr__signup' | prepend: site.baseurl }})
- action: [mepr_signup]({{ '/actions-and-filters/mepr_signup' | prepend: site.baseurl }})
- filter: [mepr_signup_checkout_url]({{ '/actions-and-filters/mepr_signup_checkout_url' | prepend: site.baseurl }})

## Settings

- filter: [mepr_currency_symbols]({{ '/actions-and-filters/mepr_currency_symbols' | prepend: site.baseurl }})
- filter: [mepr_currency_codes]({{ '/actions-and-filters/mepr_currency_codes' | prepend: site.baseurl }})
- filter: [mepr_language_codes]({{ '/actions-and-filters/mepr_language_codes' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_excerpt]({{ '/actions-and-filters/mepr_unauthorized_excerpt' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_message]({{ '/actions-and-filters/mepr_unauthorized_message' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_show_login]({{ '/actions-and-filters/mepr_unauthorized_show_login' | prepend: site.baseurl }})
- filter: [mepr_tax_rate_use_customer_address]({{ '/actions-and-filters/mepr_tax_rate_use_customer_address' | prepend: site.baseurl }})
- filter: [mepr_options_dynamic_attrs]({{ '/actions-and-filters/mepr_options_dynamic_attrs' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_message]({{ '/actions-and-filters/mepr_unauthorized_message' | prepend: site.baseurl }})
- filter: [mepr_grace_init_days]({{ '/actions-and-filters/mepr_grace_init_days' | prepend: site.baseurl }})
- filter: [mepr_grace_init_days]({{ '/actions-and-filters/mepr_grace_init_days' | prepend: site.baseurl }})
- filter: [mepr_grace_expire_days]({{ '/actions-and-filters/mepr_grace_expire_days' | prepend: site.baseurl }})
- filter: [mepr_options_get_dynamic_attribute\_{$attribute}]({{ '/actions-and-filters/mepr_options_get_dynamic_attribute_' | prepend: site.baseurl }})
- filter: [mepr_options_set_dynamic_attribute\_{$attribute}]({{ '/actions-and-filters/mepr_options_set_dynamic_attribute_' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_login_link_text]({{ '/actions-and-filters/mepr_unauthorized_login_link_text' | prepend: site.baseurl }})
- action: [mepr_extra_profile_fields]({{ '/actions-and-filters/mepr_extra_profile_fields' | prepend: site.baseurl }})
- action: [mepr_unauthorized_message_options]({{ '/actions-and-filters/mepr_unauthorized_message_options' | prepend: site.baseurl }})
- action: [mepr_integration_options]({{ '/actions-and-filters/mepr_integration_options' | prepend: site.baseurl }})
- action: [mepr_display_options_tabs]({{ '/actions-and-filters/mepr_display_options_tabs' | prepend: site.baseurl }})
- action: [mepr_display_autoresponders]({{ '/actions-and-filters/mepr_display_autoresponders' | prepend: site.baseurl }})
- action: [mepr_display_general_options]({{ '/actions-and-filters/mepr_display_general_options' | prepend: site.baseurl }})
- action: [mepr_display_options]({{ '/actions-and-filters/mepr_display_options' | prepend: site.baseurl }})
- action: [mepr_tax_rate_options]({{ '/actions-and-filters/mepr_tax_rate_options' | prepend: site.baseurl }})
- action: [mepr_tax_options]({{ '/actions-and-filters/mepr_tax_options' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_login_form]({{ '/actions-and-filters/mepr_unauthorized_login_form' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_content]({{ '/actions-and-filters/mepr_unauthorized_content' | prepend: site.baseurl }})
- filter: [mepr_bbpress_unauthorized_message]({{ '/actions-and-filters/mepr_bbpress_unauthorized_message' | prepend: site.baseurl }})
- filter: [mepr_custom_thankyou_message]({{ '/actions-and-filters/mepr_custom_thankyou_message' | prepend: site.baseurl }})
- action: [mepr_thank_you_page]({{ '/actions-and-filters/mepr_thank_you_page' | prepend: site.baseurl }})
- filter: [mepr_unauthorized_message]({{ '/actions-and-filters/mepr_unauthorized_message' | prepend: site.baseurl }})
- filter: [mepr_validate_options]({{ '/actions-and-filters/mepr_validate_options' | prepend: site.baseurl }})
- action: [mepr_process_options]({{ '/actions-and-filters/mepr_process_options' | prepend: site.baseurl }})

## Account

- filter: [mepr_active_nav_tab]({{ '/actions-and-filters/mepr_active_nav_tab' | prepend: site.baseurl }})
- filter: [mepr_account_nav_home_link]({{ '/actions-and-filters/mepr_account_nav_home_link' | prepend: site.baseurl }})
- filter: [mepr_account_nav_subscriptions_link]({{ '/actions-and-filters/mepr_account_nav_subscriptions_link' | prepend: site.baseurl }})
- filter: [mepr_account_nav_payments_link]({{ '/actions-and-filters/mepr_account_nav_payments_link' | prepend: site.baseurl }})
- action: [mepr_account_nav]({{ '/actions-and-filters/mepr_account_nav' | prepend: site.baseurl }})
- filter: [mepr_account_payment_product_name]({{ '/actions-and-filters/mepr_account_payment_product_name' | prepend: site.baseurl }})
- filter: [mepr_account_payment_product_name]({{ '/actions-and-filters/mepr_account_payment_product_name' | prepend: site.baseurl }})
- action: [mepr_account_payments]({{ '/actions-and-filters/mepr_account_payments' | prepend: site.baseurl }})
- filter: [mepr_account_welcome_message]({{ '/actions-and-filters/mepr_account_welcome_message' | prepend: site.baseurl }})
- filter: [mepr_user_message]({{ '/actions-and-filters/mepr_user_message' | prepend: site.baseurl }})
- action: [mepr_account_home_fields]({{ '/actions-and-filters/mepr_account_home_fields' | prepend: site.baseurl }})
- action: [mepr_account_home]({{ '/actions-and-filters/mepr_account_home' | prepend: site.baseurl }})
- action: [mepr_before_account_subscriptions]({{ '/actions-and-filters/mepr_before_account_subscriptions' | prepend: site.baseurl }})
- filter: [mepr_account_subscr_product_name]({{ '/actions-and-filters/mepr_account_subscr_product_name' | prepend: site.baseurl }})
- filter: [mepr_account_subscr_product_name]({{ '/actions-and-filters/mepr_account_subscr_product_name' | prepend: site.baseurl }})
- action: [mepr_account_subscriptions_table]({{ '/actions-and-filters/mepr_account_subscriptions_table' | prepend: site.baseurl }})
- action: [mepr_account_subscriptions]({{ '/actions-and-filters/mepr_account_subscriptions' | prepend: site.baseurl }})
- action: [mepr_account_password]({{ '/actions-and-filters/mepr_account_password' | prepend: site.baseurl }})
- action: [mepr_account_nav_content]({{ '/actions-and-filters/mepr_account_nav_content' | prepend: site.baseurl }})
- filter: [mepr_validate_account]({{ '/actions-and-filters/mepr_validate_account' | prepend: site.baseurl }})
- action: [mepr_save_account]({{ '/actions-and-filters/mepr_save_account' | prepend: site.baseurl }})
- action: [mepr_user_account_saved]({{ '/actions-and-filters/mepr_user_account_saved' | prepend: site.baseurl }})

## Rules

- filter: [mepr_rules_cpts]({{ '/actions-and-filters/mepr_rules_cpts' | prepend: site.baseurl }})
- filter: [mepr_search_singles_query]({{ '/actions-and-filters/mepr_search_singles_query' | prepend: site.baseurl }})
- filter: [mepr_pre_run_rule_redirection]({{ '/actions-and-filters/mepr_pre_run_rule_redirection' | prepend: site.baseurl }})
- filter: [mepr_rule_do_redirection]({{ '/actions-and-filters/mepr_rule_do_redirection' | prepend: site.baseurl }})
- filter: [mepr_pre_run_rule_content]({{ '/actions-and-filters/mepr_pre_run_rule_content' | prepend: site.baseurl }})
- filter: [mepr_rewrite_rules_no_protect_dirs]({{ '/actions-and-filters/mepr_rewrite_rules_no_protect_dirs' | prepend: site.baseurl }})
- filter: [mepr_rewrite_rules_protect_types]({{ '/actions-and-filters/mepr_rewrite_rules_protect_types' | prepend: site.baseurl }})
- filter: [mepr_rewrite_rules]({{ '/actions-and-filters/mepr_rewrite_rules' | prepend: site.baseurl }})

## Events

- action: [mepr_event_pre_store]({{ '/actions-and-filters/mepr_event_pre_store' | prepend: site.baseurl }})
- action: [mepr_event_update]({{ '/actions-and-filters/mepr_event_update' | prepend: site.baseurl }})
- action: [mepr_event_create]({{ '/actions-and-filters/mepr_event_create' | prepend: site.baseurl }})
- action: [mepr_event]({{ '/actions-and-filters/mepr_event' | prepend: site.baseurl }})
- action: [mepr_event_{$event}]({{ '/actions-and-filters/mepr_event_' | prepend: site.baseurl }})
- action: [mepr_event_store]({{ '/actions-and-filters/mepr_event_store' | prepend: site.baseurl }})
- filter: [mepr_event_destroy]({{ '/actions-and-filters/mepr_event_destroy' | prepend: site.baseurl }})

## Groups

- filter: [mepr_group_theme_templates_paths]({{ '/actions-and-filters/mepr_group_theme_templates_paths' | prepend: site.baseurl }})
- filter: [mepr_group_themes_paths]({{ '/actions-and-filters/mepr_group_themes_paths' | prepend: site.baseurl }})

## Taxes

- filter: [mepr_found_tax_rate]({{ '/actions-and-filters/mepr_found_tax_rate' | prepend: site.baseurl }})
- filter: [mepr_find_tax_rate]({{ '/actions-and-filters/mepr_find_tax_rate' | prepend: site.baseurl }})
- filter: [mepr_tax_rate_update]({{ '/actions-and-filters/mepr_tax_rate_update' | prepend: site.baseurl }})
- filter: [mepr_tax_rate_create]({{ '/actions-and-filters/mepr_tax_rate_create' | prepend: site.baseurl }})
- filter: [mepr_tax_rate_store]({{ '/actions-and-filters/mepr_tax_rate_store' | prepend: site.baseurl }})
- filter: [mepr_tax_rate_destroy]({{ '/actions-and-filters/mepr_tax_rate_destroy' | prepend: site.baseurl }})
- filter: [mepr_tax_rate_location_create]({{ '/actions-and-filters/mepr_tax_rate_location_create' | prepend: site.baseurl }})
- filter: [mepr_tax_rate_locations_destroy]({{ '/actions-and-filters/mepr_tax_rate_locations_destroy' | prepend: site.baseurl }})

## Reports
- action: [mepr_report_footer]({{ '/actions-and-filters/mepr_report_footer' | prepend: site.baseurl }})
- action: [mepr_report_footer]({{ '/actions-and-filters/mepr_report_footer' | prepend: site.baseurl }})

## Memberships

- action: [mepr_product_options_tabs]({{ '/actions-and-filters/mepr_product_options_tabs' | prepend: site.baseurl }})
- action: [mepr_product_options_pages]({{ '/actions-and-filters/mepr_product_options_pages' | prepend: site.baseurl }})
- action: [mepr_product_advanced_metabox]({{ '/actions-and-filters/mepr_product_advanced_metabox' | prepend: site.baseurl }})
- action: [mepr_product_registration_metabox]({{ '/actions-and-filters/mepr_product_registration_metabox' | prepend: site.baseurl }})
- action: [mepr_product_meta_boxes]({{ '/actions-and-filters/mepr_product_meta_boxes' | prepend: site.baseurl }})
- action: [mepr_product_save_meta]({{ '/actions-and-filters/mepr_product_save_meta' | prepend: site.baseurl }})
- filter: [mepr_product_access_string]({{ '/actions-and-filters/mepr_product_access_string' | prepend: site.baseurl }})
- filter: [mepr_product_cant_purchase_string]({{ '/actions-and-filters/mepr_product_cant_purchase_string' | prepend: site.baseurl }})
- action: [mepr_product_admin_enqueue_script]({{ '/actions-and-filters/mepr_product_admin_enqueue_script' | prepend: site.baseurl }})

## Plugin

- action: [mepr_menu]({{ '/actions-and-filters/mepr_menu' | prepend: site.baseurl }})
- action: [mepr_enqueue_scripts]({{ '/actions-and-filters/mepr_enqueue_scripts' | prepend: site.baseurl }})
- filter: [mepr_signup_styles]({{ '/actions-and-filters/mepr_signup_styles' | prepend: site.baseurl }})
- filter: [mepr_signup_scripts]({{ '/actions-and-filters/mepr_signup_scripts' | prepend: site.baseurl }})
- filter: [mepr_textdomain_paths]({{ '/actions-and-filters/mepr_textdomain_paths' | prepend: site.baseurl }})
- action: [mepr_options_admin_enqueue_script]({{ '/actions-and-filters/mepr_options_admin_enqueue_script' | prepend: site.baseurl }})

## Reminders

- action: [mepr_reminder_save_meta]({{ '/actions-and-filters/mepr_reminder_save_meta' | prepend: site.baseurl }})

<!---
This doesnt actually work so there
- filter: [mepr_ctrls_paths]({{ '/actions-and-filters/mepr_ctrls_paths' | prepend: site.baseurl }})

Huh?
- filter: [mepr_mailchimp_add_subscriber_args]({{ '/actions-and-filters/mepr_mailchimp_add_subscriber_args' | prepend: site.baseurl }})
-->

- action: [mepr_partial_content_codes]({{ '/actions-and-filters/mepr_partial_content_codes' | prepend: site.baseurl }})
- filter: [mepr_hide_cpt_access_column]({{ '/actions-and-filters/mepr_hide_cpt_access_column' | prepend: site.baseurl }})
