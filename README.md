# LEGO Mindstorms EV3 ScratchX Extension (Italian translation)
*Some fixes, updates and ITA translation*

We added some extra features:
- added velocity to the **Steering Control block**;
- restored **Gyro sensor read value block** (angle, angular velocity options) - it was commented;
- created **Gyro sensor reset angle block**;
- fixed **Touch sensor Boolean synchronous block** (it returns if the button is pressed: true/false) - we created a new ext function that calls the usual whenButtonPressed function to avoid visualisation problems of the blocks after saving and loading the .sbx file. We commented the **deprecated** readTouchSensorPort function;
- created **command Block for changing the volume** of the played note (only changes the global value of the volume variable)

In progress:
- put the translation inside a unique .js file (like in the [Arduino Extension](https://github.com/khanning/scratch-arduino-extension/blob/gh-pages/arduino_extension.js))

Furthermore we translated in it **Italian**. You can find it in this [file](http://scollovati.github.io/ev3_scratch/ev3_scratch_ita.js): this is the URL that you need to load on ScratchX. This file has some blocks (readRemoteButtonPort, playFreq) commented because we found them unuseful: however the english file (ev3_scratch.js) is aligned with the original one.

We tested these fixes and upgrades during a weeklong camp with 5 EV3 kits working simultaneously.

We work on the **master branch**.
We use the gyro-reset branch only for making pull requests to the original repo.
