---
title: "WmfSetMapperFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل META_SETMAPPERFLAGS يحدد الخوارزمية التي يستخدمها مُطابق الخطوط عندما يطابق الخطوط المنطقية إلى الخطوط الفيزيائية."
type: docs
weight: 78
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

سجل META\_SETMAPPERFLAGS يعرّف الخوارزمية التي يستخدمها محول الخطوط عند تحويل الخطوط المنطقية إلى خطوط مادية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | يحصل أو يضبط قيم المطابق. |
| [setMapperValues(int value)](#setMapperValues-int-) | يحصل أو يضبط قيم المطابق. |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


يحصل أو يضبط قيم المطابق.

القيمة: يحاول مُطابق الخطوط مطابقة نسبة أبعاد الخط إلى نسبة أبعاد الجهاز الحالية. إذا تم تعيين البت صفر، يختار المطابق الخطوط المتطابقة فقط.

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


يحصل أو يضبط قيم المطابق.

القيمة: يحاول مُطابق الخطوط مطابقة نسبة أبعاد الخط إلى نسبة أبعاد الجهاز الحالية. إذا تم تعيين البت صفر، يختار المطابق الخطوط المتطابقة فقط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

