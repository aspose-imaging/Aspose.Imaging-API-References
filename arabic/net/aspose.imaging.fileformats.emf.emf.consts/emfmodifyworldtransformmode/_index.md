---
title: "تعداد EmfModifyWorldTransformMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfModifyWorldTransformMode enum. يعرّف تعداد ModifyWorldTransformMode أوضاعًا لاستخدام بيانات التحويل المحددة لتعديل تحويل الفضاء العالمي إلى فضاء الصفحة الذي يُعرف حاليًا في سياق جهاز التشغيل"
type: docs
weight: 2860
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
## EmfModifyWorldTransformMode enumeration

تعداد ModifyWorldTransformMode يحدد الأوضاع لاستخدام بيانات التحويل المحددة لتعديل تحويل الفضاء العالمي إلى الفضاء الصفحي الذي يتم تعريفه حاليًا في سياق جهاز التشغيل.

```csharp
public enum EmfModifyWorldTransformMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| MWT_IDENTITY | `1` | إعادة تعيين التحويل الحالي باستخدام مصفوفة الهوية. في هذا الوضع، يتم تجاهل بيانات التحويل المحددة |
| MWT_LEFTMULTIPLY | `2` | ضرب التحويل الحالي. في هذا الوضع، تكون بيانات التحويل المحددة هي الضارب الأيسر، والتحويل المحدد حاليًا في سياق جهاز التشغيل هو الضارب الأيمن |
| MWT_RIGHTMULTIPLY | `3` | ضرب التحويل الحالي. في هذا الوضع، تكون بيانات التحويل المحددة هي الضارب الأيمن، والتحويل المحدد حاليًا في سياق جهاز التشغيل هو الضارب الأيسر |
| MWT_SET | `4` | تنفيذ وظيفة سجل EMR_SETWORLDTRANSFORM (القسم 2.3.12.2). |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


