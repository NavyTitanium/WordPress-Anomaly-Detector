# WordPress Anomaly Detector :rotating_light:	
Compare the files and folders of the original source code of WordPress against a website. This multithreaded script will crawl a given website and search for a directory listing.

## Purpose
It can be used agaisn't infected & poorly configured sites to hunt for malicious files :monocle_face:	
## Update the list of files

Get [the latest release of WordPress](https://github.com/WordPress/WordPress/releases) and unzip it next to the script. After unzipping the archive, simply change the version in the script. It is currently configured to read the files in the folder **WordPress-5.8.1**.

## Usage example
```
# python3 wp_anomaly.py http://[website]

[*] 281 subdirectories and 1198 PHP files loaded for comparison
[File] /wp-includes/IXR/kxnlessenm.php
[Directory] /wp-includes/css/
[File] /wp-includes/123.php
[File] /wp-includes/D66nE.php
[File] /wp-includes/GsKqG.php
[File] /wp-includes/bpqinvvh-rintelnn.php
[File] /wp-includes/droplet.php
[File] /wp-includes/editor.php
[File] /wp-includes/infodata.php
[File] /wp-includes/ohchvechtav.php
[File] /wp-includes/standard.php
[File] /wp-includes/wp-ajax-traceback.php
[File] /wp-includes/xmldatawp.php
[File] /wp-includes/Requests/Response/kich-siegenh.php
[Directory] /wp-includes/js/tinymce/langs/
[Plugin] /wp-includes/js/tinymce/plugins/
[Directory] /wp-includes/js/tinymce/skins/
[Theme] /wp-includes/js/tinymce/themes/
[Directory] /wp-includes/js/tinymce/utils/
[File] /wp-admin/css/dustparticle.php
[File] /wp-admin/css/colors/blue/ejckpqn.php
```
