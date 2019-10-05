# Members

## CameraSubject
Where the Camera's focus is.  Any rotation of the camera will be about this subject.

## CameraType
Defines how the camera will behave. <a href='http://wiki.roblox.com/index.php/CameraType' target='_blank'>More info</a>

## CFrame
The current position and rotation of the Camera.  For most CameraTypes, the rotation is set such that the CoordinateFrame lookVector is pointing at the Focus.

## CoordinateFrame
The current position and rotation of the Camera.  For most CameraTypes, the rotation is set such that the CoordinateFrame lookVector is pointing at the Focus.

## FieldOfView
The current angle, or width, of what the camera can see.  Current acceptable values are from 20 degrees to 80.

## Focus
The current CoordinateFrame that the camera is looking at.  Note: it is not always guaranteed that the camera is always looking here.

## GetRoll
Returns the camera's current roll. Roll is defined in radians, and is stored as the delta from the camera's y axis default normal vector.

## NearPlaneZ
The negative z-offset of the view frustum's near clipping plane.

## ScreenPointToRay
Takes a 2D screen position and produces a Ray object to be used for 3D raycasting. Input is x,y screen coordinates, and a (optional, defaults to 0) z position which sets how far in the camera look vector to start the ray origin.

## SetRoll
Sets the camera's current roll. Roll is defined in radians, and is stored as the delta from the camera's y axis default normal vector.

## ViewportPointToRay
Same as ScreenPointToRay, except no GUI offsets are taken into account. Useful for things like casting a ray from the middle of the Camera.ViewportSize

## ViewportSize
Holds the x,y screen resolution of the viewport the camera is presenting (note: this can differ from the AbsoluteSize property of a full screen gui).

## WorldToScreenPoint
Takes a 3D position in the world and projects it onto x,y coordinates of screen space. Returns two values, first is a Vector3 that has x,y position and z position which is distance from camera (negative if behind camera, positive if in front). Second return value is a boolean indicating if the first argument is an on-screen coordinate.

## WorldToViewportPoint
Same as WorldToScreenPoint, except no GUI offsets are taken into account.