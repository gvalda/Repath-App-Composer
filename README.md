# Repath application

The application in brief will provide users to set location of the potholes and obstacles by specifying their type(selectable) and risk status(selectable) /or custom type and risk and/or description. The set locations will be visible on map and open for rating/voting by the other application users (attesters/witnessers). Road fixing priority will be defined by these 3 parameters: type, risk status and total rate (maybe additional or lesser parameters).Priority results will be available to be monetarized for each city.

## Technologies

- **Programming languages**: Dart, Python, JS
- **Containerization**: Docker
- **Version control**: Github
- **Text editor**: VSC
  - *Plugins*: Docker, Remote Development
- **Other dependencies**: SDK Platform Tools

## Installation

```bash
git clone https://github.com/yogoh31/Repath-App-Composer

```

## [Usage](https://blog.codemagic.io/how-to-dockerize-flutter-apps/#:~:text=is%20available%20here.-,Build%20and%20run%20Docker%20container,-As%20we%20have)

### To connect the mobile device

```adb
adb devices
```
> To see the list of connected devices

```adb
adb tcpip 5555 
adb connect 192.168.0.5:5555
```
> To connect to the device wirelessly. *(Replace the IP address with that of the WiFi the mobile device is connected to. You can get it by going to **WiFi Settings -> Advanced** on your mobile device)*


```adb
flutter doctor
```
> To verify that the device is recognized by Flutter

### To run

```bash
cd mobile/workspace/app
flutter run
```
> This will run the demo counter Flutter app directly on the connected device from the Docker container.\
> P.S. *Build might take a couple of minutes*\
> P.S.S. *You may use additional run parameter **-v** to see more detailed output*

## License
[MIT](https://choosealicense.com/licenses/mit/)
