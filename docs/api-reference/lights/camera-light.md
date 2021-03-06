# CameraLight (Experimental)

CameraLight is a special [point light](/docs/api-reference/lights/point-light.md) source which always emits from the camera position.

## Usage 

Create an camera light source.

```js
import {_CameraLight as CameraLight} from '@deck.gl/core';

new CameraLight({
  color: [255, 255, 255],
  intensity: 1
});
```

## constructor

The constructor for the `CameraLight` class. Use this to create a new `CameraLight`.

```js
const cameraLight = new CameraLight({color, intensity});
```

* `color` - (*array*)  RGB color of camera light source, default value is `[255, 255, 255]`.
* `intensity` - (*number*) Strength of camera light source, default value is `1.0`.

## Source

[/modules/core/src/effects/lighting/camera-light.js](https://github.com/uber/deck.gl/tree/master/modules/core/src/effects/lighting/camera-light.js)
