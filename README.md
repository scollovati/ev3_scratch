# ev3_scratch_ita
Italian Translation + Gyro & Boolean upgrades - EV3 Scratch Edit

We're working on the [ev3_scratch_ita.js](http://scollovati.github.io/ev3_scratch/ev3_scratch_ita.js) file: this is the URL that you need to load on ScratchX.

We translated in italian the famous ScratchX plugin for the LEGO Mindstorms EV3.

We added some extra features:
- added velocity to the Steering Control block;
- Gyro read value block (angle, angular velocity options) - it was commented;
- Gyro reset angle block;
- Boolean synchronous block for the touch sensor (pressed: true/false) - we created a new ext function that calls the usual whenButtonPressed function to avoid visualisation problems of the blocks after saving and loading the .sbx file;
- Block for changing the volume of the played note (only changes the global value of a variable).

In progress:
- [nothing]
