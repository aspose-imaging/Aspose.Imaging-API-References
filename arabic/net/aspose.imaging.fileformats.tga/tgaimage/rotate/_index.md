---
title: "TgaImage.Rotate"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TgaImage. تدور الصورة حول مركزها بزاوية محددة مع الحفاظ على تناسب الحجم وحفظ لون الخلفية. تتيح هذه الطريقة تعديلًا دقيقًا للصورة، مما يضمن أن الدوران يحافظ على التوازن البصري والاتساق مع لون الخلفية المحدد. إنها مثالية للمهام التي تتطلب دورانًا دقيقًا حول المركز مثل تصحيح الاتجاه أو التعديلات الفنية."
type: docs
weight: 350
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/rotate/
---
## TgaImage.Rotate method

Rotates the image around its center by a specified angle while maintaining resize proportionality and preserving the background color. This method allows for precise image manipulation, ensuring that the rotation maintains visual balance and consistency with the specified background color. It's ideal for tasks where accurate rotation around the center is necessary, such as orientation correction or artistic adjustments.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | فردي | زاوية التدوير بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | Boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور فقط محتويات الصورة `internal`. |
| backgroundColor | لون | لون الخلفية. |

### انظر أيضًا

* struct [Color](../../../aspose.imaging/color/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


