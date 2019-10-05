# Summary
A type of DataStore where values must be positive integers. This makes OrderedDataStore suitable for leaderboard related scripting where you are required to order large amounts of data efficiently.

# Members

## GetSortedAsync
Returns a DataStorePages object. The length of each page is determined by pageSize, and the order is determined by isAscending. minValue and maxValue are optional parameters which will filter the result.