---
title: "IColorConverter.Convert"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة IColorConverter. تُحوِّل البيانات المُمرَّرة إلى صيغة الإخراج"
type: docs
weight: 10
url: /ar/net/aspose.imaging/icolorconverter/convert/
---
## IColorConverter.Convert method

يقوم بتحويل البيانات الممررة إلى تنسيق الإخراج.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | تنسيق المصدر. |
| بيانات | Byte[] | بيانات المصدر. |
| الإزاحة | Int32 | الإزاحة بالبايتات حيث يجب أن يبدأ نسخ البيانات. |
| bitStart | Int32 | بدء البت. لاحظ أن هذه القيمة ليست محاذاة للبايت بل هي البت الفعلي حيث يجب أن يبدأ النسخ. |
| samplesCount | Int32 | عدد العينات. |
| linesCount | Int32 | عدد الأسطر. |
| destFormat | PixelDataFormat | تنسيق الوجهة. |
| outputData | Byte[] | بيانات الإخراج. |
| outputOffset | Int32 | إزاحة الإخراج حيث يجب أن يبدأ نسخ البيانات. |

### قيمة الإرجاع

عدد البايتات المحوّلة.

### انظر أيضًا

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.Imaging](../../icolorconverter/)
* assembly [Aspose.Imaging](../../../)


