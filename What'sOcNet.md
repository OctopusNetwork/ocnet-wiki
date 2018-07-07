# What is OcNet

OcNet is a global network which is implemented based on the following technology</br>
* * *
* Block chain</br>
* Reliable transportation over UDP</br>
* Raptor code</br>
* BBR like congestion control</br>
* Multi path transportation</br>
* Multi link transportation balance</br>
* * *
OcNet want to build a network in which every network node could be accessed by others freely. Users in OcNet could provide service to others with their node. The service could be</br>
* * *
* Bandwidth sharing</br>
* Payment</br>
* High bitrate(20Mbps) live video communication</br>
* High bitrate(20Mbps) VOD streaming</br>
* Privacy communication</br>
To enhance the traditional cloud network access to be decentralized. In OcNet, each user can use network freely, with their privacy protected by the network machenism.</br>
* * *
OcNet provide a cross platform which could be run on Windows / MacOS / iOS / Linux / RTOS. Here RTOS could be a tailored Linux, or private operating system which is built by hardware manufacturor such as VxWorks, RT-Thread, ThreadX, Nucleus, etc. A platform isolation layer is implemented to provide unique APIs to upper layer service. Virtual Machine is implemented based on low level APIs and utils to run contract script， or some special application which need to be run in isolated environment. The native service is built to wrapper basic ability of low level network. Developer could develop application based on service provided by OcNet to build their application.
* * *
![avatar](https://github.com/OctopusNetwork/ocnet-wiki/blob/master/System%20Architecture.png)
