---
title: HasBackgroundColor
second_title: Aspose.Imaging for .NET API Referansı
description: Arka plan renginin olup olmadığını gösteren bir değer alır.
type: docs
weight: 60
url: /tr/net/aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/
---
## PngImage.HasBackgroundColor property

Arka plan renginin olup olmadığını gösteren bir değer alır.

```csharp
public override bool HasBackgroundColor { get; set; }
```

### Örnekler

Aşağıdaki örnek, alfa kanalını desteklemeyen bir TrueColor PNG görüntüsünün bir kısmı için tamamen saydam renklerin nasıl ayarlanacağını gösterir.

```csharp
[C#]

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\transparent.png", false);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.Truecolor;

// 100x100 piksellik bir TrueColor PNG görüntüsü oluşturun.
using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);

    // Tüm kırmızı pikseller tamamen şeffaf olarak kabul edilecektir.
    pngImage.TransparentColor = Aspose.Imaging.Color.Red;
    pngImage.HasTransparentColor = true;

    // Tüm şeffaf piksellerin bir arka plan rengi olacaktır.
    pngImage.BackgroundColor = Aspose.Imaging.Color.Green;
    pngImage.HasBackgroundColor = true;

    // Resmin tamamını beyaz renkle doldurun.
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White), pngImage.Bounds);

    // Resmin sol üst çeyreğini şeffaf renkle doldurun.
    // Bu, sol üst çeyreği arka plan renginde renklendirir.
    Rectangle rect = new Rectangle(0, 0, pngImage.Width / 2, pngImage.Height / 2);
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red), rect);

    pngImage.Save();
}
```

### Ayrıca bakınız

* class [PngImage](../../pngimage)
* ad alanı [Aspose.Imaging.FileFormats.Png](../../pngimage)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->