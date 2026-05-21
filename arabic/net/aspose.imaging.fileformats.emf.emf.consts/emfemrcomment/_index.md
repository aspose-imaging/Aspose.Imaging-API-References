---
title: "Enum EmfEmrComment"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfEmrComment enum. يحدد تعداد EmrComment أنواع البيانات التي يمكن أن يحتويها سجل التعليق العام كما هو موضح في القسم 2.3.3.4"
type: docs
weight: 2710
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/
---
## EmfEmrComment enumeration

تعداد EmrComment يحدد أنواع البيانات التي يمكن أن يحتويها سجل التعليق العام، كما هو موضح في القسم 2.3.3.4.

```csharp
public enum EmfEmrComment : uint
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| EMR_COMMENT_WINDOWS_METAFILE | `2147483649` | يحتوي سجل التعليق هذا على مواصفة لصورة في WMF. راجع [MS-WMF] لمزيد من المعلومات |
| EMR_COMMENT_BEGINGROUP | `2` | يحدد سجل التعليق هذا بداية مجموعة من سجلات الرسم. كما يحدد كائنًا داخل ملف تعريف EMF |
| EMR_COMMENT_ENDGROUP | `3` | يحدد سجل التعليق هذا نهاية مجموعة من سجلات الرسم. يجب تضمين سجل EMR_COMMENT_ENDGROUP في ملف التعريف لكل سجل EMR_COMMENT_BEGINGROUP، وقد يكونان MAY متداخلين. |
| EMR_COMMENT_MULTIFORMATS | `1073741828` | يسمح سجل التعليق هذا بتضمين تعريفات متعددة لصورة في ملف التعريف. باستخدام هذا التعليق، على سبيل المثال، يمكن لتطبيق أن يضمّن نص PostScript مغلف بالإضافة إلى تعريف EMF لصورة. |
| EMR_COMMENT_UNICODE_STRING | `64` | سجل التعليق هذا محجوز ولا MUST NOT يُستخدم في ملف تعريف EMF |
| EMR_COMMENT_UNICODE_END | `128` | سجل التعليق هذا محجوز ولا MUST NOT يُستخدم في ملف تعريف EMF |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


