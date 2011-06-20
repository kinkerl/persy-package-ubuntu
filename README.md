ubuntu-packaging for ubuntu
===========================
very short overview:

 *   place the orig.tar.gz in the root folder
 *   extract the orig.tar.gz in "persy"
 *   debuild -S the package in "persy"
 *   upload to ppa:  dput -f ppa:tmassassin/ppa persy_*-0ubuntu1_source.changes

