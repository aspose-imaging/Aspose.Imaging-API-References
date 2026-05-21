---
title: "الفئة WmfRectangle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle الفئة. سجل META_RECTANGLE يرسم مستطيلًا. المستطيل يتم تحديد حدوده باستخدام القلم وتعبئته باستخدام الفرشاة التي تم تعريفها في سياق جهاز التشغيل"
type: docs
weight: 9100
url: /ar/net/aspose.imaging.fileformats.wmf.objects/wmfrectangle/
---
## WmfRectangle class

سجل META_RECTANGLE يرسم مستطيلًا. يتم تحديد حدود المستطيل باستخدام القلم وتعبئته باستخدام الفرشاة المعرفة في سياق جهاز التشغيل.

```csharp
public class WmfRectangle : WmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WmfRectangle](wmfrectangle/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Rectangle](../../aspose.imaging.fileformats.wmf.objects/wmfrectangle/rectangle/) { get; set; } | يحصل أو يضبط المستطيل. |

## أمثلة

المثال التالي يوضح كيفية تعيين لون الخلفية لـ WMF. في الواقع يرسم مستطيلًا بلون الخلفية قبل رسم جميع الكائنات الأخرى.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image2.wmf";
string outputFilePath = dir + "ChangeBackground_" + "image2.wmf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleWmf((Aspose.Imaging.FileFormats.Wmf.WmfImage)image, Aspose.Imaging.Color.Blue);
    image.Save(outputFilePath);
}

/// <summary>
/// طريقة مساعدة لتغيير خلفية WMF. 
/// </summary>
public static void AddBackgroundRectangleWmf(Aspose.Imaging.FileFormats.Wmf.WmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    //تعيين المستطيل
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle rectangle = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle();
    rectangle.Rectangle = image.FrameBounds;

    //تعيين الفرشاة
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect brush = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    //اختر الفرشاة
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject(brush);

    //إزالة الفرشاة
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject(brush);

    //إضافة سجلات
    image.Records.Insert(0, brush);
    image.Records.Insert(1, selectObject);
    image.Records.Insert(2, rectangle);
    image.Records.Insert(3, deleteObject);
}
```

### انظر أيضًا

* class [WmfObject](../wmfobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


