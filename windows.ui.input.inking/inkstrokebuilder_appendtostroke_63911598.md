---
-api-id: M:Windows.UI.Input.Inking.InkStrokeBuilder.AppendToStroke(Windows.UI.Input.PointerPoint)
-api-type: winrt method
---

<!-- Method syntax
public Windows.UI.Input.PointerPoint AppendToStroke(Windows.UI.Input.PointerPoint pointerPoint)
-->

# Windows.UI.Input.Inking.InkStrokeBuilder.AppendToStroke

## -description
Adds a new segment to the ink stroke.

[AppendToStroke](inkstrokebuilder_appendtostroke.md) is called after [BeginStroke](inkstrokebuilder_beginstroke.md) and before [EndStroke](inkstrokebuilder_endstroke.md) during the [InkStroke](inkstroke.md) building process.

> [!NOTE]
> [AppendToStroke](inkstrokebuilder_appendtostroke.md) is not supported by [InkPresenter](inkpresenter.md). Use [CreateStrokeFromInkPoints](inkstrokebuilder_createstrokefrominkpoints.md) and [SetDefaultDrawingAttributes](inkstrokebuilder_setdefaultdrawingattributes.md) to programmatically build strokes for an [InkPresenter](inkpresenter.md).

## -parameters
### -param pointerPoint
The end point of the new segment.

## -returns
The previous end point. This end point can be used when rendering the stroke.

## -remarks

## -examples

## -see-also
[Pen and stylus interactions](http://msdn.microsoft.com/library/3da4f2d2-5405-42a1-9ed9-3a87bcd84c43), [Ink sample](http://go.microsoft.com/fwlink/p/?LinkID=620308), [Simple ink sample](http://go.microsoft.com/fwlink/p/?LinkID=620312), [Complex ink sample](http://go.microsoft.com/fwlink/p/?LinkID=620314)