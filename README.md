# React Native Log iOS

[![npm](https://img.shields.io/npm/v/react-native-log-ios.svg)](https://www.npmjs.com/package/react-native-log-ios)
[![license](https://img.shields.io/github/license/annihil/react-native-log-ios.svg)]()

This standalone script replace the broken `react-native log-ios`.  
It will watch the Mac OS X system log file and filter only the lines concerning your XCode project.  
You will be able to see the `console.log`, `console.warn` and `console.error` outputs.  


## Installation

```
npm i -g react-native-log-ios
```

## Usage

```
react-native-log-ios <XCode Project Name>
```

## Result

Line format is the following: `HH:mm:ss, <eventMessage>`

```
12:02:33, Initializing <RCTCxxBridge: 0x6000037340f0> (parent: <RCTBridge: 0x600002335f80>, executor: (null))
12:02:33, Running application Foobar ({
    initialProps =     {
    };
    rootTag = 1;
})
12:02:33, Running application "Foobar" with appParams: {"rootTag":1,"initialProps":{}}. __DEV__ === true, development-level warning are ON, performance optimizations are OFF
12:02:39, Hello world!
```

## Versioning

React Native Log iOS uses [SemVer](http://semver.org/) for versioning.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file
for details.
