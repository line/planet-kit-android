# planet-kit-virtual-background

`planet-kit-virtual-background` is the virtual background plugin of `planet-kit-android`.

The virtual background feature applies effects to the background of the video stream by detecting and segmenting the person from the background.

Starting from version 5.5.1, the `PlanetKitPluginProviderVirtualBackground` class is now provided as a separate plugin, enabling developers to obtain a `PlanetKitPluginVirtualBackground` instance through the plugin.

## Installation

Starting with version 5.5.1, `planet-kit-virtual-background` is distributed through the [Maven Central Repository](https://central.sonatype.com/).

Add dependency to your module `build.gradle`.
```groovy
// module-level build.gradle
dependencies {
    ...
    implementation ('com.linecorp.planetkit:plugin-virtualbackground:1.0.0') {
        exclude group: 'com.linecorp.planetkit', module: 'planetkit'
    }
    ...
```

## How to use PlanetKitPluginProviderVirtualBackground

```groovy
    val plugin: PlanetKitPluginVirtualBackground = PlanetKitPluginProviderVirtualBackground.getPlugin()
    PlanetKit.getCameraManager().setVirtualBackgroundPlugin(plugin)

    ...
    PlanetKitPluginProviderVirtualBackground.getPlugin().setVirtualBackgroundWithBlur(20)

```

## API Reference

For detailed information on APIs, please refer to the following documents.

[API Reference](https://https://docs.lineplanet.me/api-reference/client/android/5.5/index.html)

## Issues and Inquiries

Please file any issues or inquiries you have to our representative or dl_planet_help@linecorp.com.
Your opinions are always welcome.
