wget_google_download.pl
========

Google Drive direct download of big files

Requirements
============

*wget* and *Perl* must be in the PATH.   
**Windows** and **linux** compatible.

Usage
=====

Use Google Drive shareable links, viewable by anyone:   

    $ ./wget_google_download.pl 'google drive file url' ['desired file name']   

Example
=======

For example, to download [this tar.gz](https://drive.google.com/file/d/fghkjfdhgf/edit) just copy the url, and give a file name if desired:

    $ ./wget_google_download.pl https://drive.google.com/file/d/fghkjfdhgf/edit devang.tar.gz 
