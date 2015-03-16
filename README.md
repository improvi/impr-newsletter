# impr-newsletter
A WordPress plugin to enable your visitors to subscribe to your newsletter

== Installation ==

1. Upload the directory `impr-newsletter` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php echo do_shortcode('[impr_newsletter class="<your-class>" btn_text="<your-button-text>" text="<your-section-heading>" placeholder="<your-email-textbox-placeholder>"]'); ?>` in your templates after changing the appropriate variables

== Frequently Asked Questions ==

= Does the plugin validate the email address entered? =

Yes, it does.

= Does the plugin store the email addresses into a database? =

No, we currently do not. This is because the email addresses are mostly used for importing into mailing lists softwares, such as MailChimp, CampaignMonitor, etc
and having it as a CSV is easier than using a database.

= Can I customize the look and feel? =

Yes, you can set parameters such as a class, placeholder text, button text, and the heading section when invoking the shortcode and override the styling in your style.css.

= Where do I go to get the list of subscribed email addresses? =

Navigate to Settings > Improvi Newsletter Signups and click on the Download CSV link.
