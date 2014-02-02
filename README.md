# MMA8452Q accelerometer driver

Install:

```
npm install accel-mma84
```

Import:

```
var myHardware = tessel.port('A');
var accel = require('accel-mma84').connect(myHardware);
```

Functions:

*  **`accel`.on('connected', callback)**

*  **`accel`.getAcceleration(callback(err, xyz))**


## License

MIT
