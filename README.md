# Android-Hermes

Created on April 17, 2022

Created by [Andrew-Chen-Wang](https://github.com/Andrew-Chen-Wang)

Implementing JavaScript interpreter on Android using Hermes like iOS's JavaScriptCore

This repository is intended for the Ur, but what I've learned here is
free for everyone to view and reproduce.

### Why not iOS

Because Apple's App Store policy requires that interpreting
JavaScript requires you to use JavaScriptCore which is basically
interpreting JS without a web view.

Why Hermes? Because the other packages in the Android ecosystem are
unmaintained as of April 2022 like AndroidJSCore and LiquidCore, its
successor (and LiquidCore has been unmaintained for two years).


### License and Credit

The code in this repository is licensed under Apache 2.0. The license
file can be found in the file [LICENSE](./LICENSE)

Thank you to the FB team for creating Hermes for React Native.
