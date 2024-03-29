---
title: ProgressEventHandlerInfo
second_title: Aspose.Imaging لمرجع NET API
description: تمثل هذه الفئة معلومات حول تقدم عمليات تحميل / حفظ / تصدير الصور  التي يمكن استخدامها في تطبيق خارجي لإظهار تقدم التحويل إلى user
type: docs
weight: 10780
url: /ar/net/aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

تمثل هذه الفئة معلومات حول تقدم عمليات تحميل / حفظ / تصدير الصور ، التي يمكن استخدامها في تطبيق خارجي لإظهار تقدم التحويل إلى user

```csharp
public class ProgressEventHandlerInfo
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Description](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/description) { get; } | يحصل على وصف الحدث |
| [EventType](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/eventtype) { get; } | يحصل على نوع الحدث. |
| [MaxValue](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/maxvalue) { get; } | يحصل على الحد الأعلى لقيمة التقدم . |
| [Value](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/value) { get; } | يحصل على قيمة التقدم الحالية . |

### أمثلة

يوضح المثال التالي كيفية طباعة معلومات حول أحداث التقدم لعمليات التحميل / التصدير.

```csharp
[C#]

public void Test3460()
{
    string dir = "c:\\aspose.imaging\\net\\issues\\3460";
    string fileName = System.IO.Path.Combine(dir, "big.png");

    // مثال على استخدام معالجات أحداث تقدم العملية المنفصلة لعمليات التحميل / التصدير
    using (var image = Aspose.Imaging.Image.Load(fileName, new Aspose.Imaging.LoadOptions { ProgressEventHandler = ProgressCallback }))
    {
        image.Save(fileName + ".psd",
                   new Aspose.Imaging.ImageOptions.PsdOptions() { ProgressEventHandler = ExportProgressCallback });
    }
}

private void ProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("{0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

private void ExportProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("Export event {0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

// قد يبدو سجل STDOUT كما يلي:
// التهيئة: 1/4
// ما قبل المعالجة: 2/4
// المعالجة: 3/4
// الإنجاز: 4/4
// تهيئة حدث التصدير: 1/4
// معالجة مسبقة لحدث التصدير: 2/4
// معالجة حدث التصدير: 3/4
// حدث التصدير RelativeProgress: 1/1
// التقسيم النسبي: 1/1
// إنهاء حدث التصدير: 4/4
```

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.ProgressManagement](../../aspose.imaging.progressmanagement)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
