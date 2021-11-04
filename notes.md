# TryHackMe-Notes

To upload root.service to website:
Upload functionality restricts extensions. So change name of root.service to root.phtml (.phtml is an accepted extension), then on the webserver, rename the file:
In /var/www/html/internal/uploads: mv root.phtml root.service

