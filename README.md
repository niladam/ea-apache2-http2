# ea-apache2-http2
CentOS 7, EA4 and HTTP/2. SEE LINK FOR INFO.

If you want symlink protection, you'll need to edit SPECS/ea-apache24.spec, search for 401 or 402 and uncomment TWICE in it, depending on what you want to use.
The rack911 patch does not require apr to be modified from stock.

If you use Bluehost, you'll need to pull and compile apr from https://github.com/Cacasapo/apr or https://github.com/JPerkster/apr.
