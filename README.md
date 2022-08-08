WebXR template for Unity

This is a Unity project created with Unity 2022.1.9f1 and with the modifications detailed in https://github.com/De-Panther/unity-webxr-export/blob/master/Documentation/Getting-Started.md to give you a starter template for a webxr project.

The resulting webgl build needs to run on a https server, if you want to quickly test it without the need of installing a propert http server, you can use the script `https-server` (it was tested on Linux, it should run on macOS also). Run it in the directory the built game is.


## Compression

To be able to run the built game with the python script, the compression was disabled. When publishing the game you should probably enabled the compression (`Edit / Project Settings... / Player / Publishing Settings / Compression format')

