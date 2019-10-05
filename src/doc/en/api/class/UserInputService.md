# Members

## AccelerometerEnabled
Returns true if the local device has an accelerometer, false otherwise.

## DeviceAccelerationChanged
Fired when a user moves a device that has an accelerometer. This is fired with an InputObject, which has type Enum.InputType.Accelerometer, and position that shows the g force in each local device axis. This event only fires locally.

## DeviceGravityChanged
Fired when the force of gravity changes on a device that has an accelerometer. This is fired with an InputObject, which has type Enum.InputType.Accelerometer, and position that shows the g force in each local device axis. This event only fires locally.

## DeviceRotationChanged
Fired when a user rotates a device that has an gyroscope. This is fired with an InputObject, which has type Enum.InputType.Gyroscope, and position that shows total rotation in each local device axis.  The delta property describes the amount of rotation that last happened. A second argument of Vector4 is the device's current quaternion rotation in reference to it's default reference frame. This event only fires locally.

## GetDeviceAcceleration
Returns an InputObject that describes the device's current acceleration. This is fired with an InputObject, which has type Enum.InputType.Accelerometer, and position that shows the g force in each local device axis.  The delta property describes the amount of rotation that last happened. This event only fires locally.

## GetDeviceGravity
Returns an InputObject that describes the device's current gravity vector. This is fired with an InputObject, which has type Enum.InputType.Accelerometer, and position that shows the g force in each local device axis. The delta property describes the amount of rotation that last happened. This event only fires locally.

## GetDeviceRotation
Returns an InputObject and a Vector4 that describes the device's current rotation vector. This is fired with an InputObject, which has type Enum.InputType.Gyroscope, and position that shows total rotation in each local device axis. The delta property describes the amount of rotation that last happened. The Vector4 is the device's current quaternion rotation in reference to it's default reference frame. This event only fires locally.

## GyroscopeEnabled
Returns true if the local device has an gyroscope, false otherwise.

## InputBegan
Fired when a user begins interacting via a Human-Computer Interface device (Mouse button down, touch begin, keyboard button down, etc.). 'inputObject' is an InputObject, which contains useful data for querying user input.  This event only fires locally.  This event will always fire regardless of game state.

## InputChanged
Fired when a user changes interacting via a Human-Computer Interface device (Mouse move, touch move, mouse wheel, etc.). 'inputObject' is an InputObject, which contains useful data for querying user input.  This event only fires locally.  This event will always fire regardless of game state.

## InputEnded
Fired when a user stops interacting via a Human-Computer Interface device (Mouse button up, touch end, keyboard button up, etc.). 'inputObject' is an InputObject, which contains useful data for querying user input.  This event only fires locally.  This event will always fire regardless of game state.

## KeyboardEnabled
Returns true if the local device accepts keyboard input, false otherwise.

## MouseEnabled
Returns true if the local device accepts mouse input, false otherwise.

## TextBoxFocused
Fired when a user clicks/taps on a textbox to begin text entry. Argument is the textbox that was put in focus. This also fires if a textbox forces focus on the user. This event only fires locally.

## TextBoxFocusReleased
Fired when a user stops text entry into a textbox (usually by pressing return or clicking/tapping somewhere else on the screen). Argument is the textbox that was taken out of focus. This event only fires locally.

## TouchEnabled
Returns true if the local device accepts touch input, false otherwise.

## TouchEnded
Fired when a user moves their finger on a TouchEnabled device. 'touch' is an InputObject, which contains useful data for querying user input.  This event only fires locally.  This event will always fire regardless of game state.

## TouchLongPress
Fired when a user holds at least one finger for a short amount of time on the same screen position on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the gesture. 'state' indicates the Enum.UserInputState of the gesture.  This event only fires locally.  This event will always fire regardless of game state.

## TouchMoved
Fired when a user moves their finger on a TouchEnabled device. 'touch' is an InputObject, which contains useful data for querying user input.  This event only fires locally.  This event will always fire regardless of game state.

## TouchPan
Fired when a user drags at least one finger on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the gesture. 'totalTranslation' is a Vector2, indicating how far the pan gesture has gone from its starting point. 'velocity' is a Vector2 that indicates how quickly the gesture is being performed in each dimension. 'state' indicates the Enum.UserInputState of the gesture.  This event only fires locally.  This event will always fire regardless of game state.

## TouchPinch
Fired when a user pinches their fingers on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the pinch gesture. 'scale' is a float that indicates the difference from the beginning of the pinch gesture. 'velocity' is a float indicating how quickly the pinch gesture is happening. 'state' indicates the Enum.UserInputState of the gesture.  This event only fires locally.  This event will always fire regardless of game state.

## TouchRotate
Fired when a user rotates two fingers on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the gesture. 'rotation' is a float indicating how much the rotation has gone from the start of the gesture. 'velocity' is a float that indicates how quickly the gesture is being performed. 'state' indicates the Enum.UserInputState of the gesture.  This event only fires locally.  This event will always fire regardless of game state.

## TouchStarted
Fired when a user places their finger on a TouchEnabled device. 'touch' is an InputObject, which contains useful data for querying user input.  This event only fires locally.  This event will always fire regardless of game state.

## TouchSwipe
Fired when a user swipes their fingers on a TouchEnabled device. 'swipeDirection' is an Enum.SwipeDirection, indicating the direction the user swiped. 'numberOfTouches' is an int that indicates how many touches were involved with the gesture.  This event only fires locally.  This event will always fire regardless of game state.

## TouchTap
Fired when a user taps their finger on a TouchEnabled device. 'touchPositions' is a Lua array of Vector2, each indicating the position of all the fingers involved in the tap gesture. This event only fires locally.  This event will always fire regardless of game state.