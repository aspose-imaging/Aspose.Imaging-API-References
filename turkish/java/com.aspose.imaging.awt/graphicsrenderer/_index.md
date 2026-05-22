---
title: "GraphicsRenderer"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Sınıf, com.aspose.imaging.Image'ı doğrudan java.awt.Graphic2D üzerine çizmeyi yönetir."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

Sınıf, com.aspose.imaging.Image'i doğrudan java.awt.Graphic2D üzerine çizmeyi yönetir. Bu sınıfı kullanarak VectorImage durumunda com.aspose.Imaging tamponları ile java.awt.BufferImage arasında birden fazla tahsis ve piksel kopyalamayı önlemek mümkündür.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | Yeni bir render oluşturur. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | Yeni bir render oluşturur. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | Yeni bir render oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | Verilen `graphics` üzerinde ölçek faktörü 1.0 ile renderleme gerçekleştirir. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | Verilen `graphics` üzerinde renderleme gerçekleştirir. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


Yeni bir render oluşturur. Varsayılan olarak, render [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\\#HighQuality), [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\\#ClearTypeGridFit) kullanılarak ve beyaz bir arka plan rengiyle işlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | java.awt.Graphics2D üzerinde renderlenecek görüntü |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


Yeni bir render oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | java.awt.Graphics2D üzerinde renderlenecek görüntü |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | İhracat görüntüsünü ayarlamak için ihracat seçenekleri. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


Yeni bir render oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | java.awt.Graphics2D üzerinde renderlenecek görüntü |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka plan rengi. |
| smoothingMode | int | Yumuşatma modu. |
| textRendering | int | Metin işleme modu. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


Verilen `graphics` üzerinde ölçek faktörü 1.0 ile renderleme gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| grafikler | java.awt.Graphics2D | Çizim için grafikler. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


Verilen `graphics` üzerinde renderleme gerçekleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| grafikler | java.awt.Graphics2D | Çizim için grafikler. |
| scaleFactor | float | Ölçek faktörü. |

