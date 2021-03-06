SecSign ID Wordpress Plugin
===========================

Use the SecSign ID two-factor authentication on your Wordpress site to enable easy and secure login using your iPhone or Android phone.

<http://wordpress.org/plugins/secsign/>


SecSign ID - The mobile way to log into web sites

SecSign ID is a plugin for real two-factor authentication (2FA) for Wordpress sites. 2FA adds another layer of security to your website by using a second token. In this case the physical token is your smartphone. 
If you seek for more information about about two-factor authentication have a look at <https://www.secsign.com/two-factor-authentication/>.

* Integrate SecSign ID into your own Wordpress site in less than one minute.
* You and your users can also use SecSign ID to visit securely other web sites (e.g. <https://portal.secsign.com> for true professional messaging and cloud sharing.)
* This service is free for users and website owners and free of advertising - no matter how many users you have.
* You can also integrate the SecSign ID as inhouse solution into your existing infrastructure (on request with licensed service and maintenance contract)

<http://www.youtube.com/watch?v=DNjrbEuMB7Y>

There are also APIs for PHP, Ruby, Perl, Python and Java as well as plugins and modules for Joomla and Drupal.
A complete overview about available plugins and APIs can be found at <https://www.secsign.com/plugins/>.

## SecSign ID features:

* Quick and easy to use single sign-on with 2048 bit high security
* Eliminates password chaos and security concerns
* No mobile number, credit card or time-consuming registration required.
* No need for long cryptical passwords, time-consuming retyping of codes from SMS or reading of QR codes
* High security and strong cryptography on all levels

## Technical details (only for experts):

* Up to 2048 bit asymmetric private keys
* Brute force resistant private key storage (SafeKey mechanism)
* Private keys are never transmitted to authentication server (the SecSign ID server)
* High availability through redundant remote failover servers
* Multi-tier high security architecture with multiple firewalls and protocol filters.

More information at at <https://www.secsign.com/security-id/>.


**SecSign ID in action:**

1. Get the app for iPhone <https://itunes.apple.com/app/secsign/id581467871> or Android <https://play.google.com/store/apps/details?id=com.secsign.secsignid>
2. Choose a unique user short name
3. Choose a short PIN to secure your SecSign ID on your phone

That's it! You can now use your SecSign ID to sign in.

**How to sign in:**

Just type in your user short name (for instance at SecSign Portal <https://portal.secsign.com> or your Wordpress site using this plugin), confirm your sign-in on your phone and you are done within seconds.

Despite its simplicity SecSign ID works with comprehensive strongest security technologies. The solution we offer is unique and does not submit any confidential data through a web browser.

We have a strong background of more than 16 years in developing strong cryptography and highly sophisticated security software products for governments, public institutions and private companies.

Visit our official site to get the app and more information: <https://www.secsign.com>

and check out our flyer at <https://www.secsign.com/secsign_portal_flyer.pdf>.

## Installation

**Install the Plugin**

* Login into Wordpress as admin and go to the plugins screen and select the "Add New" submenu.
* Search for "SecSign" and click "Install Now" or click on "Upload" and select the downloaded zip archive.
* Activate the plugin in the "Installed Plugins" list.

**Note**

The SecSign ID WordPress plugin uses the SecSign ID API <https://github.com/SecSign/secsign-php-api>. 
The API requests from the SecSign ID server a so-called access pass (a session and a pass icon) which must be confirmed on the smartphone. 
In order to enable the plugin to establish a connection to the SecSign ID server, the curl packet <http://php.net/manual/de/book.curl.php> must be installed for PHP, 
and the web server on which the WordPress site is running must be able to reach the SecSign ID server under https://httpapi.secsign.com. Otherwise, you have to make changes in the settings for firewall and/or proxy.

* Or you visit the plugin site <http://wordpress.org/plugins/secsign/>

**Add the Login Widget**

* You can add the SecSignID Login Widget to your site to allow the login on e.g. the side menu.
* Go to the "Appearance" screen and click the "Widgets" submenu.
* Drag and drop the "SecSign ID Login" widget to e.g. the "Main Sidebar"

**General Configuration**

* Go to the "Settings" screen and select the "SecSign ID Login" submenu.
* Change the service address which will be shown to the user in the smartphone app. This should match the URL the user will see, when he visits your site.

**Coworker Configuration**

* You can integrate the SecSign ID login on the wp-login.php page. This is on by default.
* Optionally, you can assign SecSign IDs to the Wordpress users of your coworkers (Admins, Editors, Authors and Contributors). The users can also assign a SecSign ID in their profile themselves.
* You can also deactivate the normal password based login for the users, so they can only login using the SecSign ID. It’s recommended that you deactivate the password login for all coworkers, so your site is secured against brute force attacks. You should only allow the password based login for your own admin account, in case you lose your phone, and of course for all coworkers who have no smartphone. These accounts should be secured using a very strong password.

**User Configuration**

* Optionally, you can assign SecSign IDs to the Wordpress users of your website users (Subscibers). The users can also assign a SecSign ID in their profile themselves.
* It’s also possible to activate and deactivate the password based login for your users.

**Fast Registration**

* When new users sign in with their SecSign ID on your WordPress site, you can allow them to create a new WordPress user or assign an existing one themselves. This saves you from adding them manually and assigning a SecSign ID to their account.

<http://www.youtube.com/watch?v=utphj_m6jd4>

## Frequently Asked Questions

**How can users assign a SecSign ID to their Wordpress account?**

You can just sign in with your SecSign ID. You will then be shown a dialog, where you can create a new user or assign your SecSign ID to an existing Wordpress user.

Alternatively, you can go to your profile page to assign a SecSign ID.

## Information and Tutorial:

More information is available at the Wordpress SecSign ID tutorial website at <https://www.secsign.com/wordpress-tutorial/>.

For more detailed information about two-factor-authentication (2FA) or two-step-authentication please have a look at the SecSign blog entry <https://www.secsign.com/two-factor-authentication-vs-two-step-verification/>.


