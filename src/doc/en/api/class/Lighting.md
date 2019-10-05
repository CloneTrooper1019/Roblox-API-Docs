# Summary
Responsible for all lighting aspects of the world (affects how things are rendered).

# Members

## Ambient
The hue of the global lighting.  Changing this changes the color tint of all objects in the Workspace.

## Brightness
How much global light each Part in the Workspace receives. Standard range is 0 to 2 (0 being little light), but can be increased all the way to 10 (colors start to be appear very different at this value).

## ColorShift_Bottom
The hue of global lighting on the bottom surfaces of an object.

## ColorShift_Top
The hue of global lighting on the top surfaces of an object.

## ExposureCompensation
Exposure compensation amount. Applies a bias to the exposure level prior to the tonemap step. +1 indicates twice as much exposure and -1 means half as much exposure.

## FogColor
A Color3 value that changes the hue of distance fog.

## FogEnd
The distance at which fog completely blocks your vision. This distance is relative to the camera position. Units are in studs

## FogStart
The distance at which the fog gradient begins. This distance is relative to the camera position. Units are in studs.

## GeographicLatitude
The latitude position the level is placed at.  This affects sun position. <a href='http://wiki.roblox.com/index.php/GeographicLatitude' target='_blank'>More info</a>

## GetMinutesAfterMidnight
The number of minutes that the current time is past midnight.  If currently at midnight, returns 0.  Will return decimal values if not at an exact minute.

## GetMoonDirection
Returns the lookVector (Vector3) of the moon. If this lookVector was used in a CFrame, the Part would face the moon.

## GetMoonPhase
Currently always returns 0.75. MoonPhase cannot be edited.

## GetSunDirection
Returns the lookVector (Vector3) of the sun. If this lookVector was used in a CFrame, the Part would face the sun.

## GlobalShadows
Flag enabling shadows from sun and moon in the place

## LightingChanged
Fired whenever a property of Lighting is changed, or a skybox is added or removed. Skyboxes are of type 'Sky' and should be parented directly to lighting.

## OutdoorAmbient
Effective ambient value for outdoors, effectively shadow color outdoors (requires GlobalShadows enabled)

## Outlines
Flag enabling or disabling outlines on parts and terrain

## SetMinutesAfterMidnight
Sets the time to be a certain number of minutes after midnight.  This works with integer and decimal values.

## ShadowColor
Color the shadows appear as. Shadows are drawn mostly for characters, but depending on the lighting will also show for Parts in the Workspace.  Rendering settings can also affect if shadows are drawn.

## ShadowSoftness
This property controls how blurry the shadows are.

## TimeOfDay
A string that represent the current time of day. Time is in 24-hour clock format "XX::YY:ZZ", where X is hour, Y is minute, and Z is seconds.