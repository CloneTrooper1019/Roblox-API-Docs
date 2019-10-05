# Summary
Ensures a GuiObject will always have a particular aspect ratio. If an element with a constraint is under the control of a layout, the constraint takes precedence in determining the element’s size, but not position. You can use a Constraint by parenting it to the element you wish to constrain.

# Members

## AspectRatio
The aspect ratio to maintain. This is the width/height. Only positive numbers allowed.

## AspectType
Describes how the aspect ratio will determine its size. Options are FitWithinMaxSize, ScaleWithParentSize. FitWithinMaxSize will make the element the maximum size it can be within the current possible AbsoluteSize of the element while maintaining the AspectRatio. ScaleWithParentSize will make the element the closest to the parent element’s maximum size while maintaining aspect ratio.

## DominantAxis
Describes which axis to use when determining the new size of the element, while keeping respect to the aspect ratio.