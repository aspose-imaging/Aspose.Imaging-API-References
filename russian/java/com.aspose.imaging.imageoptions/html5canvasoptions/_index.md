---
title: "Html5CanvasOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте файлы HTML5 Canvas без усилий с помощью нашего API, позволяющего без проблем комбинировать такие элементы, как формы, текст, изображения, анимации и ссылки."
type: docs
weight: 23
url: /ru/java/com.aspose.imaging.imageoptions/html5canvasoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Html5CanvasOptions extends ImageOptionsBase
```

Создавайте файлы HTML5 Canvas без усилий с помощью нашего API, позволяющего без проблем комбинировать такие элементы, как формы, текст, изображения, анимации и ссылки. Получайте преимущества от надёжных функций, включая поддержку идентификатора тега и параметров кодирования, обеспечивая оптимальную производительность и настройку для ваших веб‑проектов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Html5CanvasOptions()](#Html5CanvasOptions--) | Инициализирует новый экземпляр класса [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions). |
| [Html5CanvasOptions(Html5CanvasOptions imageOptions)](#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-) | Инициализирует новый экземпляр класса `ImageOptionsBase`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCanvasTagId()](#getCanvasTagId--) | Получает идентификатор тега canvas. |
| [setCanvasTagId(String value)](#setCanvasTagId-java.lang.String-) | Устанавливает идентификатор тега canvas. |
| [getFullHtmlPage()](#getFullHtmlPage--) | Получает значение, указывающее, следует ли генерировать полную HTML‑страницу. |
| [setFullHtmlPage(boolean value)](#setFullHtmlPage-boolean-) | Устанавливает значение, указывающее, следует ли генерировать полную HTML‑страницу. |
| [getEncoding()](#getEncoding--) | Получает кодировку. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Устанавливает кодировку. |

## Example: Any vector image (SVG, WMF, CMX, etc.
Любое векторное изображение (SVG, WMF, CMX и т.д.) может использоваться в качестве источника для ваших изображений Canvas. Следующий код создаёт простое изображение Canvas.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save("Canvas.html", options);
}
```


## Example: You can embed more than one Canvas image within HTML page or update already existing page.
Вы можете встроить более одного изображения Canvas в HTML‑страницу или обновить уже существующую страницу. Для этого необходимо экспортировать только тег Canvas.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### Html5CanvasOptions() {#Html5CanvasOptions--}
```
public Html5CanvasOptions()
```


Инициализирует новый экземпляр класса [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions).

### Html5CanvasOptions(Html5CanvasOptions imageOptions) {#Html5CanvasOptions-com.aspose.imaging.imageoptions.Html5CanvasOptions-}
```
public Html5CanvasOptions(Html5CanvasOptions imageOptions)
```


Инициализирует новый экземпляр класса `ImageOptionsBase`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [Html5CanvasOptions](../../com.aspose.imaging.imageoptions/html5canvasoptions) | Параметры изображения. |

### getCanvasTagId() {#getCanvasTagId--}
```
public final String getCanvasTagId()
```


Получает идентификатор тега canvas.

**Returns:**
java.lang.String — идентификатор тега canvas.
### setCanvasTagId(String value) {#setCanvasTagId-java.lang.String-}
```
public final void setCanvasTagId(String value)
```


Устанавливает идентификатор тега canvas.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | идентификатор тега canvas. |

### getFullHtmlPage() {#getFullHtmlPage--}
```
public final boolean getFullHtmlPage()
```


Получает значение, указывающее, следует ли генерировать полную HTML‑страницу.

**Returns:**
boolean — значение, указывающее, следует ли генерировать полную HTML‑страницу.
### setFullHtmlPage(boolean value) {#setFullHtmlPage-boolean-}
```
public final void setFullHtmlPage(boolean value)
```


Устанавливает значение, указывающее, следует ли генерировать полную HTML‑страницу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, следует ли генерировать полную HTML‑страницу. |


**Example: You can embed more than one Canvas image within HTML page or update already existing page.**
Вы можете встроить более одного изображения Canvas в HTML‑страницу или обновить уже существующую страницу. Для этого необходимо экспортировать только тег Canvas.
``` java
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("Sample.svg"))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.Html5CanvasOptions options = new com.aspose.imaging.imageoptions.Html5CanvasOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setFullHtmlPage(false);
    image.save("Canvas.html", options);
}
```

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Получает кодировку.

**Returns:**
java.nio.charset.Charset — кодировка.
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Устанавливает кодировку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.nio.charset.Charset | кодировка. |

