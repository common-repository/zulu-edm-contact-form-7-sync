=== Zulu eDM sync with Contact Form 7 Connector ===
Contributors: zululabs, tothebeatceo
Requires PHP: 5.3.0
Donate link:  https://donate.wwf.org.au/adopt/tiger
Author URL: https://github.com/zululabsshaka/zulu_edm_wp_connector
Tags: Zulu eDM, email service provider, email, API cf7, Contact Form 7 Integrations, contact forms, Zulu eDM Integrations
Requires at least: 4.6
Tested up to: 4.9.8
Stable tag: 1.1.4
License: GPLv2.0 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html


Integrate your Contact Form 7 with Zulu eDM Campaign Management Software

== Description ==

This plugin is a bridge between your [WordPress](https://wordpress.org/) [Contact Form 7](https://wordpress.org/plugin/contact-form-7/) and [Zulu eDM](https://www.zuluedm.com).

Want to integrrate your Contact Form 7  web forms with Zulu eDM,then install this light plug in and you will be set.

= How to Use this Plugin =

*In Zulu eDM*  
*Get your API Key from your Zulu eDM Account home-screen. 

*In WordPress Admin*  
* Install this plugin only if Contact Form 7 is install prior (pre-existing). Create or Edit the Contact Form 7 form from which you want to capture the data. Set up the form as usual in the Form and Mail etc tabs. Thereafter, go to the new "Zulu eDM" tab.  
* On the "Zulu eDM" tab, copy-paste the Zulu eDM sheet name and tab name into respective positions, and hit "Save".

*In Zulu eDM*  
* In the Zulu eDM tab, provide column names in row 1. The first column should be "date". For each further column, copy paste mail tags from the Contact Form 7 form (e.g. "your-name", "your-email", "your-subject", "your-message", etc).  
* Test your form submit and verify that the data shows up in your Zulu eDM.

= Important Notes = 

* firstname:text-52 lastname:text-744 email: email:email-706 mobilephone:email-706 subscribed:acceptance-281

* You must pay very careful attention to your naming. 
*Here is a sample for you to work off (see screen shots as well) 

== Installation ==

== From your WordPress dashboard ==

1. Visit 'Plugins > Add New'
2. Search for 'Zulu eDM'
3. Activate the CF7 Zulu eDM Connector from your Plugins page.
4. Go to the Contact Form Plugin and click on the Zulu eDM Tab and enter your API key.

== From WordPress.org ==

1. Download CF7 Zulu eDM Connector.
2. Upload the 'Zulu eDM Connector' directory to your '/wp-content/plugins/' directory, using your favorite method (ftp, sftp, scp, etc...)
3. Activate CF7 Zulu eDM Connector from your Plugins page
4. Go to the Contact Form Plugin and click on the Zulu eDM Tab and enter your API key.

Enjoy!

== Upgrade Notice ==

Upgrade to see better examples of how to match fields

== Screenshots ==

1. Sample Contact 7 form published to your WordPress site
2. Zulu eDM Setting Tab
3. Screen  shot of the field matching

Integrate your Contact Form 7 with Zulu eDM Campaign Management Software

== Description ==

This plugin is a bridge between your [WordPress](https://wordpress.org/) [Contact Form 7](https://wordpress.org/plugin/contact-form-7/) and [Zulu eDM](https://wordpress.org/plugins/zulu-edm-contact-form-7-sync/).

Want to integrate your Contact Form 7  web forms with Zulu eDM,then install this light plug in and you will be set.

= How to Use this Plugin =

*In Zulu eDM*  
*Get your API Key from your Zulu eDM Account home-screen. 

*In WordPress Admin*  
* Install this plugin only if Contact Form 7 is install prior (preexisting). Create or Edit the Contact Form 7 form from which you want to capture the data. Set up the form as usual in the Form and Mail etc tabs. Thereafter, go to the new "Zulu eDM" tab.  
* On the "Zulu eDM" tab, copy-paste the Zulu eDM sheet name and tab name into respective positions, and hit "Save".

 
* In the Zulu eDM tab, provide column names in row 1. The first column should be "date". For each further column, copy paste mail tags from the Contact Form 7 form (e.g. "your-name", "your-email", "your-subject", "your-message", etc).  
* Test your form submit and verify that the data shows up in your Zulu eDM.

= Important Notes = 

* firstname:text-52 lastname:text-744 email: email:email-706 mobilephone:email-706 subscribed:acceptance-281

* You must pay very careful attention to your naming. 
*Here is a sample for you to work off (see screen shots as well) 

== Installation ==

== Installation ==

= From your WordPress dashboard =

1. Visit 'Plugins > Add New'
2. Search for 'Zulu eDM'
3. Activate the CF7 Zulu eDM Connector from your Plugins page.
4. Go to the Contact Form Plugin and click on the Zulu eDM Tab and enter your API key.

= From WordPress.org =

1. Download CF7 Zulu eDM Connector.
2. Upload the 'zip file' directory to your '/wp-content/plugins/' directory, using your favorite method (ftp, sftp, scp, etc...)
3. Activate CF7 Zulu eDM Connector from your Plugins page
4. Go to the Contact Form Plugin and click on the Zulu eDM Tab and enter your API key.

Enjoy!

== Upgrade Notice ==

Upgrade to see better examples of how to match fields

== Screenshots ==

1. Sample Contact 7 form published to your WordPress site
2. Zulu eDM Setting Tab
3. Screen  shot of the field matching

== Frequently Asked Questions ==

== Why isn't the data submitting to my Zulu eDM account? ==

1. Wrong API Key ( Check debug log )
2. Wrong Username or password
3. Wrong Column name mapping ( Column names are the contact form mail-tags. Please refer to Zulu eDM fields specified or contact the support team )

Please double-check those items and hopefully getting them right will fix the issue.

== Changelog ==

= 1.0 =
* First public release
* Integrated Contact form 7 with Zulu eDM 

= 1.1 =
* Checked compatibility with WordPress 4.8 
* Updated imagery and screenshots
* Provided a sample 
* Corrected grammar etc
* Integrated Contact form 7 with Zulu eDM 

= 1.1.1 =
* Fixed the Readme file
* Added WWF adopt a tiger
* Relocate the source to GitHub 

= 1.1.2 =
* amendments to screen shots
* Adding plugin directory imagery

= 1.1.3 =
* updating the tags

= 1.1.4 =
* checked to version 4.9.8