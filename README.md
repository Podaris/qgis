# Podaris QGIS

A QGIS plugin for interacting with projects on the Podaris platform.

## What is Podaris?

Podaris is a real-time collaboration platform for planners, engineers, policymakers, and public stakeholders.

Create multi-modal transport networks and analyze their costs and benefits. Share these models with internal or external collaborators, ensuring that they are vetted and validated from every possible angle.

High-level analytical tools give an immediate understanding of travel-time and spatial connectivity.

## Installation

While the plugin is in beta, we will not publish to a plugin repository. If you
are interested in trying out the plugin you can download the latest release zip
and extract it to your plugin directory.

The various releases can be found here: https://github.com/Podaris/qgis/releases

More information on how to do this on your OS can be found here:
https://gis.stackexchange.com/a/127791

### Requirements

- QGIS > 2.0.0
- Python

## Usage

Once installed you should see the Podaris option in the web menu of the toolbar:

![web menu](/img/webmenu.png)

The first time you click 'Import project view' in a session it will ask you for your access key.
You can find this in your account settings here: https://app.podaris.com/account/keys

Once you have autenticated you should see the select a view dialog:

![import view](/img/import_view.png)

Here you should be able to select any project you have edit level access to, and once selected any of its views.
Finally you must choose where you want to store the imported layers on your filesystem.

After clicking 'Okay' the view should appear inside of QGIS:

![network](/img/network.png)
  
## Help
For help please contact support@podaris.com
