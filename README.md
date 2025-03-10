
<div align="center">
  <a >
    <img src="images/impleo_logo.png" alt="Logo" >
  </a>
</div>

# Stanag2WebRTC

**Stanag2WebRTC** allows easy integration of live udp **STANAG 4609** streaming into web-based applications.  
Video and metadata are transcoded on the fly and sent to web clients using **WebRTC** video and data channels. 


![Stanag2WebRTC](images/uavscreen.jpg)

More info on [Stanag2WebRTC](https://impleotv.com/content/stanag2webrtc/help/index.html)


## Installing Stanag2WebRTC


### Linux:

Use **Stanag2WebRTC** docker container. The image will be automatically downloaded.  
```bash
docker run --network host impleo/stanag2webrtc:2.2.0 -url udp://227.1.1.1:30120
```


### Windows

|          | Version             | Download link                                                           | 
|:---------|:-------------------:|:------------------------------------------------------------------------|
| **Stanag2WebRTC** |  v2.1.2 | [SetupStanag2WebRtc.zip](https://github.com/impleotv/stanag2webrtc-release/releases/latest/download/SetupStanag2WebRtc.zip) | 

> Note. The Windows version currently does not support KLV. Use VM if you need KLV on Windows.


*Released on Mon, 9 Dec 2024, 11:19 GMT+2*


## License

*No license is needed for application evaluation - it will work in demo mode (with some restrictions).*

**Stanag2WebRtc** is a node-locked software, so you need to obtain a license (after purchasing the software) in order to lift the demo restrictions. Please install it and fill out an [online form](https://docs.google.com/forms/d/e/1FAIpQLSd_XW6bDsFce1G1cpds4gMQNlwNax0CvkWzcMbscxZ5rLaIbA/viewform), providing the ***Node Info*** string (IMPORTANT!!!) for the target machine.  
You can find the **nodeinfo** string at the top of the client demo app.

Once you submit the form, you will receive a **license** file and a **key** in return.

## System Requirements

OS: Linux 64bit / Windows 10/11 64 bit.

