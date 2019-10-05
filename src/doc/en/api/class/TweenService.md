# Summary
Service responsible for creating tweens on instances.

# Members

## Create
Creates a Tween object bound to a particular Instance. The first arg is the Instance to tween. The second arg is a TweenInfo struct, which specifies how a tween should behave. The third arg is a table, which should specify the properties to tween as keys, with the end value specified as values to the keys.

## GetValue
Transforms a linear alpha to a given EasingStyle and EasingDirection.