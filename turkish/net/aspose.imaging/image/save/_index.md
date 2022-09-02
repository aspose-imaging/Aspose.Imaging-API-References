---
title: Save
second_title: Aspose.Imaging for .NET API Referansı
description: Görüntü verilerini temel alınan akışa kaydeder.
type: docs
weight: 240
url: /tr/net/aspose.imaging/image/save/
---
## Save() {#save}

Görüntü verilerini temel alınan akışa kaydeder.

```csharp
public void Save()
```

### Örnekler

Aşağıdaki örnek, bir BMP görüntüsünün tamamının veya bir kısmının bir dosyaya veya akışa nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Siyah beyaz bir görüntüye dönüştür
    bmpImage.BinarizeOtsu();

    // Varsayılan seçeneklerle aynı konuma kaydedin.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Bir palet yalnızca iki renk içerir: Bu durumda Siyah ve Beyaz.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Tüm monokrom görüntüler için (siyah-beyaz olanlar dahil) piksel başına 1 bit ayırmanız yeterlidir.
    saveOptions.BitsPerPixel = 1;

    // Belirtilen seçeneklerle başka bir konuma kaydedin.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Resmin sadece orta kısmını kaydedin.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Tüm görüntüyü bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Resmin orta kısmını bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// Çıktı şöyle görünebilir:
