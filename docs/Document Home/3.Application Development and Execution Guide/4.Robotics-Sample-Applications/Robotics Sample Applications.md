

The Qualcomm® Intelligent Robotics (QIR) SDK for Ubuntu provides essential components for developing robotic features on Qualcomm platforms using the Ubuntu operating system.

## Key Features of the QIR SDK:  
•	**Reference ROS Packages**: Includes Robot Operating System (ROS) packages to support robotic application development.  
•	**End-to-End Scenario Samples**: Offers sample scenarios to help evaluate robotic platforms.  
•	**QRB ROS Transport**: Enables zero-copy transport of ROS messages on Qualcomm robotics platforms.  

:::note
 QRB ROS Transport is implemented based on [REP 2007](https://www.ros.org/reps/rep-2007.html), which defines interfaces for serializing custom types and supports intra-process communication without conversion.
:::

## Getting Started with QIR SDK on Ubuntu
This guide walks you through using QIR sample applications on development kits running Ubuntu.

## Setup Instructions:
1.	Fetch ROS2 and QIR SDK using scripts.
2.	Install the QIR SDK.
3.	Add ROS source to your device following the ROS2 documentation.
4.	Add Qualcomm public PPA archives to your Ubuntu software sources: 

```shell
sudo add-apt-repository ppa:ubuntu-qcom-iot/qcom-ppa
sudo add-apt-repository ppa:ubuntu-qcom-iot/qirp
5.	Install and configure the QIR SDK: 
sudo apt install qirp-sdk
source /usr/share/qirp-setup.sh
```

## Sample Applications
The QIR SDK includes a variety of sample applications categorized as follows:
•	**Platform Sample Applications**: Demonstrate platform-level capabilities.
•	**Robotics Sample Applications**: Enable robotic functionalities such as CPU load monitoring and robot simulation using ROS2.

## Reference Documentation  
For details instructions to run the sample applications, Please refer for [Qualcomm Intelligent Robotics SDK for Ubuntu](https://docs.qualcomm.com/bundle/publicresource/topics/80-90441-2/robotics-platform-samples_3_1.html?state=preview)





