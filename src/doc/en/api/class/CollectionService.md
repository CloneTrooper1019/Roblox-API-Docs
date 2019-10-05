# Summary
A service which provides collections of instances based on tags assigned to them.

# Members

## AddTag
Adds a tag to an instance.

## GetCollection
Deprecated. Use GetTagged instead.

## GetInstanceAddedSignal
Returns a signal that fires when the given tag either has a new instance with that tag added to the data model or that tag is assigned to an instance within the data model.

## GetInstanceRemovedSignal
Returns a signal that fires when the given tag either has an instance with that tag removed from the data model or that tag is removed from an instance within the data model.

## GetTagged
Returns an array of all of the instances in the data model which have the given tag.

## GetTags
Returns a list of all the collections that an instance belongs to.

## HasTag
Returns whether the given instance has the given tag.

## ItemAdded
Deprecated. Use GetInstanceAddedSignal instead.

## ItemRemoved
Deprecated. Use GetInstancedRemovedSignal instead.

## RemoveTag
Removes a tag to an instance.