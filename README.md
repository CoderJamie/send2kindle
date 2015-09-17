send2kindle
===========

A simple Python command line script to send ebooks, PDFs and other Kindle-friendly documents to a Kindle account.

# Configuration

Edit the _send2kindle_ file to setup your SMTP server and other default settings:

* __host:__ SMTP server
* __port:__ SMTP server port
* __use_ssl:__ Use SSL?
* __use_tls:__ Use TLS?
* __username:__ SMTP server username
* __password:__ SMTP server password
* __kindle_email:__ Default Kindle address to use (must end in either @free.kindle.com or @kindle.com)
* __from_addr:__ The address files will be sent from (must be on the "approved" list for the Kindle device, configured through the Amazon account)

# Usage
__send2kindle__ _{options}_ _{filename}_

# Command line options

* _-k {address}_ - send to specified Kindle address
* _-s {address}_ - use a different sender address
* _-c_ - Instruct Amazon to convert the file to a Kindle format
