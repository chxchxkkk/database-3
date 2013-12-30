mangos_ytdb
===========

This is a port of the YTDB Cata database.  It will be maintained to work with mangos by the mangos devs.  Fixes are welcome and will be shared with YTDB.

See the YTDB homepage for their license and copyright information.

The YTDB homepage: ytdb.ru

Installation Instructions
-------------------------
 - Do everything as normal for the characters and realmd databases.
 - Drop your mangos database if you already have one.
 - Create an empty mangos db and give your mangos user permissions on it
 - Unzip the database file
 - Import full_db.sql (mysql -u root -p mangos < full_db.sql)
 - Import all the updates in the updates folder