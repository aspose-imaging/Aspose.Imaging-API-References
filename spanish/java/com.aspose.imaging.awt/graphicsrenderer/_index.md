---
title: "GraphicsRenderer"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase maneja el dibujo de com.aspose.imaging.Image directamente sobre java.awt.Graphic2D."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

La clase maneja el dibujo de com.aspose.imaging.Image directamente sobre java.awt.Graphic2D. Usando esta clase es posible evitar múltiples asignaciones y copiar los píxeles entre los buffers de com.aspose.Imaging a java.awt.BufferImage en caso de VectorImage.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Crea un nuevo render. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Crea un nuevo render. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Crea un nuevo render. |
## Métodos

| Método | Descripción |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Realiza el renderizado en el `graphics` proporcionado con un factor de escala de 1.0. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Realiza el renderizado en el `graphics` proporcionado. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Crea un nuevo render. Por defecto, el render se procesará usando [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality), [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit), y con un color de fondo blanco.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La imagen que se renderizará en java.awt.Graphics2D |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Crea un nuevo render.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La imagen que se renderizará en java.awt.Graphics2D |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Las opciones de exportación para ajustar la imagen exportada. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Crea un nuevo render.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La imagen que se renderizará en java.awt.Graphics2D |
| backgroundColor | [Color](../../com.aspose.imaging/color) | El color de fondo. |
| smoothingMode | int | El modo de suavizado. |
| textRendering | int | El modo de renderizado de texto. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Realiza el renderizado en el `graphics` proporcionado con un factor de escala de 1.0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Los gráficos para dibujar. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Realiza el renderizado en el `graphics` proporcionado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | Los gráficos para dibujar. |
| scaleFactor | float | El factor de escala. |

