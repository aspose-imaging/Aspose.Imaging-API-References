---
title: "DicomPage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu, çok çerçeveli tipte DICOM dosyalarıyla çalışmak için bir sınıftır."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

Bu, çok çerçeveli tipte DICOM dosyalarıyla çalışmak için bir sınıftır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | `DicomPage` sınıfının yeni bir örneğini başlatır. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | `DicomPage` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getIndex()](#getIndex--) | Geçerli sayfanın indeksini alır. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getFileFormat()](#getFileFormat--) | Dosya formatının bir değerini alır |

## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Vektör grafikleri kullanarak bir şey çizin
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Çizilen görüntünün piksellerini kaydedin. Artık Dicom görüntüsünün ilk sayfasındalar.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Sonra birkaç sayfa ekleyin, onları daha karanlık hale getirerek
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Ana sayfanın önüne birkaç sayfa ekleyin, onları daha parlak yaparak
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Oluşturulan çok sayfalı görüntüyü çıktı dosyasına kaydedin
        image.save("MultiPage.dcm");
    }
}
```

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


`DicomPage` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Görüntü. |
| index | int | İndeks. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


`DicomPage` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Görüntü. |
| index | int | İndeks. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Geçerli sayfanın indeksini alır.

Değer: İndeks.

**Returns:**
int - geçerli sayfanın indeksi.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

Değer: Görüntünün genişliği.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

Değer: Görüntünün yüksekliği.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

Değer: Görüntünün piksel başına bit sayısı.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Dosya formatının bir değerini alır

**Returns:**
long
