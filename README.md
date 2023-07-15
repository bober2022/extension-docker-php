# extension-docker-php
Easy installation of PHP extensions in official PHP Docker images
This repository contains a script that can be used to easily install a PHP extension inside the official PHP Docker images.

The script will install all the required APT/APK packages; at the end of the script execution, the no-more needed packages will be removed so that the image will be much smaller.
Supported docker images are:
 -Debian-based docker images: since jessie (Debian 8) (minimum PHP version: 5.5)
 -Alpine-based docker images: since Alpine 3.9 (minimum PHP version: 7.1)
# See also the notes in the Special requirements section.


