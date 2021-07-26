# **Gitpod Flutter**


[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/krlaa/gitpod-flutter)

[![made-with-flutter](https://img.shields.io/badge/Made%20with-Gitpod-1f425f.svg)](https://www.python.org/)
# Preface
This is a gitpod solution to create and test apps with [Flutter](https://flutter.dev/) when you don't have access to necessary tools to do so.

Using the [device_preview](https://pub.dev/packages/device_preview) package will help with the feel and understanding when working in the vnc. Take a look at the master branches sample project for an example.



With the release of Flutter 2.0 the Flutter team has included support for Flutter desktop. Using [gitpod-vnc](https://www.gitpod.io/blog/native-ui-with-vnc/), this solution will allow teachers, tinkers, students and all to run Flutter.

**There will be 2 branches in this repo:**
- **[master](https://github.com/krlaa/gitpod-flutter)** branch will contain the pre-configuration for a sample flutter project.
- **[dev](https://github.com/krlaa/gitpod-flutter/tree/dev)** branch which will contain the pre-configuration with just the necessary Docker files the [README.md](https://github.com/krlaa/gitpod-flutter/blob/dev/README.md) in there will go in more depth on how to configure your own project

*I strongly recommend anyone using this repo's dev branch to install [device_preview](https://pub.dev/packages/device_preview) package into their for a better experience.*
# Setup 
### Once the gitpod container finishes loading up follow these steps:
1. Open up the folder called "flutter_project" then open up the folder called "lib" the select and open main.dart. cd flutter_project
2. Press F5 to activate debug mode (Alternatively you can run flutter run -d linux to manually control reloads) 
3. Once debug mode loads click on the ports button on the bottom of the code editor to open "Ports View":
![Access the port view](https://i.ibb.co/L9zKDRK/indication.png)
*This is to access the ports section in gitpod*
4. Hover over the port option 6080 and then you will be presented with three options. The option with the globe will open up a new tab with the vnc. Alternatively you can also click the open preview icon to use the simple browser extension to open up the vnc right in the code editor.
![Open port in simple browser](https://i.ibb.co/mqd68v9/indication2.png)

# Credit
### Credit to [vtorres/gitpod-flutter](https://github.com/vtorres/gitpod-flutter) for the idea. Their solution allows running flutter web in gitpod with the limitation of no hot-reload. They also detail a solution that allows to test the app on a physical device.
*Disclaimer: I have not tested the physical device feature but it seems like a viable solution*
