## Introduction ##

Zonewalk is a very basic 3D viewing tool for zone files. It uses the original zone files as they are, no prior conversion is required.

Currently (as of v.0.0.5) it only supports the older s3d based zones (I think they switched to egg with OOW?). And even within that group theres differences in support levels: anything up to POP works quite well, fromm there on some functionality is not yet in place. These zones load but some look awkward at best.

## First time use and configuration ##

The first time you run zonewalk after a fresh install it creates a default configuration for itself (resolution 1024,768; default zone blackburrow ) but in order to complete this step you need to provide the program with a valid path to a directory with s3d zone files.

The configuration is stored in a file named zonewalk.cfg. Under Windows 7 the Panda3D runtime stores this under C:\Users\your\_user\_name\AppData\Local\Panda3d\start\zonewalk.cfg. (todo: add other OS info). You can edit all entries in this file using a simple text editor, if you want to change the default display size for example

## User Interface ##

This is currently very basic: just a few hot keys.

  * The K Key brings up this listing in  zonewalk itself
  * WSAD Keys provide standard fwd/bck movement and camera roatation
  * Number keys 1 - 5 select camera movement speed
  * F Key toggles flymode on/off
  * ALT-F toggles FOG and FAR plane on/off. Switching this off can be usefull if you've lost your bearings but also has a very noticeable performance impact especially in larger zones
  * L Key opens the zone selection dialog
  * Z Key saves the current zone as the new default startup zone
  * ESC Key exits

Additionally you can control your view using mouselook (hold right mouse button depressed and move the mouse)