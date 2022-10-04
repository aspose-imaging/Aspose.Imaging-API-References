---
title: NormalizeAngle
second_title: Aspose.Imaging لمرجع NET API
description: تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقةGetSkewAngleaspose.imaging/rasterimage/getskewangle وRotateaspose.imaging/rasterimage/rotate الطرق .
type: docs
weight: 430
url: /ar/net/aspose.imaging/rasterimage/normalizeangle/
---
## NormalizeAngle() {#normalizeangle}

تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة[`GetSkewAngle`](../getskewangle) و[`Rotate`](../rotate) الطرق .

```csharp
public void NormalizeAngle()
```

### أنظر أيضا

* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

---

## NormalizeAngle(bool, Color) {#normalizeangle_1}

تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة[`GetSkewAngle`](../getskewangle) و[`Rotate`](../rotate) الطرق .

```csharp
public virtual void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| resizeProportionally | Boolean | إذا تم التعيين على`حقيقي` سيتم تغيير حجم صورتك وفقًا لإسقاطات المستطيل المستدير (نقاط الزاوية) في حالة أخرى والتي تترك الأبعاد دون تغيير ويتم تدوير محتويات الصورة الداخلية فقط. |
| backgroundColor | Color | لون الخلفية. |

### أمثلة

الانحراف هو قطعة أثرية قد تظهر أثناء عملية المسح الضوئي للمستند عندما يتم تدوير نص / صور المستند بزاوية طفيفة. يمكن أن يكون لها أسباب مختلفة ولكن الأكثر شيوعًا هو أن الورق يصبح في غير مكانه أثناء المسح. لذلك ، فإن الانحراف هو عملية اكتشاف هذه المشكلة وإصلاحها في الملفات الممسوحة ضوئيًا (أي صورة نقطية) بحيث تحتوي المستندات غير الصحيحة على النص / الصور بشكل صحيح ومعدلة أفقيًا.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";

string inputFilePath = dir + "skewed.png";
string outputFilePath = dir + "skewed.out.png";

// تخلص من المسح المنحرف باستخدام المعلمات الافتراضية
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    // انحراف
    image.NormalizeAngle(false /*do not resize*/, Aspose.Imaging.Color.LightGray /*background color*/);
    image.Save(outputFilePath);
}
```

### أنظر أيضا

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->