//Tüm görüntünün bayt cinsinden boyutu: 24062
//Görüntünün bayt cinsinden orta kısmının boyutu: 6046
```

### Ayrıca bakınız

* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Resmi belirtilen dosya konumuna kaydeder.

```csharp
public override void Save(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Resmin kaydedileceği dosya yolu. |

### Ayrıca bakınız

* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| options | ImageOptionsBase | Seçenekler. |

### Örnekler

Aşağıdaki örnek, bir dosyadan bir BMP görüntüsü yükler ve ardından görüntüyü bir PNG dosyasına kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Resmin tamamını bir PNG dosyasına kaydedin.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

Bu örnek, bir Görüntüyü Kaydetmek için basit adımları gösterir. Bu işlemi göstermek için, bir disk konumundan mevcut bir dosyayı yüklüyoruz, görüntü üzerinde Döndürme işlemi gerçekleştiriyoruz ve Dosya Yolu kullanarak görüntüyü PSD formatında kaydediyoruz.

```csharp
[C#]

string dir = "c:\\temp\\";

// Bir görüntü sınıfı örneği oluşturun ve onu Dosya yolu aracılığıyla mevcut bir dosyayla başlatın
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Görüntüyü X ekseni etrafında 180 derece döndür
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //Görüntüyü varsayılan PsdOptions ayarlarıyla Dosya Yoluna PSD olarak kaydedin
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

Aşağıdaki örnek, bir BMP görüntüsünün tamamının veya bir kısmının bir dosyaya veya akışa nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Siyah beyaz bir görüntüye dönüştür
    bmpImage.BinarizeOtsu();

    // Varsayılan seçeneklerle aynı konuma kaydedin.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Bir palet yalnızca iki renk içerir: Bu durumda Siyah ve Beyaz.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Tüm monokrom görüntüler için (siyah-beyaz olanlar dahil) piksel başına 1 bit ayırmanız yeterlidir.
    saveOptions.BitsPerPixel = 1;

    // Belirtilen seçeneklerle başka bir konuma kaydedin.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Resmin sadece orta kısmını kaydedin.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Tüm görüntüyü bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Resmin orta kısmını bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// Çıktı şöyle görünebilir:
//Tüm görüntünün bayt cinsinden boyutu: 24062
//Görüntünün bayt cinsinden orta kısmının boyutu: 6046
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| options | ImageOptionsBase | Seçenekler. |
| boundsRectangle | Rectangle | Hedef görüntü dikdörtgeni sınırlar. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | seçenekler |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Görüntü kaydedilemedi. |

### Örnekler

Aşağıdaki örnek, bir dosyadan bir BMP görüntüsü yükler ve ardından görüntünün dikdörtgen bir bölümünü bir PNG dosyasına kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Resmin üst yarısını bir PNG dosyasına kaydedin.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

Aşağıdaki örnek, bir BMP görüntüsünün tamamının veya bir kısmının bir dosyaya veya akışa nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Siyah beyaz bir görüntüye dönüştür
    bmpImage.BinarizeOtsu();

    // Varsayılan seçeneklerle aynı konuma kaydedin.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Bir palet yalnızca iki renk içerir: Bu durumda Siyah ve Beyaz.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Tüm monokrom görüntüler için (siyah-beyaz olanlar dahil) piksel başına 1 bit ayırmanız yeterlidir.
    saveOptions.BitsPerPixel = 1;

    // Belirtilen seçeneklerle başka bir konuma kaydedin.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Resmin sadece orta kısmını kaydedin.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Tüm görüntüyü bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Resmin orta kısmını bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// Çıktı şöyle görünebilir:
//Tüm görüntünün bayt cinsinden boyutu: 24062
//Görüntünün bayt cinsinden orta kısmının boyutu: 6046
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntü verilerinin kaydedileceği akış. |
| optionsBase | ImageOptionsBase | Kaydet seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | seçeneklerTemel |
| ArgumentException | Şu anda desteklenmediği için belirtilen biçimde kaydedilemiyor.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Görüntü dışa aktarılamadı. |

### Örnekler

Aşağıdaki örnek, bir dosyadan bir görüntü yükler ve ardından görüntüyü bir PNG dosya akışına kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Resmin tamamını bir dosya akışına kaydedin.
        image.Save(outputStream, saveOptions);
    }
}
```

Bu örnek, bir Görüntüyü MemoryStream'e Kaydetme işlemini gösterir. Bu işlemi göstermek için örnek, bazı disk konumlarından mevcut bir dosyayı yükler, görüntü üzerinde Döndürme işlemi gerçekleştirir ve görüntüyü PSD formatında kaydeder

```csharp
[C#]

//MemoryStream örneğini oluştur
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // Bir görüntü sınıfı örneği oluşturun ve onu Dosya yolu aracılığıyla mevcut bir dosyayla başlatın
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //Görüntüyü X ekseni etrafında 180 derece döndür
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //Görüntüyü varsayılan PsdOptions ayarlarıyla PSD olarak MemoryStream'e kaydedin
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

Aşağıdaki örnek, bir BMP görüntüsünün tamamının veya bir kısmının bir dosyaya veya akışa nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Siyah beyaz bir görüntüye dönüştür
    bmpImage.BinarizeOtsu();

    // Varsayılan seçeneklerle aynı konuma kaydedin.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Bir palet yalnızca iki renk içerir: Bu durumda Siyah ve Beyaz.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Tüm monokrom görüntüler için (siyah-beyaz olanlar dahil) piksel başına 1 bit ayırmanız yeterlidir.
    saveOptions.BitsPerPixel = 1;

    // Belirtilen seçeneklerle başka bir konuma kaydedin.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Resmin sadece orta kısmını kaydedin.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Tüm görüntüyü bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Resmin orta kısmını bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// Çıktı şöyle görünebilir:
//Tüm görüntünün bayt cinsinden boyutu: 24062
//Görüntünün bayt cinsinden orta kısmının boyutu: 6046
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Görüntü verilerinin kaydedileceği akış. |
| optionsBase | ImageOptionsBase | Kaydet seçenekleri. |
| boundsRectangle | Rectangle | Hedef görüntü dikdörtgeni sınırlar. Kaynak sınırlarını kullanmak için boş dikdörtgeni ayarlayın. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | seçeneklerTemel |
| ArgumentException | Şu anda desteklenmediği için belirtilen biçimde kaydedilemiyor.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Görüntü dışa aktarılamadı. |

### Örnekler

Aşağıdaki örnek, bir dosyadan bir görüntü yükler ve ardından görüntünün dikdörtgen bir bölümünü bir PNG dosya akışına kaydeder.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Resmin üst yarısını bir dosya akışına kaydedin.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

Aşağıdaki örnek, bir BMP görüntüsünün tamamının veya bir kısmının bir dosyaya veya akışa nasıl kaydedileceğini gösterir.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Siyah beyaz bir görüntüye dönüştür
    bmpImage.BinarizeOtsu();

    // Varsayılan seçeneklerle aynı konuma kaydedin.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Bir palet yalnızca iki renk içerir: Bu durumda Siyah ve Beyaz.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Tüm monokrom görüntüler için (siyah-beyaz olanlar dahil) piksel başına 1 bit ayırmanız yeterlidir.
    saveOptions.BitsPerPixel = 1;

    // Belirtilen seçeneklerle başka bir konuma kaydedin.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Resmin sadece orta kısmını kaydedin.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Tüm görüntüyü bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Resmin orta kısmını bir bellek akışına kaydedin
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// Çıktı şöyle görünebilir:
//Tüm görüntünün bayt cinsinden boyutu: 24062
//Görüntünün bayt cinsinden orta kısmının boyutu: 6046
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* ad alanı [Aspose.Imaging](../../image)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
