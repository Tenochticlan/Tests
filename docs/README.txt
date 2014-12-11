README
======

This directory should be used to place project specfic documentation including
but not limited to project notes, generated API/phpdoc documentation, or
manual files generated or hand written.  Ideally, this directory would remain
in your development environment only and should not be deployed with your
application to it's final production location.


Setting Up Your VHOST
=====================

The following is a sample VHOST you might want to consider for your project.

<VirtualHost *:80>
<<<<<<< HEAD
   DocumentRoot "/var/www/tutorial/public"
   ServerName tutorial.local
=======
   DocumentRoot "/var/www/Tutorial02/public"
   ServerName Tutorial02.local
>>>>>>> cad4804d50754241983e590551e8b16e88e72469

   # This should be omitted in the production environment
   SetEnv APPLICATION_ENV development

<<<<<<< HEAD
   <Directory "/var/www/tutorial/public">
=======
   <Directory "/var/www/Tutorial02/public">
>>>>>>> cad4804d50754241983e590551e8b16e88e72469
       Options Indexes MultiViews FollowSymLinks
       AllowOverride All
       Order allow,deny
       Allow from all
   </Directory>

</VirtualHost>
