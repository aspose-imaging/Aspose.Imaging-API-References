---
title: "PngImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Манипулируйте растровыми изображениями Portable Network Graphics PNG с помощью нашего универсального API, поддерживающего уровни сжатия и различные глубины цвета, включая оттенки серого, индексированный цвет, TrueColor и альфа-каналы."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

Манипулируйте растровыми изображениями Portable Network Graphics (PNG) с помощью нашего универсального API, поддерживающего уровни сжатия и различные глубины цвета, включая Grayscale, Indexed Color, TrueColor и альфа-каналы. Бесшовно обрабатывайте метаданные XMP, обеспечивая полное управление метаданными изображений, а также легко загружайте PNG‑изображения, выполняйте разнообразные манипуляции, применяйте фильтры и конвертируйте изображения в другие форматы файлов для максимальной гибкости и настройки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Инициализируйте новый объект класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указав параметры ширины и высоты. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), используя параметр path для указания расположения файла изображения, которое нужно загрузить. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), предоставив растровое изображение в качестве параметра. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | Инициализирует новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указав путь к файлу изображения и тип цвета. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указав растровое изображение и тип цвета. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), инициализируя его потоком. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | Создайте новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указав желаемые параметры ширины, высоты и типа цвета. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Инициализируйте новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), включив параметры PNG вместе с параметрами ширины и высоты. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получите значение бит на пиксель для изображения. |
| [getHeight()](#getHeight--) | Получите высоту изображения в пикселях. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Получите или измените горизонтальное разрешение изображения. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Получите или измените горизонтальное разрешение изображения. |
| [getFileFormat()](#getFileFormat--) | Получает формат файла, связанного с экземпляром изображения. |
| [getRawDataFormat()](#getRawDataFormat--) | Получает формат необработанных данных изображения. |
| [getVerticalResolution()](#getVerticalResolution--) | Обеспечивает доступ к вертикальному разрешению изображения. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Обеспечивает доступ к вертикальному разрешению изображения. |
| [getWidth()](#getWidth--) | Позволяет получить ширину изображения в пикселях, предоставляя важную информацию о его размерах. |
| [hasTransparentColor()](#hasTransparentColor--) | Возвращает логическое значение, указывающее, содержит ли изображение прозрачный цвет. |
| [hasAlpha()](#hasAlpha--) | Возвращает логическое значение, указывающее, имеет ли изображение альфа‑канал, определяющий его прозрачность. |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет изображения, если он существует. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Возвращает логическое значение, указывающее, содержит ли изображение прозрачный цвет. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Изменяет прозрачный цвет изображения, если он существует. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Получает логическое значение, указывающее, имеет ли изображение цвет фона. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона изображения, если он указан. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Получает логическое значение, указывающее, имеет ли изображение цвет фона. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Получает цвет фона изображения, если он указан. |
| [getInterlaced()](#getInterlaced--) | Получает логическое значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) чересстрочным, что определяет, хранится ли данные изображения прогрессивно для более быстрой загрузки или передачи. |
| [isInterlaced()](#isInterlaced--) | Получает значение, указывающее, является ли данный экземпляр изображения чересстрочным. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Получает параметры по умолчанию. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает параметры, основанные на настройках оригинального файла. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Загрузить PNG‑изображение из файла.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Преобразовать изображение в оттенки серого
    pngImage.grayscale();

    // Сохранить в файл.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Инициализировать новый объект класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указав параметры ширины и высоты. Этот конструктор упрощает создание PNG‑изображений, позволяя разработчикам задавать размеры напрямую, обеспечивая эффективное управление данными PNG‑изображений в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина. |
| height | int | Высота. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), используя параметр пути для указания местоположения файла изображения, которое нужно загрузить. Этот конструктор позволяет разработчикам удобно создавать PNG‑изображения, загружая их из файла, упрощая процесс работы с PNG‑изображениями в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь для загрузки изображения. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), передавая растровое изображение в качестве параметра. Этот конструктор позволяет разработчикам напрямую инициализировать объект PNG‑изображения, используя существующее растровое изображение, упрощая процесс работы с PNG‑изображениями в их приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


Инициализирует новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указывая путь к файлу изображения и тип цвета. Этот конструктор обеспечивает удобное создание PNG‑изображений из файлов с различными типами цветов, предоставляя гибкость при работе с различными форматами изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь для загрузки изображения. |
| colorType | int | Тип цвета. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указывая растровое изображение и тип цвета. Этот конструктор позволяет разработчикам напрямую преобразовывать растровые изображения в формат PNG, задавая желаемый тип цвета, обеспечивая гибкость представления цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |
| colorType | int | Тип цвета. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Создаёт новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), инициализируя его потоком. Этот конструктор позволяет разработчикам загружать PNG‑изображения напрямую из потока, обеспечивая гибкость получения изображений из различных источников.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для загрузки изображения. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


Создайте новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), указав желаемые параметры ширины, высоты и типа цвета. Этот конструктор обеспечивает быструю генерацию PNG‑изображений с индивидуальными размерами и цветовыми настройками, упрощая создание изображений для различных приложений и рабочих процессов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина. |
| height | int | Высота. |
| colorType | int | Тип цвета. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


Инициализируйте новый экземпляр класса [PngImage](../../com.aspose.imaging.fileformats.png/pngimage), включив параметры PNG вместе с шириной и высотой. Этот конструктор даёт разработчикам возможность создавать PNG‑изображения с настраиваемыми параметрами и размерами, обеспечивая гибкость генерации изображений для различных сценариев использования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Параметры PNG. |
| width | int | Ширина. |
| height | int | Высота. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получить значение бит на пиксель для изображения. Это свойство предоставляет важную информацию о глубине цвета изображения, позволяя разработчикам понять уровень детализации и точность цветов, присутствующие в данных изображения.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получить высоту изображения в пикселях. Это свойство возвращает вертикальное измерение изображения, позволяя разработчикам определить его размер в пикселях по вертикальной оси.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Получить или изменить горизонтальное разрешение изображения. Это свойство представляет количество пикселей на дюйм по горизонтальной оси изображения. Корректировка этого разрешения может влиять на физический размер изображения при печати или отображении.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Получить горизонтальное и вертикальное разрешение PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Горизонтальное разрешение, в пикселях на дюйм: 96.0
//Вертикальное разрешение, в пикселях на дюйм: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Получить или изменить горизонтальное разрешение изображения. Это свойство представляет количество пикселей на дюйм по горизонтальной оси изображения. Корректировка этого разрешения может влиять на физический размер изображения при печати или отображении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получает формат файла, связанного с экземпляром изображения. Это свойство предоставляет важную информацию о типе файла, позволяя эффективно обрабатывать его в соответствии с конкретными требованиями формата.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Получает формат необработанных данных изображения. Это свойство дает представление о внутренней структуре данных изображения, что может быть полезно для сложных задач обработки изображений или конвертации форматов.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// PNG‑изображения для загрузки.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Обеспечивает доступ к вертикальному разрешению изображения. Разработчики могут использовать это свойство для получения или изменения настройки разрешения, указывающей количество пикселей на дюйм (PPI) по вертикальной оси изображения.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // Получить горизонтальное и вертикальное разрешение PngImage.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Вывод может выглядеть так:
//Горизонтальное разрешение, в пикселях на дюйм: 96.0
//Вертикальное разрешение, в пикселях на дюйм: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Обеспечивает доступ к вертикальному разрешению изображения. Разработчики могут использовать это свойство для получения или изменения настройки разрешения, указывающей количество пикселей на дюйм (PPI) по вертикальной оси изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Позволяет получить ширину изображения в пикселях, предоставляя важную информацию о его размерах. Это свойство часто используется разработчиками для определения ширины изображения, позволяя выполнять различные операции в зависимости от его размера

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Возвращает логическое значение, указывающее, содержит ли изображение прозрачный цвет. Это свойство важно для приложений, которым необходимо работать с прозрачностью, позволяя разработчикам определить, требуется ли дополнительная обработка прозрачных областей изображения.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Возвращает логическое значение, указывающее, имеет ли изображение альфа-канал, определяющий его прозрачность. Это свойство полезно для приложений, которым необходимо работать с прозрачностью, позволяя разработчикам определить, требуется ли дополнительная обработка прозрачных областей изображения.

**Returns:**
boolean - `true`, если у этого экземпляра есть альфа; в противном случае `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Вспомогательный класс
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// Вот основной пример
Utils utils = new Utils();

// Получить все поддерживаемые типы цветов PNG.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// Вывод выглядит так:
// Изображение PNG в градациях серого не поддерживает альфа-канал
// Изображение PNG Truecolor не поддерживает альфа-канал
// Изображение PNG IndexedColor не поддерживает альфа-канал
// Изображение PNG GrayscaleWithAlpha поддерживает альфа-канал
// Изображение PNG TruecolorWithAlpha поддерживает альфа-канал
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Получает прозрачный цвет изображения, если он существует. Это свойство ценно для приложений, требующих точной работы с прозрачными областями изображений, позволяя разработчикам получать доступ к использованному прозрачному цвету и изменять его.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Возвращает логическое значение, указывающее, содержит ли изображение прозрачный цвет. Это свойство важно для приложений, которым необходимо работать с прозрачностью, позволяя разработчикам определить, требуется ли дополнительная обработка прозрачных областей изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Создайте PNG‑изображение TrueColor размером 100×100 пикселей.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Все красные пиксели будут рассматриваться как полностью прозрачные.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Все прозрачные пиксели получат фоновый цвет.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Заполните всё изображение белым цветом.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Заполните верхний левый квартал изображения прозрачным цветом.
    // Это делает верхний левый квартал окрашенным в фоновый цвет.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Изменяет прозрачный цвет изображения, если он существует. Это свойство ценно для приложений, требующих точной работы с прозрачными областями изображений, позволяя разработчикам получать доступ к использованному прозрачному цвету и изменять его.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Создайте PNG‑изображение TrueColor размером 100×100 пикселей.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Все красные пиксели будут рассматриваться как полностью прозрачные.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Все прозрачные пиксели получат фоновый цвет.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Заполните всё изображение белым цветом.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Заполните верхний левый квартал изображения прозрачным цветом.
    // Это делает верхний левый квартал окрашенным в фоновый цвет.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Получает логическое значение, указывающее, имеет ли изображение фоновый цвет. Это свойство полезно для приложений, которым необходимо определить, содержит ли изображение фоновый цвет, что может быть важно для различных задач обработки, таких как композитинг, рендеринг или экспорт.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает фоновый цвет изображения, если он указан. Это свойство помогает приложениям, которым нужно определить и при необходимости изменить фоновый цвет изображения.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Получает логическое значение, указывающее, имеет ли изображение фоновый цвет. Это свойство полезно для приложений, которым необходимо определить, содержит ли изображение фоновый цвет, что может быть важно для различных задач обработки, таких как композитинг, рендеринг или экспорт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Создайте PNG‑изображение TrueColor размером 100×100 пикселей.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Все красные пиксели будут рассматриваться как полностью прозрачные.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Все прозрачные пиксели получат фоновый цвет.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Заполните всё изображение белым цветом.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Заполните верхний левый квартал изображения прозрачным цветом.
    // Это делает верхний левый квартал окрашенным в фоновый цвет.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Получает фоновый цвет изображения, если он указан. Это свойство помогает приложениям, которым нужно определить и при необходимости изменить фоновый цвет изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// Создайте PNG‑изображение TrueColor размером 100×100 пикселей.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Все красные пиксели будут рассматриваться как полностью прозрачные.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Все прозрачные пиксели получат фоновый цвет.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Заполните всё изображение белым цветом.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Заполните верхний левый квартал изображения прозрачным цветом.
    // Это делает верхний левый квартал окрашенным в фоновый цвет.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Получает логическое значение, указывающее, является ли [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) чересстрочным, что определяет, хранится ли данные изображения прогрессивно для более быстрой загрузки или передачи.

**Returns:**
boolean — `true`, если чересстрочно; иначе `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Получает значение, указывающее, является ли данный экземпляр изображения чересстрочным.

Значение: `true`, если данный экземпляр изображения чересстрочный; иначе `false`.

**Returns:**
boolean — значение, указывающее, является ли данный экземпляр изображения чересстрочным.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Получает параметры по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | java.lang.Object[] | Аргументы. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загрузим черно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраним его, используя метод `DataStreamSupporter.Save(string)`, будет получено PNG‑изображение с 8 битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу `Image.Save(string, ImageOptionsBase)` в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
