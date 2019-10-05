# Members

## Cancel
Stops the tween animation. Animation can be restarted by calling Play(). Animation will start from the beginning values.

## Completed
Fires when the tween either reaches PlaybackState Completed or Cancelled. PlaybackState of one of these types is passed as the first arg to the function listening to this event.

## Pause
Temporarily stops the tween animation. Animation can be resumed by calling Play().

## Play
Starts or resumes (if Tween.PlaybackState is Paused) the tween animation. If current PlaybackState is Cancelled, this property will reset the tween to the beginning properties and play the animations from the beginning.

## PlaybackState
The current state of how the tween is animating. Possible values are Begin, Playing, Paused, Completed and Cancelled. This property is modified by using functions such as Tween:Play(), Tween:Pause(), and Tween:Cancel(). Read-only.