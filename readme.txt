selfoss
http://selfoss.aditu.de
tobias.zeising@aditu.de
Version 1.0
License: GPLv3
Icon Source: http://blog.artcore-illustrations.de/aicons/


-------
english
-------

INSTALLATION

1. upload all files of this folder (IMPORTANT: also upload the invisible .htaccess files)
2. make the directories data/cache, data/icons, data/logs, data/thumbnails writeable
3. insert database access data in config.ini
4. create cronjob for updating feeds and point it to http://<selfoss url>/update via wget or curl.

----

UPDATE

1. backup your database and your "data" folder
2. (IMPORTANT: don't delete the "data" folder) delete all old files and folders excluding the folder "data"
3. upload all new files and folders excluding the data folder (IMPORTANT: also upload the invisible .htaccess files)
4. Clean your browser cache
5. insert darabase access data in config.ini (use your old database connection)



-------
deutsch
-------

INSTALLATION

1. lade alle Dateien dieses Ordners hoch (WICHTIG: auch die unsichtbaren .htaccess Dateien hochladen)
2. setze die Schreibrechte f�r die Verzeichnisse data/cache, data/icons, data/logs, data/thumbnails 
3. setze deine Datenbankzugriffsdaten in config.ini
4. erzeuge einen cronjob f�r das Aktualisieren der Feeds auf http://<selfoss url>/update mittels wget or curl.



----

UPDATE

1. die Datenbank sowie den "data" Ordner sichern
2. (WICHTIG: nicht den "data" Ordner l�schen) alle alten Dateien und Ordnern (einschlie�lich "config") aber ohne dem Ordner "data" l�schen
3. alle neuen Dateien und Ordner hochladen (ausgenommen dem "data" Ordner) (WICHTIG: auch die unsichtbaren .htaccess Dateien hochladen)
4. Leere den Cache des Browsers
5. Datenbankzugriff in der config.ini konfigurieren (die alte Datenbank f�r die neue Version verwenden)




-----

Special thanks to the great programmers of this libraries which will be used in selfoss:

* FatFree PHP Framework: http://fatfree.sourceforge.net/
* Elastic CSS Framework: http://elasticss.com/
* HTML5 Boilerplate.com: http://html5boilerplate.com/
* SimplePie: http://simplepie.org/
* jQuery: http://jquery.com/
* WideImage: http://wideimage.sourceforge.net/
* iScroll: http://cubiq.org/iscroll
* htmLawed: http://www.bioinformatics.org/phplabware/internal_utilities/htmLawed/
* PHP Universal Feed Generator: http://www.ajaxray.com/blog/2008/03/08/php-universal-feed-generator-supports-rss-10-rss-20-and-atom/
* twitteroauth: https://github.com/abraham/twitteroauth
* floIcon: http://www.phpclasses.org/package/3906-PHP-Read-and-write-images-from-ICO-files.html
* modernizr: http://www.modernizr.com/
* keyboard shortcuts: http://www.openjs.com/scripts/events/keyboard_shortcuts/