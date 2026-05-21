---
title: "PdfOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры PDF."
type: docs
weight: 36
url: /ru/java/com.aspose.imaging.imageoptions/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PdfOptions extends ImageOptionsBase
```

Параметры PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Инициализирует новый экземпляр класса [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [isUseOriginalImageResolution()](#isUseOriginalImageResolution--) | Возвращает значение, указывающее использовать оригинальное разрешение DPI изображения |
| [setUseOriginalImageResolution(boolean value)](#setUseOriginalImageResolution-boolean-) | Устанавливает значение, указывающее использовать оригинальное разрешение DPI изображения |
| [getPdfDocumentInfo()](#getPdfDocumentInfo--) | Получает или задает метаданные документа. |
| [setPdfDocumentInfo(PdfDocumentInfo value)](#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-) | Получает или задает метаданные документа. |
| [getPdfCoreOptions()](#getPdfCoreOptions--) | Основные параметры PDF |
| [setPdfCoreOptions(PdfCoreOptions value)](#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-) | Основные параметры PDF |
| [getPageSize()](#getPageSize--) | Возвращает размер страницы. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Устанавливает размер страницы. |
| [isUseOriginalImageSize()](#isUseOriginalImageSize--) | Возвращает значение, указывающее использовать оригинальное разрешение DPI изображения |
| [setUseOriginalImageSize(boolean useOriginalImageSize)](#setUseOriginalImageSize-boolean-) | Устанавливает значение, указывающее использовать оригинальное разрешение DPI изображения. БУДЕТ УДАЛЕНО С НОМЕРА 25.3 |

## Example: The following example shows how to convert a multipage vector image to PDF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.pdf");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PdfOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы в соответствующие страницы выходного PDF‑документа.
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

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Инициализирует новый экземпляр класса [PdfOptions](../../com.aspose.imaging.imageoptions/pdfoptions).

### isUseOriginalImageResolution() {#isUseOriginalImageResolution--}
```
public final boolean isUseOriginalImageResolution()
```


Возвращает значение, указывающее использовать оригинальное разрешение DPI изображения

Значение: Индикатор использования оригинального разрешения DPI изображения

**Returns:**
boolean — значение, указывающее использовать оригинальное разрешение DPI изображения
### setUseOriginalImageResolution(boolean value) {#setUseOriginalImageResolution-boolean-}
```
public final void setUseOriginalImageResolution(boolean value)
```


Устанавливает значение, указывающее использовать оригинальное разрешение DPI изображения

Значение: Индикатор использования оригинального разрешения DPI изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее использовать оригинальное разрешение DPI изображения |

### getPdfDocumentInfo() {#getPdfDocumentInfo--}
```
public PdfDocumentInfo getPdfDocumentInfo()
```


Получает или задает метаданные документа.

**Returns:**
[PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo)
### setPdfDocumentInfo(PdfDocumentInfo value) {#setPdfDocumentInfo-com.aspose.imaging.fileformats.pdf.PdfDocumentInfo-}
```
public void setPdfDocumentInfo(PdfDocumentInfo value)
```


Получает или задает метаданные документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfDocumentInfo](../../com.aspose.imaging.fileformats.pdf/pdfdocumentinfo) |  |

### getPdfCoreOptions() {#getPdfCoreOptions--}
```
public PdfCoreOptions getPdfCoreOptions()
```


Основные параметры PDF

**Returns:**
[PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions)
### setPdfCoreOptions(PdfCoreOptions value) {#setPdfCoreOptions-com.aspose.imaging.fileformats.pdf.PdfCoreOptions-}
```
public void setPdfCoreOptions(PdfCoreOptions value)
```


Основные параметры PDF

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfCoreOptions](../../com.aspose.imaging.fileformats.pdf/pdfcoreoptions) |  |

### getPageSize() {#getPageSize--}
```
public final SizeF getPageSize()
```


Возвращает размер страницы.

Значение: Размер страницы.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the size of the page.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public final void setPageSize(SizeF value)
```


Устанавливает размер страницы.

Значение: Размер страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | размер страницы. |

### isUseOriginalImageSize() {#isUseOriginalImageSize--}
```
public boolean isUseOriginalImageSize()
```


Возвращает значение, указывающее использовать оригинальное разрешение DPI изображения

Значение: Индикатор использования оригинального разрешения DPI изображения

**Returns:**
boolean — значение, указывающее использовать оригинальное разрешение DPI изображения
### setUseOriginalImageSize(boolean useOriginalImageSize) {#setUseOriginalImageSize-boolean-}
```
public void setUseOriginalImageSize(boolean useOriginalImageSize)
```


Устанавливает значение, указывающее использовать оригинальное разрешение DPI изображения. БУДЕТ УДАЛЕНО С НОМЕРА 25.3

Значение: Индикатор использования оригинального разрешения DPI изображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| useOriginalImageSize | boolean | значение, указывающее использовать оригинальное разрешение DPI изображения |

