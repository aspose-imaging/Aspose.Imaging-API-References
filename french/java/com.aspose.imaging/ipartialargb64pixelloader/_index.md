---
title: "IPartialArgb64PixelLoader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le chargeur de pixels ARGB 64 bits."
type: docs
weight: 142
url: /fr/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Le chargeur de pixels ARGB 64 bits.
## Méthodes

| Méthode | Description |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Traite les pixels chargés. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Traite les pixels chargés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle des pixels. |
| pixels | long[] | Les pixels ARGB 64 bits. |
| start | [Point](../../com.aspose.imaging/point) | Le point de départ des pixels. S'il n'est pas égal à (gauche,haut), cela signifie que nous n'avons pas un rectangle complet. |
| end | [Point](../../com.aspose.imaging/point) | Le point de fin des pixels. S'il n'est pas égal à (droite,bas), cela signifie que nous n'avons pas un rectangle complet. |

