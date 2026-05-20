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

يصف داخل الشكل الرسومي المكوّن من المستطيلات والمسارات. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Region()](#Region--) | يقوم بتهيئة Region جديد. |
| [Region(RectangleF rect)](#Region-com.aspose.imaging.RectangleF-) | يقوم بتهيئة `T:Aspose.Imaging.Region` جديد من البنية المحددة `T:Aspose.Imaging.RectangleF`. |
| [Region(Rectangle rect)](#Region-com.aspose.imaging.Rectangle-) | يقوم بتهيئة `T:Aspose.Imaging.Region` جديد من البنية المحددة `T:Aspose.Imaging.Rectangle`. |
| [Region(GraphicsPath path)](#Region-com.aspose.imaging.GraphicsPath-) | يقوم بتهيئة `T:Aspose.Imaging.Region` جديد باستخدام `T:Aspose.Imaging.GraphicsPath` المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة دقيقة من هذا `com.aspose.imaging.region`. |
| [makeInfinite()](#makeInfinite--) | يقوم بتهيئة كائن `com.aspose.imaging.Region` هذا إلى داخل لا نهائي. |
| [makeEmpty()](#makeEmpty--) | يقوم بتهيئة `com.aspose.imaging.Region` هذا إلى داخل فارغ. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.RectangleF`. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.Rectangle`. |
| [intersect(GraphicsPath path)](#intersect-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.graphicsPath`. |
| [intersect(Region region)](#intersect-com.aspose.imaging.Region-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.region`. |
| [union(RectangleF rect)](#union-com.aspose.imaging.RectangleF-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.RectangleF`. |
| [union(Rectangle rect)](#union-com.aspose.imaging.Rectangle-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.Rectangle`. |
| [union(GraphicsPath path)](#union-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.graphicsPath`. |
| [union(Region region)](#union-com.aspose.imaging.Region-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.region`. |
| [xor(RectangleF rect)](#xor-com.aspose.imaging.RectangleF-) | يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد مع طرح تقاطع نفسه مع البنية المحددة `com.aspose.imaging.RectangleF`. |
| [xor(Rectangle rect)](#xor-com.aspose.imaging.Rectangle-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة. |
| [xor(GraphicsPath path)](#xor-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع `com.aspose.imaging.graphicsPath` المحدد. |
| [xor(Region region)](#xor-com.aspose.imaging.Region-) | يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع `com.aspose.imaging.region` المحدد. |
| [exclude(RectangleF rect)](#exclude-com.aspose.imaging.RectangleF-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية `com.aspose.imaging.RectangleF` المحددة. |
| [exclude(Rectangle rect)](#exclude-com.aspose.imaging.Rectangle-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية `com.aspose.imaging.Rectangle` المحددة. |
| [exclude(GraphicsPath path)](#exclude-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع `com.aspose.imaging.graphicsPath` المحدد. |
| [exclude(Region region)](#exclude-com.aspose.imaging.Region-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع `com.aspose.imaging.region` المحدد. |
| [complement(RectangleF rect)](#complement-com.aspose.imaging.RectangleF-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.RectangleF` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [complement(Rectangle rect)](#complement-com.aspose.imaging.Rectangle-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.Rectangle` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [complement(GraphicsPath path)](#complement-com.aspose.imaging.GraphicsPath-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.GraphicsPath` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [complement(Region region)](#complement-com.aspose.imaging.Region-) | يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.Region` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`. |
| [translate(float dx, float dy)](#translate-float-float-) | يقوم بإزاحة إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد. |
| [translate(int dx, int dy)](#translate-int-int-) | يقوم بإزاحة إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد. |
| [transform(Matrix matrix)](#transform-com.aspose.imaging.Matrix-) | يقوم بتحويل هذا `com.aspose.imaging.Region` باستخدام `com.aspose.imaging.matrix` المحدد. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.imaging.Graphics-) | يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل فارغ على سطح الرسم المحدد. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.imaging.Graphics-) | يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل لا نهائي على سطح الرسم المحدد. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت `com.aspose.imaging.Region` المحددة مطابقة لهذا `com.aspose.imaging.Region` على سطح الرسم المحدد. |
| [isVisible(float x, float y)](#isVisible-float-float-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.region`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.region`. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.imaging.RectangleF-) | يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.imaging.Graphics-) | يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن `com.aspose.imaging.Region` هذا عند الرسم باستخدام كائن `com.aspose.imaging.Graphics` المحدد. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | يفحص ما إذا كان هيكل `com.aspose.imaging.Point` المحدد موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | يفحص ما إذا كان هيكل `com.aspose.imaging.Point` المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.imaging.Rectangle-) | يفحص ما إذا كان أي جزء من هيكل `com.aspose.imaging.Rectangle` المحدد موجودًا داخل هذا `com.aspose.imaging.region`. |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-) | يفحص ما إذا كان أي جزء من هيكل `com.aspose.imaging.Rectangle` المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### Region() {#Region--}
```
public Region()
```


يقوم بتهيئة Region جديد.

### Region(RectangleF rect) {#Region-com.aspose.imaging.RectangleF-}
```
public Region(RectangleF rect)
```


يقوم بتهيئة `T:Aspose.Imaging.Region` جديد من البنية المحددة `T:Aspose.Imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `T:Aspose.Imaging.RectangleF` يحدد داخل المنطقة الجديدة `T:Aspose.Imaging.Region`. |

### Region(Rectangle rect) {#Region-com.aspose.imaging.Rectangle-}
```
public Region(Rectangle rect)
```


يقوم بتهيئة `T:Aspose.Imaging.Region` جديد من البنية المحددة `T:Aspose.Imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `T:Aspose.Imaging.Rectangle` يحدد داخل المنطقة الجديدة `T:Aspose.Imaging.Region`. |

### Region(GraphicsPath path) {#Region-com.aspose.imaging.GraphicsPath-}
```
public Region(GraphicsPath path)
```


يقوم بتهيئة `T:Aspose.Imaging.Region` جديد باستخدام `T:Aspose.Imaging.GraphicsPath` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `T:Aspose.Imaging.GraphicsPath` يحدد المنطقة الجديدة `T:Aspose.Imaging.Region`. |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


ينشئ نسخة عميقة دقيقة من هذا `com.aspose.imaging.region`.

**Returns:**
[Region](../../com.aspose.imaging/region) - The `com.aspose.imaging.Region` that this method creates.
### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


يقوم بتهيئة كائن `com.aspose.imaging.Region` هذا إلى داخل لا نهائي.

### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


يقوم بتهيئة `com.aspose.imaging.Region` هذا إلى داخل فارغ.

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` لتقاطع مع هذا `com.aspose.imaging.region`. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` لتقاطع مع هذا `com.aspose.imaging.region`. |

### intersect(GraphicsPath path) {#intersect-com.aspose.imaging.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` لتقاطع مع هذا `com.aspose.imaging.region`. |

### intersect(Region region) {#intersect-com.aspose.imaging.Region-}
```
public void intersect(Region region)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى تقاطع نفسه مع البنية المحددة `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` لتقاطع مع هذا `com.aspose.imaging.region`. |

### union(RectangleF rect) {#union-com.aspose.imaging.RectangleF-}
```
public void union(RectangleF rect)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` للاتحاد مع هذا `com.aspose.imaging.region`. |

### union(Rectangle rect) {#union-com.aspose.imaging.Rectangle-}
```
public void union(Rectangle rect)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.Rectangle`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` للاتحاد مع هذا `com.aspose.imaging.region`. |

### union(GraphicsPath path) {#union-com.aspose.imaging.GraphicsPath-}
```
public void union(GraphicsPath path)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` للاتحاد مع هذا `com.aspose.imaging.region`. |

### union(Region region) {#union-com.aspose.imaging.Region-}
```
public void union(Region region)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد نفسه مع البنية المحددة `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` للاتحاد مع هذا `com.aspose.imaging.region`. |

### xor(RectangleF rect) {#xor-com.aspose.imaging.RectangleF-}
```
public void xor(RectangleF rect)
```


يقوم بتحديث `com.aspose.imaging.Region` هذا إلى اتحاد مع طرح تقاطع نفسه مع البنية المحددة `com.aspose.imaging.RectangleF`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` لعملية XOR مع هذا `com.aspose.imaging.region`. |

### xor(Rectangle rect) {#xor-com.aspose.imaging.Rectangle-}
```
public void xor(Rectangle rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` إلى الاتحاد مطروحًا منه تقاطع نفسه مع بنية `com.aspose.imaging.Rectangle` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` لعملية XOR مع هذا `com.aspose.imaging.region`. |

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


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية `com.aspose.imaging.RectangleF` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` لاستبعاد من هذا `com.aspose.imaging.region`. |

### exclude(Rectangle rect) {#exclude-com.aspose.imaging.Rectangle-}
```
public void exclude(Rectangle rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع بنية `com.aspose.imaging.Rectangle` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` لاستبعاد من هذا `com.aspose.imaging.region`. |

### exclude(GraphicsPath path) {#exclude-com.aspose.imaging.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع `com.aspose.imaging.graphicsPath` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | `com.aspose.imaging.GraphicsPath` لاستبعاد من هذا `com.aspose.imaging.region`. |

### exclude(Region region) {#exclude-com.aspose.imaging.Region-}
```
public void exclude(Region region)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي فقط على الجزء من داخله الذي لا يتقاطع مع `com.aspose.imaging.region` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | `com.aspose.imaging.Region` لاستبعاد من هذا `com.aspose.imaging.region`. |

### complement(RectangleF rect) {#complement-com.aspose.imaging.RectangleF-}
```
public void complement(RectangleF rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.RectangleF` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | هيكل `com.aspose.imaging.RectangleF` لتكملة هذا `com.aspose.imaging.region`. |

### complement(Rectangle rect) {#complement-com.aspose.imaging.Rectangle-}
```
public void complement(Rectangle rect)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من بنية `com.aspose.imaging.Rectangle` المحددة الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | هيكل `com.aspose.imaging.Rectangle` لتكملة هذا `com.aspose.imaging.region`. |

### complement(GraphicsPath path) {#complement-com.aspose.imaging.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.GraphicsPath` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | الـ `com.aspose.imaging.GraphicsPath` لتكملة هذا `com.aspose.imaging.region`. |

### complement(Region region) {#complement-com.aspose.imaging.Region-}
```
public void complement(Region region)
```


يقوم بتحديث هذا `com.aspose.imaging.Region` ليحتوي على الجزء من `com.aspose.imaging.Region` المحدد الذي لا يتقاطع مع هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | الكائن `com.aspose.imaging.Region` لتكملة هذا الكائن `com.aspose.imaging.Region`. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


يقوم بإزاحة إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | المقدار لإزاحة هذا `com.aspose.imaging.Region` أفقياً. |
| dy | float | المقدار لإزاحة هذا `com.aspose.imaging.Region` رأسياً. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


يقوم بإزاحة إحداثيات هذا `com.aspose.imaging.Region` بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | int | المقدار لإزاحة هذا `com.aspose.imaging.Region` أفقياً. |
| dy | int | المقدار لإزاحة هذا `com.aspose.imaging.Region` رأسياً. |

### transform(Matrix matrix) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix matrix)
```


يقوم بتحويل هذا `com.aspose.imaging.Region` باستخدام `com.aspose.imaging.matrix` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | الـ `com.aspose.imaging.Matrix` التي تُستخدم لتحويل هذا `com.aspose.imaging.region`. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.imaging.Graphics-}
```
public boolean isEmpty(Graphics g)
```


يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل فارغ على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سطح رسم. |

**Returns:**
منطقي - true إذا كان داخل هذا `com.aspose.imaging.Region` فارغًا عند تطبيق التحويل المرتبط بـ `g`؛ وإلا، false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.imaging.Graphics-}
```
public boolean isInfinite(Graphics g)
```


يفحص ما إذا كان لهذا `com.aspose.imaging.Region` داخل لا نهائي على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سطح رسم. |

**Returns:**
منطقي - true إذا كان داخل هذا `com.aspose.imaging.Region` لا نهائيًا عند تطبيق التحويل المرتبط بـ `g`؛ وإلا، false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.imaging.Region-com.aspose.imaging.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


يفحص ما إذا كانت `com.aspose.imaging.Region` المحددة مطابقة لهذا `com.aspose.imaging.Region` على سطح الرسم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | الـ `com.aspose.imaging.Region` للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سطح رسم. |

**Returns:**
منطقي - True إذا كان داخل المنطقة مطابقة لداخل هذه المنطقة عند تطبيق التحويل المرتبط بالمعامل `g`؛ وإلا، false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للنقطة المراد اختبارها. |
| ص | float | إحداثي y للنقطة المراد اختبارها. |

**Returns:**
منطقي - True عندما تكون النقطة المحددة داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` لاختبار. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للنقطة المراد اختبارها. |
| ص | float | إحداثي y للنقطة المراد اختبارها. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - True عندما تكون النقطة المحددة داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


يفحص ما إذا كانت بنية `com.aspose.imaging.PointF` المحددة موجودة داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | الـ `com.aspose.imaging.PointF` لاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| ص | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| العرض | float | عرض المستطيل المراد اختباره. |
| الارتفاع | float | ارتفاع المستطيل المراد اختباره. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد داخل كائن `com.aspose.imaging.Region` هذا؛ وإلا، false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.imaging.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | الـ `com.aspose.imaging.RectangleF` لاختبار. |

**Returns:**
منطقي - true عندما يكون أي جزء من `rect` داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| ص | float | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| العرض | float | عرض المستطيل المراد اختباره. |
| الارتفاع | float | ارتفاع المستطيل المراد اختباره. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.imaging.RectangleF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


يفحص ما إذا كان أي جزء من بنية `com.aspose.imaging.RectangleF` المحددة موجودًا داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | الـ `com.aspose.imaging.RectangleF` لاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - true عندما تكون `rect` داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن `com.aspose.imaging.Region` هذا عند الرسم باستخدام كائن `com.aspose.imaging.Graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للنقطة المراد اختبارها. |
| ص | int | إحداثي y للنقطة المراد اختبارها. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - true عندما تكون النقطة المحددة داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


يفحص ما إذا كان هيكل `com.aspose.imaging.Point` المحدد موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الهيكل `com.aspose.imaging.Point` للاختبار. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


يفحص ما إذا كان هيكل `com.aspose.imaging.Point` المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | الهيكل `com.aspose.imaging.Point` للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - true عندما تكون `point` داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| ص | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| العرض | int | عرض المستطيل المراد اختباره. |
| الارتفاع | int | ارتفاع المستطيل المراد اختباره. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.imaging.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


يفحص ما إذا كان أي جزء من هيكل `com.aspose.imaging.Rectangle` المحدد موجودًا داخل هذا `com.aspose.imaging.region`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الهيكل `com.aspose.imaging.Rectangle` للاختبار. |

**Returns:**
منطقي - تُرجع هذه الطريقة true عندما يكون أي جزء من `rect` داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند الرسم باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| ص | int | الإحداثي الصادي للزاوية العليا اليسرى للمستطيل المراد اختباره. |
| العرض | int | عرض المستطيل المراد اختباره. |
| الارتفاع | int | ارتفاع المستطيل المراد اختباره. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - true عندما يكون أي جزء من المستطيل المحدد داخل هذا `com.aspose.imaging.Region`؛ وإلا، false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.imaging.Rectangle-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


يفحص ما إذا كان أي جزء من هيكل `com.aspose.imaging.Rectangle` المحدد موجودًا داخل هذا `com.aspose.imaging.Region` عند رسمه باستخدام `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | الهيكل `com.aspose.imaging.Rectangle` للاختبار. |
| g | [Graphics](../../com.aspose.imaging/graphics) | كائن `com.aspose.imaging.Graphics` يمثل سياق رسومي. |

**Returns:**
منطقي - true عندما يكون أي جزء من `rect` داخل هذا `com.aspose.imaging.Region`؛ وإلا false.
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
