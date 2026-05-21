---
title: "ImageOptionsBase.ProgressEventHandler"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية ImageOptionsBase. تحصل أو تعين معالج حدث التقدم."
type: docs
weight: 70
url: /ar/net/aspose.imaging/imageoptionsbase/progresseventhandler/
---
## ImageOptionsBase.ProgressEventHandler property

يحصل أو يضبط معالج حدث التقدم.

```csharp
public ProgressEventHandler ProgressEventHandler { get; set; }
```

### Property Value

معالج حدث التقدم.

## أمثلة

المثال التالي يوضح كيفية طباعة معلومات حول أحداث التقدم لعمليات التحميل/التصدير.

```csharp
[C#]

public void Test3460()
{
    string dir = "c:\\aspose.imaging\\net\\issues\\3460";
    string fileName = System.IO.Path.Combine(dir, "big.png");

    // مثال على استخدام معالجات أحداث تقدم العملية المنفصلة لعمليات التحميل/التصدير
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

// قد يبدو سجل STDOUT هكذا:
//التهيئة : 1/4
//المعالجة المسبقة : 2/4
//المعالجة : 3/4
//الإنهاء : 4/4
//حدث التصدير التهيئة : 1/4
//حدث التصدير المعالجة المسبقة : 2/4
//حدث التصدير المعالجة : 3/4
//حدث التصدير التقدم النسبي : 1/1
//التقدم النسبي : 1/1
//حدث التصدير الإنهاء : 4/4
```

### انظر أيضًا

* delegate [ProgressEventHandler](../../progresseventhandler/)
* class [ImageOptionsBase](../)
* namespace [Aspose.Imaging](../../imageoptionsbase/)
* assembly [Aspose.Imaging](../../../)


