# Summary
An object that describes a particular user input, such as mouse movement, touches, keyboard, and more.

# Members

## KeyCode
An enum that describes what kind of input is being pressed. For types of input like Keyboard, this describes what key was pressed. For input like mousebutton, this provides no additional information.

## Position
A Vector3 value that describes a positional value of this input. For mouse and touch input, this is the screen position of the mouse/touch, described in the x and y components. For mouse wheel input, the z component describes whether the wheel was moved forward or backward.

## UserInputState
An enum that describes what state of a particular input (touch began, touch moved, touch ended, etc.). See Enum.UserInputState for more info.

## UserInputType
An enum that describes what kind of input this object is describing (mousebutton, touch, etc.).  See Enum.UserInputType for more info.