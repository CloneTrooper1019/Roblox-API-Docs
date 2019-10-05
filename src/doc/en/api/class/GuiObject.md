# Members

## Active
If true, this GuiObject can fire mouse events and will pass them to any GuiObjects layered underneath, while false will do neither.

## BackgroundColor
Deprecated. Use BackgroundColor3 instead

## BackgroundColor3
A Color3 value that specifies the background color for the GuiObject. This value is ignored if the Style property (not found on all GuiObjects) is set to something besides custom.

## BackgroundTransparency
A number value that specifies how transparent the background of the GuiObject is. This value is ignored if the Style property (not found on all GuiObjects) is set to something besides custom.

## BorderColor
Deprecated. Use BorderColor3 instead

## BorderColor3
A Color3 value that specifies the color of the outline of the GuiObject. This value is ignored if the Style property (not found on all GuiObjects) is set to something besides custom.

## BorderSizePixel
A number value that specifies the thickness (in pixels) of the outline of the GuiObject. Currently this value can only be set to either 0 or 1, any other number has no effect. This value is ignored if the Style property (not found on all GuiObjects) is set to something besides custom.

## ClipsDescendants
If set to true, any descendants of this GuiObject will only render if contained within it's borders. If set to false, all descendants will render regardless of position.

## DragBegin
Fired when a GuiObject with Draggable set to true starts to be dragged. 'InitialPosition' is a UDim2 value of the position of the GuiObject before any drag operation began.

## Draggable
If true, allows a GuiObject to be dragged by the user's mouse. The events 'DragBegin' and 'DragStopped' are fired when the appropriate action happens, and only will fire on Draggable=true GuiObjects.

## DragStopped
Always fired after a DragBegin event, DragStopped is fired when the user releases the mouse button causing a drag operation on the GuiObject. Arguments 'x', and 'y' specify the top-left absolute position of the GuiObject when the event is fired.

## InputBegan
Fired when a user begins interacting via a Human-Computer Interface device (Mouse button down, touch begin, keyboard button down, etc.). 'inputObject' is an InputObject, which contains useful data for querying user input.  This event only fires locally.

## InputChanged
Fired when a user changes interacting via a Human-Computer Interface device (Mouse move, touch move, mouse wheel, etc.). 'inputObject' is an InputObject, which contains useful data for querying user input.  This event only fires locally.

## InputEnded
Fired when a user stops interacting via a Human-Computer Interface device (Mouse button up, touch end, keyboard button up, etc.). 'inputObject' is an InputObject, which contains useful data for querying user input.  This event only fires locally.

## MouseEnter
Fired when the mouse enters a GuiObject, as long as the GuiObject is active (see active property for more detail). Arguments 'x', and 'y' specify the absolute pixel position of the mouse.

## MouseLeave
Fired when the mouse leaves a GuiObject, as long as the GuiObject is active (see active property for more detail). Arguments 'x', and 'y' specify the absolute pixel position of the mouse.

## MouseMoved
Fired when the mouse is inside a GuiObject and moves, as long as the GuiObject is active (see active property for more detail). Arguments 'x', and 'y' specify the absolute pixel position of the mouse.

## Position
A UDim2 value describing the position of the top-left corner of the GuiObject on screen. More information on UDim2 is available <a href='http://wiki.roblox.com/index.php/UDim2' target='_blank'>here</a>.

## SelectionImageObject
Overrides the default selection adornment (used for gamepads). For best results, this should point to a GuiObject.

## Size
A UDim2 value describing the size of the GuiObject on screen in both absolute and relative coordinates. More information on UDim2 is available <a href='http://wiki.roblox.com/index.php/UDim2' target='_blank'>here</a>.

## SizeConstraint
The direction(s) that an object can be resized in. <a href='http://wiki.roblox.com/index.php/SizeConstraint' target='_blank'>More info</a>.

## TouchLongPress
Fired when a user holds at least one finger for a short amount of time on the same screen position on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the gesture. 'state' indicates the Enum.UserInputState of the gesture.  This event only fires locally.

## TouchPan
Fired when a user drags at least one finger on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the gesture. 'totalTranslation' is a Vector2, indicating how far the pan gesture has gone from its starting point. 'velocity' is a Vector2 that indicates how quickly the gesture is being performed in each dimension. 'state' indicates the Enum.UserInputState of the gesture.

## TouchPinch
Fired when a user pinches their fingers on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the pinch gesture. 'scale' is a float that indicates the difference from the beginning of the pinch gesture. 'velocity' is a float indicating how quickly the pinch gesture is happening. 'state' indicates the Enum.UserInputState of the gesture.  This event only fires locally.

## TouchRotate
Fired when a user rotates two fingers on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the gesture. 'rotation' is a float indicating how much the rotation has gone from the start of the gesture. 'velocity' is a float that indicates how quickly the gesture is being performed. 'state' indicates the Enum.UserInputState of the gesture.  This event only fires locally.

## TouchSwipe
Fired when a user swipes their fingers on a TouchEnabled device. 'swipeDirection' is an Enum.SwipeDirection, indicating the direction the user swiped. 'numberOfTouches' is an int that indicates how many touches were involved with the gesture.  This event only fires locally.

## TouchTap
Fired when a user taps their finger on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the tap gesture. This event only fires locally.  This event will always fire regardless of game state.

## TweenPosition
Smoothly moves a GuiObject from its current position to 'endPosition'. The only required argument is 'endPosition'. <a href='http://wiki.roblox.com/index.php/TweenPosition' target='_blank'>More info</a> 

## TweenSize
Smoothly translates a GuiObject's current size to 'endSize'. The only required argument is 'endSize'. <a href='http://wiki.roblox.com/index.php/TweenSize' target='_blank'>More info</a> 

## TweenSizeAndPosition
Smoothly translates a GuiObject's current size to 'endSize', and also smoothly translates the GuiObject's current position to 'endPosition'. The only required arguments are 'endSize' and 'endPosition'. <a href='http://wiki.roblox.com/index.php/TweenSizeAndPosition' target='_blank'>More info</a> 

## ZIndex
Describes the ordering in which overlapping GuiObjects will be drawn. A value of 1 is drawn first, while higher values are drawn in ascending order (each value draws over the last).