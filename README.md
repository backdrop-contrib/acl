
Access Control Lists
====================

The ACL module, short for Access Control Lists, is an API for other modules to create lists of users and give them access to nodes. It has no UI of its own and will not do anything by itself; install this module only if some other module tells you to.

Usage
-----

ACL has no UI of its own and unless some other module uses it, it won't appear
to add anything to your site. Only bother with this module if some other module
tells you to.

For client modules that want to implement by-user node access in a robust and
compatible way, ACL provides the required functionality.
For a sample implementation see the Drupal Forum Access module:
http://drupal.org/project/forum_access

Troubleshooting
---------------

Even though ACL does not do anything by its own, Core recognizes it as a node
access module, and it requires you to rebuild permissions upon installation.

The client module is fully responsible for the correct use of ACL. It is very
unlikely that ACL should cause errors. 

LICENSE
---------------    

This project is GPL v2 software. See the LICENSE.txt file in this directory 
for complete text.

CURRENT MAINTAINERS
---------------    

Looking for maintainers

CREDITS   
-------

Originally written for Drupal 5 and maintained by merlinofchaos.
Ported to Drupal 6 and 7 and maintained by salvis.

