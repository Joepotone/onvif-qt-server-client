# Onvif QT Server and Client

Onvif QT Server Client is a sample for creating `Onvif Server` and `Onvif Client` with `QT C++`. Program has built with `Qt 5.5.0(MSVC 2013, 32 bit)` on `IDE Qt Creator 3.4.2`. In program has used <a href="http://www.genivia.com/dev.html">gsoap</a> c++ api to create both server side(to generate soap services) and client side( to parse it and call). To generate service structure has used `wsdl`-s from <a href="http://www.onvif.org/">onvif</a> protocol. To support, <a href="https://www.buymeacoffee.com/hummatli" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

### About ONVIF

<a href="http://www.onvif.org/">ONVIF</a> is an open industry forum for the development of a global standard for the interface of IP-based physical security products.


### Library structure
Program contains from tree parts
```
* Onvif Client
* Onvif Server
* Onvif libs
```
OnvifLib combines from follwing onvif parts
```
* onvifcore
*        -> OnvifDeviceLib
*        -> OnvifDiscoveryLib
*        -> OnvifEventLib
* OnvifAnaliticsLib
* OnvifDeviceIOLib
* OnvifDisplayLib
* OnvifImaginingLib
* OnvifMediaLib
* OnvifPTZLib
* OnvifReceiverLib
* OnvifRecordingControlLib
* OnvifRecordinSearchLib
* OnvifReplayControlLib
* OnvifVideoAnaliticsDeviceLib
```

### To test program.
* `Run OnvifServer`. It will be listen on 8004 port
* `Run OnvifClient` to discover server and send commands to them.


### End
Thats all. If you have any probelm with using sample please let me know. Write to settarxan@gmail.com. I will help.


### Contribution
* Fork it
* Create your feature branch (git checkout -b my-new-feature)
* Commit your changes (git commit -am 'Added some feature')
* Push to the branch (git push origin my-new-feature)
* Create new Pull Request
* Star it


### Developed By
Sattar Hummatli - settarxan@gmail.com


### License
Copyright 2015  - <a href="https://www.linkedin.com/in/hummatli">Sattar Hummatli</a>   

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
