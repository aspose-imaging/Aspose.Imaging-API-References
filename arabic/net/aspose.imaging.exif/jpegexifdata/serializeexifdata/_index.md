---
title: "JpegExifData.SerializeExifData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة JpegExifData. تسلسل بيانات EXIF. يكتب قيم العلامات ومحتوياتها. العلامة التي تؤثر أكثر على الحجم هي محتويات علامة الصورة المصغرة"
type: docs
weight: 240
url: /ar/net/aspose.imaging.exif/jpegexifdata/serializeexifdata/
---
## JpegExifData.SerializeExifData method

يسلسل بيانات EXIF. يكتب قيم العلامات ومحتوياتها. العلامة التي تؤثر على الحجم أكثر هي محتويات علامة Thumbnail.

```csharp
public byte[] SerializeExifData()
```

### قيمة الإرجاع

بيانات EXIF المتسلسلة.

## ملاحظات

يجب أن يكون حجم الجزء الكلي أقل من أو يساوي MaxExifSegmentSize بايت لضمان إنتاج صورة jpeg صحيحة. تلميح: حاول تقليل حجم الصورة المصغرة أو تغيير ضغطها في حال كان حجم قسم EXIF كبيرًا جدًا.

### انظر أيضًا

* class [JpegExifData](../)
* namespace [Aspose.Imaging.Exif](../../jpegexifdata/)
* assembly [Aspose.Imaging](../../../)


