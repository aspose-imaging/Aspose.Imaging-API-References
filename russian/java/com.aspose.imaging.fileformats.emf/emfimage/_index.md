---
title: "EmfImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для поддержки векторного формата изображений Enhanced Metafile Format EMF — это всесторонний инструмент для обработки графических изображений в независимом от устройства режиме при сохранении их исходных свойств."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

API для поддержки векторного формата изображений Enhanced Metafile Format (EMF) является всесторонним инструментом для обработки графических изображений в независимом от устройства режиме при сохранении их исходных свойств. Разработан для сохранения пропорций, размеров, цветов и других графических атрибутов, включает поддержку формата EMF Plus и функции обрезки областей, изменения размеров холста и изображений, вращения, отражения, установки палитр изображений, экспорта и импорта в контекст устройства APS, сжатия и конвертации EMF в другие форматы, обеспечивая гибкую манипуляцию и бесшовную интеграцию EMF‑изображений в различных приложениях.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfImage()](#EmfImage--) | Начните работу с EMF‑изображениями, создав новый экземпляр класса [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Создайте новый экземпляр класса [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage), указав параметры ширины и высоты. |
## Методы

| Метод | Описание |
| --- | --- |
| [getHeader()](#getHeader--) | Получите запись заголовка метафайла EMF с помощью этого свойства. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Измените запись заголовка метафайла EMF с помощью этого свойства. |
| [isCached()](#isCached--) | Получите значение, указывающее, кэшированы ли данные объекта в данный момент, исключая необходимость дополнительного чтения данных. |
| [getRecords()](#getRecords--) | Получайте или изменяйте записи, связанные с объектом. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Изменяйте записи, связанные с объектом. |
| [getFileFormat()](#getFileFormat--) | Получите значение формата файла, связанное с объектом. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получите количество бит на пиксель, характерное для растровых изображений, поскольку этот параметр не применяется к векторным изображениям. |
| [getWidthF()](#getWidthF--) | Получите доступ к ширине изображения, предоставляя важную информацию для точного рендеринга и обработки. |
| [getHeightF()](#getHeightF--) | Получите высоту изображения, облегчая точный рендеринг и корректировку макета. |
| [cacheData()](#cacheData--) | Эффективно кэшируйте данные и предотвращайте избыточную загрузку из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) с помощью этого метода. |
| [getUsedFonts()](#getUsedFonts--) | Получите список шрифтов, используемых в метафайле, с помощью этого метода. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Изменяйте размер холста с легкостью, используя эту функцию. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает исходные параметры изображения. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Устанавливает палитру изображения. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


Начните работу с EMF‑изображениями, создав новый экземпляр класса [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). Идеально подходит для быстрого внедрения EMF‑изображений в ваши проекты с легкостью и эффективностью.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Создайте новый экземпляр класса [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage), указав параметры ширины и высоты. Этот конструктор упрощает процесс инициализации EMF‑изображений с конкретными размерами, повышая эффективность вашего рабочего процесса разработки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина. |
| height | int | Высота. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Получите запись заголовка метафайла EMF с помощью этого свойства. Идеально подходит для эффективного управления данными метафайла в вашем приложении. Улучшите ваш рабочий процесс благодаря упрощенному доступу к информации заголовка метафайла.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Измените запись заголовка метафайла EMF с помощью этого свойства. Идеально подходит для эффективного управления данными метафайла в вашем приложении. Улучшите ваш рабочий процесс благодаря упрощенному доступу к информации заголовка метафайла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Получите значение, указывающее, кэшированы ли данные объекта в данный момент, исключая необходимость дополнительного чтения данных. Повышайте эффективность, быстро определяя, доступны ли кэшированные данные для мгновенного доступа. Оптимизируйте ваш рабочий процесс благодаря упрощённым процессам получения данных.

**Returns:**
boolean — `true`, если данные объекта кэшированы; иначе `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Получайте или изменяйте записи, связанные с объектом. Эффективно получайте доступ и управляйте коллекцией записей для улучшенной обработки и манипуляции данными. Оптимизируйте ваш рабочий процесс, бесшовно взаимодействуя с записями объекта.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Изменяйте записи, связанные с объектом. Эффективно получайте доступ и управляйте коллекцией записей для улучшенной обработки и манипуляции данными. Оптимизируйте ваш рабочий процесс, бесшовно взаимодействуя с записями объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Записи. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получайте значение формата файла, связанного с объектом. Легко определяйте формат файла, связанного с объектом, для упрощённой обработки и проверки совместимости. Упростите ваш рабочий процесс, получая информацию о формате файла без усилий.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получайте количество бит на пиксель, специфичное для растровых изображений, поскольку этот параметр не применяется к векторным изображениям. Быстро определяйте глубину пикселей растровых изображений для точного анализа и манипуляции, обеспечивая корректную обработку данных изображения.

**Returns:**
int — Количество бит на пиксель изображения.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Получайте ширину изображения, предоставляя важную информацию для точного рендеринга и обработки. Быстро получайте ширину изображения, чтобы обеспечить совместимость и правильную компоновку в различных приложениях и платформах.

**Returns:**
float — ширина изображения в пикселях.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Получайте высоту изображения, облегчая точный рендеринг и корректировку компоновки. Доступ к свойству высоты обеспечивает совместимость и бесшовную интеграцию на разных платформах и в приложениях.

**Returns:**
float — высота изображения в пикселях.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Эффективно кэшируйте данные и предотвращайте избыточную загрузку из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) с помощью этого метода. Повышайте производительность и упрощайте доступ к данным в вашем приложении, оптимизируя использование ресурсов для улучшенной отзывчивости.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Кэшировать данные для загрузки всех записей.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Ключ — тип записи, значение — количество записей данного типа в WMF‑изображении.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Собрать статистику
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Вывести статистику
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Выровнять вывод пробелами
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//Вывод может выглядеть так:
//Общее количество записей: 1188
//Тип записи                              Количество
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Получайте список шрифтов, используемых в метафайле, с помощью этого метода. Получайте представление об использовании шрифтов, облегчая эффективное управление и оптимизацию ресурсов шрифтов для улучшенного рендеринга и точности отображения.

**Returns:**
java.lang.String[] - Список шрифтов
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Изменяйте размер холста с легкостью, используя эту функцию. Идеально подходит для корректировки общих размеров изображения без изменения его содержимого. Улучшайте презентацию и готовьте изображения к различным размерам отображения без усилий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Новый прямоугольник. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает исходные параметры изображения.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Устанавливает палитру изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

