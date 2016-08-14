# ea-apache2-http2
CentOS 7, EA4 and HTTP/2. SEE LINK FOR INFO.

You'll need to pull and compile apr from https://github.com/Cacasapo/apr or https://github.com/JPerkster/apr, which this is a fork of.

If you do not wish to use the bluehost patch, edit ea-apache24.spec and comment out: 
Patch401: symlink-protection.patch
%patch401 -p1 -b .harden

You may skip building APR, if so. 
