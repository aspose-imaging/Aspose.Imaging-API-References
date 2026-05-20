---
title: "GraphicsRenderer"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La classe gère le dessin de com.aspose.imaging.Image directement sur le java.awt.Graphic2D."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

La classe gère le dessin de com.aspose.imaging.Image directement sur le java.awt.Graphic2D. En utilisant cette classe, il est possible d'éviter de multiples allocations et la copie des pixels entre les tampons com.aspose.Imaging et java.awt.BufferImage dans le cas d'un VectorImage.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Crée un nouveau rendu. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Crée un nouveau rendu. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Crée un nouveau rendu. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Effectue le rendu sur le `graphics` fourni avec un facteur d'échelle de 1,0. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Effectue le rendu sur le `graphics` fourni. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Crée un nouveau rendu. Par défaut, le rendu sera effectué en utilisant le [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality), le [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit), et avec une couleur de fond blanche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'image qui sera rendue sur le java.awt.Graphics2D |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Crée un nouveau rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'image qui sera rendue sur le java.awt.Graphics2D |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options d'exportation pour ajuster l'image exportée. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Crée un nouveau rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | L'image qui sera rendue sur le java.awt.Graphics2D |
| backgroundColor | [Color](../../com.aspose.imaging/color) | La couleur d'arrière-plan. |
| smoothingMode | int | Le mode de lissage. |
| textRendering | int | Le mode de rendu du texte. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Effectue le rendu sur le `graphics` fourni avec un facteur d'échelle de 1,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| graphismes | java.awt.Graphics2D | Les graphismes pour le dessin. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Effectue le rendu sur le `graphics` fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| graphismes | java.awt.Graphics2D | Les graphismes pour le dessin. |
| scaleFactor | float | Le facteur d'échelle. |

