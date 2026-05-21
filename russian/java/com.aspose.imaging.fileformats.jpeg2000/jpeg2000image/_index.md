---
title: "Jpeg2000Image"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Эффективно манипулируйте файлами изображений JPEG2000 JP2 с помощью нашего API, поддерживающего широкий диапазон глубины цвета в битах на пиксель и бесшовную обработку XMP‑метаданных, содержащих важную информацию об изображении."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Эффективно манипулируйте файлами изображений JPEG2000 (JP2) с помощью нашего API, поддерживая широкий диапазон глубины цвета в битах на пиксель и бесшовную обработку XMP‑метаданных, содержащих важную информацию об изображении. Благодаря возможностям без потерь, обеспечьте оптимальное качество изображения при сохранении целостности файла, позволяя легко адаптировать изображения JP2 под ваши точные требования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Начните работу с классом [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), инициализировав новый экземпляр с путем к изображению, которое вы хотите загрузить. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Легко начните работу с классом [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), создав новый экземпляр, указав путь к файлу и требуемый параметр бит на пиксель. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Легко инициализируйте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), предоставив объект потока. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Инициализируйте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) с потоком для загрузки изображения, а также параметрами бит на пиксель. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Создайте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), указав параметры ширины и высоты. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Создайте новый объект [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), указав параметры ширины, высоты и параметров изображения. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Создайте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) с параметрами ширины, высоты и количества бит. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Создайте новый класс [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) с растровым изображением. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Инициализируйте новый экземпляр [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) с растровым изображением и параметрами бит на пиксель. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Получите формат файла изображения. |
| [getRawDataFormat()](#getRawDataFormat--) | Это свойство возвращает формат необработанных данных изображения. |
| [getRawLineSize()](#getRawLineSize--) | Это свойство возвращает размер одной строки необработанных данных изображения в байтах. |
| [getWidth()](#getWidth--) | Это свойство возвращает ширину изображения в пикселях. |
| [getHeight()](#getHeight--) | Это свойство получает высоту изображения в пикселях. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Это свойство возвращает глубину изображения, измеряемую в битах на пиксель (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | Это свойство позволяет получить или изменить горизонтальное разрешение [RasterImage](../../com.aspose.imaging/rasterimage), измеряемое в пикселях на дюйм (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Это свойство позволяет получить или изменить горизонтальное разрешение [RasterImage](../../com.aspose.imaging/rasterimage), измеряемое в пикселях на дюйм (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | Это свойство предоставляет доступ к вертикальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Это свойство предоставляет доступ к вертикальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм (PPI). |
| [getComments()](#getComments--) | Это свойство позволяет получать или обновлять комментарии, связанные с изображением. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Это свойство позволяет получать или обновлять комментарии, связанные с изображением. |
| [getCodec()](#getCodec--) | Это свойство получает кодек JPEG2000, связанный с изображением. |
| [getOriginalOptions()](#getOriginalOptions--) | Получите параметры изображения на основе исходных настроек файла. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Загрузите изображение JPEG2000.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // Сохранить в PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Начните работу с классом [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), инициализировав новый экземпляр с путем к изображению, которое вы хотите загрузить. Этот конструктор обеспечивает простой доступ к изображениям JPEG2000, упрощая процесс загрузки и обработки файлов изображений. Указав путь к файлу, вы можете быстро приступить к обработке и манипулированию изображениями JPEG2000 в вашем приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Легко начните работу с классом [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), создав новый экземпляр, указав как путь к файлу, так и требуемый параметр битов на пиксель. Этот конструктор позволяет точно настраивать процесс загрузки изображения, обеспечивая совместимость с различными форматами изображений и настройками качества. Благодаря этой гибкости вы можете эффективно управлять и манипулировать изображениями JPEG2000 в соответствии с вашими конкретными требованиями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с которым инициализируются данные пикселей и палитры |
| bitsPerPixel | int | Биты на пиксель. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Легко инициализируйте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), предоставив объект потока. Этот конструктор упрощает процесс загрузки изображений JPEG2000 напрямую из потоков, предоставляя гибкость и удобство при работе с данными изображений из различных источников.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Инициализируйте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), указав поток для загрузки изображения и параметры битов на пиксель. Этот конструктор предоставляет гибкость, позволяя указать как источник данных изображения, так и требуемое количество бит на пиксель, обеспечивая более точный контроль над процессом загрузки изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с которым инициализируются данные пикселей и палитры. |
| bitsPerPixel | int | Биты на пиксель. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Создайте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), указав параметры ширины и высоты. Этот конструктор позволяет инициализировать изображение JPEG2000 с конкретными размерами, что полезно в сценариях, когда необходимо программно создать изображение определённого размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения |
| height | int | Высота изображения |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Создайте новый объект [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), указав параметры ширины, высоты и параметров изображения. Этот конструктор позволяет создавать изображения JPEG2000 с конкретными размерами и дополнительными опциями, обеспечивая гибкость при генерации изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения |
| height | int | Высота изображения |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Параметры. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Создайте новый экземпляр класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) с параметрами ширины, высоты и количества бит. Этот конструктор позволяет создавать изображения JPEG2000 с конкретными размерами и глубиной цвета, обеспечивая гибкость для различных задач обработки изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения |
| height | int | Высота изображения |
| bitsCount | int | Количество бит. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Создайте новый объект класса [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) с растровым изображением. Этот конструктор облегчает создание изображения JPEG2000 из существующего растрового изображения, обеспечивая бесшовную интеграцию и конвертацию между различными форматами изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Создайте новый экземпляр [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) с растровым изображением и параметрами битов на пиксель. Этот конструктор обеспечивает точный контроль над качеством и размером получаемого изображения JPEG2000, что делает его идеальным для сценариев, где важна настройка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, с которым инициализируются данные пикселей и палитры. |
| bitsPerPixel | int | Биты на пиксель. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите формат файла изображения. Это свойство предоставляет информацию о формате файла изображения. Используйте это свойство для программного определения формата файла изображения, что облегчает соответствующую обработку и обработку в зависимости от формата файла.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Это свойство получает формат необработанных данных изображения. Оно предоставляет информацию о том, как пиксельные данные хранятся в памяти. Используйте это свойство, чтобы понять базовый формат данных изображения, что может быть критически важным для различных операций обработки изображений, таких как преобразование цветов, сжатие или декомпрессия.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Это свойство получает размер одной строки необработанных данных изображения в байтах. Оно указывает количество памяти, занимаемой одной строкой пикселей в формате необработанных данных изображения. Понимание размера строки данных необходимо для задач, таких как выделение памяти, манипуляция данными и алгоритмы обработки изображений, работающие с отдельными строками изображения.

**Returns:**
int - Размер необработанной строки в байтах.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Это свойство возвращает ширину изображения в пикселях. Оно предоставляет базовую информацию о размерах изображения, важную для различных задач обработки изображений, включая изменение размера, обрезку и рендеринг.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Это свойство получает высоту изображения в пикселях. Оно служит важной информацией для понимания вертикальных размеров изображения, помогая в различных задачах манипуляции изображением, таких как изменение размера, обрезка и рендеринг. Доступ к этому свойству позволяет пользователям определить вертикальный размер изображения, обеспечивая точную компоновку и отображение в приложениях.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Это свойство возвращает глубину изображения, измеряемую в битах на пиксель (bpp). Оно указывает количество цветовой информации, хранящейся в каждом пикселе изображения. Понимание глубины изображения критически важно для определения цветовой точности и качества изображения. Имея эту информацию, пользователи могут оценить уровень детализации и насыщенности цветов в изображении.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Это свойство позволяет получить или изменить горизонтальное разрешение [RasterImage](../../com.aspose.imaging/rasterimage), измеряемое в пикселях на дюйм (PPI). Регулировка этого разрешения может влиять на размер и качество изображения при печати или отображении. Устанавливая горизонтальное разрешение, пользователи могут оптимизировать изображение для конкретных выводных устройств или приложений, обеспечивая наилучший визуальный результат.

**Returns:**
double - Горизонтальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Получить горизонтальное и вертикальное разрешение Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 72.0
// Вертикальное разрешение, в пикселях на дюйм: 72.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 72.0
// Вертикальное разрешение, в пикселях на дюйм: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Это свойство позволяет получить или изменить горизонтальное разрешение [RasterImage](../../com.aspose.imaging/rasterimage), измеряемое в пикселях на дюйм (PPI). Регулировка этого разрешения может влиять на размер и качество изображения при печати или отображении. Устанавливая горизонтальное разрешение, пользователи могут оптимизировать изображение для конкретных выводных устройств или приложений, обеспечивая наилучший визуальный результат.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Горизонтальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Это свойство предоставляет доступ к вертикальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм (PPI). Изменение этого разрешения может влиять на качество и размер изображения при печати или отображении. Регулируя вертикальное разрешение, пользователи могут оптимизировать изображение для различных выводных устройств или приложений, обеспечивая оптимальный визуальный рендеринг.

**Returns:**
double - Вертикальное разрешение.

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Получить горизонтальное и вертикальное разрешение Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Используйте метод SetResolution для обновления обоих значений разрешения одним вызовом.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// Горизонтальное разрешение, в пикселях на дюйм: 72.0
// Вертикальное разрешение, в пикселях на дюйм: 72.0
// Установить значения разрешения в 96 dpi
// Горизонтальное разрешение, в пикселях на дюйм: 72.0
// Вертикальное разрешение, в пикселях на дюйм: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Это свойство предоставляет доступ к вертикальному разрешению [RasterImage](../../com.aspose.imaging/rasterimage), измеряемому в пикселях на дюйм (PPI). Изменение этого разрешения может влиять на качество и размер изображения при печати или отображении. Регулируя вертикальное разрешение, пользователи могут оптимизировать изображение для различных выводных устройств или приложений, обеспечивая оптимальный визуальный рендеринг.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | double | Вертикальное разрешение. |

Примечание: по умолчанию это значение всегда равно 96, поскольку разные платформы не могут вернуть разрешение экрана. Вы можете рассмотреть возможность использования метода SetResolution для обновления обоих значений разрешения одним вызовом. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Это свойство позволяет получать или обновлять комментарии, связанные с изображением. Комментарии предоставляют дополнительную информацию о содержимом изображения, такую как аннотации, описания или метаданные. Изменение этих комментариев может быть полезным для организации и классификации изображений, а также для передачи важной информации зрителям или пользователям.

**Returns:**
java.lang.String[] - Комментарии.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Это свойство позволяет получать или обновлять комментарии, связанные с изображением. Комментарии предоставляют дополнительную информацию о содержимом изображения, такую как аннотации, описания или метаданные. Изменение этих комментариев может быть полезным для организации и классификации изображений, а также для передачи важной информации зрителям или пользователям.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] | Комментарии. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Это свойство получает JPEG2000 кодек, связанный с изображением. JPEG2000 кодек отвечает за кодирование и декодирование данных изображения в формате JPEG2000, обеспечивая эффективное сжатие при сохранении высокого качества изображения. Доступ к этому кодеку может быть полезен для выполнения продвинутых операций обработки изображений или оптимизации настроек сжатия изображения, адаптированных к конкретным требованиям.

**Returns:**
int - Кодек.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получите параметры изображения на основе исходных настроек файла. Этот метод полезен для сохранения глубины цвета и других параметров оригинального изображения, обеспечивая согласованность и сохранность целостности данных изображения. Доступ к этим параметрам облегчает беспроблемную обработку и обработку изображения, сохраняя его исходные характеристики. Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), будет получено PNG‑изображение с 8 битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их в метод [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
