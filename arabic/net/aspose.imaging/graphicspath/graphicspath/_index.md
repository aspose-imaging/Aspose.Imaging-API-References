---
title: GraphicsPath
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفGraphicsPathaspose.imaging/graphicspath فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging/graphicspath/graphicspath/
---
## GraphicsPath() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../../graphicspath) فئة .

```csharp
public GraphicsPath()
```

### أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath و Graphics لإنشاء الأشكال ومعالجتها على سطح الصورة. ينشئ المثال صورة جديدة (من النوع Tiff) ، ويمسح السطح ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية ، يتم استدعاء طريقة DrawPath المعروضة بواسطة فئة الرسومات لعرض المسارات على السطح.

```csharp
[C#]

// إنشاء مثيل لـ FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    // قم بإنشاء مثيل لـ TiffOptions وعيّن خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // تعيين المصدر لمثيل ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        // إنشاء وتهيئة مثيل لفئة الرسومات
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        // مسح سطح الرسومات
        graphics.Clear(Color.Wheat);

        // إنشاء مثيل لفئة GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        // إنشاء مثيل لفئة الشكل
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // إضافة أشكال إلى كائن الشكل
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        // إضافة كائن الشكل إلى GraphicsPath
        graphicspath.AddFigure(figure);

        // رسم المسار باستخدام كائن القلم ذي اللون الأسود
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### أنظر أيضا

* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [Aspose.Imaging](../../graphicspath)
* المجسم [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[]) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../../graphicspath) فئة .

```csharp
public GraphicsPath(Figure[] figures)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| figures | Figure[] | الأرقام المطلوب التهيئة منها. |

### أنظر أيضا

* class [Figure](../../figure)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [Aspose.Imaging](../../graphicspath)
* المجسم [Aspose.Imaging](../../../)

---

## GraphicsPath(Figure[], FillMode) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../../graphicspath) فئة .

```csharp
public GraphicsPath(Figure[] figures, FillMode fillMode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| figures | Figure[] | الأرقام المطلوب التهيئة منها. |
| fillMode | FillMode | وضع الملء. |

### أنظر أيضا

* class [Figure](../../figure)
* enum [FillMode](../../fillmode)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [Aspose.Imaging](../../graphicspath)
* المجسم [Aspose.Imaging](../../../)

---

## GraphicsPath(FillMode) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`GraphicsPath`](../../graphicspath) فئة .

```csharp
public GraphicsPath(FillMode fillMode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fillMode | FillMode | وضع الملء. |

### أنظر أيضا

* enum [FillMode](../../fillmode)
* class [GraphicsPath](../../graphicspath)
* مساحة الاسم [Aspose.Imaging](../../graphicspath)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->