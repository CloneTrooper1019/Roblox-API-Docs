# Summary
Creates a paged viewing window, like the home screen of a mobile device. You can use a UIPageLayout by parenting it to a GuiObject. The UIPageLayout will then apply itself to all of its GuiObject siblings.

# Members

## Animated
Whether or not to animate transitions between pages.

## Circular
Whether or not the page layout wraps around at the ends.

## CurrentPage
The page that is either currently being displayed or is the target of the current animation.

## EasingDirection
The easing direction to use when performing an animation.

## EasingStyle
The easing style to use when performing an animation.

## JumpTo
If the instance is in the layout, then it sets CurrentPage to it and animtes to it. If circular layout is set, it will take the shortest path.

## JumpToIndex
If the index is >= 0 and less than the size of the layout, acts like JumpTo. If it's out of bounds and circular is set, it will animate the full distance between the in-bounds index of CurrentPage and the new index.

## Next
Sets CurrentPage to the page after the current page and animates to it, or does nothing if there isn't a next page.

## Padding
Determines the amount that pages are separated from each other by. Can be set either using scale (Percentage of parent's size in the current direction) or offset (a static spacing value, similar to pixel size).

## PageEnter
Fires when a page comes into view, and is going to be rendered.

## PageLeave
Fires when a page leaves view, and will not be rendered.

## Previous
Sets CurrentPage to the page after the current page and animates to it, or does nothing if there isn't a next page.

## Stopped
Fires when an animation to CurrentPage is completed without being cancelled, and the view stops scrolling.

## TweenTime
The length of the animation.