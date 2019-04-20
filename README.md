##Yarshud

Yarshud is a free PHP based software which allows you to manage your site's support with a web-based support ticket system.

Orginanally developed and abandoned as HelpDeskZ by Evolution Script S.A.C. (http://www.helpdeskz.com)

## Requirements

Yarshud requires:

- PHP 7.x
- MySQL database
- GD Library (only for captcha verification)
- Mod_rewrite (only if you want to use permalinks)-

## Upgrading

To upgrade your HelpDeskZ from previous versions, please read the file UPGRADING.txt

## Installation steps

- Connect with FTP to the <em>public folder</em> of your server where the rest of your Web site is
- Create a new folder where you will install Yarshud. Name it anything you like, for example "helpdesk" or "support".<br>
Example: /public_html/support<br>
Corresponding URL: http://www.site.com/support
- Upload all HelpDeskZ files to your server.
- Open **/install** in your browser, for example (modify to your URL):<br />
http://www.site.com/support/install
- The HelpDeskZ setup script will run. Click <strong>INSTALL HELPDESKZ</strong> and follow the instructions through License agreement, Check Setup and Database settings.
- Before closing the install script **DELETE the "install" directory from your server!**
- Now it's time to setup your help desk! Open the <strong>staff</strong> panel in your browser, for example:<br />
http://www.site.com/support/?v=staff<br />
Use the login details that you entered in the installation process.
- Go to <strong>Settings -&gt; General</strong> to get to the settings page.
- Take some time and get familiar with all of the available settings. Most of them should be self-explanatory.
- If you want to use permalinks like http://www.site.com/support/staff/ then you have to enable this option on Settings -> General -> Helpdesk -> Use SEO-friendly URLs
- Good luck using Yarshud!
- 
## Email Piping

## Customize the look

## Translate HelpDeskZ to your language

