# io.repro.cordova

This plugin provides the ability to use [Repro](https://repro.io/)

## Installation

cordova plugin add https://github.com/iflagri/bun2card-cordova-plugin-repro.git

cordova-plugin-repro 2.0.1
```
@see cordova plugin add cordova-plugin-repro
```

### Supported Platforms

- iOS
- Android

### Quick Example

```
onDeviceReady: function() {
    app.receivedEvent('deviceready');
    Repro.setup("YOUR_APP_TOKEN");
    Repro.startRecording();
},
```

For more detail, see http://docs.repro.io/
