# LegoTruckControl

This repository is created as part of a demo project, where a Lego truck is controlled by a Resperry Pi 3 with Titan and TTCN-3 code running on it. Control is done via mobile phone connected to a Web server. The web server is communicating via COAP messages  with the LegoTruck.

**************
*** STEP 1 ***
**************
You need Eclipse Titan binary installed on the Rasberry.

**************
*** STEP 2 *** -get the source code
**************
mkdir ~/LegoTruckControl
cd ~/LegoTruckControl
git init
git clone https://github.com/cskoppany/LegoTruckControl.git 
git submodule init 
git submodules update 

**************
*** STEP 3 *** - build binary
**************
mkdir bin
cd bin
../LegoTruckMakefilegen
make

**************
*** STEP 4 *** - Execute
**************
TBA




The following product/project repositories are used to be able to build the executable:
Abstract_Socket
CoAP
GPIO
HTTPmsg
IPL4asp
MQTT
SocketAPI
TCCUsefulFunctions
