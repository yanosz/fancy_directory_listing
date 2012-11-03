![Screenshot](https://github.com/tdegeling/fancy_directory_listing/blob/master/screenshot.png?raw=true)

fancy_directory_listing
=======================

as seen on http://wtf.muling.lu/29c3/

you have to put these lines in your apache config:
```
Options FollowSymLinks Indexes MultiViews
ReadmeName /inc/footer.html
AddIcon /inc/pics/folder.png ^^DIRECTORY^^
AddIcon /inc/pics/back.png ..
AddIcon /inc/pics/file.png *.*
IndexIgnore favicon.ico
```
