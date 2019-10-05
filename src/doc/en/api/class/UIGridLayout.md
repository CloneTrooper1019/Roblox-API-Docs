# Summary
Sets the position of UI elements in a 2D grid (this can be modified to 1D grid for list layout). This will also set the elements to a particular size, although this can be overridden with particular constraints on elements. You can use a UIGridLayout by parenting it to a GuiObject. The UIGridLayout will then apply itself to all of its GuiObject siblings.

# Members

## AbsoluteSize
Returns the current size of the grid. If more elements are added, this can increase. If elements are removed this can decrease.

## CellPadding
How much space between elements there should be.

## CellSize
Denotes what size each element should be. Can be overridden by elements using constraints on individual elements.

## FillDirectionMaxCells
Determines how many cells over in the FillDirection we go before starting a new row or column. Set to 0 for max cell count.  Will be clamped if this is set higher than the parent container allows room for.

## StartCorner
Which corner we start laying the elements out from. Can be TopLeft, TopRight, BottomLeft, BottomRight.