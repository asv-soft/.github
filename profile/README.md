<p align="center">
<img src="https://github.com/asv-soft/asv-drones-gui-afis/assets/151620493/932425b6-547e-4d35-bf90-6430265c8e97" width="300px" >  
</p>

## Hi there 👋

Our team create open source user-friendly software for drones:
 - [Asv.Drones.Gui](https://github.com/asv-soft/asv-drones) - Open-source cross-platform application for UAV management:
   - Can control multiple UAV
   - Support command mode: one operator control one\multiple drones
   - Work with other applications (Mission Planer, QGroundControl) on the same network
   - Extensible plugin interface ([weather example](https://github.com/asv-soft/asv-drones-gui-weather))
   - Multiple ports: TCP_CLIENT, TCP_SERVER, UDP, SERIAL
 - [Asv.Drones.Gbs](https://github.com/asv-soft/asv-drones-gbs) - Ground base station service with RTK supprot:
   - Mavlink router with multiple ports: TCP_CLIENT, TCP_SERVER, UDP, SERIAL
   - Supports various GNSS receiver manufacturers
   - Transmits differential corrections to UAV via standard Mavlink messages
 - [Asv.Drones.Sdr](https://github.com/asv-soft/asv-drones-sdr) - SDR payload to analyze radio signals in the surrounding environment
   
We also have [documentation](https://docs.asv.me) where you can familiarize yourself with the project in more detail.
If you want DIY, we have libraries for that: 
 - [Asv.Gnss](https://github.com/asv-soft/asv-gnss) - GNSS library
   - Open protocols RTCMv2, RTCMv3, NMEA, raw GPS\GLONASS frames
   - Control recievers througt SBF, ComNav, UBX protocols
 - [Asv.Mavlink](https://github.com/asv-soft/asv-mavlink) - Mavlink library and code generator
   - Create your custom Mavlink messages and use them
   - You can choose simple using: send and receive Mavlink messages
   - Then connect a router and connect multiple devices
   - Or use out abstractions over devices: ArduPlane, ArduCopter, GroundBaseStation....
   - Or use out abstractions over microservices: Params, Missions...
   - There is a service to find devices in the network
   - And a lot more ...
 - [Asv.Avalonia.Toolkit](https://github.com/asv-soft/asv-avalonia-toolkit) - ASV Toolkit is a collection of various controls primarily developed for the ASV Drones project. These controls are designed to facilitate the management and control of UAVs and can be seamlessly integrated into other projects. Developers can leverage the implementation of these controls to enhance the functionality of their own applications.
   - Custom Controls: A variety of user-friendly controls tailored for UAV management tasks.
   - Integration Support: Seamlessly integrate controls into existing projects.
   - Extensibility: Easily extend functionality through a plugin interface.
   - Compatibility: Works across different platforms.
 - [Asv.Avalonia.Map](https://github.com/asv-soft/asv-avalonia-map) - ASV Map is a standalone application that provides a mapping interface with functionalities derived from the ASV Drones project. It offers:
   - Interactive Map: Includes features such as route planning, distance measurement, various map providers, and anchor sets used in the main application.
   - Integration Flexibility: Integrate map functionality into your own applications.
   - Compatibility: Compatible with various platforms and frameworks.
  In essence, ASV Map provides a comprehensive implementation of mapping functionality along with essential tools for enhancing user experience. Developers can seamlessly integrate these features into their projects.

Feel free to connect with us or join to the team

![image](https://github.com/asv-soft/.github/assets/1770739/d3a2d2a0-134d-486f-960d-f2759e52d70d)


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
