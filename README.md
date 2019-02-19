# webRTC

This repo are the source code I fetch and sync from google. For me, I use on linux(Ubuntu 14.04) and it works well.  
As you know, fetch from google, a tool named `depot_tools` is required. It also generated a file named `.gclient`. these are the contents in the file. Oh by the way, I've done this on 2019-2-2.  
 1 solutions = [   
 2   {  
 3     "url": "https://chromium.googlesource.com/external/webrtc.git",  
 4     "managed": False,  
 5     "name": "src",  
 6     "deps_file": "DEPS",  
 7     "custom_deps": {},  
 8   },  
 9 ]  
 10 target_os = ["android", "unix"]  
 I put it here just want to help you know if this code can work with you.  
 I'm new here so if I do something wrong I can fix it, and thank you.

### Development

See http://www.webrtc.org/native-code/development for instructions on how to get
started developing with the native code.

### More info

 * Official web site: http://www.webrtc.org
 * Master source code repo: https://webrtc.googlesource.com/src
 * Samples and reference apps: https://github.com/webrtc
 * Mailing list: http://groups.google.com/group/discuss-webrtc
 * Continuous build: http://build.chromium.org/p/client.webrtc
 * [Coding style guide](style-guide.md)
 * [Code of conduct](CODE_OF_CONDUCT.md)
