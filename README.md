The SN-1 is a lighting installation for the ceiling. The prototype was custom designed and built for a space in Bushwick.

You can see a short video demo here:
http://www.youtube.com/watch?v=Dl0pmE9US4w

## Project Goals

The problem with most lighting controlers is they don't provide UI feedback of what the lights are actually doing. The only display mechanism is the lights themselves. The problem with most homebrew kits created using Arduino or Phidges is they have no GUI at all.

Our goal was to borrow best practices from the world of user interface design to create an interface for controlling the lighting installation in real time. We wanted to allow the user to "play" the lights in the same way a DJ plays music.

### Technical challenges
We chose to use the Phidgets controller board because it supports a wide range of languages. Building on the Adobe Flex platform allows us to create a rich and flexible GUI.

The project features an event driven architecture. We also followed modern OOP principles like single-concerns, DRY and loose coupling.


## Requirements
The Adobe Flex compiler v3.5+
http://www.adobe.com/cfusion/entitlement/index.cfm?e=flex3sdk

The Phidgets webservice framework:
http://www.phidgets.com/docs/OS_-_OS_X#Quick_Downloads

The Phidgets actionscript framework for the LED64 board (also included in this project):
http://www.phidgets.com/docs/Language_-_Flash_AS3#Quick_Downloads