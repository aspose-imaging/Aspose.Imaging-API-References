---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد أعلام DriverStringOptions خصائص تموضع نص الرسومات وعرضه."
type: docs
weight: 21
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

تحدد أعلام DriverStringOptions خصائص تموضع النص الرسومي وعرضه. يمكن دمج هذه الأعلام لتحديد خيارات متعددة.

--------------------

يتم تحديد إخراج النص الرسومي في سجلات [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring).
## الحقول

| حقل | الوصف |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | إذا تم الضبط، يجب تحديد مواضع رموز الأحرف في جدول بحث خريطة الأحرف. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | إذا تم الضبط، يجب عرض السلسلة عموديًا. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | إذا تم الضبط، يجب حساب مواضع رموز الأحرف نسبةً إلى موضع الرمز الأول. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | إذا تم الضبط، يجب استخدام ذاكرة أقل لتخزين رموز الأحرف المضادة للتنعيم، مما ينتج عرض نص بجودة أقل. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


إذا تم الضبط، يجب تحديد مواضع رموز الأحرف في جدول بحث خريطة الأحرف. إذا تم إلغاء الضبط، يجب الحصول على مواضع الرموز من مصفوفة إحداثيات.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


إذا تم الضبط، يجب عرض السلسلة عموديًا. إذا تم إلغاء الضبط، يجب عرض السلسلة أفقيًا.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


إذا تم الضبط، يجب حساب مواضع رموز الحروف نسبةً إلى موضع الرمز الأول. إذا لم يتم الضبط، يجب الحصول على مواضع الرموز من مصفوفة من الإحداثيات.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


إذا تم الضبط، يجب استخدام ذاكرة أقل لتخزين رموز مضادة للتنعيم مؤقتًا، مما ينتج عرض نص بجودة أقل. إذا لم يتم الضبط، يجب استخدام ذاكرة أكثر، مما ينتج عرض نص بجودة أعلى.

