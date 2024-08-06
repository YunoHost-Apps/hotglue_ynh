Hotglue 1.0.4 YunoHost app

developed by Gottfried Haider and Danja Vasiliev
and the people from WORM (worm.org)
with support from the Mondriaan Foundation
made for you

HOTGLUE is a visual tool for creating websites directly in the web-browser. Whether you want to make a personal webpage, online gallery or a website for your band - HOTGLUE is an interesting alternative to over-complicated systems like Wordpress, Drupal, etc.

You will enjoy the simplicity of the user interface and fast learning curve – making a website with HOTGLUE is just as easy as making a paper collage!

![Screenshot of Example app](./doc/screenshots/example.jpg)

Hotglue repo https://github.com/k0a1a/hotglue2

HOW DOES THIS WORK

  * see INSTALL
  * if you feel like reading boring lists, check out doc/FEATURES
  * otherwise make sure you have seen http://www.vimeo.com/17924249
  * Demo site - https://hotglue.me/demo/


BUNDLED THIRD-PARTY CODE

  * jQuery (MIT, BSD and GPL licensed)
  * jQuery UI (MIT, GPLv2 licensed)
  * Farbtastic: JQuery color picker plug-in (GPL licensed)
  * jQuery xcolor (MIT, GPLv2 licensed)
  * DejaVu Fonts (Copyright (c) 2003 by Bitstream, Inc. All Rights Reserved. Bitstream Vera is a trademark of Bitstream, Inc.)
  * the file icon has been taken from gnome-icon-theme (GPL licensed)


KNOWN ISSUES

  * Hotglue 1.0 is not compatible with prior versions of the software. We aim 
    to preserve compatibility with upcoming releases though.

  * On certain shared hosts we have seen issues with digest authentication (see AUTH_METHOD configuration option). For those hosts basic authentication has to be used.

  * On certain hosts or configurations it might be required to explicitly set RewriteBase in .htaccess when using short URLs. This has been observed on hosts using mod_rewrite even before the request hits the Hotglue directory. If you experience unexpected blank pages after installation or can't manage to log in, this might be worth trying.

	* On certain (cheap) hosts the use of .htaccess file is disallowed. If you are experiencing strange errors like ERROR 500 try renaming .htaccess file back to htaccess-dist and see if that helps. Sometimes you might be able to request .htaccess functionality from your webhosting provider. 
  
  * Native JSON decoding seems to be broken in early versions of PHP 5.2. This can result in error messages such as "Error saving state as class 'object' is not set". Make sure you are using PHP 5.2.6 or later.

  * Support for supporting hosts that have PHP installed as a (Fast-)CGI binary is still worked on. For now it is recommended to use mod_php, although success with FastCGI has been reported as well.

  * Rewrite rules in the Apache configuration or in any parent directory .htaccess file can clash with the Hotglue one.

  * If you receive an error message while uploading a large file this 
    might  be due to the limits set in the servers's php.ini file.
    You might want to change the values of these settings:
    - post_max_size
    - upload_max_filesize
    - memory-limit (if memory limits have been enabled)
    - max_input_time
    - max_file_uploads

  * For now, caching or seeking is not implemented for retrieval of uploaded files. 
    This might be an issue when embedding large video files.

  * Making animated GIF images smaller than their native size disables the animation.

  * The looping property of YouTube's new HTML5 video embed code seems to be broken at the moment.

  * Vimeo does not currently offer a way to embed videos over HTTPS. You might thus receive a (legitimate) browser warning when accessing a page containing a Vimeo video using HTTPS.

  * When modifying objects that also appear on other pages, these changes might not immediately appear on them if caching is enabled.

