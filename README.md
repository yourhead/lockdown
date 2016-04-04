# Lockdown
### Secure your pages.
#### originally by LogHound
Lockdown is a plugin that will easily secure your RapidWeaver pages.

![Lockdown Icon](https://raw.githubusercontent.com/yourhead/lockdown/master/assets/icon_256.png)


## Download
 - [Stable Release v2.90.7](https://github.com/yourhead/lockdown/raw/v2.90.7/downloads/lockdown_2.90.7.zip)
 - [Beta Release v3.0.0 beta 2](https://github.com/yourhead/lockdown/raw/v3.0.0b2/downloads/Lockdown_3.0.0b2_1064.zip) -- [Release Notes](http://yourhead.com/appcast/RW6/Lockdown/release_notes_3.0.0b2_1064)


### From the LogHound site

Lockdown is a simple plug-in that solves a vexing problem.. How to easily 'secure' a web page. 

> Note: This plugin requires a web host that uses Apache & PHP. Please download the free version and test it before buying!

Please see the *Testing* section below to learn how to test your host.

[GoDaddy users should check the FAQ.]()

Using this plug is really quite simple, simply install the plugin and add a 'Lockdown' page. Go to the 'Passwords' tab and add a password prompt, users and select 'password protect this page' (you may also optionally enter a date this password should expire as well as a web page to send each user to) 


On the 'Page' tab you have a full styled text page that you can put your secure information in. You can also optionally redirect the user to another page (say you want to keep your flickr photos secure, you can put a 'rapidflickr' page below the 'Lockdown' page and redirect the top level page to your flickr photos)



> Note that everything 'nested' under a Lockdown page is also secured, you can also have Lockdown Pages under Lockdown pages with different usernames & passwords!






### Testing
Once you have a page you need to test it to verify that your hosting company supports locking down a page.
I recommend creating a 'dummy' website with perhaps two pages, one that is locked down and one that is not. "Publish" your 'Dummy' site and then visit it. Your Lockdown pages aren't secure until you visit it at least once (this is necessary to configure your server correctly). The very first time you visit a locked down page it will configure your account, if it's successful it'll tell you.


Now hit the 'refresh' button on your browser. If everything is working you should see a password prompt

(In some cases it won't be able to configure and will give you an alternate approach. Please follow the instructions provided at that point)


If you see the above then that page (and all pages below it) are Password Protected! Note that you only need to do this configuration step once. After it's been done once it'll remain locked down (even if you add or change content or add or change usernames & passwords!)

If you ever want to 'un password protect' the page simple uncheck the 'Password Protect' button, republish the page, visit the page to reconfigure and it's now no longer password protected!
