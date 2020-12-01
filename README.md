# Simple FPS Controller

This is an extremely simple FPS controller for Unity games.

There used to be a somewhat functional FPS controller as part of the [Unity Standard Assets](https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-for-unity-2018-4-32351#reviews) package, but it had quite a few problems such as horribly stuttery movement when strafing and rotating.

I thought the FPS controller that was part of Unity's [FPS microgame](https://assetstore.unity.com/packages/templates/fps-microgame-156015) would be a good place to start, but that controller is hopelessy entangled with the rest of the game's components. You can't just extract out just the FPS controller part, without also dragging a bunch of other systems with it.

So I made this. It's a combination of a few different bits of tutorials and forum posts here and there. It was created out of the work I did in making an FPS tower defense game for [Global Game Jam 2020](https://globalgamejam.org), called Scrappy Defense.

This FPS controller is extremely simple. It's self-contained and very easy to build on and modify. If you have suggestions for improvements, I'm happy to hear them, but keep in mind that the intention of this package is to keep it extremely basic and simple.

## Installation

1) Download **SimpleFPSController.package** file
2) Open Unity
3) Click **Custom Package** under the **Assets > Import Package** menu.
4) Find the package file you downloaded and import it
5) Drag the SimpleFPSController_Prefab into your scene
6) If you already had a Main Camera in your scene, either disable or remove it so that the Simple FPS Controller camera is the Main Camera

## Notes

* Tested in Unity 2019.x and 2020.x

## License
This is public domain. Use this code however you want.