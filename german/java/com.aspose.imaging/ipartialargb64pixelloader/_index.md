---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der 64‑Bit‑ARGB‑Pixel‑Lader."
type: docs
weight: 142
url: /de/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Der 64‑Bit‑ARGB‑Pixel‑Lader.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Verarbeitet die geladenen Pixel. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Verarbeitet die geladenen Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Pixelrechteck. |
| Pixel | long[] | Die 64-Bit ARGB-Pixel. |
| start | [Point](../../com.aspose.imaging/point) | Der Startpixelpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](../../com.aspose.imaging/point) | Der Endpixelpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

