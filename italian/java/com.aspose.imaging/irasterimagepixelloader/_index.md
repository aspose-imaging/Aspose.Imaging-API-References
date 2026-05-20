---
title: "IRasterImagePixelLoader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il caricatore di pixel per immagini raster."
type: docs
weight: 147
url: /it/java/com.aspose.imaging/irasterimagepixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageRawDataLoader](../../com.aspose.imaging/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

Il caricatore di pixel per immagini raster.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Carica i pixel parzialmente (a blocchi). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Carica i pixel parzialmente (a blocchi).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui caricare i pixel. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Il caricatore parziale. |

