JcSImpleFrameWrk ( V1.1 )
==========

Simple Web Site.
Translable, routing SEO friendly and translable. 
Static Content with no db query and dynamic pages.

Landing sites or Business Sites with none or little logic.

/includes/Config:
routing, key=>value

/web/index.php to control what to view and how.

Not finished, nice error 500 layout. 
In include / boostrap.php global var environment is settet.


Vhosts

<VirtualHost *:80>
	DocumentRoot "path to /github/BeFrameOne/web"
	ServerName beframeone.dev
	<Directory "path to /github/BeFrameOne/web/">
        Options Indexes FollowSymLinks MultiViews
		AllowOverride ALL
		Order allow,deny
		allow from all
    </Directory>
</VirtualHost>