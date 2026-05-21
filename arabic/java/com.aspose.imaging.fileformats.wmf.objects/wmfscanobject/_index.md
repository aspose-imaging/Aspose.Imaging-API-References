---
title: "WmfScanObject"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كائن Scan يحدد مجموعة من خطوط المسح."
type: docs
weight: 69
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfscanobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfScanObject extends MetaObject
```

كائن Scan يحدد مجموعة من خطوط المسح.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfScanObject()](#WmfScanObject--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يحصل أو يعيّن العدد. |
| [setCount(int value)](#setCount-int-) | يحصل أو يعيّن العدد. |
| [getTop()](#getTop--) | يحصل أو يعيّن الأعلى. |
| [setTop(int value)](#setTop-int-) | يحصل أو يعيّن الأعلى. |
| [getBottom()](#getBottom--) | يحصل أو يعيّن الأسفل. |
| [setBottom(int value)](#setBottom-int-) | يحصل أو يعيّن الأسفل. |
| [getScanLines()](#getScanLines--) | يحصل أو يعيّن خطوط المسح. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | يحصل أو يعيّن خطوط المسح. |
| [getCount2()](#getCount2--) | يحصل أو يعيّن count2. |
| [setCount2(int value)](#setCount2-int-) | يحصل أو يعيّن count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


يحصل أو يعيّن العدد.

القيمة: عدد الإحداثيات الأفقية (محور x) في مصفوفة `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. يجب أن تكون هذه القيمة مضاعفًا للعدد 2، لأن نقاط النهاية اليسرى واليمنى مطلوبة لتحديد كل سطر مسح.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


يحصل أو يعيّن العدد.

القيمة: عدد الإحداثيات الأفقية (محور x) في مصفوفة `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. يجب أن تكون هذه القيمة مضاعفًا للعدد 2، لأن نقاط النهاية اليسرى واليمنى مطلوبة لتحديد كل سطر مسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


يحصل أو يعيّن الأعلى.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لسطر المسح العلوي.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


يحصل أو يعيّن الأعلى.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لسطر المسح العلوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


يحصل أو يعيّن الأسفل.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لسطر المسح السفلي.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


يحصل أو يعيّن الأسفل.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لسطر المسح السفلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


يحصل أو يعيّن خطوط المسح.

القيمة: مصفوفة من أسطر المسح، كل منها محدد بإحداثيات أفقية (محور x) للنقاط اليسرى واليمنى لنهايته.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


يحصل أو يعيّن خطوط المسح.

القيمة: مصفوفة من أسطر المسح، كل منها محدد بإحداثيات أفقية (محور x) للنقاط اليسرى واليمنى لنهايته.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


يحصل أو يعيّن count2.

القيمة: نفس قيمة الحقل `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`؛ وهي موجودة للسماح بالانتقال للأعلى في البنية.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


يحصل أو يعيّن count2.

القيمة: نفس قيمة الحقل `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`؛ وهي موجودة للسماح بالانتقال للأعلى في البنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

