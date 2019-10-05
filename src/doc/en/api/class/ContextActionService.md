# Summary
A service used to bind input to various lua functions.

# Members

## BindAction
Binds 'functionToBind' to fire when any 'inputTypes' happen. InputTypes can be variable in number and type. Types can be Enum.KeyCode, single character strings corresponding to keys, or Enum.UserInputType. 'actionName' is a key used by many other ContextActionService functions to query state. 'createTouchButton' if true will create a button on screen on touch devices.  This button will fire 'functionToBind' with three arguments: first argument is the actionName, second argument is the UserInputState of the input, and the third is the InputObject that fired this function. If 'functionToBind' yields or returns nil or Enum.ContextActionResult.Sink, the input will be sunk. If it returns Enum.ContextActionResult.Pass, the next bound action in the stack will be invoked.

## GetAllBoundActionInfo
Returns a table with all bound action info. Each entry is a key with 'actionName' and value being the same table you would get from ContextActionService:GetBoundActionInfo('actionName').

## GetBoundActionInfo
Returns a table with info regarding the function bound with 'actionName'. Table has the keys 'title' (current title that was set with SetTitle) 'image' (image set with SetImage) 'description' (description set with SetDescription) 'inputTypes' (tuple containing all input bound for this 'actionName') 'createTouchButton' (whether or not we created a touch button for this 'actionName'). 

## GetButton
If 'actionName' key contains a bound action, then this will return the touch button (if was created). Returns nil if a touch button was not created. No guarantees are made whether button will be retrievable when button is manipulated.

## SetDescription
If 'actionName' key contains a bound action, then 'description' is set as the description of the bound action. This description will appear for users in a listing of current actions availables.

## SetImage
If 'actionName' key contains a bound action, then 'image' is set as the image of the touch button. Does nothing if a touch button was not created. No guarantees are made whether image will be set when button is manipulated.

## SetPosition
If 'actionName' key contains a bound action, then 'position' is set as the position of the touch button. Does nothing if a touch button was not created. No guarantees are made whether position will be set when button is manipulated.

## SetTitle
If 'actionName' key contains a bound action, then 'title' is set as the title of the touch button. Does nothing if a touch button was not created. No guarantees are made whether title will be set when button is manipulated.

## UnbindAction
If 'actionName' key contains a bound action, removes function from being called by all input that it was bound by (if function was also bound by a different action name as well, those bound input are still active). Will also remove any touch button created (if button was manipulated manually there is no guarantee it will be cleaned up).

## UnbindAllActions
Removes all functions bound. No actionNames will remain. All touch buttons will be removed. If button was manipulated manually there is no guarantee it will be cleaned up.