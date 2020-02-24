## iOS WebRTC build 

Because of Google stopped building webRTC and we need prepared build for our projects, we decided to share precompiled builds.

How it is done:
1. we make build with each new Chrome version - same WebRTC branch, that is used in Chrome is used here
2. the versioning is based by Chrome version (1.M80 is equals to Chrome 80)
3. the build is just basic one - equivalent to calling `tools_webrtc/ios/build_ios_libs.sh`