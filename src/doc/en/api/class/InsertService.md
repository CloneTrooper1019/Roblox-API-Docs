# Summary
A service used to insert objects stored on the website into the game.

# Members

## AllowClientInsertModels
Can be set in non-filtering-enabled places to allow LoadAsset to be used in LocalScripts.

## AllowInsertFreeModels
Allows free models to be inserted into place.

## ApproveAssetId
Deprecated

## ApproveAssetVersionId
Deprecated

## GetBaseCategories
Deprecated. Use GetBaseSets() instead.

## GetBaseSets
Returns a table containing a list of the various setIds that are ROBLOX approved. <a href='http://wiki.roblox.com/index.php/Sets' target='_blank'>More info on sets</a>

## GetCollection
Returns a table for the assets stored in the category.  A category is an setId from www.roblox.com that links to a set.  <a href='http://wiki.roblox.com/index.php?title=API:Class/InsertService/GetCollection' target='_blank'>More info on table format</a>. <a href='http://wiki.roblox.com/index.php/Sets' target='_blank'>More info on sets</a>

## GetUserCategories
Deprecated. Use GetUserSets() instead.

## GetUserSets
Returns a table containing a list of the various setIds that correspond to argument 'userId'. <a href='http://wiki.roblox.com/index.php/Sets' target='_blank'>More info on sets</a>

## Insert
Inserts the Instance into the workspace.  It is recommended to use Instance.Parent = game.Workspace instead, as this can cause issues currently.

## LoadAsset
Returns a Model containing the Instance that resides at AssetId on the web. This call will also yield the script until the model is returned. Script execution can still continue, however, if you use a <a href='http://wiki.roblox.com/index.php?title=Coroutine' target='_blank'>coroutine</a>.

## LoadAssetVersion
Similar to LoadAsset, but instead an AssetVersionId is passed in, which refers to a particular version of the asset which is not neccessarily the latest version.