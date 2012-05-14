=== Easy Postmark Integration ===
Contributors: apowellgt, andy7629, alexknowshtml
Tags: postmark, email, smtp, notifications, wp_mail
Requires at least: 3.2
Tested up to: 3.2.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Replaces wp_mail to send email via the Postmark API. Supports Reply-To for simple integration with contact form plugins.

== Description ==

Replaces wp_mail to send email via the Postmark API.  Supports Reply-To for easy integration with common contact form plugins, including Contact Form 7 and Gravity Forms.

This plugin is based on the "Postmark Approved WordPress Plugin".  Aside from being customers and fans, we're not affiliated with Postmark.

You can create an account at http://www.PostmarkApp.com

== Installation ==

1. Upload and activate plugin.
2. Enter your Postmark credentials in the Plugin settings.
3. Verify the plugin works "Send Test Email" button.
5. Once verified, then check "Enable" to override wp_mail and send using Postmark instead.

== Frequently Asked Questions ==

= Is this the official Postmark plugin? =

No, it's not.  I modified the official plugin to scratch an itch, and I though others may find it useful.

= Why is setting the 'Reply-To' header important? =

Typically, contact forms set the 'From' name and email address headers based on user input on a contact form.  To ensure deliverability, Postmark overrides this with a verified sender signature.  

If a 'Reply-To' isn't set, then when you click 'Reply' on a Postmark-delivered email, it'll send to your Postmark email address, not to the person who submitted the contact form.

== Screenshots ==

== Changelog ==

= v1.0 =
* First Public release.