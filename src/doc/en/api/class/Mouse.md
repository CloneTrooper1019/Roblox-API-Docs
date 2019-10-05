# Summary
Used to receive input from the user. Actually tracks mouse events and keyboard events.

# Members

## Button1Down
Fired when the first button (usually the left, but could be another) on the mouse is depressed.

## Button1Up
Fired when the first button (usually the left, but could be another) on the mouse is release.

## Button2Down
This event is currently non-operational.

## Button2Up
This event is currently non-operational.

## Hit
The CoordinateFrame of where the Mouse ray is currently hitting a 3D object in the Workspace.  If the mouse is not over any 3D objects in the Workspace, this property is nil.

## Icon
The current Texture of the Mouse Icon. Stored as a string, for more information on how to format the string <a href='http://wiki.roblox.com/index.php/Content' target='_blank'>go here</a>

## Idle
Fired constantly when the mouse is not firing any other event (i.e. the mouse isn't moving, nor any buttons being pressed or depressed).

## KeyDown
Fired when a user presses a key on the keyboard. Argument is a string representation of the key.  If the key has no string representation (such as space), the string passed in is the keycode for that character. Keycodes are currently in ASCII.

## KeyUp
Fired when a user releases a key on the keyboard. Argument is a string representation of the key.  If the key has no string representation (such as space), the string passed in is the keycode for that character. Keycodes are currently in ASCII.

## Move
Fired when the mouse X or Y member changes.

## Origin
The CoordinateFrame of where the Mouse is when the mouse is not clicking.

## Origin
The CoordinateFrame of where the Mouse is when the mouse is not clicking.  This CoordinateFrame will be very close to the Camera.CoordinateFrame.

## Target
The Part the mouse is currently over. If the mouse is not currently over any object (on the skybox, for example) this property is nil.

## TargetFilter
A Part or Model that the Mouse will ignore when trying to find the Target, TargetSurface and Hit.

## TargetSurface
The NormalId (Top, Left, Down, etc.) of the face of the part the Mouse is currently over.

## UnitRay
The Unit Ray from where the mouse is (Origin) to the current Mouse.Target.

## ViewSizeX
The viewport's (game window) width in pixels.

## ViewSizeY
The viewport's (game window) height in pixels.

## WheelBackward
This event is currently non-operational.

## WheelForward
This event is currently non-operational.

## X
The absolute pixel position of the Mouse along the x-axis of the viewport (game window). Values start at 0 on the left hand side of the screen and increase to the right.

## Y
The absolute pixel position of the Mouse along the y-axis of the viewport (game window). Values start at 0 on the top of the screen and increase to the bottom.