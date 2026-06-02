---
title: "EmfRop4"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "عملية نقطية رباعية تحدد عمليات نقطية ثلاثية للألوان الأمامية والخلفية لملف bitmap."
type: docs
weight: 110
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

عملية نقطية رباعية، تحدد عمليات نقطية ثلاثية للألوان الأمامية والخلفية لملف bitmap. هذه القيم تحدد كيفية دمج بيانات ألوان المستطيل المصدر مع بيانات ألوان المستطيل الهدف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | يُنشئ مثيلاً جديدًا من الفئة `EmfRop4`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | يحصل على ROP3 الخلفية. |
| [getForegroundRop3()](#getForegroundRop3--) | يحصل على ROP3 الأمامية. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


يُنشئ مثيلاً جديدًا من الفئة `EmfRop4`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dwordData | int | بيانات الـ dword. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


يحصل على ROP3 الخلفية. البتات الثمانية غير الموقعة، الأكثر أهمية، من قيمة عملية نقطية ثلاثية 24‑بت من تعداد عمليات نقطية ثلاثية WMF ([MS‑WMF] القسم 2.1.1.31). يحدد هذا الرمز كيفية دمج بيانات لون الخلفية للصور النقطية المصدر والوجهة ونمط الفرشاة.

القيمة: ROP3 الخلفية.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


يحصل على ROP3 المقدمة. البتات الثمانية غير الموقعة، الأكثر أهمية، من قيمة عملية نقطية ثلاثية 24‑بت من تعداد عمليات نقطية ثلاثية WMF. يحدد هذا الرمز كيفية دمج بيانات لون المقدمة للصور النقطية المصدر والوجهة ونمط الفرشاة.

القيمة: ROP3 المقدمة.

**Returns:**
byte
