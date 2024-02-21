# planet-kit-android
LINE Planet is a cloud-based real-time communications platform as a service (CPaaS) that helps you build a voice and video call environment. With LINE Planet, you can integrate call features into your service at minimum cost.

## Planet Documentation
Planet Documentation provides additional resources to help you integrate LINE Planet into your service. These resources include LINE Planet specifications, developer guides for each client platform, and server API references.

[Planet Documentation](https://docs.lineplanet.me/)

## Installation
Starting with version 5.3.3, PlanetKit Android is distributed through the [Maven Central Repository](https://central.sonatype.com/).

If the Maven Central Repository is not set up in your project, add the repository as follows:
```groovy
// Root-level build.gradle
allprojects {
    repositories {
        mavenCentral()
    }
}
```

Add dependency to your module `build.gradle`.
```groovy
// module-level build.gradle
dependencies {
    ...
    implementation 'com.linecorp.planetkit:planetkit:5.3.3'
    ...
```

## API Reference
For detailed information on APIs, please refer to the following documents.

[API Reference](https://docs.lineplanet.me/api-reference/client/android/5.3/index.html)

## Issues and Inquiries

Please file any issues or inquiries you have to our representative or dl_planet_help@linecorp.com
Your opinions are always welcome. 

## FAQ
You can find answers to our frequently asked questions in the [FAQ](https://docs.lineplanet.me/help/faq/) section.