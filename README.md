## Overview
Welcome to the Webcam Search Guide repository! This repository provides a collection of Google and Shodan dorks specifically designed to locate various types of webcams. It includes search queries for different brands and models and offers tips on effectively using these queries.

## Google Dorks
This section lists various Google dorks that can be used to find webcams:

- `inurl:"CgiStart?page="` - Search for webcams with CGI interfaces.
- `inurl:camctrl.cgi` - Find cameras using CGI for control.
- `inurl:"view/index.shtml"` - Locate webcams with specific view pages.
- `intitle:"IP CAMERA Viewer" intext:"setting |Client setting"` - Search for IP camera viewers.
- `intitle:"Device(" AND intext:"Network Camera" AND "language:" "AND "Password"` - Locate network cameras with device settings.
- `intitle:"webcam 7" inurl:"/gallery.html"` - Find galleries of webcams.
- `intitle:"yawcam" inurl:":8081"` - Search for webcams using Yawcam.
- `intitle:"iGuard Fingerprint Security System"` - Locate iGuard security systems.
- `(intitle:MOBOTIX intitle:PDAS) | (intitle:MOBOTIX intitle:Seiten) | (inurl:/pda/index.html +camera)` - Search for MOBOTIX cameras.
- `intitle:"Edr1680 remote viewer"` - Find remote viewers for Edr1680.
- `intitle:"NetCam Live Image" -.edu -.gov -johnny.ihackstuff.com` - Locate NetCam live images.
- `intitle:"INTELLINET" intitle:"IP Camera Homepage"` - Search for INTELLINET IP camera homepages.
- `intitle:"WEBDVR" -inurl:product -inurl:demo` - Find WEBDVR systems excluding products and demos.
- `intitle:"Middle frame of Videoconference Management System" ext:htm` - Locate videoconference management systems.
- `tilt intitle:"Live View / - AXIS" | inurl:view/view.shtml` - Search for AXIS live view cameras.
- `intitle:"AXIS 240 Camera Server" intext:"server push" -help` - Find AXIS 240 camera servers.
- `intitle:"--- VIDEO WEB SERVER ---" intext:"Video Web Server" "Any time & Any where" username password` - Search for video web servers with default credentials.
- `intitle:HomeSeer.Web.Control | Home.Status.Events.Log` - Locate HomeSeer web controls.
- `intitle:"supervisioncam protocol"` - Find supervision cameras.
- `intitle:"active webcam page"` - Search for active webcam pages.
- `inurl:"MultiCameraFrame?Mode=Motion"` - Locate multi-camera frames in motion mode.
- `VB Viewer inurl:/viewer/live/ja/live.html` - Find VB viewers with live feed.
- `inurl:control/camerainfo` - Search for camera control information.
- `intitle:"webcamXP 5" -download` - Locate webcamXP 5 downloads.
- `inurl:"/view/view.shtml?id="` - Find webcam view pages by ID.
- `inurl:/view/viewer_index.shtml` - Search for viewer index pages.
- `intext:"powered by webcamXP 5"` - Find pages powered by webcamXP 5.
- `intitle:"webcam 7" inurl:"8080" -intext:"8080"` - Locate webcam 7 on port 8080.
- `intitle:"Live View /- AXIS" |inurl:view/view.shtml OR inurl:view/indexFrame.shtml |intitle:"MJPG Live Demo" |intext:"Select preset position"` - Search for AXIS live view or MJPG demos.
- `allintitle:Axis 2.10 OR 2.12 OR 2.30 OR 2.31 OR 2.32 OR 2.33 OR 2.34 OR 2.40 OR 2.42 OR 2.43 "Network Camera"` - Locate Axis network cameras.
- `allintitle:Edr1680 remote viewer` - Find Edr1680 remote viewers.
- `allintitle:EverFocus |EDSR |EDSR400 Applet` - Search for EverFocus and EDR cameras.
- `allintitle:EDR1600 login |Welcome` - Find EDR1600 login pages.
- `intitle:"BlueNet Video Viewer"` - Locate BlueNet video viewers.
- `intitle:"SNC-RZ30" -demo` - Find SNC-RZ30 demo pages.
- `inurl:cgi-bin/guestimage.html` - Search for guest image pages.
- `(intitle:(EyeSpyFX|OptiCamFX) "go to camera")|(inurl:servlet/DetectBrowser)` - Locate EyeSpyFX or OptiCamFX cameras.
- `intitle:"Veo Observer XT"` - Find Veo Observer XT cameras.
- `inurl:shtml|pl|php|htm|asp|aspx|pDf|cfm -(intext:observer)` - Search for observer-related camera pages.
- `inurl:top.htm inurl:currenttime` - Locate time-related top pages.
- `intitle:"webcamXP 5"` - Find webcamXP 5 related pages.
- `inurl:"lvappl.htm"` - Locate lvappl.htm pages.
- `inurl:/view.shtml` - Search for view.shtml pages.
- `intitle:"Live View/ — AXIS"` - Locate AXIS live view pages.
- `inurl:iview/view.shtml` - Find iview pages.
- `inurl:ViewerFrame?M0de=` - Search for ViewerFrame mode pages.
- `inurl:ViewerFrame?M0de=Refresh` - Locate ViewerFrame refresh mode pages.
- `inurliaxis-cgi/jpg` - Find Axis CGI JPEG feeds.
- `inurliaxis-cgi/mjpg (motion-JPEG) (disconnected)` - Locate Axis CGI MJPEG feeds.
- `inurl:view/indexFrame.shtml Axis` - Search for Axis index frame pages.
- `inurl:iview/index.shtml` - Find iview index pages.
- `inurl:ViewerFrame? intitle:"Network Camera NetworkCamera"` - Locate network camera pages.
- `intitle:"WEBCAM 7 " -inurl:/admin.html` - Search for webcam 7 excluding admin pages.
- `intitle:NetworkCamera intext:"Pan / Tilt" inurl:ViewerFrame` - Locate network cameras with Pan/Tilt features.
- `inurl:/live.htm intext:"M-JPEG"|"System Log"|"Camera-1"|"View Control"` - Find M-JPEG live feeds with system logs.
- `intitle:"webcamXP 5" inurl:8080 'Live'` - Search for live webcamXP 5 feeds on port 8080.
- `inurl:"MultiCameraFrame?Mode=Motion"` - Locate multi-camera frames in motion mode.
- `intitle:"IP CAMERA Viewer" intext:"setting | Client setting"` - Find IP camera viewers.
- `intitle:"Weather Wing WS-2"` - Locate Weather Wing WS-2 cameras.

