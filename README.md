# WP-Slimstat-SQLI
WP-Slimstat 3.9.5 and lower blind SQL injection exploit

This is a poc exploit for the WP-Slimstat sql injection.
To fix this vulnerability update to the latest version(3.9.6)!

Credits for finding the vulnerability goto sucuri.net. Read this explanation of the vulnerability: 
http://blog.sucuri.net/2015/02/security-advisory-wp-slimstat-3-9-5-and-lower.html

The blog talks about using sites like archive.org (in my expierence netcraft is better) to estimate the installation date.
This is not accurate and not neccessary, it sometimes speeds things up a little bit, but bruteforcing every epoch value from 2010 to 2015 takes less than an hour on a normal desktop comptuer. The time range of 5 year might be a little bit overkill.


Also a nice writeup(not in english): http://lynt.cz/blog/zranitelnost-ve-wordpress-pluginu-wp-slimstat-3-9-5
Offical WP-Slimstat github repository: https://github.com/getusedtoit/wp-slimstat


Todo:
----
* Review and improve code
* Improve readme
