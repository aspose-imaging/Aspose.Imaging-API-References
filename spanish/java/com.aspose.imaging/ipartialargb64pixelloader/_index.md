---
title: "IPartialArgb64PixelLoader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El cargador de píxeles ARGB de 64 bits."
type: docs
weight: 142
url: /es/java/com.aspose.imaging/ipartialargb64pixelloader/
---
**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

El cargador de píxeles ARGB de 64 bits.
## Métodos

| Método | Descripción |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Procesa los píxeles cargados. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.imaging.Rectangle-long---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Procesa los píxeles cargados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de píxeles. |
| píxeles | long[] | Los píxeles ARGB de 64 bits. |
| start | [Point](../../com.aspose.imaging/point) | El punto de inicio de los píxeles. Si no es igual a (izquierda,arriba) significa que no tenemos un rectángulo completo. |
| end | [Point](../../com.aspose.imaging/point) | El punto final de los píxeles. Si no es igual a (derecha,abajo) significa que no tenemos un rectángulo completo. |

