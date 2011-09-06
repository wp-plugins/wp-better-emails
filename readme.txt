=== WP Better Emails ===
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=7Q49VJQNRCQ8E&lc=FR&item_name=ArtyShow&item_number=wp%2dbetter%2demails&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
Tags: email, emails, html emails, templates, notification, wp_mail, wpmu, multisite
Requires at least: 2.8
Tested up to: 3.2+
Stable tag: 0.1.3

Adds a customizable good looking HTML template to all WP default plain/text emails and lets you set
 a custom sender name and email address.

== Description ==

All emails from Wordpress (lost password, notifications, etc.) are sent by default in text/plain format. WP Better
Emails wraps them with a much better looking customizable **HTML email template** and lets you also set your own **sender name** and **email address**.

* WP Better Emails comes with a default simple and clean template that has been tested on various and popular email clients
 like Gmail, Yahoo Mail, Hotmail/Live, AOL, Outlook, Apple Mail and many more. This to ensure your emails will always display
nicely in your recipient mailbox. But you can of course design your own.
* WP Better Emails lets you send sample emails to test and preview your own custom HTML email template.
* Watch your HTML email template during editing with the live preview.
* Fancy HTML editor with CodeMirror syntax highlighting.
* All emails sent by this plugin are as 'multipart' so that email clients that don't support HTML can read them.
* You can include some variables in your template such as your blog URL, home URL, blog name, blog description, admin email or date and time. They will all be
replaced when sending the email.
* The default template is included as an HTML file in the plugin folder, feel free to edit it with your favorite editor.
* Clean uninstall process, doesn't leave some useless data in your database when deleted, you can easily give it a try !

= Examples usages : =

* Add some ads/sponsored links to every email sent with wordpress
* Include some banners to promote a special event or feature of your website
* Brand your emails to your website or client website

= Internationalization =

WP Better Emails is currently available in :

* English
* French
* Dutch by [Glenn Mulleners](http://wp-expert.nl "Glenn Mulleners")

I'm looking for translators to extend to other languages. If you have translated the plugin in your language or want to,
please let me know : plugins [ at ] artyshow-studio.fr

= Credits =

[CodeMirror](http://codemirror.net/ "CodeMirror") library

== Installation ==

1. Extract and upload the `wp-better-emails` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in the WordPress admin panel
3. (Optional) Set a sender email and name, if none, wordpress defaults will be used : 'wordpress@yourdomain.com' and 'Your Blog Title'
4. (Optional) Edit your own email template. See the screenshot tab to have a look at the default template
5. Every emails going out of your Wordpress Blog (notifications, lost password, etc.) looks better now !

== Upgrade Notice ==

= Manual update =

1. Delete the plugin `wp-better-emails` folder under the `/wp-content/plugins/` directory
2. Upload the last version and activate it

= Automatic update =

Just use the Wordpress automatic plugin update system

== Frequently Asked Questions ==

= What if recipient can't read HTML emails ? =

WP Better Emails sends all emails in both formats ('multipart', i.e. HTML and plain text) so that email can be displayed in every email client.

= Why are the emails still sent in plain text format ? =

Be sure to include the **%content%** tag in your template. WP Better Emails wrap the content with the template, if no tag
is found, sending HTML emails is automatically desactivated.

= My custom email template doesn't look the same in Gmail and other email clients ? =

For example, Gmail strips everything before the `<body>` tag so if you included styles there, they won't be applied.
I included a few helpful links in the 'Help & support' tab, you will find complete information about coding for emails.

== Screenshots ==

1. The default template that comes with WP Better Emails. Tested on many email clients like Gmail, Yahoo!, Live/Hotmail, etc.
2. WP Better Emails settings screen with the default WP TinyMCE editor.
3. Editor in source mode using CodeMirror syntax highlighting.
4. Live preview your template.

== Changelog ==

= 0.2 =
 * WP TinyMCE editor support
 * HTML editor with CodeMirror as a TinyMCE plugin
 * Live preview (> WP 3.1)
 * Help moved to contextual help 
 * Translations for spanish, hebrew

= 0.1.3 =
 * Sender email and name are now optional
 * Fixes replacing URLs of plain text content to handle https protocol

= 0.1.2 =
 * Added 3.1 compatibility
 * Dutch translation

= 0.1.1 =
 * French translation added

= 0.1 =
 * WP Better Emails first release