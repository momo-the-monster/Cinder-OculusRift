Cinder-OculusRift
=================

Fork of [simongeilfus' block](https://github.com/simongeilfus/Cinder-OculusRift/tree) for easy installation on OSX.

1. Download the [OculusRift SDK](https://developer.oculusvr.com) and recompile the lib with support for c++ exceptions and RTTI (run time type information). This can be set in the SDK's xcode project settings.
2. Then copy the LibOVR folder to the root of this block folder. 
3. You should then be able to use Tinderbox to create projects with the block included. This is how the included xcode sample was set up.
