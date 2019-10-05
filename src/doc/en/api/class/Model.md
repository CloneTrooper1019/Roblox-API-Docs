# Summary
A construct used to group Parts and other objects together, also allows manipulation of multiple objects.

# Members

## BreakJoints
Breaks all surface joints contained within

## GetModelCFrame
Returns a CFrame that has position of the centroid of all Parts in the Model.  The rotation matrix is either the rotation matrix of the user-defined PrimaryPart, or if not specified then  a part in the Model chosen by the engine.

## GetModelSize
Returns a Vector3 that is union of the extents of all Parts in the model.

## GetPrimaryPartCFrame
Returns the cframe of the Model.PrimaryPart. If PrimaryPart is nil, then this function will throw an error.

## makeJoints
Use MakeJoints() instead

## MakeJoints
Creates the appropriate SurfaceJoints between all touching Parts contrained within the model. Technically, this function calls MakeJoints() on all Parts inside the model.

## move
Use MoveTo() instead

## MoveTo
Moves the centroid of the Model to the specified location, respecting all relative distances between parts in the model.

## PrimaryPart
A Part that serves as a reference for the Model's CFrame. Used in conjunction with GetModelPrimaryPartCFrame and SetModelPrimaryPartCFrame. Use this to rotate/translate all Parts relative to the PrimaryPart.

## ResetOrientationToIdentity
Rotates all parts in the model to the orientation that was set using SetIdentityOrientation().  If this function has never been called, rotation is reset to GetModelCFrame()'s rotation.

## SetIdentityOrientation
Takes the current rotation matrix of the model and stores it as the model's identity matrix. The rotation is applied when ResetOrientationToIdentity() is called.

## SetPrimaryPartCFrame
Sets the cframe of the Model.PrimaryPart. If PrimaryPart is nil, then this function will throw an error. This also sets the cframe of all descendant Parts relative to the cframe change to PrimaryPart.

## TranslateBy
Similar to MoveTo(), except instead of moving to an explicit location, we use the model's current CFrame location and offset it.