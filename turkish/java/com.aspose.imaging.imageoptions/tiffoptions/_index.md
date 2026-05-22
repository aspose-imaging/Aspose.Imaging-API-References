---
title: "TiffOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff dosya formatı seçenekleri."
type: docs
weight: 48
url: /tr/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

Tiff dosya formatı seçenekleri. Genişlik ve yükseklik etiketlerinin, görüntü oluşturulurken genişlik ve yükseklik parametreleriyle üzerine yazılacağını ve bu nedenle doğrudan belirtilmelerine gerek olmadığını unutmayın. Birçok seçeneğin varsayılan bir değer döndürdüğü, bunun ise seçeneğin etiket değeri olarak açıkça ayarlandığı anlamına gelmediği unutulmamalıdır. Etiketin mevcut olduğunu doğrulamak için Tags özelliğini veya ilgili IsTagPresent yöntemini kullanın.

` UYARI! kaydetme sırasında tiff seçeneklerini asla değiştirmeyin, çünkü bu yan etkilere ve bulunması zor hatalara yol açabilir. Aşağıdaki satır, veri başlangıcının yanlış belirlenmesine neden olduğu için özellikle yorum satırı olarak bırakıldı. Geçen seçeneklerde spp bulunmuyordu (bu durumda seçenekler doğru olmasa da bu senaryo hatalara neden olur) ve sonraki satır +spp etiketi +bpp etiketi eklenmesine yol açtı; seçenekler veri tamamen yazıldıktan sonra yazıldığında sıkıştırılmamış codec için veri başlangıcını üzerine yazmış oldu!!! See TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3; `
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Yeni bir `TiffOptions` sınıf örneği başlatır. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Yeni bir `TiffOptions` sınıf örneği başlatır. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Yeni bir `TiffOptions` sınıf örneği başlatır. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Yeni bir `TiffOptions` sınıf örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Geçerli etiket sayısını alır. |
| [getTagCount()](#getTagCount--) | Etiket sayısını alır. |
| [getFileStandard()](#getFileStandard--) | TIFF dosya standardını alır veya ayarlar. |
| [setFileStandard(int value)](#setFileStandard-int-) | TIFF dosya standardını alır veya ayarlar. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Varsayılan bellek tahsis sınırını alır veya ayarlar. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren değeri alır veya ayarlar. |
| [isValid()](#isValid--) | `TiffOptions`'ın doğru şekilde yapılandırılıp yapılandırılmadığını gösteren değeri alır. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | YCbCrCoefficients'ı alır veya ayarlar. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | YCbCrCoefficients'ı alır veya ayarlar. |
| [isTiled()](#isTiled--) | Görüntünün döşenmiş olup olmadığını gösteren değeri alır. |
| [getArtist()](#getArtist--) | Sanatçıyı alır veya ayarlar. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sanatçıyı alır veya ayarlar. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Etiketin seçeneklerde bulunup bulunmadığını belirler. |
| [getByteOrder()](#getByteOrder--) | TIFF bayt sırasını gösteren değeri alır veya ayarlar. |
| [setByteOrder(int value)](#setByteOrder-int-) | TIFF bayt sırasını gösteren değeri alır veya ayarlar. |
| [getIccProfile()](#getIccProfile--) | icc profil akışını alır. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | icc profil akışını ayarlar. |
| [isDisableIccExport()](#isDisableIccExport--) | ICC profil dışa aktarımının devre dışı bırakılıp bırakılmadığını gösteren değeri alır (ICC profil önceden kaynak piksellere uygulanır). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | ICC profil dışa aktarımının devre dışı bırakılıp bırakılmadığını gösteren değeri ayarlar (ICC profil önceden kaynak piksellere uygulanır). |
| [getBitsPerSample()](#getBitsPerSample--) | Örnek başına bit sayısını alır. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Örnek başına bit sayısını ayarlar. |
| [getExtraSamples()](#getExtraSamples--) | Ek örnek değerlerini alır. |
| [getCompression()](#getCompression--) | Sıkıştırmayı alır. |
| [setCompression(int value)](#setCompression-int-) | Sıkıştırmayı ayarlar. |
| [getCompressedQuality()](#getCompressedQuality--) | Sıkıştırılmış görüntü kalitesini alır. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Sıkıştırılmış görüntü kalitesini ayarlar. |
| [getCopyright()](#getCopyright--) | Telif hakkını alır. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Telif hakkını ayarlar. |
| [getColorMap()](#getColorMap--) | Renk haritasını alır veya ayarlar. |
| [setColorMap(int[] value)](#setColorMap-int---) | Renk haritasını alır veya ayarlar. |
| [getPalette()](#getPalette--) | Renk paletini alır veya ayarlar. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Renk paletini alır veya ayarlar. |
| [getDateTime()](#getDateTime--) | Tarih ve saati alır veya ayarlar. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Tarih ve saati alır veya ayarlar. |
| [getDocumentName()](#getDocumentName--) | Belgenin adını alır veya ayarlar. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Belgenin adını alır veya ayarlar. |
| [getAlphaStorage()](#getAlphaStorage--) | Alfa depolama seçeneğini alır veya ayarlar. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Alfa depolama seçeneğini alır veya ayarlar. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Ek örneklerin mevcut olup olmadığını gösteren bir değeri alır. |
| [getFillOrder()](#getFillOrder--) | Bayt bitlerinin doldurma sırasını alır veya ayarlar. |
| [setFillOrder(int value)](#setFillOrder-int-) | Bayt bitlerinin doldurma sırasını alır veya ayarlar. |
| [getHalfToneHints()](#getHalfToneHints--) | Yarı ton ipuçlarını alır veya ayarlar. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Yarı ton ipuçlarını alır veya ayarlar. |
| [getImageDescription()](#getImageDescription--) | Görüntü açıklamasını alır veya ayarlar. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Görüntü açıklamasını alır veya ayarlar. |
| [getInkNames()](#getInkNames--) | Mürekkep adlarını alır veya ayarlar. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Mürekkep adlarını alır veya ayarlar. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Tarayıcı üreticisini alır veya ayarlar. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Tarayıcı üreticisini alır veya ayarlar. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Azami örnek değerini alır veya ayarlar. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Azami örnek değerini alır veya ayarlar. |
| [getMinSampleValue()](#getMinSampleValue--) | Asgari örnek değerini alır veya ayarlar. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Asgari örnek değerini alır veya ayarlar. |
| [getScannerModel()](#getScannerModel--) | Tarayıcı modelini alır veya ayarlar. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Tarayıcı modelini alır veya ayarlar. |
| [getOrientation()](#getOrientation--) | Yönlendirmeyi alır veya ayarlar. |
| [setOrientation(int value)](#setOrientation-int-) | Yönlendirmeyi alır veya ayarlar. |
| [getPageName()](#getPageName--) | Sayfa adını alır veya ayarlar. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Sayfa adını alır veya ayarlar. |
| [getPageNumber()](#getPageNumber--) | Sayfa numarası etiketini alır veya ayarlar. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Sayfa numarası etiketini alır veya ayarlar. |
| [getPhotometric()](#getPhotometric--) | Fotometrik değerini alır veya ayarlar. |
| [setPhotometric(int value)](#setPhotometric-int-) | Fotometrik değerini alır veya ayarlar. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Planar yapılandırmayı alır veya ayarlar. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Planar yapılandırmayı alır veya ayarlar. |
| [getResolutionUnit()](#getResolutionUnit--) | Çözünürlük birimini alır veya ayarlar. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Çözünürlük birimini alır veya ayarlar. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Şerit başına satır sayısını alır veya ayarlar. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Şerit başına satır sayısını alır veya ayarlar. |
| [getTileWidth()](#getTileWidth--) | Döşeme genişliğini alır veya ayarlar. |
| [setTileWidth(long value)](#setTileWidth-long-) | Döşeme genişliğini alır veya ayarlar. |
| [getTileLength()](#getTileLength--) | Döşeme uzunluğunu alır veya ayarlar. |
| [setTileLength(long value)](#setTileLength-long-) | Döşeme uzunluğunu alır veya ayarlar. |
| [getSampleFormat()](#getSampleFormat--) | Örnek biçimini alır veya ayarlar. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Örnek biçimini alır veya ayarlar. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Piksel başına örnekleri alır. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Azami örnek değerini alır veya ayarlar. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Azami örnek değerini alır veya ayarlar. |
| [getSminSampleValue()](#getSminSampleValue--) | Asgari örnek değerini alır veya ayarlar. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Asgari örnek değerini alır veya ayarlar. |
| [getSoftwareType()](#getSoftwareType--) | Yazılım türünü alır veya ayarlar. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Yazılım türünü alır veya ayarlar. |
| [getStripByteCounts()](#getStripByteCounts--) | Şerit bayt sayımlarını alır veya ayarlar. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Şerit bayt sayımlarını alır veya ayarlar. |
| [getStripOffsets()](#getStripOffsets--) | Şerit ofsetlerini alır veya ayarlar. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Şerit ofsetlerini alır veya ayarlar. |
| [getTileByteCounts()](#getTileByteCounts--) | Döşeme bayt sayılarını alır veya ayarlar. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Döşeme bayt sayılarını alır veya ayarlar. |
| [getTileOffsets()](#getTileOffsets--) | Döşeme ofsetlerini alır veya ayarlar. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Döşeme ofsetlerini alır veya ayarlar. |
| [getSubFileType()](#getSubFileType--) | Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar. |
| [setSubFileType(long value)](#setSubFileType-long-) | Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar. |
| [getTargetPrinter()](#getTargetPrinter--) | Hedef yazıcıyı alır veya ayarlar. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Hedef yazıcıyı alır veya ayarlar. |
| [getThreshholding()](#getThreshholding--) | Eşikleme değerini alır veya ayarlar. |
| [setThreshholding(int value)](#setThreshholding-int-) | Eşikleme değerini alır veya ayarlar. |
| [getTotalPages()](#getTotalPages--) | Toplam sayfaları alır. |
| [getXposition()](#getXposition--) | X konumunu alır veya ayarlar. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | X konumunu alır veya ayarlar. |
| [getResolutionSettings()](#getResolutionSettings--) | Çözünürlük ayarlarını alır veya ayarlar. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | Çözünürlük ayarlarını alır veya ayarlar. |
| [getXresolution()](#getXresolution--) | X çözünürlüğünü alır veya ayarlar. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | X çözünürlüğünü alır veya ayarlar. |
| [getYposition()](#getYposition--) | Y konumunu alır veya ayarlar. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | Y konumunu alır veya ayarlar. |
| [getYresolution()](#getYresolution--) | Y çözünürlüğünü alır veya ayarlar. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Y çözünürlüğünü alır veya ayarlar. |
| [getFaxT4Options()](#getFaxT4Options--) | Faks t4 seçeneklerini alır veya ayarlar. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Faks t4 seçeneklerini alır veya ayarlar. |
| [getPredictor()](#getPredictor--) | LZW sıkıştırması için öngörücüyü alır veya ayarlar. |
| [setPredictor(int value)](#setPredictor-int-) | LZW sıkıştırması için öngörücüyü alır veya ayarlar. |
| [getImageLength()](#getImageLength--) | Görüntü uzunluğunu alır veya ayarlar. |
| [setImageLength(long value)](#setImageLength-long-) | Görüntü uzunluğunu alır veya ayarlar. |
| [getImageWidth()](#getImageWidth--) | Görüntü genişliğini alır veya ayarlar. |
| [setImageWidth(long value)](#setImageWidth-long-) | Görüntü genişliğini alır veya ayarlar. |
| [getExifIfd()](#getExifIfd--) | EXIF IFD'ye işaretçiyi alır veya ayarlar. |
| [getTags()](#getTags--) | Etiketleri alır veya ayarlar. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Etiketleri alır veya ayarlar. |
| [getValidTagCount()](#getValidTagCount--) | Geçerli etiket sayısını alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Piksel başına bit sayısını alır. |
| [getXPTitle()](#getXPTitle--) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi ayarlar. |
| [getXPComment()](#getXPComment--) | Windows Gezgini tarafından kullanılan görüntüye ilişkin yorumu alır. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntüye ilişkin yorumu ayarlar. |
| [getXPAuthor()](#getXPAuthor--) | Windows Gezgini tarafından kullanılan görüntünün yazarını alır. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntünün yazarını ayarlar. |
| [getXPKeywords()](#getXPKeywords--) | Windows Gezgini tarafından kullanılan görüntünün konusunu alır. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Windows Gezgini tarafından kullanılan konu görüntüsünü ayarlar. |
| [getXPSubject()](#getXPSubject--) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi ayarlar. |
| [getExifData()](#getExifData--) | Exif verilerini alır. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Exif verisini ayarlar. |
| [removeTag(int tag)](#removeTag-int-) | Etiketi kaldırır. |
| [removeTags(int[] tags)](#removeTags-int...-) | Etiketleri kaldırır. |
| [validate()](#validate--) | Seçeneklerin geçerli etiket kombinasyonuna sahip olup olmadığını doğrular |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Etiketleri ekler. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Yeni bir etiket ekler. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Etiketin türüne göre örneğini alır. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Bu örnek, dışa aktarma amaçları için SaveOptions ad alanındaki farklı sınıfların kullanımını gösterir. Gif türünde bir görüntü, Image sınıfının bir örneğine yüklenir ve ardından çeşitli formatlara dışa aktarılır.
``` java
String dir = "c:\\temp\\";

//Image sınıfının bir örneğine mevcut bir görüntüyü (Gif türünde) yükleyin
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Varsayılan seçenekleri kullanarak BMP dosya formatına dışa aktar
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya formatına dışa aktar
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak PNG dosya formatına dışa aktar
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya formatına dışa aktar
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Sadece ilk iki sayfayı dışa aktar. Bu sayfalar çıktı TIFF'inde çerçeve olarak sunulacak.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Yeni bir `TiffOptions` sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expectedFormat | int | Beklenen tiff dosya formatı. |
| byteOrder | int | tiff dosya formatı bayt sırası. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


`TiffOptions` sınıfının yeni bir örneğini başlatır. Varsayılan olarak, küçük endian kuralı kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| expectedFormat | int | Beklenen tiff dosya formatı. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Yeni bir `TiffOptions` sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Kopyalanacak seçenekler. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Yeni bir `TiffOptions` sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Seçenekleri başlatmak için kullanılacak etiketler. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Geçerli etiket sayısını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Doğrulanacak etiketler. |

**Returns:**
int - Geçerli etiket sayısı.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


Etiket sayısını alır.

**Returns:**
int - etiket sayısı.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


TIFF dosya standardını alır veya ayarlar.

**Returns:**
int - TIFF dosya standardı.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


TIFF dosya standardını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | TIFF dosya standardı. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Varsayılan bellek tahsis sınırını alır veya ayarlar.

**Returns:**
int - Varsayılan bellek tahsis sınırı.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Varsayılan bellek tahsis sınırını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Varsayılan bellek tahsis sınırı. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren değeri alır veya ayarlar.

**Returns:**
boolean - bileşenlerin ön çarpılması gerekiyorsa `true`; aksi takdirde `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` bileşenlerin ön çarpılması gerekiyorsa; aksi takdirde `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


`TiffOptions`'ın doğru yapılandırılıp yapılandırılmadığını gösteren bir değer alır. Hata nedenini bulmak için Validate yöntemini kullanın.

**Returns:**
boolean - TiffOptions doğru yapılandırılmışsa `true`; aksi takdirde `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar.

**Returns:**
int[] - YCbCr fotometrik için alt örnekleme faktörleri.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | YCbCr fotometrik için alt örnekleme faktörleri. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarla.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Big Endian bayt sırasını (Motorola) ayarla.
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// LZW sıkıştırmasını ayarla.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Sürekli tonlu görüntülerin boyutunu azaltmaya izin verir.
// Şu anda bu alan yalnızca LZW kodlamasıyla kullanılıyor çünkü LZW muhtemelen tek TIFF kodlama şemasıdır.
// bu, tahmin adımından önemli ölçüde fayda sağlar.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// RGB renk modelini ayarla.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// YCbCr için aşağıdaki seçeneklerden birini kullanabilirsiniz:
// YCbCrSubSampling alanı   JPEG örnekleme faktörleri
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(varsayılan değer)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tüm renk bileşenleri tek bir düzlemde saklanacak.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 100x100 piksel bir TIFF Çerçevesi oluştur.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Tüm görüntüyü mavi-sarı degrade ile doldur.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


YCbCrCoefficients'ı alır veya ayarlar.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - YCbCr Katsayıları.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


YCbCrCoefficients'ı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | YCbCr Katsayıları. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Görüntünün döşenmiş olup olmadığını gösteren değeri alır.

**Returns:**
boolean - `true` if image is tiled; otherwise, `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Sanatçıyı alır veya ayarlar.

**Returns:**
java.lang.String - Sanatçı.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Sanatçıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Sanatçı. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Etiketin seçeneklerde bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| etiket | int | Kontrol edilecek etiket kimliği. |

**Returns:**
boolean - `true` if tag is present; otherwise, `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


TIFF bayt sırasını gösteren değeri alır veya ayarlar.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


TIFF bayt sırasını gösteren değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarla.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Big Endian bayt sırasını (Motorola) ayarla.
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// LZW sıkıştırmasını ayarla.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Sürekli tonlu görüntülerin boyutunu azaltmaya izin verir.
// Şu anda bu alan yalnızca LZW kodlamasıyla kullanılıyor çünkü LZW muhtemelen tek TIFF kodlama şemasıdır.
// bu, tahmin adımından önemli ölçüde fayda sağlar.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// RGB renk modelini ayarla.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// YCbCr için aşağıdaki seçeneklerden birini kullanabilirsiniz:
// YCbCrSubSampling alanı   JPEG örnekleme faktörleri
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(varsayılan değer)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tüm renk bileşenleri tek bir düzlemde saklanacak.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 100x100 piksel bir TIFF Çerçevesi oluştur.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Tüm görüntüyü mavi-sarı degrade ile doldur.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


icc profil akışını alır.

**Returns:**
byte[] - icc profili.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


icc profil akışını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] | icc profili. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


ICC profil dışa aktarımının devre dışı bırakılıp bırakılmadığını gösteren değeri alır (ICC profil önceden kaynak piksellere uygulanır).

**Returns:**
boolean - ICC profilinin dışa aktarımının devre dışı bırakılıp bırakılmadığını gösteren değer (ICC profili önceden kaynak piksellere uygulanır).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


ICC profil dışa aktarımının devre dışı bırakılıp bırakılmadığını gösteren değeri ayarlar (ICC profil önceden kaynak piksellere uygulanır).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | ICC profilinin dışa aktarımının devre dışı bırakılıp bırakılmadığını gösteren değer (ICC profili önceden kaynak piksellere uygulanır). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Örnek başına bit sayısını alır.

**Returns:**
int[] - Örnek başına bit değeri.

Bu değeri ayarlarken, aynı zamanda SamplesPerPixel değerinin dizi uzunluğuna ayarlanacağını unutmayın. Bu iki özellik çok sıkı bir şekilde bağlanmıştır, bu yüzden yalnızca birlikte ayarlanabilirler.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Örnek başına bit sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int[] | Örnek başına bit değeri. |

Bu değeri ayarlarken, aynı zamanda SamplesPerPixel değerinin dizi uzunluğuna ayarlanacağını unutmayın. Bu iki özellik çok sıkı bir şekilde bağlanmıştır, bu yüzden yalnızca birlikte ayarlanabilirler. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Kalıcı, geçici olmayan bir dosya kaynağı oluştur.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Görüntünün sol üst köşesinden sağ alt köşesine doğru lineer degrade.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Aktif çerçeveyi lineer degrade fırçası ile doldur.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Gri tonlama seçenekleri
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Aktif çerçevenin gri tonlamalı bir kopyasını oluştur.
    // Piksel verileri korunur ancak istenen formata dönüştürülür.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Yeni oluşturulan çerçeveyi TIFF görüntüsüne ekle.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


Ek örnek değerlerini alır.

Değer: Ek örnek değeri.

**Returns:**
int[] - ek örnek değerleri.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Sıkıştırmayı alır.

**Returns:**
int - Sıkıştırma.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Sıkıştırmayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Sıkıştırma. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// İlk çerçeve için seçenekler
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarla.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// Big Endian bayt sırasını (Motorola) ayarla.
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// LZW sıkıştırmasını ayarla.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// RGB renk modelini ayarla.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Tüm renk bileşenleri tek bir düzlemde saklanacak.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 100x100 piksel ilk TIFF çerçevesini oluştur.
// Çerçeveler TiffImage içine dahil edildiğinde, çerçeveleri açıkça yok etmeniz gerekmediğini unutmayın.
// Konteyner yok edildiğinde tüm çerçeveler otomatik olarak yok edilecektir.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// İlk çerçeveyi mavi-sarı degrade ile doldurun.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// İlk çerçeve için seçenekler
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Siyah/beyaz görüntü için piksel başına 1 bit ayarlayın.
createOptions2.setBitsPerSample(new int[]{1});

// Little Endian bayt sırasını (Intel) ayarlayın.
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// CCITT Group 3 Fax sıkıştırmasını ayarlayın.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// 0'ın siyah, 1'in beyaz olduğu B/W renk modelini ayarlayın.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// 200x200 piksel ikinci TIFF çerçevesini oluştur.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// İkinci çerçeveyi mavi-sarı degrade ile doldurun.
// Çerçevenin ilgili ayarları nedeniyle otomatik olarak B/W formatına dönüştürülecek.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// Bir TIFF görüntüsü oluştur.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Sıkıştırılmış görüntü kalitesini alır. Jpeg sıkıştırmasıyla kullanılır.

**Returns:**
int - sıkıştırılmış görüntü kalitesi.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Sıkıştırılmış görüntü kalitesini ayarlar. Jpeg sıkıştırmasıyla kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | sıkıştırılmış görüntü kalitesi. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // RGB renk modelini ayarla.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // Jpeg sıkıştırmasını ayarlayın.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // Her renk bileşeni için 8 bit ayarla.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Telif hakkını alır.

**Returns:**
java.lang.String - Telif hakkı.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Telif hakkını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Telif hakkı. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Renk haritasını alır veya ayarlar.

**Returns:**
int[] - renk haritası.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Renk haritasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Renk haritası. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Renk paletini alır veya ayarlar.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Renk paletini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Tarih ve saati alır veya ayarlar.

**Returns:**
java.lang.String - tarih ve saat.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Tarih ve saati alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Tarih ve saat. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Belgenin adını alır veya ayarlar.

**Returns:**
java.lang.String - belgenin adı.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Belgenin adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Belgenin adı. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Alfa depolama seçeneğini alır veya ayarlar. `TiffAlphaStorage.Unspecified` dışındaki seçenekler, 3'ten fazla `SamplesPerPixel` tanımlandığında kullanılır.

**Returns:**
int - Alfa depolama seçeneği.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Alfa depolama seçeneğini alır veya ayarlar. `TiffAlphaStorage.Unspecified` dışındaki seçenekler, 3'ten fazla `SamplesPerPixel` tanımlandığında kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Alfa depolama seçeneği. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Ek örneklerin mevcut olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - `true` ekstra örnekler mevcutsa; aksi takdirde `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Bayt bitlerinin doldurma sırasını alır veya ayarlar.

**Returns:**
int - Bayt bitlerinin doldurma sırası.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Bayt bitlerinin doldurma sırasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bayt bitlerinin doldurma sırası. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Yarı ton ipuçlarını alır veya ayarlar.

**Returns:**
int[] - Yarı ton ipuçları.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Yarı ton ipuçlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Yarı ton ipuçları. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Görüntü açıklamasını alır veya ayarlar.

**Returns:**
java.lang.String - Görüntü açıklaması.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Görüntü açıklamasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Görüntü açıklaması. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Mürekkep adlarını alır veya ayarlar.

**Returns:**
java.lang.String - Mürekkep adları.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Mürekkep adlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Mürekkep adları. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Tarayıcı üreticisini alır veya ayarlar.

**Returns:**
java.lang.String - Tarayıcı üreticisi.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Tarayıcı üreticisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Tarayıcı üreticisi. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Azami örnek değerini alır veya ayarlar.

**Returns:**
int[] - Azami örnek değeri.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Azami örnek değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Azami örnek değeri. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Asgari örnek değerini alır veya ayarlar.

**Returns:**
int[] - Asgari örnek değeri.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Asgari örnek değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Asgari örnek değeri. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Tarayıcı modelini alır veya ayarlar.

**Returns:**
java.lang.String - Tarayıcı modeli.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Tarayıcı modelini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Tarayıcı modeli. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Yönlendirmeyi alır veya ayarlar.

**Returns:**
int - Yönlendirme [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Yönlendirmeyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int | Yönlendirme [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


Sayfa adını alır veya ayarlar.

**Returns:**
java.lang.String - Sayfa adı.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Sayfa adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Sayfa adı. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Sayfa numarası etiketini alır veya ayarlar.

**Returns:**
int[] - Sayfa numarası etiketi.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Sayfa numarası etiketini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Sayfa numarası etiketi. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Fotometrik değerini alır veya ayarlar.

**Returns:**
int - Fotometrik.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Fotometrik değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Fotometrik. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Kalıcı, geçici olmayan bir dosya kaynağı oluştur.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Görüntünün sol üst köşesinden sağ alt köşesine doğru lineer degrade.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Aktif çerçeveyi lineer degrade fırçası ile doldur.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Gri tonlama seçenekleri
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Aktif çerçevenin gri tonlamalı bir kopyasını oluştur.
    // Piksel verileri korunur ancak istenen formata dönüştürülür.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Yeni oluşturulan çerçeveyi TIFF görüntüsüne ekle.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Planar yapılandırmayı alır veya ayarlar.

**Returns:**
int - Düzlemsel yapılandırma.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Planar yapılandırmayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Düzlemsel yapılandırma. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarla.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Big Endian bayt sırasını (Motorola) ayarla.
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// LZW sıkıştırmasını ayarla.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// RGB renk modelini ayarla.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Tüm renk bileşenleri tek bir düzlemde saklanacak.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 100x100 piksel bir TIFF Çerçevesi oluştur.
// Bir çerçeve TiffImage içine dahil edilmişse, onu açıkça yok etmeniz gerekmediğini unutmayın.
// Konteyner yok edildiğinde tüm çerçeveler otomatik olarak yok edilecektir.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Tüm çerçeveyi mavi‑sarı degrade ile doldur.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Bir TIFF görüntüsü oluştur.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Çözünürlük birimini alır veya ayarlar.

**Returns:**
int - Çözünürlük birimi.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Çözünürlük birimini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Çözünürlük birimi. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Şerit başına satır sayısını alır veya ayarlar.

**Returns:**
long - Şerit başına satır sayısı.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Şerit başına satır sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Şerit başına satır sayısı. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Döşeme genişliğini alır veya ayarlar.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Döşeme genişliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Döşeme uzunluğunu alır veya ayarlar.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Döşeme uzunluğunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Örnek biçimini alır veya ayarlar.

**Returns:**
int[] - Örnek formatı.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Örnek biçimini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] | Örnek formatı. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Piksel başına örnekleri alır. Bu özellik değerini değiştirmek için `BitsPerSample` özelliği ayarlayıcısını kullanın.

**Returns:**
int - Piksel başına örnek sayısı.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Maksimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Returns:**
long[] - Maksimum örnek değeri.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Maksimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Azami örnek değeri. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Minimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Returns:**
long[] - Minimum örnek değeri.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Minimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Asgari örnek değeri. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Yazılım türünü alır veya ayarlar.

**Returns:**
java.lang.String - Yazılım türü.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Yazılım türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yazılım türü. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Şerit bayt sayımlarını alır veya ayarlar.

**Returns:**
long[] - Şerit bayt sayıları.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Şerit bayt sayımlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Şerit bayt sayıları. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Şerit ofsetlerini alır veya ayarlar.

**Returns:**
long[] - Şerit ofsetleri.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Şerit ofsetlerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] | Şerit ofsetleri. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Döşeme bayt sayılarını alır veya ayarlar.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Döşeme bayt sayılarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Döşeme ofsetlerini alır veya ayarlar.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Döşeme ofsetlerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar.

**Returns:**
long - Bu alt dosyada bulunan veri türünün genel göstergesi.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Bu alt dosyada bulunan veri türünün genel göstergesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Bu alt dosyada bulunan veri türünün genel göstergesi. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Hedef yazıcıyı alır veya ayarlar.

**Returns:**
java.lang.String - Hedef yazıcı.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Hedef yazıcıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Hedef yazıcı. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Eşikleme değerini alır veya ayarlar.

**Returns:**
int - Eşikleme.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Eşikleme değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Eşikleme. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Toplam sayfaları alır.

**Returns:**
int - Toplam sayfalar.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


X konumunu alır veya ayarlar.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


X konumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | x konumu. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Çözünürlük ayarlarını alır veya ayarlar.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Çözünürlük ayarlarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


X çözünürlüğünü alır veya ayarlar.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


X çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | x çözünürlüğü. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Y konumunu alır veya ayarlar.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Y konumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | y konumu. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Y çözünürlüğünü alır veya ayarlar.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Y çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | y çözünürlüğü. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Faks t4 seçeneklerini alır veya ayarlar.

**Returns:**
long - Fax t4 seçenekleri.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Faks t4 seçeneklerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Fax t4 seçenekleri. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


LZW sıkıştırması için öngörücüyü alır veya ayarlar.

**Returns:**
int - Tahminci türü.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


LZW sıkıştırması için öngörücüyü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Tahminci türü. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarla.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// Big Endian bayt sırasını (Motorola) ayarla.
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// LZW sıkıştırmasını ayarla.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Sürekli tonlu görüntülerin boyutunu azaltmaya izin verir.
// Şu anda bu alan yalnızca LZW kodlamasıyla kullanılıyor çünkü LZW muhtemelen tek TIFF kodlama şemasıdır.
// bu, tahmin adımından önemli ölçüde fayda sağlar.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// RGB renk modelini ayarla.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// YCbCr için aşağıdaki seçeneklerden birini kullanabilirsiniz:
// YCbCrSubSampling alanı   JPEG örnekleme faktörleri
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(varsayılan değer)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// Tüm renk bileşenleri tek bir düzlemde saklanacak.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 100x100 piksel bir TIFF Çerçevesi oluştur.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Tüm görüntüyü mavi-sarı degrade ile doldur.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Görüntü uzunluğunu alır veya ayarlar.

**Returns:**
long - Görüntü uzunluğu.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Görüntü uzunluğunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Görüntü uzunluğu. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Görüntü genişliğini alır veya ayarlar.

**Returns:**
long - Görüntü genişliği.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Görüntü genişliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | Görüntünün genişliği. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


EXIF IFD'ye işaretçiyi alır veya ayarlar.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Etiketleri alır veya ayarlar.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - Etiketler.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Etiketleri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Etiketler. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Geçerli etiket sayısını alır. Bu, toplam etiket sayısı değil, korunabilecek etiketlerin sayısıdır.

**Returns:**
int - Geçerli etiket sayısı.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Piksel başına bit sayısını alır.

**Returns:**
int - Piksel başına bit sayısı.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır.

Değer: Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır. `XPTitle`(`\#getXPTitle`/\#setXPTitle(String).setXPTitle(String)) Windows Explorer tarafından, `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) etiketi mevcutsa yok sayılır.

**Returns:**
java.lang.String - görüntü hakkında bilgi, Windows Explorer tarafından kullanılan.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgi ayarlar.

Değer: Görüntü hakkında bilgi, Windows Explorer tarafından kullanılır. `XPTitle`(\#getXPTitle.getXPTitle/`\#setXPTitle(String)`) Windows Explorer tarafından, `ImageDescription`(\#getImageDescription.getImageDescription/\#setImageDescription(String).setImageDescription(String)) etiketi mevcutsa yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntü hakkında bilgi, Windows Explorer tarafından kullanılan. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Windows Gezgini tarafından kullanılan görüntüye ilişkin yorumu alır.

Değer: Görüntü üzerine yorum, Windows Explorer tarafından kullanılır.

**Returns:**
java.lang.String - görüntü üzerine yorum, Windows Explorer tarafından kullanılan.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Windows Gezgini tarafından kullanılan görüntüye ilişkin yorumu ayarlar.

Değer: Görüntü üzerine yorum, Windows Explorer tarafından kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Windows Gezgini tarafından kullanılan görüntüye yorum. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Windows Gezgini tarafından kullanılan görüntünün yazarını alır.

Değer: Görüntü Yazarı, Windows Gezgini tarafından kullanılır. `XPAuthor`(`\#getXPAuthor`/\#setXPAuthor(String).setXPAuthor(String)) etiketi, `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) etiketi mevcutsa Windows Gezgini tarafından yok sayılır.

**Returns:**
java.lang.String - görüntü yazarı, Windows Gezgini tarafından kullanılır.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Windows Gezgini tarafından kullanılan görüntünün yazarını ayarlar.

Değer: Görüntü Yazarı, Windows Gezgini tarafından kullanılır. `XPAuthor`(\#getXPAuthor.getXPAuthor/`\#setXPAuthor(String)`) etiketi, `Artist`(\#getArtist.getArtist/\#setArtist(String).setArtist(String)) etiketi mevcutsa Windows Gezgini tarafından yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntü yazarı, Windows Gezgini tarafından kullanılır. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Windows Gezgini tarafından kullanılan görüntünün konusunu alır.

Değer: Konu görüntüsü, Windows Gezgini tarafından kullanılır.

**Returns:**
java.lang.String - konu görüntüsü, Windows Gezgini tarafından kullanılır.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Windows Gezgini tarafından kullanılan konu görüntüsünü ayarlar.

Değer: Konu görüntüsü, Windows Gezgini tarafından kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | konu görüntüsü, Windows Gezgini tarafından kullanılır. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır.

Değer: Görüntü hakkında bilgi, Windows Gezgini tarafından kullanılır.

**Returns:**
java.lang.String - görüntü hakkında bilgi, Windows Explorer tarafından kullanılan.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Windows Gezgini tarafından kullanılan görüntü hakkında bilgi ayarlar.

Değer: Görüntü hakkında bilgi, Windows Gezgini tarafından kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntü hakkında bilgi, Windows Explorer tarafından kullanılan. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Exif verilerini alır.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Exif verisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif verileri. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Etiketi kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| etiket | int | Kaldırılacak etiket. |

**Returns:**
boolean - başarılı bir şekilde kaldırıldıysa true
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


Etiketleri kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| etiketler | int[] | Kaldırılacak etiketler. |

**Returns:**
boolean - `` eğer etiket koleksiyonu boyutu değiştiyse.
### validate() {#validate--}
```
public void validate()
```


Seçeneklerin geçerli etiket kombinasyonuna sahip olup olmadığını doğrular

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Etiketleri ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Eklenecek etiketler. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Yeni bir etiket ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Eklenecek etiket. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Etiketin türüne göre örneğini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagKey | int | Etiket anahtarı. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
