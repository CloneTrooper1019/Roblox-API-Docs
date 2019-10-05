# Summary
The root of ROBLOX's parent-child hierarchy (commonly known as game after the global variable used to access it)

# Members

## IsLoaded
Returns true if the game has finished loading, false otherwise.  Check this before listening to the Loaded signal to ensure a script knows when a game finishes loading.

## Loaded
Fires when the game finishes loading.  Use this to know when to remove your custom loading gui.  It is best to check IsLoaded() before connecting to this event, as the game may load before the event is connected to.

## OnClose
Deprecated. Use DataModel.BindToClose

## SetCreatorID
Use SetCreatorId() instead

## SetPlaceID
Use SetPlaceId() instead

## ShowMouse
Deprecated. Use Workspace.IsMouseCursorVisible

## workspace
Deprecated. Use Workspace