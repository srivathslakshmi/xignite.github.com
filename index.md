Xignite Engineering Examples, by Language
=============================

Java
===
 
 * [Full example](https://gist.github.com/4323381), using [Apache Axis2](http://axis.apache.org/axis2/java/core) to make authenticating web service calls via SOAP
 * [Example snippet](https://gist.github.com/4323384), also using Axis2, but manually circumventing an issue where a .NET enum with the [FlagsAttribute](http://msdn.microsoft.com/en-us/library/system.flagsattribute.aspx) is exposed, requiring an array of the enum type to be passed in, regardless of intended cardinality


PHP
-----

 * [Full example](https://gist.github.com/4323414) using the [PHP5 SOAP](http://php.net/manual/en/book.soap.php) module, authenticating and consuming [xGlobalHistorical](http://www.xignite.com/Product/XigniteGlobalHistorical/) data
 * [Full example](https://gist.github.com/4323407) using [xMetals'](http://www.xignite.com/product/gold-metal/) custom charting API

Ruby
-----

 * [Full example](https://gist.github.com/4323425) using the [Savon](http://savonrb.com/) SOAP gem
 * Note that this is not necessary; Xignite provides a RESTful API that can emit JSON.