ldapAliasSync
=============

Roundcube Plugin for fetching Identities (name, email, organization, reply, bcc, signature) from LDAP Aliases at login

This is a fork of https://github.com/yakatz/roundcube-ldapAliasSync which itself is a fork of an older unmaintained version of this plugin. 

This fork updates the few LDAP funtions following the changes made for PHP8.1 to the LDAP functions. 

All functions from the LDAP extension that accepted/returned resource objects prior to PHP 8.1 accept/return standard PHP class instances from PHP 8.1.

Have tested it on php8.1 and confirmed it works. 

Copyright according to GPLv3 (see COPYING).


Bugs & Issues:
- Enter bug reports in https://github.com/dim-0/ldapAliasSync/issues

Basic Installation:
- Copy config-default.inc.php in config.inc.php, and modify the values you need.
