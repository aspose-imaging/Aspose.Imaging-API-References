---
title: "EmfStretchMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يُستخدم تعداد StretchMode لتحديد كيفية إضافة بيانات اللون أو إزالتها من الصور النقطية التي يتم تمديدها أو ضغطها."
type: docs
weight: 43
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

يُستخدم تعداد StretchMode لتحديد كيفية إضافة بيانات اللون أو إزالتها من الصور النقطية التي يتم تمديدها أو ضغطها.
## الحقول

| حقل | الوصف |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | ينفذ عملية AND منطقية باستخدام قيم اللون للبكسلات المحذوفة والموجودة. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | ينفذ عملية OR منطقية باستخدام قيم اللون للبكسلات المحذوفة والموجودة. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | يحذف البكسلات. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | يرسم البكسلات من المستطيل المصدر إلى كتل من البكسلات في المستطيل الوجهة. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


ينفذ عملية AND منطقية باستخدام قيم اللون للبكسلات المحذوفة والموجودة. إذا كان الصورة النقطية أحادية اللون، فإن هذا الوضع يحافظ على البكسلات السوداء على حساب البكسلات البيضاء.

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


ينفذ عملية OR منطقية باستخدام قيم اللون للبكسلات المحذوفة والموجودة. إذا كان الصورة النقطية أحادية اللون، فإن هذا الوضع يحافظ على البكسلات البيضاء على حساب البكسلات السوداء.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


يحذف البكسلات. هذا الوضع يحذف جميع خطوط البكسلات المحذوفة دون محاولة الحفاظ على معلوماتها.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


يرسم البكسلات من المستطيل المصدر إلى كتل من البكسلات في المستطيل الوجهة. اللون المتوسط للكتلة الوجهة من البكسلات يقترب من لون البكسلات المصدر.

