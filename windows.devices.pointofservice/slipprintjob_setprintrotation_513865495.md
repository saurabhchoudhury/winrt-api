---
-api-id: M:Windows.Devices.PointOfService.SlipPrintJob.SetPrintRotation(Windows.Devices.PointOfService.PosPrinterRotation,System.Boolean)
-api-type: winrt method
---

<!-- Method syntax
public void SetPrintRotation(Windows.Devices.PointOfService.PosPrinterRotation value, System.Boolean includeBitmaps)
-->

# Windows.Devices.PointOfService.SlipPrintJob.SetPrintRotation

## -description
Sets the rotation of the text or image on the page on the slip printer station.

## -parameters
### -param value
The rotation of the text or image on the page.

### -param includeBitmaps
Whether bitmaps should also be rotated. This setting takes effect only for subsequent calls to [PrintBitmap](slipprintjob_printbitmap.md), and may not apply to saved bitmaps that you print using [PrintSavedBitmap](slipprintjob_printsavedbitmap.md).

## -remarks
This rotation setting persists beyond the current print job.

## -examples

## -see-also