## Shodan Dorks
These Shodan dorks can help you locate webcams with specific configurations:

- `DCS-5220 IP camera` - D-Link IP cameras.
- `IP CAMERA Viewer | TP-Link IP Cameras` - Several cameras have a PTZ option (Pan-Tilt-Zoom). No authentication is required.
- `Sony Network Camera` - CCTV systems from the 'Sony' brand.
- `webcamxp` - One of the best dorks for IP cameras/webcams.
- `Foscam (old Web UI)` - Foscam devices using an old Web UI around the world.
- `IP Camera 3` - Another great IP cam search.
- `Planet IP Cam` - Finds Planet IP cams.
- `VMax Web Viewer` - VMax Web Viewer Login (http://publiclibrary.dwcc.tv/DVR/VMAX/01Manual_VMAX.pdf). Default User/Pass -> admin/.
- `IQeye Cameras` - Default login: root / system.
- `IP cam 2` - Different IP cam search. Results in US, France, Brazil, Switzerland, etc.
- `Netwave IP Camera` - Finds over 100,000 Netwave IP cams.
- `IP Cam Hikvision` - Hikvision IP cameras.
- `IP Cams with Screenshots` - Finds IP cameras with screenshots.
- `Web Viewer for Samsung DVR` - Default password is: Username = admin / Password = 4321.
- `Vilar IPCamera` - You can control these cameras using their motorization system (Pan / Tilt / Zoom - PTZ). Warning! Your IP address may be memorized in the system log! It is recommended to use a proxy or VPN before you connect to these cameras. Default password is: Username: admin / Password: 123456.
- `Foscam (IP Cameras) - Spain/España` - IP cameras (Foscam devices) in Spain / España. -- Default Authentication -- User name: admin Password: nothing / blank.
- `Heden` - French IP cameras from the 'Heden' brand.
- `Chianet Nodinfo Cameras` - Chinese brand IP cameras.
- `Amcrest IP Camera` - Amcrest IP cameras with default authentication.
- `Logitec IP Cameras` - Logitec IP cameras.
- `Axis IP Camera` - Axis IP cameras in Malaysia. Default Password: admin / pass.
- `NETGEAR IP Camera` - NETGEAR IP cameras.
- `Panasonic IP Cameras` - Panasonic IP Cameras.

## Ethical Considerations
Using the information from this repository should be done ethically and responsibly. Always ensure that you have permission to access and view any webcam feeds you find. Unauthorized access to private webcams is illegal and unethical.

## Legal Implications
Accessing webcams without authorization is illegal in many jurisdictions. Ensure you understand and comply with all relevant laws and regulations. This repository is for educational purposes only, and the author does not condone any illegal activities.

## Contributing
We welcome contributions to enhance and expand this guide. If you have any improvements, feel free to submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, feel free to contact Tariqul Islam.
 
[X Profile](https://x.com/tariqul_404)


## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or suggestions, feel free to contact Tariqul Islam.[X Profile](https://x.com/tariqul_404)

