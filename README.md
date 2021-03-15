


AEM We-Retail Content Package
========
This sample code include content package for AEM sample site(we-retail)

Building
--------

This project uses Maven for building. 

First, be sure that your Maven **settings.xml** file contains the **Adobe Public Maven Repository profile** (see:  [repo.adobe.com](https://repo.adobe.com "Adobe Public Maven Repository"))


Common build commands:

From the root directory, run ``mvn -PautoInstallPackage clean install`` to build the bundle and content package and install to a CQ instance.

From the bundle directory, run ``mvn -PautoInstallBundle clean install`` to build *just* the bundle and install to a CQ instance.


Specifying CRX Host/Port
------------------------

The CRX host and port can be specified on the command line with:
mvn -Dcrx.host=otherhost -Dcrx.port=5502 <goals>


