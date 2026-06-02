---
title: "TgaImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Манипулируйте растровыми файлами TGA с помощью нашего API, адаптированного для формата TARGA Truevision Advanced Raster Adapter, обеспечивая беспрепятственную загрузку и настройку."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

Манипулируйте растровыми файлами TGA с помощью нашего API, адаптированного для формата TARGA (Truevision Advanced Raster Adapter), обеспечивая беспрепятственную загрузку и настройку. Легко обновляйте публичные свойства, такие как автор, метка времени, идентификатор изображения и версия программного обеспечения, используя различные настройки бит на пиксель, альфа-канал и прозрачность цветов. Кроме того, вы можете экспортировать изображения TGA в другие популярные растровые форматы, обеспечивая совместимость для ваших проектов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Инициализирует новый объект [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), используя указанный путь к файлу для загрузки содержимого изображения. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Создайте новый экземпляр класса [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), предоставив растровый объект изображения. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Инициализируйте новый экземпляр класса [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), используя поток для загрузки изображения. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получите значение бит на пиксель, предоставляющее важную информацию о глубине цвета изображения. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Получите значение байт на пиксель, которое указывает объём памяти, занимаемый каждым пикселем изображения. |
| [hasAlpha()](#hasAlpha--) | Получите логическое значение, указывающее, содержит ли [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) альфа-канал, обеспечивая эффекты прозрачности. |
| [isGrayScale()](#isGrayScale--) | Получите логическое значение, указывающее, представляет ли [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) изображение в градациях серого. |
| [getWidth()](#getWidth--) | Получите ширину изображения, представленного этим экземпляром [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getHeight()](#getHeight--) | Получите высоту изображения, инкапсулированного в этом экземпляре [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getFileFormat()](#getFileFormat--) | Получите важную информацию о формате файла изображения, представленного этим экземпляром [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [hasColorMap()](#hasColorMap--) | Получите информацию о том, содержит ли этот экземпляр [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) цветовую карту. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Получает числитель значения гаммы, которое необходимо для точного представления цветов в изображениях. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Получает знаменатель значения гаммы, являющийся важным фактором при определении представления цветов в изображениях. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Получает числитель компонента соотношения сторон пикселя, влияющего на визуальный вид пикселей в изображении. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Получает знаменатель соотношения сторон пикселя, важный фактор при определении визуального вида пикселей в изображении. |
| [getXOrigin()](#getXOrigin--) | Получает абсолютную горизонтальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA). |
| [setXOrigin(int value)](#setXOrigin-int-) | Устанавливает абсолютную горизонтальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA). |
| [getYOrigin()](#getYOrigin--) | Получает абсолютную вертикальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA). |
| [setYOrigin(int value)](#setYOrigin-int-) | Устанавливает абсолютную вертикальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA). |
| [getImageId()](#getImageId--) | Получает уникальный идентификатор, связанный с изображением. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Устанавливает уникальный идентификатор, связанный с изображением. |
| [getAuthorComments()](#getAuthorComments--) | Получает или задает комментарии, предоставленные автором изображения. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Получает или задает комментарии, предоставленные автором изображения. |
| [getAuthorName()](#getAuthorName--) | Получает или задает имя автора, связанного с изображением. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Получает или задает имя автора, связанного с изображением. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Получает метку даты/времени. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Задает метку даты/времени. |
| [getJobNameOrId()](#getJobNameOrId--) | Получает или задает имя задания или его идентификатор, связанный с изображением. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Получает или задает имя задания или его идентификатор, связанный с изображением. |
| [getJobTime()](#getJobTime--) | Получает или задает метку времени, указывающую время задания, связанного с изображением. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Получает или задает метку времени, указывающую время задания, связанного с изображением. |
| [getTransparentColor()](#getTransparentColor--) | Получает или задает ключевой цвет, связанный с изображением. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Получает или задает ключевой цвет, связанный с изображением. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает или задает логическое значение, указывающее, содержит ли изображение прозрачный цвет. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Получает или задает логическое значение, указывающее, содержит ли изображение прозрачный цвет. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает цвет фона изображения. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Получает или задает цвет фона изображения. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Получает или задает значение, указывающее, содержит ли изображение цвет фона. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Получает или задает значение, указывающее, содержит ли изображение цвет фона. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Получает или задает версию программного обеспечения, связанную с изображением. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Получает или задает версию программного обеспечения, связанную с изображением. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Получает или задает буквенную часть версии программного обеспечения, связанной с изображением. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Получает или задает буквенную часть версии программного обеспечения, связанной с изображением. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Получает или задает числовую часть версии программного обеспечения, связанной с изображением. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Получает или задает числовую часть версии программного обеспечения, связанной с изображением. |
| [getSoftwareId()](#getSoftwareId--) | Управляет идентификацией программного обеспечения (ID), связанной с изображением, позволяя использовать до 40 символов ASCII. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Управляет идентификацией программного обеспечения (ID), связанной с изображением, позволяя использовать до 40 символов ASCII. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Выполняет сравнение на равенство двух TGA‑изображений, учитывая как первое, так и второе изображение, участвующие в процессе сравнения. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Проводит сравнение на неравенство двух TGA‑изображений, оценивая как первое, так и второе изображение, участвующие в сравнении. |
| [deepClone()](#deepClone--) | Создаёт дубликат текущего экземпляра, генерируя новый объект, который клонирует все атрибуты и свойства оригинала. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Копирует свойства другого объекта [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), создавая новый экземпляр с идентичными атрибутами. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | При сравнении на равенство метод оценивает, равен ли текущий экземпляр [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) второму изображению, переданному в качестве параметра. |
| [equals(Object other)](#equals-java.lang.Object-) | Метод выполняет сравнение на равенство между текущим экземпляром [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) и другим объектом, переданным в качестве параметра. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Метод "rotateFlip" позволяет выполнять операции вращения и отражения изображения. |
| [hashCode()](#hashCode--) | Получить хеш‑код текущего экземпляра. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Обрезать изображение до указанного региона. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Обрезать изображение, указав смещения для левых, правых, верхних и нижних границ. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменить размер изображения, применяя определённые настройки для поддержания требуемых размеров и соотношения сторон. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Регулирует размер изображения с использованием указанного типа изменения размера, который определяет, как выполняется операция масштабирования. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Поворачивает изображение вокруг его центра на заданный угол, сохраняя пропорциональность изменения размера и сохраняет цвет фона. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Инициализирует новый объект [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) с использованием указанного пути к файлу для загрузки содержимого изображения. Этот конструктор эффективно инициализирует экземпляр изображения, позволяя беспрепятственно получать доступ к TGA‑файлам, упрощая интеграцию в рабочий процесс вашего приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь для загрузки изображения. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Создайте новый экземпляр класса [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), предоставив растровый объект изображения. Этот конструктор облегчает прямую интеграцию существующих растровых изображений в формат TGA, упрощая процесс конвертации для повышения совместимости в ваших программных системах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Инициализируйте новый экземпляр класса [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) с использованием потока для загрузки изображения. Этот конструктор позволяет беспрепятственно интегрировать данные изображения из потоков, обеспечивая эффективную обработку и работу с TGA‑изображениями в ваших программных приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток для загрузки изображения. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получите значение бит на пиксель, предоставляющее важную информацию о глубине цвета изображения. Это свойство служит ключевым показателем для понимания уровня детализации и насыщенности цветов в изображении, помогая разработчикам оптимизировать алгоритмы обработки и распределение ресурсов для эффективного манипулирования изображениями и их рендеринга.

**Returns:**
int — бит на пиксель.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Получите значение байт на пиксель, которое указывает объём памяти, занимаемый каждым пикселем изображения. Это свойство является важным показателем для управления памятью и её оптимизации, помогая разработчикам эффективно распределять ресурсы и обрабатывать данные изображения.

**Returns:**
int — байт на пиксель.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получите логическое значение, указывающее, содержит ли [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) альфа‑канал, позволяя реализовать эффекты прозрачности. Это свойство предоставляет важную информацию для работы с композицией и рендерингом изображений, помогая разработчикам внедрять разнообразные визуальные эффекты и операции композитинга.

**Returns:**
boolean — значение, указывающее, имеет ли данный [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) альфа‑канал.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Получите логическое значение, указывающее, представляет ли [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) изображение в градациях серого. Это свойство важно для различения цветных и черно‑белых изображений, помогая разработчикам применять соответствующие методы обработки и рендеринга в зависимости от цветовых характеристик изображения.

**Returns:**
boolean — значение, указывающее, является ли данный [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) изображением в градациях серого.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получите ширину изображения, представленного этим экземпляром [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Это свойство предоставляет разработчикам важную информацию о размерах изображения, облегчая различные задачи манипулирования и обработки изображений в их программных приложениях.

**Returns:**
int — ширина изображения в пикселях.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получите высоту изображения, инкапсулированного в этом экземпляре [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Это свойство предоставляет разработчикам критические детали о вертикальных размерах изображения, обеспечивая беспрепятственную интеграцию и манипуляцию изображениями в их программных решениях.

**Returns:**
int — высота изображения в пикселях.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите важную информацию о формате файла изображения, представленного этим экземпляром [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). Понимание формата файла необходимо для проверки совместимости и обеспечения беспрепятственной интеграции в программных системах, позволяя эффективно обрабатывать и манипулировать изображениями.

**Returns:**
long — важная информация о формате файла изображения, представленного этим экземпляром [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage).
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Определите, содержит ли этот экземпляр [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) цветовую карту. Понимание наличия цветовой карты имеет решающее значение для точной интерпретации и обработки цветовых данных изображения.

**Returns:**
boolean — значение, указывающее, имеет ли изображение цветовую карту.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Получает числитель значения гаммы, которое необходимо для точного представления цветов в изображениях. В изображениях без коррекции гаммы это значение должно быть 1,0. Понимание и использование этого значения критически важно для поддержания цветовой достоверности и обеспечения точного отображения изображения.

**Returns:**
int — числитель значения гаммы, который необходим для точного представления цветов в изображениях.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Получает знаменатель значения гаммы, являющийся важным фактором при определении цветового представления в изображениях. Для изображений без коррекции гаммы это значение должно быть 1,0, обеспечивая точное отображение цветов. Оценка и использование этого параметра является фундаментальным для поддержания цветовой достоверности и достижения точной визуализации изображения.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Получает числитель компонента соотношения сторон пикселя, который влияет на визуальный вид пикселей в изображении. Понимание и изменение этого значения необходимо для достижения точного представления пикселей и соотношения сторон при рендеринге и обработке изображений.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Получает знаменатель соотношения сторон пикселя, критический фактор при определении визуального вида пикселей в изображении. Это значение необходимо для сохранения точного представления пикселей и соотношения сторон в различных операциях рендеринга и обработки изображений, обеспечивая высококачественный визуальный результат.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Получает абсолютную горизонтальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA).

**Returns:**
int — абсолютная горизонтальная координата нижнего левого угла изображения, когда оно размещено на дисплейном устройстве с началом координат в нижнем левом углу экрана.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Устанавливает абсолютную горизонтальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | абсолютная горизонтальная координата нижнего левого угла изображения, когда оно размещено на дисплейном устройстве с началом координат в нижнем левом углу экрана. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Получает абсолютную вертикальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA).

**Returns:**
int — абсолютная вертикальная координата нижнего левого угла изображения, когда оно размещено на дисплейном устройстве с началом координат в нижнем левом углу экрана.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Устанавливает абсолютную вертикальную координату нижнего левого угла изображения, когда оно расположено на дисплейном устройстве с началом координат в нижнем левом углу экрана (например, серия TARGA).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | абсолютная вертикальная координата нижнего левого угла изображения, когда оно размещено на дисплейном устройстве с началом координат в нижнем левом углу экрана. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Получает уникальный идентификатор, связанный с изображением. Этот ID служит точкой отсчёта для идентификации и различения изображения от других в системе или приложении. Устанавливая или получая Image ID, вы можете эффективно управлять и отслеживать изображения, облегчая организованное управление и извлечение изображений.

Это необязательное поле содержит идентифицирующую информацию об изображении. Максимальная длина этого поля — 255 байт.

**Returns:**
java.lang.String — уникальный идентификатор, связанный с изображением.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Устанавливает уникальный идентификатор, связанный с изображением. Этот ID служит точкой отсчёта для идентификации и различения изображения от других в системе или приложении. Устанавливая или получая Image ID, вы можете эффективно управлять и отслеживать изображения, облегчая организованное управление и извлечение изображений.

Это необязательное поле содержит идентифицирующую информацию об изображении. Максимальная длина этого поля — 255 байт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | уникальный идентификатор, связанный с изображением. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Получает или задаёт комментарии, предоставленные автором изображения. Эти комментарии часто содержат ценную информацию, такую как описания, аннотации или дополнительный контекст об изображении. Получая доступ к свойству Author Comments или изменяя его, разработчики могут улучшить метаданные изображения, предоставляя пользователям ценные сведения и контекст относительно его содержания или создания. Это ASCII‑поле объёмом 324 байта, организованное в четыре строки по 80 символов, каждая из которых завершается нулевым терминатором.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Получает или задаёт комментарии, предоставленные автором изображения. Эти комментарии часто содержат ценную информацию, такую как описания, аннотации или дополнительный контекст об изображении. Получая доступ к свойству Author Comments или изменяя его, разработчики могут улучшить метаданные изображения, предоставляя пользователям ценные сведения и контекст относительно его содержания или создания. Это ASCII‑поле объёмом 324 байта, организованное в четыре строки по 80 символов, каждая из которых завершается нулевым терминатором.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Получает или задаёт имя автора, связанное с изображением. Это свойство позволяет разработчикам получать или изменять метаданные имени автора, предоставляя ценную информацию о создателе изображения. Используя свойство Author Name, пользователи могут легко определить лицо, отвечающее за создание или вклад в изображение, улучшая общие метаданные и предоставляя ценный контекст для зрителей. Это поле состоит из 40 ASCII‑символов для имени. Если поле используется, оно должно содержать имя человека, создавшего изображение (автор).

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Получает или задаёт имя автора, связанное с изображением. Это свойство позволяет разработчикам получать или изменять метаданные имени автора, предоставляя ценную информацию о создателе изображения. Используя свойство Author Name, пользователи могут легко определить лицо, отвечающее за создание или вклад в изображение, улучшая общие метаданные и предоставляя ценный контекст для зрителей. Это поле состоит из 40 ASCII‑символов для имени. Если поле используется, оно должно содержать имя человека, создавшего изображение (автор).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Author Name. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Получает отметку даты/времени. Это поле определяет значение даты и времени сохранения изображения. Хотя операционные системы обычно ставят метки даты и времени на файлы, эта возможность предоставлена, потому что ОС может изменить метку даты и времени при копировании файла. Используя эту область, вы гарантируете неизменный регион для записи даты и времени.

**Returns:**
java.util.Date — отметка даты/времени.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Устанавливает метку даты/времени. Это поле определяет значение даты и времени, когда изображение было сохранено. Хотя операционные системы обычно ставят метки даты и времени на файлы, эта функция предоставляется, потому что ОС может изменить метку даты и времени при копировании файла. Используя эту область, вы гарантируете неизменную область для записи даты и времени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Метка даты/времени. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


Получает или задает имя задания или идентификатор, связанные с изображением. Это свойство позволяет получать или изменять метаданные, связанные с конкретным заданием или проектом, к которому относится изображение. Используя свойство Job Name/ID, пользователи могут легко определить проект или задачу, к которой относится изображение, облегчая организацию и управление ресурсами изображений в рамках более крупных рабочих процессов или проектов.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Получает или задает имя задания или идентификатор, связанные с изображением. Это свойство позволяет получать или изменять метаданные, связанные с конкретным заданием или проектом, к которому относится изображение. Используя свойство Job Name/ID, пользователи могут легко определить проект или задачу, к которой относится изображение, облегчая организацию и управление ресурсами изображений в рамках более крупных рабочих процессов или проектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Получает или задает метку времени, указывающую время задания, связанное с изображением. Это свойство позволяет разработчикам получать или изменять метаданные времени, связанные с конкретным заданием или проектом, к которому относится изображение.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Получает или задает метку времени, указывающую время задания, связанное с изображением. Это свойство позволяет разработчикам получать или изменять метаданные времени, связанные с конкретным заданием или проектом, к которому относится изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date | Job Time. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Получает или задает ключевой цвет, связанный с изображением. Это свойство позволяет получать или изменять цвет, назначенный в качестве ключевого цвета для конкретных задач или эффектов обработки изображений. Использование свойства Key Color позволяет пользователям применять операции, основанные на цвете, такие как хромакейинг или замена цвета, расширяя возможности манипуляции изображением и творческие возможности.

Ключевой цвет можно рассматривать как \\u2018background color\\u2019 или \\u2018transparent color\\u2019. Это цвет области экрана \\u2018non image\\u201d, и тот же цвет, в который экран будет очищен, если его стереть в приложении.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Получает или задает ключевой цвет, связанный с изображением. Это свойство позволяет получать или изменять цвет, назначенный в качестве ключевого цвета для конкретных задач или эффектов обработки изображений. Использование свойства Key Color позволяет пользователям применять операции, основанные на цвете, такие как хромакейинг или замена цвета, расширяя возможности манипуляции изображением и творческие возможности.

Ключевой цвет можно рассматривать как \\u2018background color\\u2019 или \\u2018transparent color\\u2019. Это цвет области экрана \\u2018non image\\u201d, и тот же цвет, в который экран будет очищен, если его стереть в приложении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Получает или задает логическое значение, указывающее, содержит ли изображение прозрачный цвет. Это свойство необходимо для определения, поддерживает ли изображение прозрачность, помогая реализовать соответствующую обработку операций, связанных с прозрачностью, таких как наложение, композитинг или маскирование.

**Returns:**
boolean — значение, указывающее, имеет ли изображение прозрачный цвет.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Получает или задает логическое значение, указывающее, содержит ли изображение прозрачный цвет. Это свойство необходимо для определения, поддерживает ли изображение прозрачность, помогая реализовать соответствующую обработку операций, связанных с прозрачностью, таких как наложение, композитинг или маскирование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, имеет ли изображение прозрачный цвет. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает или задает цвет фона изображения. Это свойство позволяет указать цвет, используемый для фона изображения, обеспечивая согласованность и улучшая визуальное представление. Оно особенно полезно в сценариях, когда изображение отображается на фоне другого цвета или при рендеринге изображения на другой холст.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Получает или задает цвет фона изображения. Это свойство позволяет указать цвет, используемый для фона изображения, обеспечивая согласованность и улучшая визуальное представление. Оно особенно полезно в сценариях, когда изображение отображается на фоне другого цвета или при рендеринге изображения на другой холст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | цвет фона. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Получает или задает значение, указывающее, содержит ли изображение цвет фона. Это свойство полезно для определения, включает ли изображение отдельный цвет фона, отличающийся от содержимого переднего плана. Оно позволяет настраивать обработку или рендеринг изображения в зависимости от наличия или отсутствия цвета фона.

**Returns:**
boolean — значение, указывающее, имеет ли изображение цвет фона.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Получает или задает значение, указывающее, содержит ли изображение цвет фона. Это свойство полезно для определения, включает ли изображение отдельный цвет фона, отличающийся от содержимого переднего плана. Оно позволяет настраивать обработку или рендеринг изображения в зависимости от наличия или отсутствия цвета фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, имеет ли изображение цвет фона. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Получает или задает версию программного обеспечения, связанную с изображением. Допустимая длина строки версии обычно составляет от 3 до 4 символов. Это свойство полезно для отслеживания программного обеспечения, использованного для создания или обработки изображения, и может предоставить ценную информацию для проверки совместимости и обработки изображений.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Получает или задает версию программного обеспечения, связанную с изображением. Допустимая длина строки версии обычно составляет от 3 до 4 символов. Это свойство полезно для отслеживания программного обеспечения, использованного для создания или обработки изображения, и может предоставить ценную информацию для проверки совместимости и обработки изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Software Version. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Получает или задает буквенную часть версии программного обеспечения, связанную с изображением. Это свойство представляет дополнительную деталь в строке версии программного обеспечения и может быть полезно для более точного различия версий.

**Returns:**
char - буквенная часть версии программного обеспечения.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Получает или задает буквенную часть версии программного обеспечения, связанную с изображением. Это свойство представляет дополнительную деталь в строке версии программного обеспечения и может быть полезно для более точного различия версий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char | Буквенная часть версии программного обеспечения. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Получает или задает числовой компонент версии программного обеспечения, связанной с изображением. Это свойство представляет числовую часть строки версии программного обеспечения, предоставляя важную информацию о версии программного обеспечения, использованного для создания или изменения изображения.

**Returns:**
int - числовая часть версии программного обеспечения.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Получает или задает числовой компонент версии программного обеспечения, связанной с изображением. Это свойство представляет числовую часть строки версии программного обеспечения, предоставляя важную информацию о версии программного обеспечения, использованного для создания или изменения изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Числовая часть версии программного обеспечения. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Управляет идентификацией программного обеспечения (ID), связанной с изображением, позволяя использовать до 40 символов ASCII. Это свойство служит средством уникальной идентификации программного обеспечения, использованного при создании или обработке изображения, предоставляя ценные метаданные для организационных и информационных целей.

**Returns:**
java.lang.String - Идентификатор программного обеспечения.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Управляет идентификацией программного обеспечения (ID), связанной с изображением, позволяя использовать до 40 символов ASCII. Это свойство служит средством уникальной идентификации программного обеспечения, использованного при создании или обработке изображения, предоставляя ценные метаданные для организационных и информационных целей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Идентификатор программного обеспечения. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Выполняет сравнение на равенство двух изображений TGA, учитывая как первое, так и второе изображение, участвующие в процессе сравнения. Этот метод облегчает простую оценку равенства изображений, обеспечивая точный анализ и принятие решений в рамках рабочих процессов обработки изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Первый [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), участвующий в сравнении. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Второй [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), участвующий в сравнении. |

**Returns:**
boolean - результаты сравнения.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Проводит сравнение на неравенство двух изображений TGA, оценивая как первое, так и второе изображение, участвующие в сравнении. Этот метод помогает выявлять несоответствия или различия между изображениями, обеспечивая точный анализ и принятие решений в задачах обработки изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Первый [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), участвующий в сравнении. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Второй [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), участвующий в сравнении. |

**Returns:**
boolean - результаты сравнения.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Создаёт дубликат текущего экземпляра, генерируя новый объект, который копирует все атрибуты и свойства оригинала. Этот метод облегчает создание идентичных копий, обеспечивая целостность данных и сохраняет состояние текущего экземпляра без влияния на оригинальный объект.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Копирует свойства другого объекта [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), создавая новый экземпляр с идентичными атрибутами. Эта операция обеспечивает сохранение целостности данных и облегчает дублирование свойств изображения без изменения исходного объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Другой [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


При сравнении на равенство метод оценивает, равен ли текущий экземпляр [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) второму изображению, переданному в качестве параметра. Эта операция облегчает определение того, являются ли два изображения TGA идентичными, помогая в задачах обработки и сравнения изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Второй [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), участвующий в сравнении. |

**Returns:**
boolean - результаты сравнения.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Метод выполняет сравнение на равенство между текущим экземпляром [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) и другим объектом, переданным в качестве параметра. В частности, он оценивает, совпадают ли свойства текущего изображения со свойствами второго объекта, помогая определить их эквивалентность для целей сравнения в рамках рабочих процессов обработки изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | java.lang.Object | Второй [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), участвующий в сравнении. |

**Returns:**
boolean - результаты сравнения.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Метод "rotateFlip" позволяет выполнять операции вращения и отражения изображения. Он предлагает универсальные возможности для изменения ориентации изображения, позволяя пользователям выполнять вращения и отражения в соответствии с их требованиями, облегчая эффективную обработку изображений в программных приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | int | Тип вращения и отражения. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Получите хеш‑код текущего экземпляра. Однако следует отметить, что этот хеш‑код может быть непригоден для использования в качестве ключа, особенно потому, что экземпляры класса TgaImage не являются неизменяемыми.

**Returns:**
int - хеш‑код этого экземпляра.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Обрезать изображение до указанного региона. Этот метод позволяет определить прямоугольную область внутри изображения, которую следует сохранить, отбрасывая остальное. Эта операция полезна для фокусировки на конкретном содержимом изображения или удаления нежелательных частей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Обрезать изображение, указав сдвиги для левых, правых, верхних и нижних границ. Этот метод позволяет обрезать изображение, перемещая его границы независимо по горизонтальной и вертикальной осям. Регулируя эти сдвиги, вы можете точно контролировать, какие части изображения сохранять, эффективно обрезая его до требуемых размеров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftShift | int | Левый сдвиг. |
| rightShift | int | Правый сдвиг. |
| topShift | int | Верхний сдвиг. |
| bottomShift | int | Нижний сдвиг. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Изменить размер изображения, применяя определённые настройки для поддержания требуемых размеров и соотношения сторон. Настраивая параметры изображения, вы можете эффективно изменить его размер, обеспечивая оптимальное визуальное качество и совместимость с различными устройствами отображения или приложениями.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Регулирует размер изображения с использованием указанного типа изменения размера, который определяет, как выполняется операция масштабирования. Этот метод обеспечивает гибкость при изменении размеров изображений в соответствии с различными алгоритмами или техниками. Выбирая подходящий тип изменения размера, вы можете достичь желаемого баланса между качеством изображения и вычислительной эффективностью в зависимости от конкретных требований или предпочтений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| resizeType | int | Тип изменения размера. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Поворачивает изображение вокруг его центра на заданный угол, сохраняя пропорциональность изменения размера и сохраняет цвет фона. Этот метод позволяет точно манипулировать изображением, обеспечивая сохранение визуального баланса и согласованности с указанным цветом фона при вращении. Он идеален для задач, где необходим точный поворот вокруг центра, например корректировка ориентации или художественные корректировки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resizeProportionally | boolean | если установить `true`, размер вашего изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только `` содержимое изображения. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Цвет фона. |

