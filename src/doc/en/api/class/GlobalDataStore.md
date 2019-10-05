# Summary
Exposes functions for saving and loading data for the DataStoreService

# Members

## GetAsync
Returns the value of the entry in the DataStore with the given key

## IncrementAsync
Increments the value of a particular key amd returns the incremented value

## OnUpdate
Sets callback as a function to be executed any time the value associated with key is changed. It is important to disconnect the connection when the subscription to the key is no longer needed. 

## SetAsync
Sets the value of the key. This overwrites any existing data stored in the key

## UpdateAsync
Retrieves the value of the key from the website, and updates it with a new value. The callback until the value fetched matches the value on the web. Returning nil means it will not save.