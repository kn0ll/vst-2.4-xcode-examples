this repository is an updating and reformatting of the defacto examples that come with the VST 2.4 SDK. they have been updated to play nice with Xcode 4.3 and OS X.

download VST 2.4 SDK
===
1. go to [Steinberg's developer page](http://www.steinberg.net/en/company/developer.html)
2. download [VST Audio Plug-Ins SDK (Version 2.3 and 2.4)](http://www.steinberg.net/nc/en/company/developer/sdk_download_portal.html)

install VST 2.4 SDK
===
1. extract `vst_sdk2_4_rev2.zip`
2. copy the extracted `vstsdk2.4` to `~/Code` **✝**

build Xcode project
===
1. `git clone git@github.com:catshirt/vst-2.4-xcode-examples.git`
2. `cd vst-2.4-xcode-examples`
3. `open "VST 2.4.xcodeproj"`
4. build the project **✝✝**

**✝** this Xcode project assumes `vstsdk2.4` is installed in `~/Code`. if you'd like to install it elsewhere, you will need to relink the `vstsdk2.4` group in the project.

**✝✝** surrounddelay currently fails  to build on OS 10.7 because it uses deprecated drawing APIs. i hope to find time to resolve this.