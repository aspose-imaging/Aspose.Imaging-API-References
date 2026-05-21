---
title: "VectorRasterizationOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры векторной растеризации."
type: docs
weight: 52
url: /ru/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

Параметры векторной растеризации. Обратите внимание, что [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) более не будет наследоваться от [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) начиная с версии Aspose.Imaging 24.12.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Получает режим сглаживания. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Устанавливает режим сглаживания. |
| [getBorderX()](#getBorderX--) | Получает или задает границу X. |
| [setBorderX(float value)](#setBorderX-float-) | Получает или задает границу X. |
| [getBorderY()](#getBorderY--) | Получает или задает границу Y. |
| [setBorderY(float value)](#setBorderY-float-) | Получает или задает границу Y. |
| [getCenterDrawing()](#getCenterDrawing--) | Получает значение, указывающее, включено ли центрирование рисования. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Устанавливает значение, указывающее, следует ли центрировать рисование. |
| [getPageHeight()](#getPageHeight--) | Получает высоту страницы. |
| [setPageHeight(float value)](#setPageHeight-float-) | Устанавливает высоту страницы. |
| [getPageSize()](#getPageSize--) | Получает размер страницы. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Устанавливает размер страницы. |
| [getPageWidth()](#getPageWidth--) | Получает ширину страницы. |
| [setPageWidth(float value)](#setPageWidth-float-) | Устанавливает ширину страницы. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Устанавливает цвет фона. |
| [getDrawColor()](#getDrawColor--) | Получает цвет переднего плана. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Устанавливает цвет переднего плана. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Получает подсказку рендеринга текста. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Устанавливает подсказку рендеринга текста. |
| [getPositioning()](#getPositioning--) | Получает позиционирование. |
| [setPositioning(int value)](#setPositioning-int-) | Устанавливает позиционирование. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Получает сопоставление замены текста. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Устанавливает сопоставление замены текста. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Копирует этот экземпляр в `vectorRasterizationOptions`. |
| [deepClone()](#deepClone--) | Создаёт поверхностную копию объекта. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Получает режим сглаживания.

**Returns:**
int - режим сглаживания.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Устанавливает режим сглаживания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | режим сглаживания. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки изображения.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Для растеризации SVG необходимо указать параметры растеризации.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Установите цвет фона по умолчанию для изображения. Значение по умолчанию — белый.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Установите размер страницы
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Сглаживание применяется к линиям и кривым, а также к краям заполненных областей.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Каждый символ отрисовывается с использованием его сглаженного глифового битмапа без хинтинга.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Уменьшите размер изображения в 10 раз, то есть размер вывода будет 10 % от оригинального.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Сохранить в файл PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Получает или задает границу X.

**Returns:**
float - граница X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Получает или задает границу X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Граница X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Получает или задает границу Y.

**Returns:**
float - граница Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Получает или задает границу Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Граница Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Получает значение, указывающее, включено ли центрирование рисования.

**Returns:**
boolean - значение, указывающее, следует ли центрировать рисование.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Устанавливает значение, указывающее, следует ли центрировать рисование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, следует ли центрировать рисование. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Получает высоту страницы.

**Returns:**
float - высота страницы.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Устанавливает высоту страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | высота страницы. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Получает размер страницы.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Устанавливает размер страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | размер страницы. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Текст будет преобразован в фигуры.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Размер страницы.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Если встроенный emf существует, отобразите emf; иначе отобразите wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — это единый способ загрузки всех типов изображений, включая EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Текст будет преобразован в фигуры.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Размер страницы.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Если встроенный emf существует, отобразите emf; иначе отобразите wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Установите горизонтальный отступ
    rasterizationOptions.setBorderX(50);

    // Установите вертикальный отступ
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Получает ширину страницы.

**Returns:**
float - ширина страницы.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Устанавливает ширину страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | ширина страницы. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет фона.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает цвет фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | цвет фона. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки всех типов изображений, включая WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Текст будет преобразован в фигуры.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Размер страницы.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Если встроенный emf существует, отобразите emf; иначе отобразите wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — это единый способ загрузки всех типов изображений, включая EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Текст будет преобразован в фигуры.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Цвет фона поверхности рисования.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Размер страницы.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Если встроенный emf существует, отобразите emf; иначе отобразите wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Установите горизонтальный отступ
    rasterizationOptions.setBorderX(50);

    // Установите вертикальный отступ
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Получает цвет переднего плана.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Устанавливает цвет переднего плана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | цвет переднего плана. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Получает подсказку рендеринга текста.

Значение: Подсказка рендеринга текста.

**Returns:**
int - подсказка рендеринга текста.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Устанавливает подсказку рендеринга текста.

Значение: Подсказка рендеринга текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | подсказка рендеринга текста. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Использование Aspose.Imaging.Image.Load — единый способ загрузки изображения.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Для растеризации SVG необходимо указать параметры растеризации.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Установите цвет фона по умолчанию для изображения. Значение по умолчанию — белый.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Установите размер страницы
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Сглаживание применяется к линиям и кривым, а также к краям заполненных областей.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Каждый символ отрисовывается с использованием его сглаженного глифового битмапа без хинтинга.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Уменьшите размер изображения в 10 раз, то есть размер вывода будет 10 % от оригинального.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // Сохранить в файл PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Получает позиционирование.

Значение: позиционирование.

**Returns:**
int - позиционирование.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Устанавливает позиционирование.

Значение: позиционирование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | позиционирование. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Получает сопоставление замены текста.

Значение: сопоставление замены текста.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - сопоставление замены текста.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Устанавливает сопоставление замены текста.

Значение: сопоставление замены текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.HashMap<java.lang.String,java.lang.String> | сопоставление замены текста. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Копирует этот экземпляр в `vectorRasterizationOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Параметры векторной растеризации. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


Создаёт поверхностную копию объекта.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
