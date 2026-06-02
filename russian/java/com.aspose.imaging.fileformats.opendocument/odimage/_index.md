---
title: "OdImage"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Открытый документ"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

Открытый документ
## Методы

| Метод | Описание |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Получает страницу по умолчанию, связанную с изображением, обеспечивая необходимый доступ к основной странице в коллекции изображений. |
| [isCached()](#isCached--) | Получает логическое значение, указывающее, кэшированы ли данные объекта в данный момент, тем самым устраняя необходимость чтения данных. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель для изображения. |
| [getPageCount()](#getPageCount--) | Получает общее количество страниц в изображении. |
| [getOdMetadata()](#getOdMetadata--) | Получает метаданные, специфичные для файлов OpenDocument. |
| [getRecords()](#getRecords--) | Получает записи OpenDocument, хранящиеся в изображении. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Получает страницу по умолчанию, связанную с изображением, обеспечивая необходимый доступ к основной странице в коллекции изображений. Это свойство упрощает навигацию и манипуляцию данными изображения, повышая эффективность рабочих процессов разработки программного обеспечения.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Получает логическое значение, указывающее, кэшированы ли данные объекта в данный момент, тем самым устраняя необходимость чтения данных. Это свойство служит индикатором оптимизации, повышая производительность за счёт минимизации избыточных операций доступа к данным.

**Returns:**
boolean — значение, указывающее, кэшированы ли данные объекта в данный момент и требуется ли чтение данных.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения. Это свойство дает представление об уровне детализации и глубине цвета, представленных в изображении, помогая в различных задачах обработки изображений и оптимизации.

**Returns:**
int — количество бит на пиксель изображения.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Получает общее количество страниц в изображении. Это свойство необходимо для приложений, работающих с многостраничными изображениями, позволяя точно определить количество доступных страниц для обработки или отображения.

**Returns:**
int — количество страниц.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


Получает метаданные, специфичные для файлов OpenDocument. Это свойство обеспечивает доступ к важной информации, встроенной в файлы OD, облегчая различные операции, такие как извлечение, модификация или анализ метаданных.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Получает записи OpenDocument, хранящиеся в изображении. Это свойство предоставляет доступ к конкретным структурированным элементам данных, встроенным в файлы OpenDocument, облегчая извлечение или манипуляцию соответствующей информацией для дальнейшей обработки или анализа.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - записи.
