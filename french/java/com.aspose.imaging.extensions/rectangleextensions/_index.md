---
title: "RectangleExtensions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Contient des méthodes d'extension pour Rectangle."
type: docs
weight: 21
url: /fr/java/com.aspose.imaging.extensions/rectangleextensions/
---
**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Contient des méthodes d'extension pour `Rectangle`.
## Méthodes

| Méthode | Description |
| --- | --- |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.imaging.Rectangle-) | Convertit le `Rectangle` en `System.Drawing.Rectangle`. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.imaging.RectangleF-) | Convertit le `RectangleF` en `System.Drawing.Rectangle`. |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Fusionne deux rectangles. |
### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


Convertit le `Rectangle` en `System.Drawing.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle à convertir. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted `System.Drawing.Rectangle`.
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.imaging.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Convertit le `RectangleF` en `System.Drawing.Rectangle`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Le rectangle à convertir. |

**Returns:**
java.awt.geom.Rectangle2D.Float - Le `System.Drawing.RectangleF` converti.
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


Fusionne deux rectangles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Le premier rectangle. |
| otherRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Le deuxième rectangle. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - New rectangle as union operation result
