# Summary
Renders its contained GuiObjects flat against the face of a part.

# Members

## Active
If true, this GuiObject can fire mouse events and will pass them to any GuiObjects layered underneath, while false will do neither.

## Adornee
The Object the surface gui uses as its base to render from.  Currently, the only way to set this property is thru a script, and must exist in the workspace.  This will only render if the object assigned derives from BasePart.

## Enabled
If true, surface gui will render, otherwise rendering will be skipped.

## LightInfluence
Specifies the amount of influence lighting has on the surface gui. A value of 0 is unlit, 1 is fully lit. Fractional values blend from unlit to lit.