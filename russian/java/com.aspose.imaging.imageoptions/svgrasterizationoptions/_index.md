---
title: "SvgRasterizationOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры растеризации SVG."
type: docs
weight: 46
url: /ru/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

Параметры растеризации SVG.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | Инициализирует новый экземпляр класса `SvgRasterizationOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getScaleX()](#getScaleX--) | Получает или задает масштаб x. |
| [setScaleX(float value)](#setScaleX-float-) | Получает или задает масштаб x. |
| [getScaleY()](#getScaleY--) | Получает или задает масштаб y. |
| [setScaleY(float value)](#setScaleY-float-) | Получает или задает масштаб y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Копирует этот экземпляр в `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


Инициализирует новый экземпляр класса `SvgRasterizationOptions`.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Получает или задает масштаб x.

**Returns:**
float - масштаб x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Получает или задает масштаб x.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Масштаб x. |


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

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Получает или задает масштаб y.

**Returns:**
float - масштаб y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Получает или задает масштаб y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Масштаб y. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Копирует этот экземпляр в `vectorRasterizationOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Параметры векторной растеризации. |

