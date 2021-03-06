# Drupal Security
Resources, tips, howtos, and everything in between to secure your Drupal app.

Resources
---------
1. [Steps to a Drupal security review](http://crackingdrupal.com/node/71)
2. [Automated Security Review](http://crackingdrupal.com/node/70)
3. [Cracking Drupal](http://crackingdrupal.com/)
4. [Drupal Security Report](http://drupalsecurityreport.org/)
5. [Drupal Security Group](https://groups.drupal.org/security)
6. [Securing your site](https://www.drupal.org/security/secure-configuration)
7. [Enhancing security using contributed modules](https://www.drupal.org/node/382752)

Modules
-------
1. [Paranoia](https://www.drupal.org/project/paranoia) - The Paranoia module attempts to identify all the places that a user can evaluate PHP via Drupal's web interface and then block those. It reduces the potential impact of an attacker gaining elevated permission on a Drupal site.
2. [Security Review](https://www.drupal.org/project/security_review) - The Security Review module automates testing for many of the easy-to-make mistakes that render your site insecure.
3. [Drupalgeddon](https://www.drupal.org/project/drupalgeddon) - Drupalgeddon (with an "L") checks for backdoors and other traces of known Drupal exploits of "Drupageddon" (no "L"), aka [SA-CORE-2014-005 SQL injection](https://www.drupal.org/SA-CORE-2014-005). Drupalgeddon is not a module; it's a Drush command.
4. [Hacked!](https://www.drupal.org/project/hacked) - This module scans the currently installed Drupal, contributed modules and themes, re-downloads them and determines if they have been changed.
5. [MD5 Check](https://www.drupal.org/project/md5check) - The MD5 Check generates a md5 checksum of all module files. If module is changed a critical security error is generated in watchdog log.
6. [File Integrity Check](https://www.drupal.org/project/file_integrity) - This module lets the site maintainer “fingerprint” an entire site (except the files below the public:// upload directory) when it is in an untainted state.
7. [Site Audit](https://www.drupal.org/project/site_audit) - Site Audit is a Drupal static site analysis platform that generates reports with actionable best practice recommendations.
8. [Security Kit](https://www.drupal.org/project/seckit) - SecKit provides Drupal with various security-hardening options. This lets your mitigate the risks of exploitation of different web application vulnerabilities.
9. [Unused Modules](https://www.drupal.org/project/unused_modules) - Not really for security but still good to have it here. This is a helper / development module that lists unused modules / projects that can be safely deleted. This makes your repository cleaner and your website faster.
10. [Login Security](https://www.drupal.org/project/login_security) - Login Security module improves the security options in the login operation of a Drupal site. With Login Security module, a site administrator may protect and restrict access by adding access control features to the login forms (default login form in /user and the block called "login form block").
11. [Flood Control](https://www.drupal.org/project/flood_control) - This project is intended to add an administration interface for hidden flood control variables in Drupal 7, like the login attempt limiters and any future hidden variables.
12. [Captcha](https://www.drupal.org/project/captcha) - A CAPTCHA is a challenge-response test most often placed within web forms to determine whether the user is human.
13. [Spamspan Filter](https://www.drupal.org/project/spamspan) - The SpamSpan module obfuscates email addresses to help prevent spambots from collecting them.
14. [ACL](https://www.drupal.org/project/acl) - The ACL module, short for Access Control Lists, is an API for other modules to create lists of users and give them access to nodes.
15. [Content Access](https://www.drupal.org/project/content_access) - This module allows you to manage permissions for content types by role and author. It allows you to specifiy custom view, edit and delete permissions for each content type. Optionally you can enable per content access settings, so you can customize the access for each content node.
16. [Lightweight Directory Access Protocol (LDAP)](https://www.drupal.org/project/ldap) - The Lightweight Directory Access Protocol (LDAP) project provides integration with LDAP for authentication, user provisioning, authorization, feeds, and views.
17. [Password Policy](https://www.drupal.org/project/password_policy) - This module provides a way to enforce restrictions on user passwords by defining password policies.
18. [Oauth](https://www.drupal.org/project/oauth) - This module implements the OAuth 1.0 standard for use with Drupal and acts as a support module for other modules that wish to use OAuth.

Standalone Applications
-----------------------
1. [Droopescan](https://github.com/droope/droopescan) - A plugin-based scanner that aids security researchers in identifying issues with several CMSs, mainly Drupal & Silverstripe.

HowTo and Best Practices
------------------------
Coming soon...

Credits
-------
1. [Greggles](https://www.drupal.org/u/greggles)
2. [Droope](https://github.com/droope)
3. Drupal community and contributors

