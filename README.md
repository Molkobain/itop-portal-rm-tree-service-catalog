👋 [Available on Molkobain I/O!](https://www.molkobain.com/product/remove-tree-view-from-service-catalog/)

# iTop extension: molkobain-portal-rm-tree-service-catalog
* [Description](#description)
* [Compatibility](#compatibility)
* [Installation](#installation)
* [Configuration](#configuration)

## Description
Remove the *tree* view from the service catalog of the user portal.

*Note: This extension will fail to install if the tree view has already be removed from the service catalog. Also, you must define the default view to something else then tree or the portal will crash.*

*Before*

![Description decoration](https://raw.githubusercontent.com/Molkobain/itop-portal-rm-tree-service-catalog/master/docs/mprtsc-service-catalog-before.PNG)

*After*

![Description decoration](https://raw.githubusercontent.com/Molkobain/itop-portal-rm-tree-service-catalog/master/docs/mprtsc-service-catalog-after.PNG)

## Compatibility
Compatible with iTop 2.3+

## Installation
* Unzip the extension
* Copy the ``dist/molkobain-portal-rm-tree-service-catalog`` folder under ``<PATH_TO_ITOP>/extensions`` folder of your iTop
* Run iTop setup & select extension *Portal: Remove tree mode from service catalog*

*Your folders should look like this*

![Extensions folder](https://raw.githubusercontent.com/Molkobain/itop-portal-rm-tree-service-catalog/master/docs/mprtsc-install.PNG)

## Configuration
### Standard portal
No configuration needed.

### Customized portal
If you customized the user portal, you will have to check/modify 2 things on the ``datamodel.molkobain-portal-rm-tree-service-catalog.xml`` file of the extension, then run an iTop setup.
* Portal ID: If your portal ID is not ``itop-portal``, change it to your custom ID on line 4.
* Service catalog brick: If you are not targetting the standard service catalog, change the brick ID on line 6 (``services``) with yours.

## Licensing
This extension is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
