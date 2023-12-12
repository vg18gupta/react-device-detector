[![npm version](https://badge.fury.io/js/react-device-detector-hook.svg)](https://badge.fury.io/js/react-device-detector-hook)


# react-device-detector-hook



React hook to detect the device type. This hook is able to detect mobile, desktop, android or iOS device.

# Installing

```bash
npm install react-device-detector-hook


```

```bash
yarn add react-device-detector-hook


```

# Usage

```javascript
import useDeviceDetector from 'react-device-detector-hook';




function MyComponent  = (props) => {
const detectMobile = useDeviceDetector();


  return (
      <div>
        is Mobile: { detectMobile.isMobile() } <br/>
        is Desktop: { detectMobile.isDesktop() } <br/>
        is Android: { detectMobile.isAndroid() } <br/>
        is iOS: { detectMobile.isIos() }
      </div>
  );
};
```

# Contributing

If you have any new suggestions, new features, bug fixes, etc. please contribute by raising pull request on the [repository](https://github.com/vg18gupta/react-device-detector).


If you have any issue with the `react-device-detector-hook`, open an issue on [Github](https://github.com/vg18gupta/react-device-detector).


