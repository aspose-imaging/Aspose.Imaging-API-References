---
title: "SvgOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте файлы SVG (Scalar Vector Graphics) с помощью нашего API, используя гибкие параметры для типов цветов и уровней сжатия."
type: docs
weight: 45
url: /ru/java/com.aspose.imaging.imageoptions/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public class SvgOptions extends ImageOptionsBase implements ICompressOptions
```

Создавайте файлы SVG (Scalar Vector Graphics) с помощью нашего API, используя гибкие параметры для типов цветов и уровней сжатия. Точно настраивайте свои SVG‑изображения, обеспечивая оптимальное качество и совместимость для ваших дизайнерских задач.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgOptions()](#SvgOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getColorType()](#getColorType--) | Получает или задаёт тип цвета для SVG‑изображения. |
| [setColorType(int value)](#setColorType-int-) | Получает или задаёт тип цвета для SVG‑изображения. |
| [getTextAsShapes()](#getTextAsShapes--) | Получает значение, указывающее, должен ли текст отображаться в виде фигур. |
| [setTextAsShapes(boolean value)](#setTextAsShapes-boolean-) | Устанавливает значение, указывающее, должен ли текст отображаться в виде фигур. |
| [getCallback()](#getCallback--) | Получает стратегию хранения встроенных ресурсов [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), таких как шрифты, вложенные растр. |
| [setCallback(ISvgResourceKeeperCallback value)](#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-) | Устанавливает стратегию хранения встроенных ресурсов [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), таких как шрифты, вложенные растр. |
| [getCompress()](#getCompress--) | Получает значение, указывающее, должно ли выходное изображение быть сжато. |
| [setCompress(boolean value)](#setCompress-boolean-) | Устанавливает значение, указывающее, должно ли выходное изображение быть сжато. |

## Example: The following example shows how to convert a multipage vector image to SVG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.svg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.SvgOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Экспортировать только первые две страницы. На самом деле будет конвертирована только одна страница, поскольку SVG не является многостраничным форматом.
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


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgOptions() {#SvgOptions--}
```
public SvgOptions()
```


### getColorType() {#getColorType--}
```
public int getColorType()
```


Получает или задаёт тип цвета для SVG‑изображения.

**Returns:**
int — тип цвета SVG‑изображения.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Получает или задаёт тип цвета для SVG‑изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Тип цвета SVG‑изображения. |

### getTextAsShapes() {#getTextAsShapes--}
```
public boolean getTextAsShapes()
```


Получает значение, указывающее, должен ли текст отображаться в виде фигур.

Значение: `true`, если весь текст преобразуется в SVG‑фигуры при конвертации; иначе `false`.

**Returns:**
boolean — значение, указывающее, должен ли текст отображаться в виде фигур.
### setTextAsShapes(boolean value) {#setTextAsShapes-boolean-}
```
public void setTextAsShapes(boolean value)
```


Устанавливает значение, указывающее, должен ли текст отображаться в виде фигур.

Значение: `true`, если весь текст преобразуется в SVG‑фигуры при конвертации; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, должен ли текст отображаться в виде фигур. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Текст будет преобразован в фигуры.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Размер страницы.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Если встроенный emf существует, отобразите emf; иначе отобразите wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — это единый способ загрузки всех типов изображений, включая EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Текст будет преобразован в фигуры.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Размер страницы.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Если встроенный emf существует, отобразите emf; иначе отобразите wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Установите горизонтальный отступ
    rasterizationOptions.setBorderX(50);

    // Установите вертикальный отступ
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getCallback() {#getCallback--}
```
public ISvgResourceKeeperCallback getCallback()
```


Получает стратегию хранения встроенных ресурсов [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), таких как шрифты, вложенные растр.

**Returns:**
[ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) - the storing strategy for embedded resources of [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) such as fonts, nested rasters.
### setCallback(ISvgResourceKeeperCallback value) {#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-}
```
public void setCallback(ISvgResourceKeeperCallback value)
```


Устанавливает стратегию хранения встроенных ресурсов [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), таких как шрифты, вложенные растр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) | стратегия хранения встроенных ресурсов [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), таких как шрифты, вложенные растр. |

### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Получает значение, указывающее, должно ли выходное изображение быть сжато.

**Returns:**
boolean - значение, указывающее, должно ли выходное изображение быть сжато.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Устанавливает значение, указывающее, должно ли выходное изображение быть сжато.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, должно ли выходное изображение быть сжато. |


**Example: The following example shows how to convert a svg images to svgz format**

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

