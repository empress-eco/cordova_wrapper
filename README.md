<p align="center">
Cordova Wrapper is a versatile Cordova-based container for mobile app development, offering functionalities such as local server selection, login, and desk pages.
<br />
<a href="https://empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/cordova_wrapper/issues">Report Bug</a>
·
<a href="https://github.com/empress-eco/cordova_wrapper/issues">Request Feature</a>
</p>

## About The Project

Cordova Wrapper is an adaptable mobile app container designed for developers seeking a simplified way to load application files (HTML/JS/CSS) from the server. It's compatible with version 6/7+ of the framework it interfaces with, providing a flexible and straightforward approach to mobile app development.

### Key Features
- Local server selection for increased flexibility
- Built-in login and desk pages
- Easy loading of application files from the server

This project is built using Cordova, a renowned mobile application development framework, providing a solid foundation for your app development needs.

## Technical Stack and Setup Instructions

### Prerequisites
Ensure that Cordova is installed on your system.

### Installation
To start, clone the repository using this [link](https://github.com/empress-eco/cordova_wrapper.git). Then, install the required platforms and plugins using the following commands:

```sh
$ cordova platform add ios
$ cordova platform add android
$ cordova plugin add cordova-plugin-statusbar
$ cordova plugin add cordova-plugin-inappbrowser
$ cordova plugin add cordova-plugin-file
```

## Usage
For iOS, install and update the latest XCode. Run the following commands:

```sh
$ cordova build ios && cordova emulate ios && open -a "ios simulator"
```

For Android, install Android SDK (Android Studio is recommended). Run the following commands:

```sh
$ cordova build android
$ cordova build android --release
```

## Contribution Guidelines
We welcome your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements 

### License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are also profoundly grateful to the Cordova community for maintaining the framework that this project is built upon.