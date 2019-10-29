## QGIS version
* Tested on the mac version (64 bits) of QGIS 2.18.20 in plain english version
* ![version.png](https://bitbucket.org/repo/ayrEdXL/images/2685026011-qgis.png)

## QGIS Plugin repository
* Check [here](https://plugins.qgis.org/plugins/plugins.xml) the QGIS Python Plugins available (depends according your installed version of QGIS)

## Procedures
* Download QGIS according your operating system. Verify that the chosen version meets the system requeriments
* Install the `GDAL` complete framework
* Install `NumPy`
* Install `MatplotLib`
* Install `QGIS`

## How to deal with (our) proxy server
* Launch `QGIS`
* Click on the upper left menu: `QGIS` > `Preferences` > `Network`
* Tick on `Use proxy for web access`. On proxy type, choose from the dropdown menu the option: `HttpProxy`. 
* ![proxy.png](https://bitbucket.org/repo/ayrEdXL/images/2044149627-proxy.png)
* Then on `Host`: add `192.168.4.1`
* On `Port`: add `3128`
* On `User`: add the usual internet user provided
* On `Password`: add the usual password provided
* Clic `OK`

## How to install plugins from QGIS
* In QGIS, from the upper menu, go to `Plugins`. A dropwdown menu will display. Select the `Manage and install Plugins...` option
* Automatically it will display this menu
* ![plugin.png](https://bitbucket.org/repo/ayrEdXL/images/261314794-plugins.png)
* Select the plugin that wish to install. Then click on `Install plugin` option on the lower right of the menu. Once installed, click on `Close`

 
