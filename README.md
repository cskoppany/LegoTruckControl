# LegoTruckControl

This repository is created as part of a demo project, where a Lego truck is controlled by a Resperry Pi 3 with Titan and TTCN-3 code running on it. Control is done via mobile phone connected to a Web server. The web server is communicating via COAP messages  with the LegoTruck.
The code is very simple and uses several submodules from Eclipse.Titan and IoT Fuctiojn Test Framework.


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
