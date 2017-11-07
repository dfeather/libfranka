# CHANGELOG

## 0.2.0 - unreleased

  * **BREAKING** change on the network protocol:
    - Added `tau_J_d` to the robot state.
  * Added logs to ControlException.
  * Added saturation to joint velocity, joint position, and joint impedance examples
  * Changed examples to read initial states inside control loops (after controller switching)
  * Always throw `ControlException`s for control-related command responses
  * Add support for commanding elbow positions for Cartesian motions
  * Removed unnecessary public dependencies for libfranka

## 0.1.0 - 2017-09-15

  * Initial release
