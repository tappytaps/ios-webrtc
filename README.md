## iOS WebRTC build 

Because of Google stopped building webRTC and we need up to date builds for our projects, we decided to share our precompiled builds to save computers / developers energy.

How it is done:
1. we are makeing build with each new Chrome version - same WebRTC branch, that is used in Chrome is used here. First one is M81 (Chrome 81)
2. the versioning is based by Chrome version (1.M81 is equals to Chrome 81)
3. the build is just basic one - equivalent to calling `tools_webrtc/ios/build_ios_libs.sh`