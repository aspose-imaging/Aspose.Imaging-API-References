---
title: "SvgImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Манипулируйте файлами изображений SVG (Scalar Vector Graphics) с помощью нашего API, используя возможности XML‑текстового формата для бесшовной настройки и масштабируемости."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

Манипулируйте файлами изображений Scalar Vector Graphics (SVG) с помощью нашего API, используя возможности XML‑текстового формата для бесшовной настройки и масштабируемости. Легко загружайте SVG‑изображения, растеризуйте векторные элементы и конвертируйте их в другие форматы, контролируя уровни сжатия для оптимизации размера файла и качества в ваших проектах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Создаёт новый объект класса [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), используя указанный путь для поиска и загрузки изображения. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Создаёт новый экземпляр класса [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), загружая изображение из предоставленного потока. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Создаёт новый объект [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) с указанными шириной и высотой. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Создаёт новый экземпляр класса [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) с указанными параметрами SVG‑опций, ширины и высоты изображения. |
## Методы

| Метод | Описание |
| --- | --- |
| [isCached()](#isCached--) | Возвращает логическое значение, указывающее, кэшированы ли данные объекта в данный момент, устраняя необходимость дополнительных операций чтения данных. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Возвращает количество бит на пиксель изображения. |
| [getFileFormat()](#getFileFormat--) | Возвращает формат файла изображения, предоставляя важные метаданные для обработки и проверки совместимости. |
| [cacheData()](#cacheData--) | Кешируйте данные и гарантируйте, что дальнейшая загрузка данных из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) не произойдёт. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Измените размер изображения, чтобы соответствовать указанным размерам, сохраняя его пропорции. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезает указанный прямоугольник. |
| [rotate(float angle)](#rotate-float-) | Поворачивает изображение вокруг центра. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Применяет указанную палитру к изображению, позволяя настраивать цветовые схемы для эстетических или функциональных целей. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Загрузите SVG‑изображение из файлового потока.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // Для растеризации SVG необходимо указать параметры растеризации.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
Следующий пример показывает, как преобразовать сжатые изображения (*.emz,*.wmz, *.svgz) в растровый формат
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
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

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Создаёт новый объект класса [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), используя указанный путь для поиска и загрузки изображения. Этот конструктор упрощает создание экземпляров SVG‑изображений из внешних файлов, обеспечивая бесшовную интеграцию в программные системы и рабочие процессы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Создаёт новый экземпляр класса [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), загружая изображение из предоставленного потока. Этот конструктор позволяет напрямую загружать SVG‑изображения из потоков, повышая гибкость и эффективность работы с ресурсами изображений в программных приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Создаёт новый объект [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) с указанными шириной и высотой. Этот конструктор позволяет разработчикам создавать SVG‑изображения с предопределёнными размерами, обеспечивая точный контроль над размером изображения при инициализации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Создаёт новый экземпляр класса [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) с указанными SVG‑опциями, шириной и высотой изображения. Этот конструктор позволяет разработчикам инициализировать SVG‑изображения с пользовательскими параметрами и размерами, обеспечивая гибкость при управлении содержимым и макетом SVG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | SVG‑опции. |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Возвращает логическое значение, указывающее, кэшированы ли данные объекта в данный момент, устраняя необходимость дополнительных операций чтения данных. Это свойство предоставляет информацию о текущем статусе кэширования, оптимизируя процессы получения и обработки данных для повышения производительности и эффективности.

**Returns:**
boolean — `true`, если данные объекта кэшированы; иначе `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Возвращает количество бит на пиксель изображения. Важно отметить, что этот параметр не применяется к векторным изображениям, поскольку они не измеряются в пикселях. Это свойство предоставляет важную информацию о глубине цвета изображения, помогая в задачах обработки и манипуляции.

**Returns:**
int — Количество бит на пиксель изображения.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Возвращает формат файла изображения, предоставляя важные метаданные для обработки и проверки совместимости. Это свойство играет ключевую роль в определении подходящих стратегий декодирования и кодирования для эффективного работы с данными изображения в разных системах и приложениях.

**Returns:**
long - формат файла
### cacheData() {#cacheData--}
```
public void cacheData()
```


Кэшируйте данные и гарантируйте отсутствие дальнейшей загрузки данных из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Эта оптимизация повышает производительность, устраняя избыточные операции получения данных, что особенно полезно в сценариях, требующих частого доступа к данным изображения.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Измените размер изображения, чтобы он соответствовал указанным параметрам, сохраняя его соотношение сторон. Этот метод предоставляет удобный способ регулировать размер изображения без искажения пропорций, обеспечивая оптимальное отображение или хранение в соответствии с требуемыми размерами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезает указанный прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Поворачивает изображение вокруг центра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Применяет указанную палитру к изображению, позволяя настраивать цветовые схемы для эстетических или функциональных целей. Этот метод обеспечивает гибкость управления цветовыми палитрами в соответствии с различными требованиями дизайна или приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

