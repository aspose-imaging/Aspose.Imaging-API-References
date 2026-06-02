---
title: "RectangleExtensions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Enthält Erweiterungsmethoden für Rectangle."
type: docs
weight: 21
url: /de/java/com.aspose.imaging.extensions/rectangleextensions/
---
**Inheritance:**
java.lang.Object
```
public final class RectangleExtensions
```

Enthält Erweiterungsmethoden für `Rectangle`.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [toGdiRectangle(Rectangle rectangle)](#toGdiRectangle-com.aspose.imaging.Rectangle-) | Konvertiert das `Rectangle` zu `System.Drawing.Rectangle`. |
| [toGdiRectangle(RectangleF rectangle)](#toGdiRectangle-com.aspose.imaging.RectangleF-) | Konvertiert das `RectangleF` zu `System.Drawing.Rectangle`. |
| [unionWith(RectangleF rectangle, RectangleF otherRectangle)](#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Vereint zwei Rechtecke. |
### toGdiRectangle(Rectangle rectangle) {#toGdiRectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle toGdiRectangle(Rectangle rectangle)
```


Konvertiert das `Rectangle` zu `System.Drawing.Rectangle`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck zum Konvertieren. |

**Returns:**
[Rectangle](../../java.awt/rectangle) - The converted `System.Drawing.Rectangle`.
### toGdiRectangle(RectangleF rectangle) {#toGdiRectangle-com.aspose.imaging.RectangleF-}
```
public static Rectangle2D.Float toGdiRectangle(RectangleF rectangle)
```


Konvertiert das `RectangleF` zu `System.Drawing.Rectangle`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck zum Konvertieren. |

**Returns:**
java.awt.geom.Rectangle2D.Float - Das konvertierte `System.Drawing.RectangleF`.
### unionWith(RectangleF rectangle, RectangleF otherRectangle) {#unionWith-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF unionWith(RectangleF rectangle, RectangleF otherRectangle)
```


Vereint zwei Rechtecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das erste Rechteck. |
| otherRectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das zweite Rechteck. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - New rectangle as union operation result
