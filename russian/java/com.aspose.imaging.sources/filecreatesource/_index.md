---
title: "FileCreateSource"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет файловый источник для создания."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Представляет файловый источник для создания.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Инициализирует новый экземпляр класса `FileCreateSource`. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Инициализирует новый экземпляр класса `FileCreateSource`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFilePath()](#getFilePath--) | Получает путь к файлу для создания. |
| [isTemporal()](#isTemporal--) | Получает значение, указывающее, будет ли файл временным. |
| [getStreamContainer()](#getStreamContainer--) | Получает контейнер потока. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Этот пример демонстрирует использование классов Font и SolidBrush для рисования строк на поверхности Image. Пример создаёт новое Image и рисует фигуры с помощью Figures и GraphicsPath.
``` java
//Создаёт экземпляр BmpOptions и задаёт его различные свойства.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
//Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Создаёт экземпляр Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Создаёт и инициализирует экземпляр класса Graphics.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Очищает поверхность Graphics.
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Создаёт экземпляр Font.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Создаёт экземпляр SolidBrush с красным цветом.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Рисует строку.
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Инициализирует новый экземпляр класса `FileCreateSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для создания. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Инициализирует новый экземпляр класса `FileCreateSource`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу для создания. |
| isTemporal | boolean | Если установлено `true`, созданный файл будет временным. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Получает путь к файлу для создания.

Значение: Путь к файлу для создания.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Получает значение, указывающее, будет ли файл временным.

Значение: `true`, если файл будет временным; иначе `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Получает контейнер потока.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Используйте с осторожностью. После получения вам потребуется освободить контейнер потока.
