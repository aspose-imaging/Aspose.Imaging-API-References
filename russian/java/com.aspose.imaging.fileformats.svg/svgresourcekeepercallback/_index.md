---
title: "SvgResourceKeeperCallback"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Обратный вызов хранителя ресурсов"
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.svg/svgresourcekeepercallback/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback)
```
public class SvgResourceKeeperCallback implements ISvgResourceKeeperCallback
```

Обратный вызов хранителя ресурсов
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgResourceKeeperCallback()](#SvgResourceKeeperCallback--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)](#onImageResourceReady-byte---int-java.lang.String-boolean---) | Вызывается, когда ресурс изображения готов к экспорту. |
| [onFontResourceReady(FontStoringArgs args)](#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-) | Вызывается, когда ресурс шрифта готов к экспорту. |
| [onSvgDocumentReady(byte[] htmlData, String suggestedFileName)](#onSvgDocumentReady-byte---java.lang.String-) | Вызывается, когда документ SVG готов к экспорту. |
### SvgResourceKeeperCallback() {#SvgResourceKeeperCallback--}
```
public SvgResourceKeeperCallback()
```


### onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage) {#onImageResourceReady-byte---int-java.lang.String-boolean---}
```
public String onImageResourceReady(byte[] imageData, int imageType, String suggestedFileName, boolean[] useEmbeddedImage)
```


Вызывается, когда ресурс изображения готов к экспорту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageData | byte[] | Данные ресурса. |
| imageType | int | Тип изображения. |
| suggestedFileName | java.lang.String | Имя предлагаемого файла. |
| useEmbeddedImage | boolean[] | если установлено `true`, необходимо использовать встроенное изображение. |

**Returns:**
java.lang.String - Возвращает путь к сохранённому ресурсу. Путь должен быть относительным к целевому документу SVG.
### onFontResourceReady(FontStoringArgs args) {#onFontResourceReady-com.aspose.svg.options.FontStoringArgs-}
```
public void onFontResourceReady(FontStoringArgs args)
```


Вызывается, когда ресурс шрифта готов к экспорту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | com.aspose.svg.options.FontStoringArgs | Параметры сохранения шрифта. |

### onSvgDocumentReady(byte[] htmlData, String suggestedFileName) {#onSvgDocumentReady-byte---java.lang.String-}
```
public String onSvgDocumentReady(byte[] htmlData, String suggestedFileName)
```


Вызывается, когда документ SVG готов к экспорту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlData | byte[] | Данные SVG. |
| suggestedFileName | java.lang.String | Имя предлагаемого файла. |

**Returns:**
java.lang.String - Возвращает путь к сохранённому документу SVG.
