---
title: "GraphicsRenderer"
second_title: "Aspose.Imaging för Java API-referens"
description: "Klassen hanterar ritning av com.aspose.imaging.Image direkt på java.awt.Graphic2D."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

Klassen hanterar ritning av com.aspose.imaging.Image direkt på java.awt.Graphic2D. Med denna klass är det möjligt att undvika flera allokeringar och kopiering av pixlar mellan com.aspose.Imaging-buffertar till java.awt.BufferImage i fallet med VectorImage.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Skapar en ny rendering. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Skapar en ny rendering. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Skapar en ny rendering. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Utför rendering på den givna `graphics` med skalningsfaktor 1.0. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Utför rendering på den givna `graphics`. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Skapar en ny rendering. Som standard kommer rendering att utföras med [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality), [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit), och med en vit bakgrundsfärg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Bilden som kommer att renderas på java.awt.Graphics2D |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Skapar en ny rendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Bilden som kommer att renderas på java.awt.Graphics2D |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Exportalternativen för att justera den exporterade bilden. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Skapar en ny rendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Bilden som kommer att renderas på java.awt.Graphics2D |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Bakgrundsfärgen. |
| smoothingMode | int | Jämningsläget. |
| textRendering | int | Textrenderingsläget. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Utför rendering på den givna `graphics` med skalningsfaktor 1.0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Grafiken för ritning. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Utför rendering på den givna `graphics`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Grafiken för ritning. |
| scaleFactor | float | Skalfaktorn. |

