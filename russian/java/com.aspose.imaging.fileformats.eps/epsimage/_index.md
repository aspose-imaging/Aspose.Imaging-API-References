---
title: "EpsImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для поддержки формата файлов изображений Encapsulated PostScript (EPS) предлагает мощные возможности для манипулирования композициями, состоящими из текста, графики и изображений."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

API для поддержки формата файлов изображений Encapsulated PostScript (EPS) предлагает мощные возможности для манипулирования композициями, состоящими из текста, графики и изображений. Включает такие функции, как обработка растровых превью‑изображений, переключение ориентации, получение ограничивающего прямоугольника для границ иллюстрации, изменение размеров, вращение изображений и добавление превью‑изображений. Этот API обеспечивает бесшовную обработку и интеграцию EPS‑файлов в различные приложения с точностью и универсальностью.
## Методы

| Метод | Описание |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Получите количество доступных превью‑изображений с лёгкостью. |
| [getPreviewImages()](#getPreviewImages--) | Получите превью‑изображения, связанные с вашим файлом. |
| [getFileFormat()](#getFileFormat--) | Получите формат файла вашего изображения с помощью этого свойства. |
| [getEpsType()](#getEpsType--) | Получите и интерпретируйте значение подтипа вашего EPS‑изображения, упрощая рабочий процесс и повышая совместимость между платформами. |
| [hasRasterPreview()](#hasRasterPreview--) | Легко определите наличие растрового превью с помощью этого свойства. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Легко получите точную глубину цвета изображения с помощью этого свойства. |
| [getWidthF()](#getWidthF--) | Получите ширину изображения с помощью этого удобного свойства. |
| [getHeightF()](#getHeightF--) | Получите высоту изображения, используя это свойство. |
| [isCached()](#isCached--) | Это свойство предоставляет удобный способ проверить, кэшированы ли данные объекта в данный момент, устраняя необходимость дополнительного чтения данных. |
| [getPsStream()](#getPsStream--) | Получает поток, содержащий PostScript для выполнения. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Это свойство получает версию PostScript, связанную с экземпляром [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getTitle()](#getTitle--) | Это свойство получает заголовок, извлечённый из комментариев EPS Document Structuring Conventions (DSC), встроенных в EPS‑файл. |
| [getCreator()](#getCreator--) | Это свойство предоставляет доступ к информации о создателе, полученной из комментариев EPS Document Structuring Conventions (DSC), найденных в EPS‑файле. |
| [getCreationDate()](#getCreationDate--) | Получая дату создания из комментариев EPS Document Structuring Conventions (DSC), это свойство предоставляет важные метаданные, указывающие на момент создания EPS‑файла. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Получая дату создания из комментариев EPS Document Structuring Conventions (DSC), это свойство предоставляет важные метаданные, указывающие на момент создания EPS‑файла. |
| [getBoundingBox()](#getBoundingBox--) | Получая оригинальный ограничивающий прямоугольник в независимых от устройства точках, это свойство предоставляет важную геометрическую информацию о размерах [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Это свойство возвращает оригинальный ограничивающий прямоугольник экземпляра [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) в пикселях, предоставляя важные геометрические данные для точного рендеринга и манипуляций. |
| [cacheData()](#cacheData--) | Это свойство возвращает оригинальный ограничивающий прямоугольник экземпляра [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) в пикселях, предоставляя важные геометрические данные для точного рендеринга и манипуляций. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Получает доступ к превью‑изображениям, связанным с экземпляром [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), позволяя бесшовно извлекать их для проверки или использования в приложениях. |
| [getPreviewImage()](#getPreviewImage--) | Получает существующее превью‑изображение в указанном `format` или возвращает ``, если оно не найдено. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Получает существующее превью‑изображение в указанном `format` или возвращает ``, если оно не найдено. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Настройте палитры изображений, чтобы создать уникальные цветовые схемы и улучшить визуальную привлекательность. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// Загрузить EPS‑изображение
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Изменить размер изображения с использованием метода кубической интерполяции Mitchell
    image.resize(400, 400, ResizeType.Mitchell);

    // Экспортировать изображение в формат PNG
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// Загрузить EPS‑изображение
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Установить режим интерполяции
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Установить тип фильтра
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Устанавливает метод сравнения цветов
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Установить метод квантования цветов
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Изменить размер изображения с использованием расширенных настроек масштабирования
    image.resize(400, 400, resizeSettings);

    // Экспортировать изображение в формат PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Получите количество доступных превью‑изображений с лёгкостью. Это свойство позволяет без усилий получить число превью‑изображений, связанных с вашим файлом, обеспечивая эффективное управление и навигацию по превью ваших изображений. Идеально подходит для оптимизации рабочего процесса и эффективной организации ваших графических ресурсов.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Получите превью‑изображения, связанные с вашим файлом. Это свойство обеспечивает бесшовный доступ к коллекции превью‑изображений, позволяя эффективно просматривать и управлять ими по мере необходимости. Идеально подходит для быстрого предварительного просмотра и выбора подходящего изображения для вашего проекта.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получите формат файла вашего изображения с помощью этого свойства. Получите важную информацию о формате вашего графического файла, способствуя совместимости и эффективной обработке. Идеально подходит для определения формата ваших изображений для бесшовной интеграции в проекты.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


Получайте доступ и интерпретируйте значение подтипа вашего EPS‑изображения, упрощая рабочий процесс и повышая совместимость между платформами. Идеально подходит для точного и эффективного получения подтипа EPS в ваших проектах.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Легко определяйте наличие растрового предварительного просмотра с помощью этого свойства. Получайте логическое значение, указывающее, содержит ли экземпляр [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) растровый предварительный просмотр, что повышает ясность и эффективность ваших задач обработки изображений. Идеально подходит для упрощения принятия решений в рабочем процессе на основе наличия или отсутствия растровых предварительных просмотров в EPS‑изображениях.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Легко получайте точную глубину цвета изображения с помощью этого свойства. Извлекайте количество бит на пиксель, получая важную информацию о цветовой глубине изображения и помогая оптимизировать задачи обработки. Идеально подходит для приложений, требующих тонкого контроля над манипуляцией и анализом изображений.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Получайте ширину изображения с помощью этого удобного свойства. Легко получайте ширину изображения, облегчая точные расчёты макета, операции масштабирования и задачи, связанные с размерами, в вашем приложении. Идеально подходит для обеспечения точного отображения и рендеринга изображений на различных платформах и устройствах.

**Returns:**
float — ширина изображения в пикселях.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Получайте высоту изображения с помощью этого свойства. Легко получайте высоту изображения, позволяя бесшовно настраивать макет, вычислять соотношение сторон и обеспечивать точный рендеринг на разных разрешениях экрана и в различных средах отображения.

**Returns:**
float — высота изображения в пикселях.
### isCached() {#isCached--}
```
public boolean isCached()
```


Это свойство предоставляет удобный способ проверить, кэшированы ли данные объекта в данный момент, исключая необходимость дополнительного чтения данных. Оно предлагает быстрый и эффективный метод определить, доступна ли необходимая информация, оптимизируя производительность и снижая нагрузку на ресурсы в операциях с большим объёмом данных.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Получает поток, содержащий PostScript для выполнения.

**Returns:**
java.io.InputStream — поток, содержащий PostScript для выполнения.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Это свойство извлекает версию PostScript, связанную с экземпляром [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Оно предоставляет информацию о конкретной версии языка PostScript, используемой в EPS‑файле, помогая оценить совместимость и облегчая бесшовную интеграцию со средами, поддерживающими PostScript.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


Это свойство извлекает заголовок, полученный из комментариев EPS Document Structuring Conventions (DSC), встроенных в EPS‑файл. Оно предоставляет ценные метаданные о содержимом EPS‑файла, помогая в организации документов и их идентификации в совместимых программных приложениях.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Это свойство предоставляет доступ к информации о создателе, полученной из комментариев EPS Document Structuring Conventions (DSC), найденных в EPS‑файле. Понимание данных о создателе дает представление о программном обеспечении или инструменте, использованном для создания EPS‑файла, облегчая оценку совместимости на разных платформах и в приложениях.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


Извлекая дату создания из комментариев EPS Document Structuring Conventions (DSC), это свойство предоставляет важные метаданные, указывающие на момент создания EPS‑файла. Получая эту информацию, пользователи получают представление о происхождении и хронологии файла, улучшая управление и организацию файлов.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


Извлекая дату создания из комментариев EPS Document Structuring Conventions (DSC), это свойство предоставляет важные метаданные, указывающие на момент создания EPS‑файла. Получая эту информацию, пользователи получают представление о происхождении и хронологии файла, улучшая управление и организацию файлов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Получая оригинальный ограничивающий прямоугольник в независимых от устройства точках, это свойство предоставляет важную геометрическую информацию о размерах [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). Извлекая эти данные, пользователи могут точно оценить размер и соотношение сторон изображения, облегчая точную компоновку и позиционирование в различных приложениях.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Это свойство возвращает оригинальный ограничивающий прямоугольник экземпляра [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) в пикселях, предоставляя важные геометрические данные для точного рендеринга и манипуляций. Имея эту информацию, пользователи могут обеспечить точное размещение и масштабирование EPS‑изображений в своих проектах, улучшая общую визуальную презентацию и качество.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


Это свойство возвращает оригинальный ограничивающий прямоугольник экземпляра [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) в пикселях, предоставляя важные геометрические данные для точного рендеринга и манипуляций. Имея эту информацию, пользователи могут обеспечить точное размещение и масштабирование EPS‑изображений в своих проектах, улучшая общую визуальную презентацию и качество.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


Получает доступ к превью‑изображениям, связанным с экземпляром [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage), позволяя беспрепятственно извлекать их для просмотра или использования в приложениях. Этот метод обеспечивает удобный доступ к превью‑изображениям, улучшая взаимодействие пользователя с данными изображения.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> — превью‑изображения.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Извлекает существующее превью‑изображение в указанном `format` или возвращает ``, если оно не найдено. Этот метод предоставляет гибкость доступа к превью‑изображениям, адаптированным к конкретным форматам, оптимизируя совместимость и управление ресурсами в приложениях.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Извлекает существующее превью‑изображение в указанном `format` или возвращает ``, если оно не найдено. Этот метод предоставляет гибкость доступа к превью‑изображениям, адаптированным к конкретным форматам, оптимизируя совместимость и управление ресурсами в приложениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| format | long | Формат превью‑изображения EPS. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Настраивайте палитры изображений для создания уникальных цветовых схем и повышения визуальной привлекательности. Подбирайте цвета для конкретных эффектов и легко оптимизируйте качество изображения на разных платформах и устройствах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра для установки. |
| updateColors | boolean | Если установить значение `true`, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся неизменными. Обратите внимание, что неизменные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей в палитре. |

