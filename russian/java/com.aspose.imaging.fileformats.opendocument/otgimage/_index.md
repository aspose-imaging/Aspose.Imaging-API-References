---
title: "OtgImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Обрабатывайте файлы изображений чертежей OpenDocument Template OTG с помощью нашего API, используя формат OpenDocument XML с графическим содержимым для бесшовной манипуляции."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

Обрабатывайте файлы изображений чертежей OpenDocument Template (OTG) с помощью нашего API, используя формат OpenDocument XML с графическим содержимым для бесшовной манипуляции. Легко разбирайте документы, настраивайте цвета фона и регулируйте размеры страниц, обеспечивая оптимальный контроль и гибкость для ваших проектов векторной графики OTG.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Инициализируйте новый объект [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage), предоставив контейнер потока и параметры загрузки. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Создайте новый объект класса [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage), предоставив контейнер потока. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Это свойство предоставляет доступ к формату файла OTG, предлагая важную информацию о типе данных, содержащихся в файле изображения. |
| [getPages()](#getPages--) | Получает коллекцию страниц, связанных с изображением, позволяя разработчикам программного обеспечения эффективно получать доступ к каждой отдельной странице и манипулировать ею. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Инициализируйте новый объект [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage), предоставив контейнер потока и параметры загрузки. Этот конструктор позволяет разработчикам эффективно загружать OTG‑изображения из потоков, указывая пользовательские параметры загрузки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Поток. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Параметры загрузки. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Создайте новый объект класса [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage), предоставив контейнер потока. Этот конструктор позволяет разработчикам создавать OTG‑изображения напрямую из контейнеров потоков, упрощая процесс работы с данными OTG‑изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Это свойство предоставляет доступ к формату файла OTG, предлагая важную информацию о типе данных, содержащихся в файле изображения. Оно служит ключевой точкой отсчёта для разработчиков программного обеспечения, позволяя им эффективно работать с OTG‑файлами в своих приложениях. Используя это свойство, вы можете определить конкретный формат файла изображения, обеспечивая бесшовную интеграцию и манипуляцию OTG‑файлами в их программных системах.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


Получает коллекцию страниц, связанных с изображением, позволяя разработчикам программного обеспечения эффективно получать доступ к каждой отдельной странице и манипулировать ею. Это свойство обеспечивает беспрепятственное перебирание страниц для различных операций, повышая функциональность и универсальность приложений обработки изображений.

**Returns:**
com.aspose.imaging.Image[] — страницы.
