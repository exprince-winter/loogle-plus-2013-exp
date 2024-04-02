# Loogle+ Setup Guide

Note: You'll need PHP 7+ iirc

# How to host? 

Windows:
1. Get XAMPP
2. Add only PHPMyAdmin and PHP
3. Replace htdocs with repo
4. Start PHPMyAdmin and PHP
5. go to 127.0.0.1/phpmyadmin and make a new db
6. import the SQL file
7. Change db.php with all information
<br>
<!-- im on mobile so hopefully that works-->

Linux:
https://ubuntu.com/server/docs/databases-mysql (I tested it on Ubuntu 23.10 and Fedora 39, php-mysql must be installed for myphpadmin)

1. Download myphpadmin and put it in the myphpadmin folder, https://www.phpmyadmin.net/

2. Create a database and input the SQL file.

3. Fill in the info in db.php.

4. Make sure you properly update all the URLs for the url, for the index.php and others. It will be added to a config file soon.

5. The mobile app will also need to be patched.
