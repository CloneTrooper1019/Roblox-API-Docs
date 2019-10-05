# Summary
A structural class, not creatable

# Members

## Anchored
Determines whether or not physics acts upon the Part.  If true, part stays 'Anchored' in space, not moving regardless of any collision/forces acting upon it.  If false, physics works normally on the part.

## BreakJoints
Destroys SurfaceJoints with all parts that are touching this Instance (including internal joints in the Instance, as in a Model).

## CanCollide
Determines whether physical interactions with other Parts are respected.  If true, will collide and react with physics to other Parts.  If false, other parts will pass thru instead of colliding

## CastShadow
Determines whether this Part casts a shadow.

## CFrame
Contains information regarding the Part's position and a matrix that defines the Part's rotation.  Can read/write. <a href='http://wiki.roblox.com/index.php/Cframe' target='_blank'>More info</a>

## Color
Color3 of the part.

## Elasticity
A float value ranging from 0.0f to 1.0f. Sets how much the Part will rebound against another. a value of 1 is like a superball, and 0 is like a lead block.

## Friction
A float value ranging from 0.0f to 1.0f. Sets how much the Part will be able to slide. a value of 1 is no sliding, and 0 is no friction, so infinite sliding.

## getMass
Use GetMass() instead

## GetMass
Returns a number that is the mass of this Instance.  Mass of a Part is immutable, and is changed only by the size of the Part.

## LocalSimulationTouched
Deprecated. Use Touched instead

## Locked
Determines whether building tools (in-game and studio) can manipulate this Part.  If true, no editing allowed.  If false, editing is allowed.

## makeJoints
Use MakeJoints() instead

## MakeJoints
Creates the appropriate SurfaceJoints with all parts that are touching this Instance (including internal joints in the Instance, as in a Model).  This uses the SurfaceTypes defined on the surfaces of parts to create the appropriate welds. <a href='http://wiki.roblox.com/index.php/MakeJoints' target='_blank'>More info</a>

## Massless
If true the part will be massless when welded to another part that is not massless. The part will still have mass like a normal part if it is an assembly root part according to GetRootPart().

## Material
Specifies the look and feel the Part should have.  Note: this does not define the color the Part is, see BrickColor for that. <a href='http://wiki.roblox.com/index.php/Material' target='_blank'>More info</a>

## Orientation
Rotation around X, Y, and Z axis.  Rotations applied in YXZ order.

## OrientationLocal
Orientation relative to parent part, or global space if there is no parent.

## PositionLocal
Position relative to parent part, or global space if there is no parent.

## Reflectance
Specifies how shiny the Part is. A value of 1 is completely reflective (chrome), while a value of 0 is no reflectance (concrete wall)

## Resize
Resizes a Part in the direction of the face defined by 'NormalId', by the amount specified by 'deltaAmount'. If the operation will expand the part to intersect another Instance, the part will not resize at all.  Return true if the call is successful, false otherwise.

## ResizeableFaces
Sets the value for the faces allowed to be resized by the Resize(NormalId, int) function.

## ResizeIncrement
Sets the value for the smallest change in size allowable by the Resize(NormalId, int) function.

## RootPriority
An integer from -127 to 127. Compares before other all other part properties besides massless for deciding which part is the assembly root part according to GetRootPart().

## StoppedTouching
Deprecated. Use TouchEnded instead

## TouchEnded
Fired when the part stops touching another part

## Transparency
Sets how visible an object is. A value of 1 makes the object invisible, while a value of 0 makes the object opaque.

## Velocity
How fast the Part is traveling in studs/second. This property is NOT recommended to be modified directly, unless there is good reason.  Otherwise, try using a BodyForce to move a Part.