---
title: "TiffImage.GetOriginalOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. استرجاع الخيارات المستمدة من إعدادات الملف الأصلي لتسهيل الحفاظ السلس على المعلمات الرئيسية مثل عمق اللون وغيرها من السمات الأساسية للصورة الأصلية. استخدم هذه الطريقة للحفاظ على الدقة والاتساق في مهام معالجة الصور وضمان نتائج مثالية دون تعديلات غير ضرورية. على سبيل المثال إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة Save سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى طريقة Save كمعامل ثانٍ."
type: docs
weight: 260
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions/
---
## TiffImage.GetOriginalOptions method

استرجاع الخيارات المستمدة من إعدادات الملف الأصلي، مما يسهل الحفاظ السلس على المعلمات الرئيسية مثل عمق البت وغيرها من السمات الأساسية للصورة الأصلية. استخدم هذه الطريقة للحفاظ على الدقة والاتساق في مهام معالجة الصور، وضمان نتائج مثالية دون تعديلات غير ضرورية. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى طريقة [`Save`](../../../aspose.imaging/image/save/) كمعامل ثانٍ.

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### قيمة الإرجاع

الخيارات بناءً على إعدادات الملف الأصلي.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | لا توجد خيارات أصلية يمكن استخراجها من الصورة |

### انظر أيضًا

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


