---
title: CanLoad
second_title: Aspose.Imaging لمرجع NET API
description: تحديد ما إذا كان بإمكان أداة تحميل الصور قراءة صورة جديدة من التدفق المحدد واختيارياً باستخدام امتدادloadOptions .
type: docs
weight: 10
url: /ar/net/aspose.imaging/iimageloaderdescriptor/canload/
---
## IImageLoaderDescriptor.CanLoad method

تحديد ما إذا كان بإمكان أداة تحميل الصور قراءة صورة جديدة من التدفق المحدد واختيارياً باستخدام امتداد*loadOptions* .

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| streamContainer | StreamContainer | حاوية التدفق. |
| loadOptions | LoadOptions | تفاصيل تنسيق الملف المحددة بواسطة*loadOptions* . ال*loadOptions* قد تكون فارغة. |

### قيمة الإرجاع

`حقيقي` إذا كان برنامج تحميل الصور الذي تم إنشاؤه بواسطة هذا الواصف يمكنه قراءة الصورة من الدفق ؛ خلاف ذلك،`خاطئة` .

### أنظر أيضا

* class [StreamContainer](../../streamcontainer)
* class [LoadOptions](../../loadoptions)
* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor)
* مساحة الاسم [Aspose.Imaging](../../iimageloaderdescriptor)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->