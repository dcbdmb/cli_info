# URL's

##Unix
ihttp://http://cb.vu/unixtoolbox.xhtml

## Images
convert -resize 300 image.jpg small_image.jpg

##MP3
cat 1.mp3 2.mp3 > combo.mp3

##Data
dd if=/deb/hda of=/dev/hdb

##Video
ffmpeg -i orig.avi final.mpg

##Other
cdrecord -v speed=8 dev=0,0,0 iso_file_name.isp
cdrecord -scanbus (to get dev= variables)
sed 's/XXXX/YYYY/g' file.c
