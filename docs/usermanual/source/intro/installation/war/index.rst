.. _intro.installation.war:

OpenGeo Suite for Application Servers
=====================================

In addition to being available through installers and packages, OpenGeo Suite web applications such as GeoServer are available individually for use with a custom application server. Web applications are distributed as web archives (WAR files).
   
**This is the recommended method of install for systems that already have an application server** in place, rather than using a duplicate container, as can happen with the installers.
   
The individual applications shipped as part of the WAR bundle are:

* GeoServer
* GeoExplorer
* GeoWebCache
* Dashboard
* Documentation

An additional :ref:`extensions <intro.installation.war.extensions>` download is available as well.

.. note:: As PostGIS is not a web application, it is not included in this bundle. If you want to use PostGIS as part of your OpenGeo Suite installation, you should install it from the installer or from packages (``opengeo-postgis``).

.. note:: QGIS is also not included. Boundless has installers for :ref:`Windows <intro.installation.windows.qgis>` and :ref:`OS X <intro.installation.mac.qgis>`. To use QGIS with Linux, please see the `QGIS community installation instructions <https://www.qgis.org/en/site/forusers/download.html>`_.

Please select the option that best matches your system:

:ref:`intro.installation.war.install`
  For new installations.

:ref:`intro.installation.war.strategies`
  Methods to ensure optimal deployments.

:ref:`intro.installation.war.update`
  For all updates. To update from either OpenGeo Suite 3.x or 4.x, start here.

:ref:`intro.installation.war.postinstall`
  Useful information about the installation.

:ref:`intro.installation.war.extensions`
  Details about the optional extensions bundle.

:ref:`intro.installation.war.uninstall`
  For removing OpenGeo Suite.

.. toctree::
   :hidden:

   install
   strategies
   update
   postinstall
   extensions
   uninstall

