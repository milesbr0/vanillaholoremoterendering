# Holographic Remoting

## Unity project preparation

1. Build Settings: set build platform to UWP
2. import [MRTK fundamentals](https://github.com/microsoft/MixedRealityToolkit-Unity/releases/download/v2.4.0/Microsoft.MixedReality.Toolkit.Unity.Foundation.2.4.0.unitypackage)
3. Package Manager: add Windows Mixed Reality **v4.2.1** package
4. Package Manager: add MSBuild for Unity **v0.9.2** package(_may not need it, didn&#39;t test without it_)
5. XRSettings : Enable Virtual Reality Support + add WMR SDK
6. XRSettings : enable WSA holographic Remoting
7. Download + import **HolographicRemoting** _prefab_ and **HolographicRemoteConnect** _script_[MRTK.Tutorials.PCHolographicRemoting.unitypackage](https://github.com/onginnovations/MixedRealityLearning/releases/download/pc-holographic-remoting-v2.4.0.0/MRTK.Tutorials.PCHolographicRemoting.unitypackage)
8. XRSettings : 16-bit depth format + single pass instanced rendering mode
9. Capabilities:
  - InternetClient
  - InternetClientServer

### Screenshots

1 _Package Manager_

![alt text](https://github.com/milesbr0/vanillaholoremoterendering/blob/master/tutimages/packagemanager.png?raw=true)

2 _Build Settings_

![alt text](https://github.com/milesbr0/vanillaholoremoterendering/blob/master/tutimages/buildsettings.png?raw=true)

3 _Capabilities_

![alt text](https://github.com/milesbr0/vanillaholoremoterendering/blob/master/tutimages/capabilities.png?raw=true)

4 _XRSettings_

![alt text](https://github.com/milesbr0/vanillaholoremoterendering/blob/master/tutimages/XRsettings.png?raw=true)

## Visual Studio settings

- Release + x64
- Local machine
- Start without debugging (CTRL+F5)

### Screenshots

![alt text](https://github.com/milesbr0/vanillaholoremoterendering/blob/master/tutimages/vssettings1.png?raw=true)
![alt text](https://github.com/milesbr0/vanillaholoremoterendering/blob/master/tutimages/vssettings2.png?raw=true)
