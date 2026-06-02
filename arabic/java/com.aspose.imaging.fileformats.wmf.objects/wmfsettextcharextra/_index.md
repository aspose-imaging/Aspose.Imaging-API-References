---
title: "WmfSetTextCharExtra"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "سجل META_SETTEXTCHAREXTRA يحدد التباعد بين الأحرف لتبرير النص في سياق جهاز التشغيل."
type: docs
weight: 86
url: /ar/java/com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

سجل META\_SETTEXTCHAREXTRA يحدد التباعد بين الأحرف لتبرير النص في سياق جهاز التشغيل. يُضاف التباعد إلى المسافة البيضاء بين كل حرف، بما في ذلك الأحرف ``, عندما يتم إخراج سطر من النص المبرر.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | يحصل أو يعيّن القيمة الإضافية للحرف. |
| [setCharExtra(int value)](#setCharExtra-int-) | يحصل أو يعيّن القيمة الإضافية للحرف. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


يحصل أو يعيّن القيمة الإضافية للحرف.

القيمة: مقدار المسافة الإضافية، بوحدات منطقية، التي تُضاف إلى كل حرف. إذا لم يكن وضع التخطيط الحالي هو MM\_TEXT، يتم تحويل هذه القيمة وتدويرها إلى أقرب بكسل. للحصول على تفاصيل حول ضبط وضع التخطيط، راجع META\_SETMAPMODE (القسم 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


يحصل أو يعيّن القيمة الإضافية للحرف.

القيمة: مقدار المسافة الإضافية، بوحدات منطقية، التي تُضاف إلى كل حرف. إذا لم يكن وضع التخطيط الحالي هو MM\_TEXT، يتم تحويل هذه القيمة وتدويرها إلى أقرب بكسل. للحصول على تفاصيل حول ضبط وضع التخطيط، راجع META\_SETMAPMODE (القسم 2.3.5.17).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

