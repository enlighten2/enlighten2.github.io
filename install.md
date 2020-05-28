---
title: "Installation"
permalink: /install/
css: /assets/css/install.css
---

## Installation

> **NB**: This instruction is for the Enlighten2 PyMOL plugin. Installation 
instructions for the Python package can be found 
[here](https://github.com/vanderkamp/enlighten2) 
(aimed for advanced users, requires 
[AmberTools19](https://ambermd.org/AmberTools.php) and 
[Propka3.1](https://github.com/jensengroup/propka-3.1)).

The only dependencies of the Enlighten2 PyMOL plugin are 
[PyMOL](https://github.com/schrodinger/pymol-open-source) and 
[Docker](https://docs.docker.com/install/). Installation instructions for 
different platform can be found on the following webpages.

### PyMOL
* [Windows](https://pymolwiki.org/index.php/Windows_Install)
* [Mac](https://pymolwiki.org/index.php/MAC_Install)
* [Linux](https://github.com/schrodinger/pymol-open-source/blob/master/INSTALL)

### Docker
* [Windows 10 Pro](https://docs.docker.com/docker-for-windows/install/) Note that 
Windows Home 
* [Windows 10 Home](https://docs.docker.com/docker-for-windows/install-windows-home/) 
(version 2004 or higher, for older versions, please, install 
[Docker Toolbox](https://docs.docker.com/toolbox/toolbox_install_windows/))
* [Mac](https://docs.docker.com/docker-for-mac/install/)
* [Linux](https://docs.docker.com/engine/install/)

### Enlighten2 PyMOL plugin 

1. We will first obtain the Enlighten plugin from the github repository. It 
can be done either by clicking on "Download PyMOL plugin" on top of this page or 
from the [github repository](https://github.com/vanderkamp/enlighten2-pymol).

2. Open PyMOL. The following window will appear, consisting of a viewing window 
and a control panel:
![](assets/img/install/01.png)

3. We now need to load the enlighten plugin into PyMOL. From the menu bar
choose Plugin and then Plugin Manager.
![](assets/img/install/02.png)

4. In the Plugin manager choose the Install New Plugin tab and then select 
install from local file. When you click on the "Choose file" button you will 
need to choose the zip file with the Enlighten plugin downloaded in step 1.
![](assets/img/install/03.png)

5. A new window will pop-up asking you to select a plugin directory. Choose the 
first option and click OK.
![](assets/img/install/04.png)

6. A message will appear to say that the plugin has been successfull installed. 
Exit the Plugin manager.
![](assets/img/install/05.png)

7. The Enlighten plugin is now available in the Plugin drop-down menu.
![](assets/img/install/06.png)