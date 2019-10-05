# Summary
Studio.App.RobloxRibbonMainWindow.ScrollingFrameTooltip

# Members

## AbsoluteWindowSize
The size in pixels of the frame, without the scrollbars.

## BottomImage
The "Down" image on the vertical scrollbar. Size of this is always ScrollBarThickness by ScrollBarThickness. This is also used as the "right" image on the horizontal scroll bar.

## CanvasPosition
The absolute position the scroll frame is in respect to the canvas size. The minimum this can be set to is (0,0), while the max is the absolute canvas size - AbsoluteWindowSize.

## CanvasSize
Determines the size of the area that is scrollable. The UDim2 is calculated using the parent gui's size, similar to the regular Size property on gui objects.

## MidImage
The "Middle" image on the vertical scrollbar. Size of this can vary in the y direction, but is always set at ScrollBarThickness in x direction. This is also used as the "mid" image on the horizontal scroll bar.

## ScrollBarThickness
How thick the scroll bar appears. This applies to both the horizontal and vertical scroll bars. Can be set to 0 for no bars render.

## ScrollingEnabled
Determines whether or not scrolling is allowed on this frame. If turned off, no scroll bars will be rendered.

## TopImage
The "Up" image on the vertical scrollbar. Size of this is always ScrollBarThickness by ScrollBarThickness. This is also used as the "left" image on the horizontal scroll bar.