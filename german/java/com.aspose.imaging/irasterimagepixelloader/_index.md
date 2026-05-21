---
title: "IRasterImagePixelLoader"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Rasterbild‑Pixel‑Lader."
type: docs
weight: 147
url: /de/java/com.aspose.imaging/irasterimagepixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageRawDataLoader](../../com.aspose.imaging/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

Der Rasterbild‑Pixel‑Lader.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Lädt Pixel teilweise (nach Blöcken). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Lädt Pixel teilweise (nach Blöcken).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, aus dem Pixel geladen werden sollen. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Der partielle Loader. |

