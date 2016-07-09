---
layout: post
title: 'Cross Platform Oculus and Google Daydream Development'
date: '2016-05-27 16:27:47 +0800'
category: Virtual Reality
featured-image: http://i.giphy.com/BRBSiPddmQQlW.gif
thumbnail-image: http://i.giphy.com/BRBSiPddmQQlW.gif
comments: true

---

A current challenge in VR application development is that there are several environments that a user can build for. These environments include the Oculus Rift PC, Oculus Mobile via Gear VR, and Google Daydream. The goal of this example project was to be able to create a unified prototype that would be able to cross-compile for all 3 of the given VR environments.

In this prototype we unified the camera and input controls for the Oculus Rift and Google Daydream. It allows us to test the VR view on Unity Editor with an Oculus Rift instead of making an APK and testing it on device.

The code should also allow cross-platform compilation for Oculus / Gear VR and Google Daydream phones.

![Flying Castle](http://i.giphy.com/BRBSiPddmQQlW.gif "Flying Castle!")

[Project Code can be found here](https://github.com/polats/gvr-unity-sdk/tree/master/Samples/CastleDefense)

This prototype uses code from the following projects:

1. The Google Daydream Castle Defense Example
* [Github Link](https://github.com/googlevr/gvr-unity-sdk/tree/master/Samples/CastleDefense)

1. The Oculus Sample Framework Code
* [Overview](https://developer.oculus.com/blog/introducing-the-oculus-sample-framework-for-unity-5/ "Overview")
* [Unity Project Download](https://developer.oculus.com/downloads/game-engines/1.3.0/Oculus_Sample_Framework_for_Unity_5_Project/ "Source Code Download")
