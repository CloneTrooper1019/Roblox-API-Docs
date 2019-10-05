# Summary
A service used to set and get information about assets stored on the Roblox website.

# Members

## GetAssetVersions
Given a placeID, this function will return a table with the version info of the place. An optional arg of page number can be used to page through all revisions (a single page may hold about 50 revisions).

## GetCreatorAssetID
Given a creationID, this function will return the asset that created the creationID. If no other asset created the given creationID, 0 is returned.

## GetPlacePermissions
Given a placeID, this function will return a table with the permissions of the place. Useful for determining what kind of permissions a particular user may have for a place.

## RevertAsset
Reverts a given place id to the version number provided. Returns true if successful on reverting, false otherwise.

## SetPlacePermissions
Sets the permissions for a placeID to the place accessType. An optional table (inviteList) can be included that will set the accessType for only the player names provided. The table should be set up as an array of usernames (strings).