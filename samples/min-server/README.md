Minimum Config Server Sample
===

This sample shows a minimal set of configuration directives. This server supports the file and ESP handlers.
CGI, PHP, Ejscript and SSL are not configured.

You are encouraged to read the [typical-server - Typical server](../typical-server/README.md) sample to see what
other appweb.conf directives are available.

Requirements
---
* [Appweb](https://embedthis.com/appweb/download.html)
* [MakeMe Build Tool](https://embedthis.com/makeme/download.html)

To build:
---
    me 

To run:
---
    me run

The server listens on port 8080. Browse to: 
 
     http://localhost:8080/

Code:
---
* [appweb.conf](appweb.conf) - Appweb server configuration file
* [auth.conf](auth.conf) - User/Password/Role authorization file
* [index.html](index.html) - web page to serve
* [web](web) - Web content to serve
* [start.me](start.me) - MakeMe build instructions

Documentation:
---
* [Appweb Documentation](https://embedthis.com/appweb/doc/index.html)
* [Configuration Directives](https://embedthis.com/appweb/doc/users/configuration.html#directives)
* [Sandbox Limits](https://embedthis.com/appweb/doc/users/dir/sandbox.html)

See Also:
---
* [max-server - Maximum server configuration](../max-server/README.md)
* [simple-server - Simple one-line embedding API](../simple-server/README.md)
* [typical-server - Typical server](../typical-server/README.md)
