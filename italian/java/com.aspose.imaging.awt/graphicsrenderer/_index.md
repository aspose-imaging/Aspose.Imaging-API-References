---
title: "GraphicsRenderer"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe gestisce il disegno di com.aspose.imaging.Image direttamente su java.awt.Graphic2D."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

La classe gestisce il disegno di com.aspose.imaging.Image direttamente su java.awt.Graphic2D. Utilizzando questa classe è possibile evitare molteplici allocazioni e la copia dei pixel tra i buffer com.aspose.Imaging e java.awt.BufferImage nel caso di VectorImage.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Crea un nuovo render. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Crea un nuovo render. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Crea un nuovo render. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Esegue il rendering sul `graphics` fornito con fattore di scala 1.0. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Esegue il rendering sul `graphics` fornito. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Crea un nuovo render. Per impostazione predefinita, il render verrà eseguito utilizzando il [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality), il [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit) e con un colore di sfondo bianco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'immagine che sarà renderizzata su java.awt.Graphics2D |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Crea un nuovo render.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'immagine che sarà renderizzata su java.awt.Graphics2D |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Le opzioni di esportazione per regolare l'immagine esportata. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Crea un nuovo render.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'immagine che sarà renderizzata su java.awt.Graphics2D |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Il colore di sfondo. |
| smoothingMode | int | La modalità di smussatura. |
| textRendering | int | La modalità di rendering del testo. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Esegue il rendering sul `graphics` fornito con fattore di scala 1.0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | La grafica per il disegno. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Esegue il rendering sul `graphics` fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | La grafica per il disegno. |
| scaleFactor | float | Il fattore di scala. |

