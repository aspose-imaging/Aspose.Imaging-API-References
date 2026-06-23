---
title: "Region"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يصف داخل شكل رسومي مكوّن من مستطيلات ومسارات."
type: docs
weight: 95
url: /ar/java/com.aspose.imaging/region/
---
**Inheritance:**
java.lang.Object
```
public final class Region
```

يصف داخل الشكل الرسومي المكوّن من مستطيلات ومسارات. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Region()](#Region--) | ينشئ Region جديدًا. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | ينشئ `T:Aspose.Imaging.Region` جديدًا من بنية `T:Aspose.Imaging.RectangleF` المحددة. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | ينشئ `T:Aspose.Imaging.Region` جديدًا من بنية `T:Aspose.Imaging.Rectangle` المحددة. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | ينشئ `T:Aspose.Imaging.Region` جديدًا باستخدام `T:Aspose.Imaging.GraphicsPath` المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة مطابقة تمامًا من هذا `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | يُهيئ كائن `com.aspose.imaging.Region` هذا إلى داخل لا نهائي. |
| [makeEmpty()](#makeEmpty--) | يُهيئ هذا `com.aspose.imaging.Region` إلى داخل فارغ. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع بنية `com.aspose.imaging.RectangleF` المحددة. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع `com.aspose.imaging.graphicsPath` المحدد. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع `com.aspose.imaging.region` المحدد. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | يُحدّث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع بنية `com.aspose.imaging.RectangleF` المحددة. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع `com.aspose.imaging.graphicsPath` المحدد. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع `com.aspose.imaging.region` المحدد. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية `com.aspose.imaging.RectangleF` المحددة. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع `com.aspose.imaging.graphicsPath` المحدد. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع `com.aspose.imaging.region` المحدد. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع بنية `com.aspose.imaging.RectangleF` المحددة. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع بنية `com.aspose.imaging.Rectangle` المحددة. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع `com.aspose.imaging.graphicsPath` المحدد. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع `com.aspose.imaging.region` المحدد. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.RectangleF` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.Rectangle` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.GraphicsPath` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.Region` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | يُزاح إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد. |
| [translate(int dx, int dy)](#translate-int-int-) | يُزاح إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | يحوّل هذا `com.aspose.imaging.Region` باستخدام `com.aspose.imaging.matrix` المحدد. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل فارغ على سطح الرسم المحدد. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل لا نهائي على سطح الرسم المحدد. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت `com.aspose.imaging.Region` المحددة مطابقة لهذا `com.aspose.imaging.Region` على سطح الرسم المحدد. |
| [isVisible(float x, float y)](#isVisible-float-float-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند رسمها باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند رسمها باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن `com.aspose.imaging.Region` هذا عند رسمه باستخدام كائن `com.aspose.imaging.Graphics` المحدد. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | يفحص ما إذا كانت بنية `com.aspose.imaging.Point` المحددة موجودة داخل هذا `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت بنية `com.aspose.imaging.Point` المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.Rectangle` المحددة موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.Rectangle` المحددة موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### Region() {#Region--}
```
public Region()
```


ينشئ Region جديدًا.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


ينشئ `T:Aspose.Imaging.Region` جديدًا من بنية `T:Aspose.Imaging.RectangleF` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | بنية `T:Aspose.Imaging.RectangleF` التي تحدد الجزء الداخلي للمنطقة الجديدة `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


ينشئ `T:Aspose.Imaging.Region` جديدًا من بنية `T:Aspose.Imaging.Rectangle` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | بنية `T:Aspose.Imaging.Rectangle` التي تحدد الجزء الداخلي للمنطقة الجديدة `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


ينشئ `T:Aspose.Imaging.Region` جديدًا باستخدام `T:Aspose.Imaging.GraphicsPath` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `T:Aspose.Imaging.GraphicsPath` الذي يحدد المنطقة الجديدة `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


ينشئ نسخة عميقة مطابقة تمامًا من هذا `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


يُهيئ كائن `com.aspose.imaging.Region` هذا إلى داخل لا نهائي.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


يُهيئ هذا `com.aspose.imaging.Region` إلى داخل فارغ.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع بنية `com.aspose.imaging.RectangleF` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | بنية `com.aspose.imaging.RectangleF` للتقاطع مع هذا `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | بنية `com.aspose.imaging.Rectangle` للتقاطع مع هذا `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع `com.aspose.imaging.graphicsPath` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` للتقاطع مع هذا `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


يُحدّث هذا `com.aspose.imaging.Region` إلى تقاطع نفسه مع `com.aspose.imaging.region` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` للتقاطع مع هذا `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


يُحدّث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع بنية `com.aspose.imaging.RectangleF` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | بنية `com.aspose.imaging.RectangleF` للاتحاد مع هذا `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | بنية `com.aspose.imaging.Rectangle` للاتحاد مع هذا `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع `com.aspose.imaging.graphicsPath` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` للاتحاد مع هذا `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى اتحاد نفسه مع `com.aspose.imaging.region` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` للاتحاد مع هذا `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية `com.aspose.imaging.RectangleF` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | بنية `com.aspose.imaging.RectangleF` لعملية XOR مع هذا `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | بنية `com.aspose.imaging.Rectangle` لعملية XOR مع هذا `com.aspose.imaging.region`. |

### xor(GraphicsPath path) {#xor-com.aspose.imaging.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع `com.aspose.imaging.graphicsPath` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` لعملية XOR مع هذا `com.aspose.imaging.region`. |

### xor(Region region) {#xor-com.aspose.imaging.Region-}
```
public void xor(Region region)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع `com.aspose.imaging.region` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` لعملية XOR مع هذا `com.aspose.imaging.region`. |

### exclude(RectangleF rect) {#exclude-com.aspose.imaging.RectangleF-}
```
public void exclude(RectangleF rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع بنية `com.aspose.imaging.RectangleF` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | بنية `com.aspose.imaging.RectangleF` لاستبعادها من هذا `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع بنية `com.aspose.imaging.Rectangle` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | بنية `com.aspose.imaging.Rectangle` لاستبعادها من هذا `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع `com.aspose.imaging.graphicsPath` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | الـ `com.aspose.imaging.GraphicsPath` لاستبعادها من هذا `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء الداخلي منه الذي لا يتقاطع مع `com.aspose.imaging.region` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | الـ `com.aspose.imaging.Region` لاستبعادها من هذا `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.RectangleF` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | الـ `com.aspose.imaging.RectangleF` بنية لتكمل هذا `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.Rectangle` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الـ `com.aspose.imaging.Rectangle` بنية لتكمل هذا `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.GraphicsPath` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | الـ `com.aspose.imaging.GraphicsPath` لتكمل هذا `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.Region` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | الـ `com.aspose.imaging.Region` كائن لتكمل هذا `com.aspose.imaging.Region` كائن. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


يُزاح إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | الكمية لإزاحة هذا `com.aspose.imaging.Region` أفقياً. |
| dy | float | الكمية لإزاحة هذا `com.aspose.imaging.Region` عمودياً. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


يُزاح إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | int | الكمية لإزاحة هذا `com.aspose.imaging.Region` أفقياً. |
| dy | int | الكمية لإزاحة هذا `com.aspose.imaging.Region` عمودياً. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


يحوّل هذا `com.aspose.imaging.Region` باستخدام `com.aspose.imaging.matrix` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | الـ `com.aspose.imaging.Matrix` التي يتم من خلالها تحويل هذا `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل فارغ على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سطح رسم. |

**Returns:**
منطقي - true إذا كان داخل هذا `com.aspose.imaging.Region` فارغاً عندما يتم تطبيق التحويل المرتبط بـ `g`؛ وإلا false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل لا نهائي على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سطح رسم. |

**Returns:**
منطقي - true إذا كان داخل هذا `com.aspose.imaging.Region` لا نهائيًا عندما يتم تطبيق التحويل المرتبط بـ `g`؛ وإلا false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


يفحص ما إذا كانت `com.aspose.imaging.Region` المحددة مطابقة لهذا `com.aspose.imaging.Region` على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | الـ `com.aspose.imaging.Region` للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سطح رسم. |

**Returns:**
منطقي - True إذا كان داخل المنطقة مطابقاً لداخل هذه المنطقة عندما يتم تطبيق التحويل المرتبط بالمعامل `g`؛ وإلا false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |

**Returns:**
منطقي - True عندما تكون النقطة المحددة داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` بنية للاختبار. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند رسمها باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للنقطة المراد اختبارها. |
| y | float | الإحداثي الصادي للنقطة المراد اختبارها. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - True عندما تكون النقطة المحددة داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند رسمها باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` بنية للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | float | الإحداثي Y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| width | float | العرض للمستطيل للاختبار. |
| height | float | الارتفاع للمستطيل للاختبار. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد داخل هذا `com.aspose.imaging.Region` كائن؛ وإلا false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | الـ `com.aspose.imaging.RectangleF` بنية للاختبار. |

**Returns:**
منطقي - true عندما يكون أي جزء من `rect` موجودًا داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | float | الإحداثي Y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| width | float | العرض للمستطيل للاختبار. |
| height | float | الارتفاع للمستطيل للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | الـ `com.aspose.imaging.RectangleF` بنية للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - true عندما يكون `rect` موجودًا داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن `com.aspose.imaging.Region` هذا عند رسمه باستخدام كائن `com.aspose.imaging.Graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للنقطة المراد اختبارها. |
| y | int | الإحداثي الصادي للنقطة المراد اختبارها. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - true عندما تكون النقطة المحددة موجودة داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


يفحص ما إذا كانت بنية `com.aspose.imaging.Point` المحددة موجودة داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `com.aspose.imaging.Point` بنية للاختبار. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


يفحص ما إذا كانت بنية `com.aspose.imaging.Point` المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الـ `com.aspose.imaging.Point` بنية للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي X للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| width | int | العرض للمستطيل للاختبار. |
| height | int | الارتفاع للمستطيل للاختبار. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.Rectangle` المحددة موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الـ `com.aspose.imaging.Rectangle` بنية للاختبار. |

**Returns:**
منطقي - تُرجع هذه الطريقة true عندما يكون أي جزء من `rect` موجودًا داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي X للزاوية العلوية اليسرى للمستطيل للاختبار. |
| y | int | الإحداثي Y للزاوية العلوية اليسرى للمستطيل للاختبار. |
| width | int | العرض للمستطيل للاختبار. |
| height | int | الارتفاع للمستطيل للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.Rectangle` المحددة موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الـ `com.aspose.imaging.Rectangle` بنية للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | الـ `com.aspose.imaging.Graphics` التي تمثل سياق رسومي. |

**Returns:**
منطقي - true عندما يكون أي جزء من `rect` موجودًا داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن الآخر. |

**Returns:**
boolean - نتيجة مقارنة المساواة.
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int - رمز التجزئة.
