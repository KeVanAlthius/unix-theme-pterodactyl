# unix-theme-pterodactyl
unix theme




Before proceeding with installation make sure you have checked the following things:

* Make sure you're running the latest version of Pterodactyl
* Make sure you don't have any other theme installed
* It is recommended to install Unix on stock Pterodactyl, installing it on a Panel with lot of addons might break certain parts since the files will conflict


Installation:

1. Open the "Pterodactyl" Folder found in this directory
2. Upload all the folders you see to "/var/www/pterodactyl" ( Enable option to overwrite old files )
3. Open Command Line and run the following command: php artisan migrate --path=/database/migrations/2021_05_30_141248_create_unix_settings_table.php
4. You'll see that Unix is now Installed, however there is one more step left to get the sidebar working,
   please follow this guide on Pterodactyl website https://pterodactyl.io/community/customization/panel.html
5. Your done!
