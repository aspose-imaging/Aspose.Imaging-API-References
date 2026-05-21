---
title: "RasterImage.NormalizeAngle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تقوم بتطبيع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من المسح المائل. تستخدم هذه الطريقة طريقتي GetSkewAngle و Rotate."
type: docs
weight: 480
url: /ar/net/aspose.imaging/rasterimage/normalizeangle/
---
## NormalizeAngle() {#normalizeangle}

تطبع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من المسح المائل. تستخدم هذه الطريقة طريقتي [`GetSkewAngle`](../getskewangle/) و [`Rotate`](../rotate/).

```csharp
public void NormalizeAngle()
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## NormalizeAngle(bool, Color) {#normalizeangle_1}

تطبع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من المسح المائل. تستخدم هذه الطريقة طريقتي [`GetSkewAngle`](../getskewangle/) و [`Rotate`](../rotate/).

```csharp
public virtual void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeProportionally | Boolean | إذا تم الضبط على `true` سيتغير حجم الصورة وفقاً لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى يبقى الأبعاد دون تغيير وتدور محتويات الصورة الداخلية فقط. |
| backgroundColor | لون | لون الخلفية. |

## أمثلة

الانحراف هو ظاهرة قد تظهر أثناء عملية مسح المستند عندما يتم تدوير النص/الصور في المستند بزاوية طفيفة. يمكن أن تكون له أسباب متعددة لكن الأكثر شيوعًا هو أن الورقة تُنقل بشكل غير صحيح أثناء المسح. لذلك، تصحيح الانحراف (deskew) هو عملية اكتشاف وإصلاح هذه المشكلة في الملفات الممسوحة (مثل bitmap) بحيث تكون المستندات المصححة تحتوي على النص/الصور بشكل صحيح وأفقي.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";

string inputFilePath = dir + "skewed.png";
string outputFilePath = dir + "skewed.out.png";

// تخلص من المسح المائل باستخدام المعلمات الافتراضية
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    // Deskew
    image.NormalizeAngle(false /*do not resize*/, Aspose.Imaging.Color.LightGray /*background color*/);
    image.Save(outputFilePath);
}
```

### انظر أيضًا

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


