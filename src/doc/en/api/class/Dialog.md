# Summary
An object used to make dialog trees to converse with players

# Members

## BehaviorType
Indicates how the dialog may be used by players. Use Enum.DialogBehaviorType.SinglePlayer if only one player should interact with the dialog at a time, otherwise use Enum.DialogBehaviorType.MultiplePlayers.

## ConversationDistance
The maximum distance that the player's character can be from the dialog's parent in order to use the dialog.

## GetCurrentPlayers
Returns an array of the players currently conversing with this dialog.

## GoodbyeChoiceActive
Indicates whether or not an extra choice is available for the player to exit the dialog tree at this node.

## GoodbyeDialog
The prompt text for an extra choice that allows the player to exit the dialog tree at this node.

## InitialPrompt
The chat message that is displayed to the player when they first activate the dialog.

## InUse
Indicates whether or not the dialog is currently being used by one or more players.

## Purpose
Describes the purpose of the dialog, which is used to display a relevant icon on the dialog's activation button.

## Tone
Describes the tone of the dialog, which is used to display a relevant color in the dialog interface.