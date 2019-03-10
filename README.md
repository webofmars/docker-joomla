# webofmars/joomla docker image

A joomla image able to run older versions of Joomla than the official image (based on PHP )

At the time only the fpm image is ready to be tested

## Things that DO work

- image based on php:5.4
- support for apc and mbstring extensions

## TODOs

- apply the changes made to fpm image to apache and fpm-alpine
- replace the version of joomla bundled inside of the image (which was latest at the time of writting this image and might not even work with this image)
- better handling of ftpasswd account and password
