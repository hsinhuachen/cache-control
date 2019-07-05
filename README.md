# Cache-Control

## .htaccess file
	<filesMatch ".(css|jpg|jpeg|png|gif|js|ico)$">
	Header set Cache-Control "max-age=31557600, public"
	</filesMatch>

