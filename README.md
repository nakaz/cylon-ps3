# Cylon-PS3

Get working inputs from your Playstation 3 controller console logged on your terminal!

This may or may not work with Playstation 4's DualShock 4 controller. According to the [docs](http://cylonjs.com/documentation/platforms/joystick/) and their [blog](http://cylonjs.com/blog/), it works! Just change the devices' controller.drive value to `dualshock-4`.

Cylon-Joystick currently only works on Node -v `0.12.7`. Node 4 and 5 do not seem to work. However if it works for you, awesome!

### Installation

If on OSX you may need to install some libraries to compile  `cylon-joystick`:

``` bash
brew install sdl2 sdl2_image sdl2_ttf
```

Then simply `npm install`. For a quick test: hook up your PS3 Controller via USB and start up `node index.js` and watch the console logs!