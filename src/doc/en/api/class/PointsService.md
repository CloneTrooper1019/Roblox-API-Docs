# Summary
A service used to query and award points for Roblox users using the universal point system.

# Members

## AwardPoints
Will attempt to award the 'amount' points to 'userId', returns 'userId' awarded to, the number of points awarded, the new point total the user has in the game, and the total number of points the user now has. Will also fire PointsService.PointsAwarded. Works with server scripts ONLY.

## GetAwardablePoints
Returns the number of points the current universe can award to players. Works with server scripts ONLY.

## GetGamePointBalance
Returns the balance of points that player with userId has in the current game (all placeID points combined within the game). Works with server scripts ONLY.

## GetPointBalance
Returns the overall balance of points that player with userId has (the sum of all points across all games). Works with server scripts ONLY.

## PointsAwarded
Fired when points are successfully awarded 'userId'. Also returns the updated balance of points for usedId in universe via 'userBalanceInUniverse', total points via 'userTotalBalance', and the amount points that were awarded via 'pointsAwarded'. This event fires on the server and also all clients in the game that awarded the points.