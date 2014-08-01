![Screenshot](https://github.com/kaweechelchen/fancy_directory_listing/blob/master/screenshot.png?raw=true)

fancy_directory_listing
=======================

as seen on https://camp.haxogreen.lu/share

you have to put these lines in your apache config:
```
Options FollowSymLinks Indexes MultiViews
ReadmeName /inc/footer.html
AddIcon /inc/pics/folder.png ^^DIRECTORY^^
AddIcon /inc/pics/folder.png ^^BLANKICON^^
AddIcon /inc/pics/back.png ..
AddIcon /inc/pics/file.png *.*
```
