---
title: "TgaImage.Crop"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage method. قص الصورة إلى منطقة محددة. تتيح هذه الطريقة لك تحديد مساحة مستطيلة داخل الصورة للاحتفاظ بها مع حذف البقية. هذه العملية مفيدة للتركيز على محتوى معين داخل الصورة أو لإزالة أجزاء غير مرغوب فيها."
type: docs
weight: 310
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/crop/
---
## Crop(Rectangle) {#crop}

قص الصورة إلى منطقة محددة. تسمح لك هذه الطريقة بتحديد مساحة مستطيلة داخل الصورة للاحتفاظ بها، مع حذف البقية. هذه العملية مفيدة للتركيز على محتوى معين داخل الصورة أو لإزالة أجزاء غير مرغوب فيها.

```csharp
public override void Crop(Rectangle rectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

قص الصورة بتحديد إزاحات للحدود اليسرى، اليمنى، العليا، والسفلى. تسمح لك هذه الطريقة بتقليم الصورة عن طريق تحريك حدودها بشكل مستقل على المحورين الأفقي والرأسي. من خلال ضبط هذه الإزاحات، يمكنك التحكم بدقة في الأجزاء التي تريد الاحتفاظ بها من الصورة، وبالتالي قصها إلى الأبعاد المطلوبة.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | Int32 | الإزاحة اليسرى. |
| rightShift | Int32 | الإزاحة اليمنى. |
| topShift | Int32 | الإزاحة العلوية. |
| bottomShift | Int32 | الإزاحة السفلية. |

### انظر أيضًا

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


