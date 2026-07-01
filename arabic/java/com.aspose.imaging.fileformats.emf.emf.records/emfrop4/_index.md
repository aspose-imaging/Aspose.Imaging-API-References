---
title: "EmfRop4"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "عملية نقطية رباعية تحدد عمليات نقطية ثلاثية لألوان المقدمة والخلفية لملف bitmap."
type: docs
weight: 110
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfrop4/
---
**Inheritance:**
java.lang.Object
```
public final class EmfRop4
```

عملية نقطية رباعية، تحدد عمليات نقطية ثلاثية لألوان المقدمة والخلفية لملف bitmap. هذه القيم تحدد كيفية دمج بيانات اللون للمستطيل المصدر مع بيانات اللون للمستطيل الهدف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfRop4(int dwordData)](#EmfRop4-int-) | يقوم بتهيئة نسخة جديدة من الفئة `EmfRop4`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBackgroundRop3()](#getBackgroundRop3--) | يحصل على ROP3 الخلفي. |
| [getForegroundRop3()](#getForegroundRop3--) | يحصل على ROP3 المقدمة. |
### EmfRop4(int dwordData) {#EmfRop4-int-}
```
public EmfRop4(int dwordData)
```


يقوم بتهيئة نسخة جديدة من الفئة `EmfRop4`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dwordData | int | بيانات الـ dword. |

### getBackgroundRop3() {#getBackgroundRop3--}
```
public byte getBackgroundRop3()
```


يحصل على ROP3 الخلفي. البتات الثمانية غير الموقعة، الأكثر أهمية، من قيمة عملية نقطية ثلاثية 24-بت من تعداد عمليات نقطية WMF الثلاثية ([MS-WMF] section 2.1.1.31). يحدد هذا الرمز كيفية دمج بيانات لون الخلفية للصور النقطية المصدر والوجهة ونمط الفرشاة.

القيمة: ROP3 الخلفي.

**Returns:**
byte
### getForegroundRop3() {#getForegroundRop3--}
```
public byte getForegroundRop3()
```


يحصل على ROP3 المقدمة. البتات الثمانية غير الموقعة، الأكثر أهمية، من قيمة عملية نقطية ثلاثية 24-بت من تعداد عمليات نقطية WMF الثلاثية. يحدد هذا الرمز كيفية دمج بيانات لون المقدمة للصور النقطية المصدر والوجهة ونمط الفرشاة.

القيمة: ROP3 المقدمة.

**Returns:**
byte
