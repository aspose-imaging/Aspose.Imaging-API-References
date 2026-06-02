---
title: "DicomPage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Это класс для работы с файлами DICOM типа multi frame."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

Это класс для работы с файлами DICOM типа multi frame.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | Инициализирует новый экземпляр класса `DicomPage`. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | Инициализирует новый экземпляр класса `DicomPage`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIndex()](#getIndex--) | Получает индекс текущей страницы. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getFileFormat()](#getFileFormat--) | Получает значение формата файла |

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
        // Нарисуйте что‑нибудь с помощью векторной графики.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Сохраните пиксели нарисованного изображения. Они теперь находятся на первой странице изображения Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Добавьте несколько страниц после, сделав их темнее.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Добавьте несколько страниц перед основной страницей, сделав их ярче.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Сохраните созданное многостраничное изображение в выходной файл.
        image.save("MultiPage.dcm");
    }
}
```

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


Инициализирует новый экземпляр класса `DicomPage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Изображение. |
| index | int | Индекс. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


Инициализирует новый экземпляр класса `DicomPage`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Изображение. |
| index | int | Индекс. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Получает индекс текущей страницы.

Значение: индекс.

**Returns:**
int — индекс текущей страницы.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

Значение: ширина изображения.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

Значение: высота изображения.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

Значение: количество бит на пиксель изображения.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получает значение формата файла

**Returns:**
long
