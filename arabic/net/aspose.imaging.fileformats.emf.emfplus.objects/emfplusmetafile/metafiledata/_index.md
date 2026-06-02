---
title: "EmfPlusMetafile.MetafileData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfPlusMetafile. يحصل أو يعيّن بيانات بطول متغير تحدد ملف الميتافيل المدمج. يمكن أن يكون محتوى البيانات وتنسيقها مختلفين لكل نوع من أنواع الميتافيل."
type: docs
weight: 20
url: /ar/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/metafiledata/
---
## EmfPlusMetafile.MetafileData property

يحصل أو يضبط بيانات ذات طول متغير تحدد ملف الميتا المدمج. يمكن أن يكون المحتوى وتنسيق البيانات مختلفين لكل نوع من ملفات الميتا.

```csharp
public byte[] MetafileData { get; set; }
```

## ملاحظات

يتم تحديد صور الرسومات بواسطة كائنات EmfPlusImage (القسم 2.2.1.4). يجب أن يكون كائن EmfPlusMetafile موجودًا في حقل ImageData لكائن EmfPlusImage إذا تم تحديد ImageTypeMetafile في حقل Type الخاص به. هذا الكائن عام ويُستخدم لأنواع مختلفة من البيانات، بما في ذلك: ملف WMF ميتافيل [MS-WMF]؛ ملف WMF يمكن وضعه؛ ملف EMF ميتافيل [MS-EMF]؛ ملف EMF+ ميتافيل يحدد عمليات الرسومات بسجلات EMF+ فقط؛ وملف EMF+ ميتافيل يحدد عمليات الرسومات بسجلات EMF+ وEMF معًا. راجع القسم 2.2.2 لتحديد كائنات البنية الإضافية.

### انظر أيضًا

* class [EmfPlusMetafile](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusmetafile/)
* assembly [Aspose.Imaging](../../../)


