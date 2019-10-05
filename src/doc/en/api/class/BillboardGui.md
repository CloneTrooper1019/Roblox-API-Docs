# Summary
A GUI that adorns an object in the 3D world.  Add Frames/Labels/Buttons to this object to have them rendered while attached to a 3D object

# Members

## AbsolutePosition
A read-only Vector2 value that is the GuiObject's current position (x,y) in pixel space, from the top left corner of the GuiObject.

## AbsoluteSize
A read-only Vector2 value that is the GuiObject's current size (width, height) in pixel space.

## Active
If true, this GuiObject can fire mouse events and will pass them to any GuiObjects layered underneath, while false will do neither.

## Adornee
The Object the billboard gui uses as its base to render from.  Currently, the only way to set this property is thru a script, and must exist in the workspace.  This will only render if the object assigned derives from BasePart.

## AlwaysOnTop
If true, billboard gui does not get occluded by 3D objects, but always renders on the screen.

## Enabled
If true, billboard gui will render, otherwise rendering will be skipped.

## ExtentsOffset
A Vector3 (x,y,z) defined in studs that will offset the gui from the extents of the 3d object it is rendering from.

## LightInfluence
Specifies the amount of influence lighting has on the billboard gui. A value of 0 is unlit, 1 is fully lit. Fractional values blend from unlit to lit.

## PlayerToHideFrom
Specifies a Player that the BillboardGui will not render to.

## Size
A UDim2 value describing the size of the BillboardGui. More information on UDim2 is available <a href='http://wiki.roblox.com/index.php/UDim2' target='_blank'>here</a>. Relative values are defined as one-to-one with studs.

## SizeOffset
A Vector2 (x,y) defined in studs that will offset the gui size from it's current size.

## StudsOffset
A Vector3 (x,y,z) defined in studs that will offset the gui from the centroid of the 3d object it is rendering from