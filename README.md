# WooCommerce Simply Order Export Add-on Documentation
This contains documentation for WooCommerce WooCommerce Order Export Scheduler and Logger plugin. This can be used as reference for usability of plugin. To purchase the plugin [follow this link](http://sharethingz.com/downloads/wsoe-scheduler-logger/)

[1. Installation](#installation)

[2. Fields added by plugin](#fields-added)

[3. FAQ](#faq)

[4. Refund policy](#refund)

[5. Giving Back!](#contribute)

### <a name="installation"></a>Installation

* Go to Plugins => Add New => Upload Plugin, from your wordpress dashboard.
* Select zip file you downloaded and click "Install Now"
* Click "Activate plugin"

### <a name="fields-added"></a> Fields added by plugin

![Fields added by plugin]
(http://sharethingz.com/wp-content/uploads/2015/09/Scheduler-Fields.png)

##### 1. Auto-update Email

This is email address which you used during purchase on checkout page. This will help to receive auto-update notifications and you can keep your plugin up-to-date.
It is highly recommended that you should always keep your plugin updated to ensure that it is not always compatible with other dependednt plugins and non-vulnerable.

##### 2. Export Start Time

This is mandatory field. This is the time from which export should be scheduled. You can select the time from the dropdown, once you click into textbox.
Example: Suppose current time is 3 P.M. and you selected 2 P.M. from dropdown, export will be scheduled from next day's 2 P.M. time.

##### 3. Export Interval (In Minutes)

This is mandatory field. This is the interval after which scheduled export will be repeated. Its value should always be inputted in minutes.

##### 4. Export Start Date

This field is mandatory. It is the date from which orders will be exported (fetched).

##### 5. Export End Date

This field is mandatory. It is the date up to which orders will be exported (fetched).

##### 6. Email

This field is mandatory. This is the email address on which exported report (.csv file) will be sent as an attachment.

##### 7. Timezone

This field is optional, if not selected, it will get timezone according to server's default timezone. This is necessary to set because it will help you to schedule the export according to your timezone.
Example: Suppose you are residing in India and your server is located in U.S.A., it will take default timezone of U.S.A. and will schedule according to U.S.A. timing, selecting timezone "Asia/Kolkata" makes it possible to schedule export according to Indian timezone.

##### 8. Clear

It will clear all the fields and will remove the scheduled export, so that it will no longer be scheduled and exported. This is kind of reset button. :)

### <a name="faq"></a> Frequently asked questions

**When I click download link in email, index.php file is getting downloaded instead of plugin zip file. What should I do?**

* This is happening because of [bug](https://github.com/easydigitaldownloads/Easy-Digital-Downloads/issues/3498) in Easy Digital Downloads plugin.
* You can simply rename index.php file to index.zip, and everything should work fine.
* Alternatively, you can send message from [sharethingz contact form](http://sharethingz.com/contact/) reporting the issue. I will send you the zip file of plugin on your registered email which you used during plugin purchase.

**I have purchased plugn, made the payment, but haven't received any email for download. What to do now?**

* Check in your spam folder, email can be present there.
* If email is configured on your website's server, check settings for incoming emails.
* Contact by [sharethingz contact form](http://sharethingz.com/contact/) from your registered email, if your payment is successfully completed, zip file of plugin will be sent to you by email.

**I cannot see order export settings under woocommerce=>settings**

* Please confirm if latest versions of woocommerce and [woocommerce simply order export plugin](https://wordpress.org/plugins/woocommerce-simply-order-export/) is installed.
* Deactivate all plugins except woocommerce, woocommerce simply order export and woocommerce simply order export add-on plugins and switch to default wordpress theme (Twenty Fifteen), check if similar issue still persists or not?
* If none of these helps, contact through [ShareThingz Contact Form](http://sharethingz.com/contact/)


**Where I can get support regarding this plugin?**

When you purchase the add-on, an account is created for you on [ShareThing](http://sharethingz.com). You can use [ShareThingz Support Forum](http://sharethingz.com/support/forum/woocommerce-simply-order-export-addon/) for any queries after purchasing add-on. Pre-purchase queries can be posted through [ShareThingz Contact](http://sharethingz.com/contact)

**Export button is not working**

* Deactivate all plugins except woocommerce, woocommerce simply order export and woocommerce simply order export add-on.
* Switch to default wordpress theme, check if issue still persists.
* If issue still persists, contact at [ShareThingz facebook page](http://facebook.com/shrthngz)

### <a name="refund"></a> Refund policy

No Refund.

### <a name="contribute"></a> Giving back to community!

![Akshay Patra]
(http://www.akshayapatra.org/apadmin/uploads/settings/logo.png)

For every purchase of copy of this plugin, $1 will be donated to [Akshaya Patra Foundation](http://www.akshayapatra.org/about-us). Akshaya Patra is a non-profit organisation in India that runs school lunch programme across India.

So, indirectly you are also contributing to feed a child with purchase of this plugin. This donation will be sent to the organization last day of every month depending on number of copies sold. So, if 100 copies of this plugin got sold, then $100 will be donated to the organization. :)




 [![Buy Now][2]][1]
 [1]: http://sharethingz.com/downloads/wsoe-scheduler-logger/
 [2]: http://sharethingz.com/wp-content/uploads/2015/06/buy.gif