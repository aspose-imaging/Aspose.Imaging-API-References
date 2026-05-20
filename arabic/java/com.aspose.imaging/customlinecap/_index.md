---
title: "CustomLineCap"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على غطاء خط مخصص معرف من قبل المستخدم."
type: docs
weight: 35
url: /ar/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

يحتوي على غطاء خط مخصص معرف من قبل المستخدم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | ينشئ مثلاً جديداً من الفئة `CustomLineCap` بالمخطط المحدد والملء. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | ينشئ مثلاً جديداً من الفئة `CustomLineCap` من تعداد `LineCap` الموجود المحدد مع المخطط والملء المحددين. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | ينشئ مثلاً جديداً من الفئة `CustomLineCap` من تعداد `LineCap` الموجود المحدد مع المخطط والملء والجزء الداخلي المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFillPath()](#getFillPath--) | يحصل على الكائن الذي يحدد الملء للغطاء المخصص. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | يحدد الكائن الذي يعرّف التعبئة للغطاء المخصص. |
| [getStrokePath()](#getStrokePath--) | يحصل على الكائن الذي يعرّف المخطط الخارجي للغطاء المخصص. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | يحدد الكائن الذي يعرّف المخطط الخارجي للغطاء المخصص. |
| [getStrokeJoin()](#getStrokeJoin--) | يحصل على تعداد `LineJoin` الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن `CustomLineCap` هذا. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | يحدد تعداد `LineJoin` الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن `CustomLineCap` هذا. |
| [getBaseCap()](#getBaseCap--) | يحصل على تعداد `LineCap` الذي يُبنى عليه كائن `CustomLineCap` هذا. |
| [setBaseCap(int value)](#setBaseCap-int-) | يحدد تعداد `LineCap` الذي يُبنى عليه كائن `CustomLineCap` هذا. |
| [getBaseInset()](#getBaseInset--) | يحصل على المسافة بين الغطاء والخط. |
| [setBaseInset(float value)](#setBaseInset-float-) | يحدد المسافة بين الغطاء والخط. |
| [getWidthScale()](#getWidthScale--) | يحصل على مقدار التحجيم لهذا كائن `CustomLineCap` من الفئة بالنسبة إلى عرض كائن `System.Drawing.Pen`. |
| [setWidthScale(float value)](#setWidthScale-float-) | يحدد مقدار التحجيم لهذا كائن `CustomLineCap` من الفئة بالنسبة إلى عرض كائن `System.Drawing.Pen`. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | يحدد الأغطية المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذا الغطاء المخصص. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | يحصل على الأغطية المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذا الغطاء المخصص. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


ينشئ مثلاً جديداً من الفئة `CustomLineCap` بالمخطط المحدد والملء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | كائن `GraphicsPath` يعرّف التعبئة للغطاء المخصص. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | كائن `GraphicsPath` يعرّف المخطط الخارجي للغطاء المخصص. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


ينشئ مثلاً جديداً من الفئة `CustomLineCap` من تعداد `LineCap` الموجود المحدد مع المخطط والملء المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | كائن `GraphicsPath` يعرّف التعبئة للغطاء المخصص. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | كائن `GraphicsPath` يعرّف المخطط الخارجي للغطاء المخصص. |
| baseCap | int | غطاء الخط الذي يُنشأ منه الغطاء المخصص. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


ينشئ مثلاً جديداً من الفئة `CustomLineCap` من تعداد `LineCap` الموجود المحدد مع المخطط والملء والجزء الداخلي المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | كائن `GraphicsPath` يعرّف التعبئة للغطاء المخصص. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | كائن `GraphicsPath` يعرّف المخطط الخارجي للغطاء المخصص. |
| baseCap | int | غطاء الخط الذي يُنشأ منه الغطاء المخصص. |
| baseInset | float | المسافة بين الغطاء والخط. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


يحصل على الكائن الذي يحدد الملء للغطاء المخصص.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


يحدد الكائن الذي يعرّف التعبئة للغطاء المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | الكائن الذي يعرّف التعبئة للغطاء المخصص. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


يحصل على الكائن الذي يعرّف المخطط الخارجي للغطاء المخصص.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


يحدد الكائن الذي يعرّف المخطط الخارجي للغطاء المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | الكائن الذي يعرّف المخطط الخارجي للغطاء المخصص. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


يحصل على تعداد `LineJoin` الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن `CustomLineCap` هذا.

**Returns:**
int - تعداد `LineJoin` الذي يستخدمه كائن `CustomLineCap` لربط الخطوط.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


يحدد تعداد `LineJoin` الذي يحدد كيفية ربط الخطوط التي تُكوّن كائن `CustomLineCap` هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد `LineJoin` الذي يستخدمه كائن `CustomLineCap` لربط الخطوط. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


يحصل على تعداد `LineCap` الذي يُبنى عليه كائن `CustomLineCap` هذا.

**Returns:**
int - تعداد `LineCap` الذي يُبنى عليه كائن `CustomLineCap`.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


يحدد تعداد `LineCap` الذي يُبنى عليه كائن `CustomLineCap` هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تعداد `LineCap` الذي يُبنى عليه كائن `CustomLineCap`. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


يحصل على المسافة بين الغطاء والخط.

**Returns:**
float - المسافة بين بداية الغطاء ونهاية الخط.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


يحدد المسافة بين الغطاء والخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | المسافة بين بداية الغطاء ونهاية الخط. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


يحصل على مقدار التحجيم لهذا كائن `CustomLineCap` من الفئة بالنسبة إلى عرض كائن `System.Drawing.Pen`.

**Returns:**
float - مقدار تحجيم الغطاء.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


يحدد مقدار التحجيم لهذا كائن `CustomLineCap` من الفئة بالنسبة إلى عرض كائن `System.Drawing.Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | مقدار تحجيم الغطاء. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


يحدد الأغطية المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذا الغطاء المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startCap | int | التعداد `LineCap` المستخدم في بداية الخط داخل هذا الغطاء. |
| endCap | int | التعداد `LineCap` المستخدم في نهاية الخط داخل هذا الغطاء. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


يحصل على الأغطية المستخدمة لبدء وإنهاء الخطوط التي تُكوّن هذا الغطاء المخصص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startCap | int[] | التعداد `LineCap` المستخدم في بداية الخط داخل هذا الغطاء. |
| endCap | int[] | التعداد `LineCap` المستخدم في نهاية الخط داخل هذا الغطاء. |

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
