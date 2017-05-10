# SpaceNav3D

An unofficial [3DConnexion](https://www.3dconnexion.eu) Space Navigator support for [Unreal Engine 4](https://www.unrealengine.com/).

## Installation

 1. Download and install the 3DConnexion [3DxWare drivers](http://www.3dconnexion.eu/service/drivers.html)
 2.	[Download the latest release](releases)
 3.	Extract the SpaceNav3D folder into your UE4 Engine Plugins folder (usually something like `C:\Program Files (x86)\Epic Games\UE_4.15\Engine\Plugins`.
 4. Enable the plugin via Edit > Plugins > Installed > Input Devices > SpaceNav3D. Click Enabled.
 5.	Restart the Editor and open your project again. Plugin is now ready to use.

## Help

[Main discussion thread](https://forums.unrealengine.com/showthread.php?380-Support-for-Space-Navigator-3D-Mouse/)

## Compile SpaceNav3D plugin
To Use in a newer UE4 version (Tested on UE4.15) compile the source code by following these steps

1. Download the [3DxWare SDK](http://www.3dconnexion.com/nc/service/software-developer/licence-agreement/sdk_download.html), you must be registred
2. Copy or reference **3DxWare SDK** to `Plugins\SpaceNav3D\ThirdParty`
3. Enable the plugin via Edit > Plugins > Installed > Input Devices > SpaceNav3D. Click Enabled.
4. Restart the Editor

## Developing

If you want to develop for the plugin, you will need to download the 3DxWare SDK yourself from the [3DConnextion SDK Website](https://www.3dconnexion.eu/service/software-developer/licence-agreement/sdk-download.html) (requires free registration), and then extract it into the provided folder (ThirdParty/3DxWare SDK). The SDK terms prevent distribution by developers.

## Credit and License
Plugin made by [ParcelRot](https://github.com/ParcelRot) and updated by [aaronsnoswell](https://github.com/aaronsnoswell). Point all questions to the main discussion thread.

The 3DConnexion SDK is governed by the [3DConnexion Terms](http://www.3dconnexion.eu/terms.html) and [3DConnextion SDK License](https://www.3dconnexion.eu/service/software-developer/licence-agreement/sdk-download.html).
