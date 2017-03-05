# UPDATE LOCAL WORDPRESS
Automatically updates a local WordPress installation for development porpouses.
Made for those situations when you have ssh access to the server and the production database is accessible only by installed wordpress server.
What does the script do:
-Access ssh folder server.
-Reads the wp-config and get the production database credentials.
-Use the database credentials to make a database backup file right in the production environment.
-Download everything locally.
-Replaces in the database backup file paths and the domain from the production site to the local settings.
-Replaces database credentials from wp-config to the local database credentals.
-Restores the local database with the backup with paths and domain already ajusted to the local environment.
-CHANGES IN THE .htaccess MAYBE STILL NEED BE MADE.
# update_local_wordpress
