ldapAliasSync
=============

Roundcube Plugin for fetching Identities (name, email, organization, reply, bcc, signature) from LDAP Aliases at login

This is a fork of https://github.com/yakatz/roundcube-ldapAliasSync which itself is a fork of an older unmaintained version of this plugin. 

This fork updates the few LDAP functions results checks following the changes made in PHP8.1. 

All functions from the LDAP extension that accepted/returned resource objects prior to PHP 8.1 accept/return standard PHP class instances from PHP 8.1.

Have tested it on php8.1 and confirmed it works in combination with roundcube 1.6.4.  

Copyright according to GPLv3 (see COPYING).


Basic Installation:
- Copy config-default.inc.php in config.inc.php, and modify the values you need.
