---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.Imaging för Java API-referens"
description: "64-bitars ARGB-pixel-laddare."
type: docs
weight: 142
url: /sv/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

64-bitars ARGB-pixel-laddare.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Bearbetar de inlästa pixlarna. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Bearbetar de inlästa pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Pixelrektangeln. |
| pixlar | long[] | De 64-bitars ARGB-pixlarna. |
| start | [Point](../../com.aspose.imaging/point) | Startpunkten för pixlarna. Om den inte är lika med (vänster,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](../../com.aspose.imaging/point) | Slutpunkten för pixlarna. Om den inte är lika med (höger,botten) betyder det att vi inte har en fullständig rektangel. |

