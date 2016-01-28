PHP has [SOAP support](http://no2.php.net/manual/en/book.soap.php). What is missing is a WSDL generator that supports document/literal SOAP style.

The original code was published on [http://www.schlossnagle.org/~george/php/WSDL\_Gen.tgz](http://web.archive.org/web/*/http://www.schlossnagle.org/~george/php/WSDL_Gen.tgz) and supported only RPC encoded SOAP. I put a copy of the original under [Downloads](http://code.google.com/p/php-wsdl-generator/downloads/detail?name=WSDL_Gen.tar.gz&can=1&q=).

Unfortunately the site is not operational any longer and there is no license attached to the package. If you are the original developer of the package, please step forward, I would like to give you some credit.

**NB:** complex types as return types are not supported because PHP's `SoapServer` class does not create a proper return. For now, just return a string. You can json-encode complex structures.

&lt;wiki:gadget url="http://www.ohloh.net/p/488478/widgets/project\_partner\_badge.xml" height="53" border="0"/&gt;