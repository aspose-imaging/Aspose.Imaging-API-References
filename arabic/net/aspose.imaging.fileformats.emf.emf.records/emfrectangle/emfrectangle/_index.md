---
title: "EmfRectangle.EmfRectangle"
second_title: "Aspose.Imaging for .NET API Reference"
description: "EmfRectangle المُنشئ. يُنشئ مثيلًا جديدًا من الفئة EmfRectangle"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfrectangle/emfrectangle/
---
## EmfRectangle(EmfRecord) {#constructor_1}

يُنشئ مثيلًا جديدًا من الفئة [`EmfRectangle`](../).

```csharp
public EmfRectangle(EmfRecord source)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المصدر | EmfRecord | المصدر. |

### انظر أيضًا

* class [EmfRecord](../../emfrecord/)
* class [EmfRectangle](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfrectangle/)
* assembly [Aspose.Imaging](../../../)

---

## EmfRectangle() {#constructor}

يُنشئ مثيلًا جديدًا من الفئة [`EmfRectangle`](../).

```csharp
public EmfRectangle()
```

## أمثلة

المثال التالي يوضح كيفية تعيين لون الخلفية لـ EMF. في الواقع يضع مستطيلًا بلون الخلفية قبل رسم جميع الكائنات الأخرى.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image1.emf";
string outputFilePath = dir + "ChangeBackground_" + "image1.emf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleEmf((Aspose.Imaging.FileFormats.Emf.EmfImage)image, Aspose.Imaging.Color.Blue);

    image.Save(outputFilePath);
}
    
/// <summary>
/// طريقة مساعدة لتغيير خلفية EMF.
/// </summary>
public static void AddBackgroundRectangleEmf(Aspose.Imaging.FileFormats.Emf.EmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    //تعيين المستطيل
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle rectangle = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRectangle();
    rectangle.Box = image.Header.EmfHeader.Bounds;

    //تعيين الفرشاة
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect brush = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreateBrushIndirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    // تبدأ فهارس الكائنات من 1؛ الصفر محجوز للإشارات إلى ملف الميتافايل نفسه، انظر
    // https://docs.microsoft.com/en-us/openspecs/windows_protocols/ms-emf/e4fa4e63-9096-4cdc-b776-85e2a1e4e1f4
    brush.IhBrush = 1;

    //اختر الفرشاة
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSelectObject();
    selectObject.ObjectHandle = 1;

    //إزالة الفرشاة
    Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDeleteObject();
    deleteObject.ObjectHandle = 1;

    //إضافة سجلات
    image.Records.Insert(1, brush);
    image.Records.Insert(2, selectObject);
    image.Records.Insert(3, rectangle);
    image.Records.Insert(4, deleteObject);
}
```

### انظر أيضًا

* class [EmfRectangle](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfrectangle/)
* assembly [Aspose.Imaging](../../../)


