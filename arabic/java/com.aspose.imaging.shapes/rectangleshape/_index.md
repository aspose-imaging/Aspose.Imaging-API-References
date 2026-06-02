---
title: "RectangleShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل شكلًا مستطيليًا."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.shapes/rectangleshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public class RectangleShape extends RectangleProjectedShape
```

يمثل شكلًا مستطيليًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RectangleShape()](#RectangleShape--) | ينشئ مثيلاً جديدًا من الفئة `RectangleShape`. |
| [RectangleShape(RectangleF rectangle)](#RectangleShape-com.aspose.imaging.RectangleF-) | ينشئ مثيلاً جديدًا من الفئة `RectangleShape`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
هذا المثال ينشئ صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures و GraphicsPath على سطح الصورة.
``` java
//ينشئ مثيلاً من BmpOptions ويضبط خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
//المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//إنشاء نسخة من Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //إنشاء وتهيئة نسخة من فئة Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //مسح سطح Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //إنشاء نسخة من فئة GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //إنشاء نسخة من فئة Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //إضافة شكل إلى كائن Figure.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //إنشاء نسخة من فئة Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //إضافة شكل إلى كائن Figure.
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //رسم مسار باستخدام كائن Pen باللون الأسود
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // احفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### RectangleShape() {#RectangleShape--}
```
public RectangleShape()
```


ينشئ مثيلاً جديدًا من الفئة `RectangleShape`.

### RectangleShape(RectangleF rectangle) {#RectangleShape-com.aspose.imaging.RectangleF-}
```
public RectangleShape(RectangleF rectangle)
```


ينشئ مثيلاً جديدًا من الفئة `RectangleShape`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | المستطيل. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل.

القيمة: مقاطع الشكل.

**Returns:**
com.aspose.imaging.ShapeSegment[]
