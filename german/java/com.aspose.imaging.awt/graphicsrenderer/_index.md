---
title: "GraphicsRenderer"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Klasse verarbeitet das Zeichnen von com.aspose.imaging.Image direkt auf java.awt.Graphic2D."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

Die Klasse verarbeitet das Zeichnen von com.aspose.imaging.Image direkt auf dem java.awt.Graphic2D. Mit dieser Klasse ist es möglich, mehrere Allokationen zu vermeiden und die Pixel zwischen com.aspose.Imaging-Puffern in java.awt.BufferImage zu kopieren, im Fall von VectorImage.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Erstellt ein neues Render. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Erstellt ein neues Render. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Erstellt ein neues Render. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Führt das Rendering auf dem angegebenen `graphics` mit dem Skalierungsfaktor 1,0 aus. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Führt das Rendering auf dem angegebenen `graphics` aus. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Erstellt ein neues Render. Standardmäßig wird das Render mit [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality), [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit) und einer weißen Hintergrundfarbe durchgeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das Bild, das auf dem java.awt.Graphics2D gerendert wird. |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Erstellt ein neues Render.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das Bild, das auf dem java.awt.Graphics2D gerendert wird. |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Die Exportoptionen zum Anpassen des exportierten Bildes. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Erstellt ein neues Render.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | Das Bild, das auf dem java.awt.Graphics2D gerendert wird. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Die Hintergrundfarbe. |
| smoothingMode | int | Der Glättungsmodus. |
| textRendering | int | Der Textdarstellungsmodus. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Führt das Rendering auf dem angegebenen `graphics` mit dem Skalierungsfaktor 1,0 aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Die Grafik zum Zeichnen. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Führt das Rendering auf dem angegebenen `graphics` aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Die Grafik zum Zeichnen. |
| scaleFactor | float | Der Skalierungsfaktor. |

