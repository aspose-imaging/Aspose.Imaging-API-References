---
title: "OdgImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "OpenDocument Graphic ODG vektör görüntü dosya biçimini, çizim öğelerini vektör formatında depolamak için OpenOffice ve LibreOffice Draw uygulamaları tarafından yaygın olarak kullanılan API'mizle yönetin."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

OpenDocument Graphic (ODG) vektör görüntü dosya biçimini, çizim öğelerini vektör formatında depolamak için OpenOffice ve LibreOffice Draw uygulamaları tarafından yaygın olarak kullanılan API'mizle yönetin. Belgeleri sorunsuz bir şekilde ayrıştırın, sayfalara erişin, görüntüleri yeniden boyutlandırın ve döndürün; böylece ODG dosyalarının verimli işlenmesini ve özelleştirilmesini sağlayarak belirli gereksinimlerinizi karşılayabilirsiniz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Yeni bir örnek başlatarak [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) sınıf nesnesinin yeni bir oluşturulmasını başlatın. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Yazılım çözümlerine sorunsuz entegrasyon için tasarlanmış olan [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) yapıcı, bir akış konteyneri kullanarak yeni bir örnek başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu kullanıcı dostu özellik sayesinde dosya formatı değerini kolayca alabilirsiniz. |
| [getPages()](#getPages--) | Sayfalar koleksiyonunu alırken, bu özellik bir görüntüyle ilişkili tüm sayfalara erişim sağlar. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Aspose.Imaging.Image.Load kullanmak, görüntü yüklemenin birleşik bir yoludur.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // OdgImage'e dönüştür
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Tüm sayfaları al
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Biraz görüntü işleme yapın
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Yeni bir örnek başlatarak [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) sınıf nesnesinin yeni bir oluşturulmasını başlatın. Bir akış konteyneri ile yükleme seçenekleri parametrelerini birleştirerek potansiyelini kullanın, görüntüleri sorunsuz bir şekilde yüklemek için çok yönlü bir yapıcıyı sürdürün. Bu yapıcı, verimli görüntü işleme sağlayarak çeşitli senaryolarda artırılmış uyarlanabilirlik ve performans için özelleştirilebilir yükleme yapılandırmaları sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Yazılım çözümlerine sorunsuz entegrasyon için tasarlanmış olan [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) yapıcı, bir akış konteyneri kullanarak yeni bir örnek başlatır. Bu yöntem, yazılım ortamlarında ODG görüntü verilerinin verimli bir şekilde işlenmesini sağlayarak kaynak kullanımını optimize eder ve sorunsuz görüntü işleme iş akışlarını kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Akış konteyneri. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu kullanıcı dostu özellik ile dosya formatı değerini kolayca alın. Dosya formatı hakkında bilgiye hızlı erişim isteyen geliştiriciler için idealdir.

**Returns:**
long - dosya formatı değeri
### getPages() {#getPages--}
```
public Image[] getPages()
```


Sayfalar koleksiyonunu alırken, bu özellik bir görüntüyle ilişkili tüm sayfalara erişim sağlar. Bu özelliğe erişerek, geliştiriciler bireysel sayfalar arasında iterasyon yapabilir, indekslerine göre belirli sayfaları alabilir veya tüm koleksiyon üzerinde toplu işlemler gerçekleştirebilir.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.
