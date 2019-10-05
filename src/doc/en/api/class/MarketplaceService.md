# Members

## GetProductInfo
Takes one argument "assetId" which should be a number of an asset on www.roblox.com.  Returns a table containing the product information (if this process fails, returns an empty table).

## PlayerOwnsAsset
Checks to see if 'Player' owns the product associated with 'assetId'. Returns true if the player owns it, false otherwise. This call will produce a warning if called on a guest player.

## ProcessReceipt
Callback that is executed for pending Developer Product receipts.
            <p>If this function does not return Enum.ProductPurchaseDecision.PurchaseGranted, then you will not be granted the money for the purchase!</p>
            <p>The callback will be invoked with a table, containing the following informational fields:</p>
            <ul>
            <li>PlayerId: int64 - the id of the player making the purchase.</li>
            <li>PlaceIdWherePurchased: int64:  - the specific place where the purchase was made.</li>
            <li>PurchaseId: string - a unique identifier for the purchase, should be used to prevent granting an item multiple times for one purchase.</li>
            <li>ProductId: int64 - the id of the purchased product.</li>
            <li>CurrencyType: CurrencyType - the type of currency used (Tix, Robux).</li>
            <li>CurrencySpent: int - the amount of currency spent on the product for this purchase.</li>
            </ul>
            

## PromptPurchase
Will prompt 'player' to purchase the item associated with 'assetId'.  'equipIfPurchased' is an optional argument that will give the item to the player immediately if they buy it (only applies to gear).  'currencyType' is also optional and will attempt to prompt the user with a specified currency if the product can be purchased with this currency, otherwise we use the default currency of the product.

## PromptPurchaseFinished
Fired when a 'player' dismisses a purchase dialog for 'assetId'.  If the player purchased the item 'isPurchased' will be true, otherwise it will be false. This call will produce a warning if called on a guest player.