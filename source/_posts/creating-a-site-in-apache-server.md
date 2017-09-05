title: how to create a site in apache2 server (cheat sheet)
author: LordAlex Leon
date: 2017-09-05 11:12:38
tags:
---
~~~~
1. Add user: useradd YourUser
~~~~
~~~~
2. Create folders www & logs in home directory: mkdir www, mkdir logs
~~~~
~~~~
3. Go to /etc/apache2/sites-available create the Create the First Virtual Host File ex: example.com.conf
~~~~
~~~~
.4 Enable the New Virtual Host Files: sudo a2ensite example.com.conf then re-start apache by typing: sudo service apache2 restart
~~~~
~~~~
.5 Done!
~~~~