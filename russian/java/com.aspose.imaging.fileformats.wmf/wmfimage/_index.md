---
title: "WmfImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Манипулируйте изображениями Microsoft Windows Metafile WMF с помощью нашего API, бесшовно обрабатывая как векторные, так и растровые данные, хранящиеся в записях переменной длины."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Манипулируйте изображениями Microsoft Windows Metafile (WMF) с помощью нашего API, бесшовно обрабатывая как векторные, так и растровые данные, хранящиеся в записях переменной длины. Изменяйте размер, вращайте и отражайте изображения с легкостью, задавая пользовательские палитры. Конвертируйте файлы WMF в сжатые форматы WMZ или сохраняйте их в растровых форматах для универсального использования на разных платформах и в приложениях.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfImage()](#WmfImage--) | Создайте новый экземпляр класса [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), инициализируя его для дальнейшего манипулирования и обработки данных изображения Windows Metafile (WMF). |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Создайте новый экземпляр класса [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) с настраиваемыми параметрами ширины и высоты, облегчая создание пустых WMF‑изображений, соответствующих определённым размерам. |
## Методы

| Метод | Описание |
| --- | --- |
| [isCached()](#isCached--) | Получите логическое значение, указывающее, кэшированы ли данные объекта в данный момент, устраняя необходимость дополнительных операций чтения данных. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получите количество бит на пиксель для изображения, указывающее уровень глубины цвета или гранулярности. |
| [getWidthF()](#getWidthF--) | Получите ширину изображения, указывающую количество пикселей по горизонтальной оси. |
| [getHeightF()](#getHeightF--) | Получите высоту изображения, представляющую количество пикселей по вертикальной оси. |
| [getInch()](#getInch--) | Получите или измените свойство inch, представляющее единицу измерения, обычно используемую для указания физических размеров в печати или отображении. |
| [setInch(int value)](#setInch-int-) | Получите или измените свойство inch, представляющее единицу измерения, обычно используемую для указания физических размеров в печати или отображении. |
| [getFileFormat()](#getFileFormat--) | Получите значение формата файла, связанного с изображением, предоставляющее информацию о формате, в котором хранится изображение. |
| [getFrameBounds()](#getFrameBounds--) | Получите границы кадра, указывающие его положение и размеры внутри изображения. |
| [cacheData()](#cacheData--) | Эффективно кэшируйте данные, устраняя необходимость дополнительной загрузки из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\\#getDataStreamContainer)). |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Примените указанную палитру к изображению, позволяя настроить представление цветов. |
| [getUsedFonts()](#getUsedFonts--) | Получите список шрифтов, используемых в метафайле, предоставляющий информацию о ресурсах шрифтов, применяемых в изображении. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Измените размер холста изображения, корректируя его размеры, сохраняя содержимое изображения. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Включите указанный объект записи в изображение, обогащая его содержимое дополнительными данными или метаданными. |
| [getPostScript()](#getPostScript--) | Получите данные PostScript, связанные с изображением, предоставляющие подробную информацию о его структуре или содержимом. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает исходные параметры изображения. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

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


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Создайте новый экземпляр класса [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), инициализируя его для дальнейшего манипулирования и обработки данных изображений Windows Metafile (WMF). Этот конструктор предоставляет базовый объект для работы с WMF‑изображениями, обеспечивая бесшовную интеграцию возможностей обработки WMF‑изображений в функциональность вашего приложения.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Создайте новый экземпляр класса [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) с настраиваемыми параметрами ширины и высоты, что облегчает создание пустых WMF‑изображений, соответствующих определённым размерам. Используйте этот конструктор для динамического генерирования WMF‑изображений с точными размерами, позволяя гибко создавать и изменять изображения в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина. |
| height | int | Высота. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Получите логическое значение, указывающее, кэшированы ли данные объекта в данный момент, устраняя необходимость дополнительных операций чтения данных. Используйте это свойство для оптимизации производительности, определяя, доступны ли данные объекта без затратных процессов получения данных в вашем приложении.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получите количество бит на пиксель изображения, указывающее уровень глубины цвета или гранулярности. Используйте это свойство для определения цветового представления и точности изображения, облегчая проверки совместимости и обработку, связанную с цветом, в вашем приложении.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Получите ширину изображения, указывающую количество пикселей по горизонтальной оси. Используйте это свойство для определения пространственных размеров и соотношения сторон изображения, позволяя точно настраивать макет и рендеринг в вашем приложении.

**Returns:**
float — ширина изображения в пикселях.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Получите высоту изображения, представляющую количество пикселей по вертикальной оси. Используйте это свойство для определения пространственных размеров и соотношения сторон изображения, позволяя точно настраивать макет и рендеринг в вашем приложении.

**Returns:**
float — высота изображения в пикселях.
### getInch() {#getInch--}
```
public int getInch()
```


Получайте или изменяйте свойство inch, представляющее единицу измерения, обычно используемую для указания физических размеров в печати или отображении. Используйте это свойство для установки или получения значений дюймов, связанных с изображением, обеспечивая точное представление физических размеров в вашем приложении.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Получайте или изменяйте свойство inch, представляющее единицу измерения, обычно используемую для указания физических размеров в печати или отображении. Используйте это свойство для установки или получения значений дюймов, связанных с изображением, обеспечивая точное представление физических размеров в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите значение формата файла, связанного с изображением, предоставляющее информацию о формате, в котором изображение хранится. Используйте это свойство для определения формата файла изображения, облегчая проверки совместимости и обработку, специфичную для формата, в вашем приложении.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Получите границы кадра, указывающие его позицию и размеры внутри изображения. Используйте это свойство для получения подробной информации о пространственном расположении кадра, позволяя точно управлять им и выполнять рендеринг в вашем приложении.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Эффективно кэшируйте данные, устраняя необходимость дополнительной загрузки из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Используйте этот метод для оптимизации производительности и минимизации использования ресурсов в вашем приложении путем сохранения и доступа к локальному кэшу данных.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Кэшировать данные для загрузки всех записей.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // Ключ — тип записи, значение — количество записей данного типа в WMF‑изображении.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // Собрать статистику
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
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
    wmfImage.dispose();
}

//Вывод может выглядеть так:
//Общее количество записей: 613
//Тип записи                              Количество
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Примените указанную палитру к изображению, позволяя настраивать представление цветов. Используйте этот метод для улучшения визуального отображения и достижения определённых цветовых эффектов в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Получите список шрифтов, используемых в метафайле, получая представление о ресурсах шрифтов, применяемых в изображении. Используйте этот метод для анализа использования шрифтов и обеспечения их доступности для рендеринга или дальнейшей обработки в вашем приложении.

**Returns:**
java.lang.String[] - Список шрифтов
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Измените размер холста изображения, корректируя его размеры при сохранении содержимого изображения. Используйте этот метод для изменения размеров холста без изменения содержимого, облегчая корректировку макета и изменения композиции в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Новый прямоугольник. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Внедрите указанный объект записи в изображение, обогащая его содержимое дополнительными данными или метаданными. Используйте этот метод для бесшовной интеграции объектов записей в изображение, облегчая комплексное хранение и организацию данных в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | Запись. |

**Returns:**
int - Количество записей.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Получите доступ к данным PostScript, связанным с изображением, предоставляя подробную информацию о его структуре или содержимом. Используйте этот метод для получения данных PostScript для дальнейшего анализа или обработки в вашем приложении, позволяя реализовать расширенную функциональность, связанную с рендерингом или манипуляцией PostScript.

**Returns:**
java.lang.String - PostScript
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает исходные параметры изображения.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
