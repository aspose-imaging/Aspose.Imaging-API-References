---
title: "IPartialArgb64PixelLoader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il caricatore di pixel ARGB a 64 bit."
type: docs
weight: 142
url: /it/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Il caricatore di pixel ARGB a 64 bit.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Elabora i pixel caricati. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Elabora i pixel caricati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo dei pixel. |
| pixel | long[] | I pixel ARGB a 64 bit. |
| start | [Point](../../com.aspose.imaging/point) | Il punto di partenza dei pixel. Se non è uguale a (left,top) significa che non è un rettangolo completo. |
| end | [Point](../../com.aspose.imaging/point) | Il punto finale dei pixel. Se non è uguale a (right,bottom) significa che non è un rettangolo completo. |

