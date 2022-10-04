---
title: BufferSizeHint
second_title: Aspose.Imaging for .NET API Referansı
description: Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.imaging/imageoptionsbase/buffersizehint/
---
## ImageOptionsBase.BufferSizeHint property

Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar.

```csharp
public int BufferSizeHint { get; set; }
```

### Mülk değeri

Megabayt cinsinden arabellek boyutu ipucu. Pozitif olmayan değer, dahili arabellekler için bellek sınırlaması olmadığı anlamına gelir

### Örnekler

Aşağıdaki örnek, yeni bir JPEG görüntüsü oluştururken bir bellek sınırının nasıl ayarlanacağını gösterir. Bellek sınırı, tüm dahili arabellekler için izin verilen maksimum boyuttur (megabayt olarak).

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// Hedef oluşturulan görüntü için 50 megabayt bellek sınırı ayarlama
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.JpegOptions
{
    CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive,
    BufferSizeHint = 50,
    Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "createdFile.jpg", false),
};
    
using (var image = Aspose.Imaging.Image.Create(createOptions, 1000, 1000))
{
    image.Save(); // aynı konuma kaydet
}
```

Aşağıdaki örnek, bir PNG görüntüsü oluştururken ve üzerinde karmaşık grafikler çizerken bir bellek sınırının nasıl ayarlanacağını gösterir. Bellek sınırı, tüm dahili arabellekler için izin verilen maksimum boyuttur (megabayt olarak).

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3383\\";

const int ImageSize = 2000;
Aspose.Imaging.ImageOptionsBase createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_simple.png", false);
createOptions.BufferSizeHint = 30; // Hafıza limiti 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    // Burada herhangi bir grafik işlemi kullanabilirsiniz, hepsi belirlenen hafıza limiti dahilinde gerçekleştirilecektir.
    // Örneğin:
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);
    graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 3f), 0, 0, image.Width, image.Height);

    image.Save();
}

// Çok sayıda grafik işlemi de desteklenir:
const int OperationAreaSize = 10;
createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "graphics_complex.png", false);
createOptions.BufferSizeHint = 30; // Hafıza limiti 30 Mb

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, ImageSize, ImageSize))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.BeginUpdate();
    graphics.Clear(Aspose.Imaging.Color.LightSkyBlue);

    int x, y;
    int numberOfOperations = 0;
    for (int column = 0; column * OperationAreaSize < ImageSize; column++)
    {
        for (int row = 0; row * OperationAreaSize < ImageSize; row++)
        {
            x = column * OperationAreaSize;
            y = row * OperationAreaSize;

            bool reversed = (column + row) % 2 != 0;
            if (reversed)
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x + OperationAreaSize - 2,
                    y,
                    x,
                    y + OperationAreaSize);
            }
            else
            {
                graphics.DrawLine(
                    new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red),
                    x,
                    y,
                    x + OperationAreaSize - 2,
                    y + OperationAreaSize);
            }

            numberOfOperations++;
        }
    }

    // Çok fazla bellek kaplamazken burada yaklaşık 40k işlem uygulanacak 
    // zaten harici dosyaya boşaltıldıkları ve oradan birer birer yüklenecekleri için
    graphics.EndUpdate();

    image.Save();
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase)
* ad alanı [Aspose.Imaging](../../imageoptionsbase)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->