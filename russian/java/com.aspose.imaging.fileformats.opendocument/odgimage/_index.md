---
title: "OdgImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Манипулируйте векторным форматом графических файлов OpenDocument ODG с помощью нашего API, широко используемого в приложениях OpenOffice и LibreOffice Draw для хранения элементов рисунка в векторном формате."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

Манипулируйте векторным форматом графических файлов OpenDocument (ODG) с помощью нашего API, широко используемого в приложениях OpenOffice и LibreOffice Draw для хранения элементов рисунка в векторном формате. Беспрепятственно разбирайте документы, получайте доступ к страницам, изменяйте размер и вращайте изображения, обеспечивая эффективную обработку и настройку ODG‑файлов в соответствии с вашими конкретными требованиями.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Начните создание нового объекта класса [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) с инициацией свежего экземпляра. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Разработанный для бесшовной интеграции в программные решения, конструктор [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) инициализирует новый экземпляр, используя контейнер потока. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Легко получить значение формата файла с помощью этого удобного свойства. |
| [getPages()](#getPages--) | Получая коллекцию страниц, это свойство позволяет получить доступ ко всем страницам, связанным с изображением. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки изображения.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // Привести к OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Получить все страницы
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Выполните некоторую обработку изображения
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Начните создание нового объекта класса [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) с инициацией свежего экземпляра. Используйте потенциал контейнера потока в сочетании с параметрами опций загрузки, поддерживая универсальный конструктор для беспрепятственной загрузки изображений. Этот конструктор обеспечивает эффективную работу с изображениями, предлагая настраиваемые конфигурации загрузки для повышения адаптивности и производительности в различных сценариях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Поток. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Разработанный для бесшовной интеграции в программные решения, конструктор [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) инициализирует новый экземпляр, используя контейнер потока. Этот метод обеспечивает эффективную работу с данными ODG‑изображений в программных средах, оптимизируя использование ресурсов и упрощая рабочие процессы обработки изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Легко получить значение формата файла с помощью этого удобного свойства. Идеально для разработчиков, которым нужен быстрый доступ к информации о формате файла.

**Returns:**
long — значение формата файла
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получая коллекцию страниц, это свойство позволяет получить доступ ко всем страницам, связанным с изображением. Получая доступ к этому свойству, разработчики могут перебрать отдельные страницы, извлечь конкретные страницы по их индексу или выполнить пакетные операции над всей коллекцией.

**Returns:**
com.aspose.imaging.Image[] — страницы.
