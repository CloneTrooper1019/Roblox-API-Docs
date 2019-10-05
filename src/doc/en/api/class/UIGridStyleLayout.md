# Members

## ApplyLayout
Forces a relayout of all elements. Useful when sort is set to Custom.

## FillDirection
Determines which direction to fill the grid. Can be Horizontal or Vertical.

## HorizontalAlignment
Determines how grid is placed within it's parent's container in the x direction. Can be Left, Center, or Right.

## SetCustomSortFunction
When SortOrder is set to Custom, this lua function is used to determine the ordering of elements. Function should take two arguments (each will be an Instance child to compare), and return true if a comes before b, otherwise return false. In other words, use this function the same way you would use a table.sort function. The sorting should be deterministic, otherwise sort will fail and fall back to name order.

## SortOrder
Determines how we decide which element to place next. Can be Name or Custom. If using Custom, make sure SetCustomSortFunction was called with an appropriate sort function.

## VerticalAlignment
Determines how grid is placed within it's parent's container in the y direction. Can be Top, Center, or Bottom.