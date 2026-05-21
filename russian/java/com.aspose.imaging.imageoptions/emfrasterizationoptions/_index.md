---
title: "EmfRasterizationOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Опции растеризации EMF."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.imageoptions/emfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class EmfRasterizationOptions extends MetafileRasterizationOptions
```

Опции растеризации EMF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRasterizationOptions()](#EmfRasterizationOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Получает или задает режим рендеринга. |
| [setRenderMode(int value)](#setRenderMode-int-) | Получает или задает режим рендеринга. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Копирует это в `vectorRasterizationOptions`. |
### EmfRasterizationOptions() {#EmfRasterizationOptions--}
```
public EmfRasterizationOptions()
```


### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Получает или задает режим рендеринга.

**Returns:**
int — режим рендеринга.
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Получает или задает режим рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Режим рендеринга. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Копирует это в `vectorRasterizationOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

