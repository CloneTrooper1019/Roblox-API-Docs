# Members

## CollisionType
An emum that selects the collision type for R15 and Rthro characters. InnerBox is classic style collisions for all characters, OuterBox is dynamically sized collisions based on Mesh size.

## EquipTool
Takes a specified tool and equips it to the Humanoid's Character.  Tool argument should be of type 'Tool'.

## GetBodyPartR15
Returns a Enum.BodyPartR15 given a body part in the Humanoid's Character.

## MoveTo
Attempts to move the Humanoid and it's associated character to 'part'. 'location' is used as an offset from part's origin.

## ReplaceBodyPartR15
Replaces the desired bodypart on the Humanoid's Character using a specified Enum.BodyPartR15 and BasePart. Returns a success boolean.

## TakeDamage
Decreases health by the amount.  Use this instead of changing health directly to make sure weapons are filtered for things such as ForceField(s).

## UnequipTools
Takes any active gear/tools that the Humanoid is using and puts them into the backpack.  This function only works on Humanoids with a corresponding Player.