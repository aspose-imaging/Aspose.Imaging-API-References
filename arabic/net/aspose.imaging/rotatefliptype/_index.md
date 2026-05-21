---
title: "تعداد RotateFlipType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "تعداد Aspose.Imaging.RotateFlipType. يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة"
type: docs
weight: 11480
url: /ar/net/aspose.imaging/rotatefliptype/
---
## RotateFlipType enumeration

يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة.

```csharp
public enum RotateFlipType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| RotateNoneFlipNone | `0` | يحدد عدم وجود دوران باتجاه عقارب الساعة ولا انعكاس. |
| Rotate90FlipNone | `1` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 90 درجة دون انعكاس. |
| Rotate180FlipNone | `2` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 180 درجة دون انعكاس. |
| Rotate270FlipNone | `3` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 270 درجة دون انعكاس. |
| RotateNoneFlipX | `4` | يحدد عدم وجود دوران باتجاه عقارب الساعة يليه انعكاس أفقي. |
| Rotate90FlipX | `5` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 90 درجة يليه انعكاس أفقي. |
| Rotate180FlipX | `6` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 180 درجة يليه انعكاس أفقي. |
| Rotate270FlipX | `7` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 270 درجة يليه انعكاس أفقي. |
| RotateNoneFlipY | `8` | يحدد عدم وجود دوران باتجاه عقارب الساعة يليه انعكاس عمودي. |
| Rotate90FlipY | `9` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 90 درجة يليه انعكاس عمودي. |
| Rotate180FlipY | `10` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 180 درجة يليه انعكاس عمودي. |
| Rotate270FlipY | `11` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 270 درجة يليه انعكاس عمودي. |
| RotateNoneFlipXY | `12` | يحدد عدم وجود دوران باتجاه عقارب الساعة يليه انعكاس أفقي وعمودي. |
| Rotate90FlipXY | `13` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 90 درجة يليه انعكاس أفقي وعمودي. |
| Rotate180FlipXY | `14` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 180 درجة يليه انعكاس أفقي وعمودي. |
| Rotate270FlipXY | `15` | يحدد دورانًا باتجاه عقارب الساعة بمقدار 270 درجة يليه انعكاس أفقي وعمودي. |

## أمثلة

هذا المثال يحمل صورة، يدورها 90 درجة باتجاه عقارب الساعة ويقلب الصورة أفقيًا و(أو) عموديًا اختياريًا.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // قم بالدوران والقلوب واحفظ إلى ملف الإخراج.
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".bmp");
    }
}
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


