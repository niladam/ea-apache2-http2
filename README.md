# ea-apache2-http2
CentOS 7, EA4 and HTTP/2. SEE LINK FOR INFO.

You'll need to pull and compile apr from https://github.com/Cacasapo/apr or https://github.com/JPerkster/apr, which this is a fork of.

If you do not wish to use the bluehost patch, edit ea-apache2.spec and comment out Patch401: symlink-protection.patch.
You may skip building APR, if so. I do not know if the patched apr will cause issues with an unpatched apache. 
