---
title: "EmfModifyWorldTransformMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد ModifyWorldTransformMode الأنماط لاستخدام بيانات التحويل المحددة لتعديل التحويل من الفضاء العالمي إلى الفضاء الصفحي الذي يتم تعريفه حاليًا في سياق جهاز التشغيل."
type: docs
weight: 33
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

تحدد تعداد ModifyWorldTransformMode الأنماط لاستخدام بيانات التحويل المحددة لتعديل التحويل من الفضاء العالمي إلى الفضاء الصفحي الذي يتم تعريفه حاليًا في سياق جهاز التشغيل.
## الحقول

| حقل | الوصف |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | إعادة تعيين التحويل الحالي باستخدام مصفوفة الهوية. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | ضرب التحويل الحالي. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | ضرب التحويل الحالي. |
| [MWT_SET](#MWT-SET) | تنفيذ وظيفة سجل EMR\_SETWORLDTRANSFORM (القسم 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


إعادة تعيين التحويل الحالي باستخدام مصفوفة الهوية. في هذا الوضع، يتم تجاهل بيانات التحويل المحددة

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


ضرب التحويل الحالي. في هذا الوضع، تكون بيانات التحويل المحددة هي الضارب الأيسر، والتحويل المعرفة حاليًا في سياق جهاز التشغيل هو الضارب الأيمن

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


ضرب التحويل الحالي. في هذا الوضع، تكون بيانات التحويل المحددة هي الضارب الأيمن، والتحويل المعرفة حاليًا في سياق جهاز التشغيل هو الضارب الأيسر

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


تنفيذ وظيفة سجل EMR\_SETWORLDTRANSFORM (القسم 2.3.12.2).

