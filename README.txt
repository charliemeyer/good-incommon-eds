This is a (unofficial) fork of the Shibboleth Embedded Discovery Service.

Shibboleth is a federated web authentication and attribute exchange
system based on SAML. The Embedded Discovery Service allows anyone
running a suitable SP to quickly and easily deploy IdP discovery.

The default Embedded Discovery Service UI doesn't look great though,
and this provides a baseline improvement. The only real changes should
occur in idpselect_languages.js (to change default instruction text) and
in idpselect.css for changing colors/widths. 

For full instructions on installation and deployment please read:

https://wiki.shibboleth.net/confluence/display/EDS10

Shibboleth is licensed under the Apache 2.0 license which is provided in the
LICENSE.txt file.

Shibboleth Project Site:
http://shibboleth.internet2.edu/

Shibboleth Documentation Site:
https://wiki.shibboleth.net/confluence/display/SHIB2/Home

Source and binary distributions
http://www.shibboleth.net/downloads/

Bug Tracker:
https://issues.shibboleth.net/

Other sources:
This tools embeds the JSON parsing tool from https://github.com/douglascrockford/JSON-js
