
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
docker run --network host impleo/stanag2webrtc:1.0.9 -url udp://227.1.1.1:30120
```


### Windows

|          | Version             | Download link                                                           | 
|:---------|:-------------------:|:------------------------------------------------------------------------|
| **Stanag2WebRTC** |  v1.0.9 | [SetupStanag2WebRtc.zip](https://github.com/impleotv/stanag2webrtc-release/releases/latest/download/SetupStanag2WebRtc.zip) | 

> Note. Windows version requires **GStreamer** demux patch. Without the patch, streams with SYNC KLV will not work.


*Released on Thu, 19 Jan, 14:07 GMT+2*


## License

*No license is needed for application evaluation - it will work in demo mode (with some restrictions).*

**Stanag2WebRtc** is a node-locked software, so you have to get a license (after purchasing the SW) in order to lift demo restrictions. Please install it and fill out an [online form](https://docs.google.com/forms/d/e/1FAIpQLSd_XW6bDsFce1G1cpds4gMQNlwNax0CvkWzcMbscxZ5rLaIbA/viewform), providing the ***Node Info*** string (IMPORTANT!!!) for the target machine.  
You can obtain the **nodeinfo** string at the top of the client demo app.

You'll get back a **license** file and a **key**.

## System Requirements

OS: Linux 64bit / Windows 10 64 bit.

