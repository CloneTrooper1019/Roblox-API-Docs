# Summary
The GuiService is a special service, which currently allows developers to control what GuiObject is currently being selected by the Gamepad Gui navigator, and allows clients to check if Roblox's main menu is currently open. This service has a lot of hidden members, which are mainly used internally by Roblox's CoreScripts.

# Members

## GetGuiInset
Returns a Tuple containing two Vector2 values representing the offset of user GUIs in pixels from the top right corner of the screen and the bottom right corner of the screen respectively.