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
| [getCount()](#getCount--) | الحصول أو تعيين العدد. |
| [setCount(int value)](#setCount-int-) | الحصول أو تعيين العدد. |
| [getTop()](#getTop--) | الحصول أو تعيين الأعلى. |
| [setTop(int value)](#setTop-int-) | الحصول أو تعيين الأعلى. |
| [getBottom()](#getBottom--) | الحصول أو تعيين الأسفل. |
| [setBottom(int value)](#setBottom-int-) | الحصول أو تعيين الأسفل. |
| [getScanLines()](#getScanLines--) | الحصول أو تعيين خطوط الفحص. |
| [setScanLines(Point[] value)](#setScanLines-com.aspose.imaging.Point---) | الحصول أو تعيين خطوط الفحص. |
| [getCount2()](#getCount2--) | الحصول أو تعيين count2. |
| [setCount2(int value)](#setCount2-int-) | الحصول أو تعيين count2. |
### WmfScanObject() {#WmfScanObject--}
```
public WmfScanObject()
```


### getCount() {#getCount--}
```
public int getCount()
```


الحصول أو تعيين العدد.

القيمة: عدد الإحداثيات الأفقية (محور x) في مصفوفة `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. يجب أن تكون هذه القيمة مضاعفًا للعدد 2، لأن نقاط النهاية اليسرى واليمنى مطلوبة لتحديد كل خط فحص.

**Returns:**
int
### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


الحصول أو تعيين العدد.

القيمة: عدد الإحداثيات الأفقية (محور x) في مصفوفة `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.ScanLines`. يجب أن تكون هذه القيمة مضاعفًا للعدد 2، لأن نقاط النهاية اليسرى واليمنى مطلوبة لتحديد كل خط فحص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


الحصول أو تعيين الأعلى.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لخط الفحص العلوي.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


الحصول أو تعيين الأعلى.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لخط الفحص العلوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBottom() {#getBottom--}
```
public int getBottom()
```


الحصول أو تعيين الأسفل.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لخط الفحص السفلي.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


الحصول أو تعيين الأسفل.

القيمة: الإحداثي العمودي (محور y)، بوحدات منطقية، لخط الفحص السفلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getScanLines() {#getScanLines--}
```
public Point[] getScanLines()
```


الحصول أو تعيين خطوط الفحص.

القيمة: مصفوفة من خطوط الفحص، كل منها محدد بإحداثيات أفقية (محور x) للنقاط اليسرى واليمنى لنهايته.

**Returns:**
com.aspose.imaging.Point[]
### setScanLines(Point[] value) {#setScanLines-com.aspose.imaging.Point---}
```
public void setScanLines(Point[] value)
```


الحصول أو تعيين خطوط الفحص.

القيمة: مصفوفة من خطوط الفحص، كل منها محدد بإحداثيات أفقية (محور x) للنقاط اليسرى واليمنى لنهايته.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) |  |

### getCount2() {#getCount2--}
```
public int getCount2()
```


الحصول أو تعيين count2.

القيمة: نفس قيمة الحقل `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`؛ وهو موجود للسماح بالتنقل الصاعد في البنية.

**Returns:**
int
### setCount2(int value) {#setCount2-int-}
```
public void setCount2(int value)
```


الحصول أو تعيين count2.

القيمة: نفس قيمة الحقل `com.aspose.imaging.fileFormats.wmf.objects.wmfScanObject.Count`؛ وهو موجود للسماح بالتنقل الصاعد في البنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

