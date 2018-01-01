# improv-bot
This project is funded by VCU Arts Adjunct Faculty Grant. 

Hardware: Intel NUC5CPYH, Xbox 360 Kinect Sensor v1, AC Adapter Power Supply Cable

+ Create a [bootable USB Stick][5] on MacOS

+ Install [Ubuntu Desktop 16.04.1 LTS][6] on NUC

+ Follow these instructions to install [Ubuntu Core][4] on NUC

+ Install [Processing 3][3] for Linux 64-bit

+ Install [Oracle Java 8][1] (JDK8 and JRE8)

+ Install [libfreenect][2]

+ Install OpenNI

## THE OPENNI WEBSITE HAS BEEN SHUTDOWN.
OpenNI (framework) and Nite (middleware) are libraries used for communicating with the Microsoft Kinect. Currently, versions of OpenNI and Nite used by the SDK are available on the [OpenNI SDK History][7] page. 

NOTE: On Linux systems, you will also need a C compiler to properly compile the libraries for OpenNI and other drivers. For Ubuntu-style distributions, install the "build-essential" package. Use the command sudo apt-get install build-essential to install.

## Install Notes:
Instructions copied and modified from the [avin2/SensorKinect][8] and [ColoradoSchoolOfMines/interface_sdk][9] Github repositories.

To Install, navigate to the respective directory and run the command:

       sudo ./install.sh
       
1) Install the former OpenNI (http://openni.ru/openni-sdk/openni-sdk-history-2/index.html)
2) Install Sensor 
3) Install NiTE 

4) Test #1: Run the NiViewer sample to make sure depth & image streams are working.
5) Test #2: Run the OpenNI/NiUserTracker sample play with the skeleton.
6) Test #3: Try the NITE/Sample-PointViewer sample for the hand tracking demo.

For Linux, you will need to install the latest LibUSB.

1) Run: sudo apt-get install libusb-1.0-0-dev
2) Run: sudo apt-get install freeglut3-dev

[1]:http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html
[2]:https://openkinect.org/wiki/Getting_Started#Ubuntu.2FDebian
[3]:https://processing.org/download/
[4]:https://developer.ubuntu.com/core/get-started/intel-nuc 
[5]:https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-macos#0
[6]:http://releases.ubuntu.com/16.04.2/ubuntu-16.04.2-desktop-amd64.iso
[7]:http://openni.ru/openni-sdk/openni-sdk-history-2/index.html
[8]:https://github.com/avin2/SensorKinect/tree/master
[9]:https://github.com/ColoradoSchoolOfMines/interface_sdk/wiki/Setup:-Installing-OpenNI-and-Nite
