---
title: "GraphicsRenderer"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفئة تتعامل مع رسم com.aspose.imaging.Image مباشرةً على java.awt.Graphic2D."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.awt/graphicsrenderer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public class GraphicsRenderer extends DisposableObject
```

الفئة تتعامل مع رسم com.aspose.imaging.Image مباشرةً على java.awt.Graphic2D. باستخدام هذه الفئة يمكن تجنب تخصيصات متعددة ونسخ البكسلات بين مخازن com.aspose.Imaging إلى java.awt.BufferImage في حالة VectorImage.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GraphicsRenderer(Image image)](#GraphicsRenderer-com.aspose.imaging.Image-) | ينشئ عرضًا جديدًا. |
| [GraphicsRenderer(Image image, ImageOptionsBase exportOptions)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-) | ينشئ عرضًا جديدًا. |
| [GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)](#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-) | ينشئ عرضًا جديدًا. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [render(Graphics2D graphics)](#render-java.awt.Graphics2D-) | ينفذ عملية التصيير على `graphics` المعطى بمعامل مقياس 1.0. |
| [render(Graphics2D graphics, float scaleFactor)](#render-java.awt.Graphics2D-float-) | ينفذ عملية التصيير على `graphics` المعطى. |
### GraphicsRenderer(Image image) {#GraphicsRenderer-com.aspose.imaging.Image-}
```
public GraphicsRenderer(Image image)
```


ينشئ عرضًا جديدًا. بشكل افتراضي، سيتم متابعة العرض باستخدام [SmoothingMode.HighQuality](../../com.aspose.imaging/smoothingmode\#HighQuality)، [TextRenderingHint.ClearTypeGridFit](../../com.aspose.imaging/textrenderinghint\#ClearTypeGridFit)، ومع لون خلفية أبيض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الصورة التي سيتم تصييرها على java.awt.Graphics2D |

### GraphicsRenderer(Image image, ImageOptionsBase exportOptions) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.ImageOptionsBase-}
```
public GraphicsRenderer(Image image, ImageOptionsBase exportOptions)
```


ينشئ عرضًا جديدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الصورة التي سيتم تصييرها على java.awt.Graphics2D |
| exportOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات التصدير لضبط الصورة المصدرة. |

### GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering) {#GraphicsRenderer-com.aspose.imaging.Image-com.aspose.imaging.Color-int-int-}
```
public GraphicsRenderer(Image image, Color backgroundColor, int smoothingMode, int textRendering)
```


ينشئ عرضًا جديدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الصورة التي سيتم تصييرها على java.awt.Graphics2D |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |
| smoothingMode | int | وضع التنعيم. |
| textRendering | int | وضع تصيير النص. |

### render(Graphics2D graphics) {#render-java.awt.Graphics2D-}
```
public void render(Graphics2D graphics)
```


ينفذ عملية التصيير على `graphics` المعطى بمعامل مقياس 1.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | الرسومات المستخدمة للرسم. |

### render(Graphics2D graphics, float scaleFactor) {#render-java.awt.Graphics2D-float-}
```
public void render(Graphics2D graphics, float scaleFactor)
```


ينفذ عملية التصيير على `graphics` المعطى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| graphics | java.awt.Graphics2D | الرسومات المستخدمة للرسم. |
| scaleFactor | float | معامل المقياس. |

