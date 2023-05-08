mod_cdr_mysql
=============
Modified to write SQL local file that really works for all conditions if database connection fails so we do not loose any revenue because
of lost data.

FreeSWITCH Module CDR MYSQL

apt-get install libmysql++-dev

Just copy this folder in /usr/local/src/freeswitch/src/mod/event_handlers/

      make
      make install
      
Add it to autoloadconfig/modules.conf.

Edit the file cdr_mysql.conf with your DB settings.
Add the cdr_mysql.conf file to autoloadconfig folder. 

Restart FreeSWITCH

