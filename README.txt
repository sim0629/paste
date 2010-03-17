$ID PROJECT: Paste - README.txt, v1, EcKstasy - 17/03/2010/08:47 GMT+1 (dd/mm/yy/time)

Requirements: PHP, MySQL

Paste is very easy to install, you have two options: use the installer
or follow the manual installation instructions below.

Using the installer:
1> Upload all of PASTE's files to your webserver.
either in the root directory of your site or in a subdirectory.
2> Direct your browser to the location (url) of the folder
eg: http://mysite.com/ or http://mysite.com/paste/
3> An installation page will be displayed.
Simply enter all the required fields and click "Install".
this will create the mysql table and generate a configuration file
for your settings.
4> Edit htaccess.txt to suit your needs and rename it to .htaccess
  (Please read the comments in htaccess.txt carefully)

Manual installation:
1.1> Create a database for the pastebin.
1.2> Add the tables to the database (/manual/paste.sql)

2> Edit the configuration file to suit your needs (/manual/config.php)
and move it to the main directory
3> Upload all of the files to the webserver.
4> Edit htaccess.txt to suit your needs and rename it to .htaccess
  (Please read the comments in htaccess.txt carefully)
  
If you want to file a bug report go to either:
https://sourceforge.net/tracker/?func=add&group_id=310876&atid=1308834
or http://bitbucket.org/eckstasy/paste/issues/new/

You can find support on IRC by connecting to irc.freenode.net in channel ##PASTE