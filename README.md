# maya-crMAPswitcher

[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)]()
[![MIT](https://img.shields.io/badge/license-MIT-green)]()

[![](https://img.shields.io/badge/TWITTER-%40artbycrunk-blue.svg?logo=twitter&style=flat)](https://twitter.com/artbycrunk)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/artbycrunk/maya-crMAPswitcher.svg)](https://isitmaintained.com/project/artbycrunk/maya-crMAPswitcher "Average time to resolve an issue")
[![Percentage of issues still open](https://isitmaintained.com/badge/open/artbycrunk/maya-crMAPswitcher.svg)](https://isitmaintained.com/project/artbycrunk/maya-crMAPswitcher "Percentage of issues still open")

A useful little script for easily converting and replacing your textures to .map files.

<!-- Images -->
[crMAPswitcher_screen01]: images/crMAPswitcher_screen01.jpg "crMAPswitcher_screen01"
<!-- Files -->
<!-- Links -->
[Mipmap]: http://en.wikipedia.org/wiki/Mipmap
<!-- Conent -->

![crMAPswitcher_screen01][crMAPswitcher_screen01]

* Just Source this script, it should open the crMAPswitcher Window.
* Can Convert any textures formats to a .map format. based either on selection or all the textures in scene.
* Automatically converts to .map file in background.
* Can switch selected files to its .map replacement or back to the original at the click on the button.
* All .map files are converted with **filtered mipmap image pyramid method** (Tile Based) for memory management. to know more about [Mipmap][Mipmap]
* Works with both Maya file texture nodes and MentalRay Texture Nodes.
* Looks for existing .map files and only converts files of which .map do not already exist.

**USAGE** : 
1. Source the script. Choose to work on selected or all textures. 

2. If you are working on selection basis, please select the desired file nodes, whos textures u want to convert. 

3. Click the convert textures to .map button, if you only want it to convert .map that dont exist. then click the convert only button. 

4. The .map file will be saved in the same folder as your original texture.

5. To switch to the .map at any time, select the texture and click switch .map file and it will pick up the relevant .map version. 

6. Do the same to switch back to the original by clicking the switch to use original files.
