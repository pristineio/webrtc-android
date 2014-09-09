This Android project is a mirror of the Android AppRTC demo found in the [webrtc project](https://code.google.com/p/webrtc/). However, this Android application includes the sources for the libjingle_peerconnection library normally included pre-compiled with the Android AppRTC demo. **Note that the sources in this project are not in any way ours. We are just mirroring what is all ready available to developers in an Android project form so developers can tweak all the java sources without building or downloading the WebRTC project**


Development
=============
Working with this project requires use of the [Maven Android SDK Deployer](https://github.com/mosabua/maven-android-sdk-deployer). Follow instructions there before proceeding with development. Once you have installed your Android SDK to your local maven repository you can compile and modify the project locally.

The native dependency used is pre-compiled by us and [available on maven central](https://oss.sonatype.org/content/groups/public/io/pristine/libjingle_peerconnection_so/7113/). Note that any library and application changes are bound by the libjingle_peerconnection.so file available. However, feel free to build your own .so file and drop it in this project.


Modifications
=============
This repository is meant to be a starting point for exploration with WebRTC on Android. Only configuration based changes will be considered for this repository. The sources for the application and library will not be different from what is available within the WebRTC project. If you have some changes for the library or application that you think are relevant, feel free to test them out with this project, but please contribute to the official [WebRTC repository](https://code.google.com/p/webrtc/) and the changes will be incorporated here.


Updates
==============
We won't make any promises on periodic updates to this repository, but rest assured we interact with WebRTC on a daily basis and if any noteworthy updates become available we will update the project shortly thereafter.




