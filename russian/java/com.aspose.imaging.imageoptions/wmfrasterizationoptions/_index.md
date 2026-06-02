---
title: "WmfRasterizationOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Параметры растеризации Wmf."
type: docs
weight: 55
url: /ru/java/com.aspose.imaging.imageoptions/wmfrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions), [com.aspose.imaging.imageoptions.MetafileRasterizationOptions](../../com.aspose.imaging.imageoptions/metafilerasterizationoptions)
```
public class WmfRasterizationOptions extends MetafileRasterizationOptions
```

Параметры растеризации Wmf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfRasterizationOptions()](#WmfRasterizationOptions--) | Инициализирует новый экземпляр класса `WmfRasterizationOptions`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRenderMode()](#getRenderMode--) | Получает или задает режим рендеринга WMF. |
| [setRenderMode(int value)](#setRenderMode-int-) | Получает или задает режим рендеринга WMF. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Копирует это в `vectorRasterizationOptions`. |
### WmfRasterizationOptions() {#WmfRasterizationOptions--}
```
public WmfRasterizationOptions()
```


Инициализирует новый экземпляр класса `WmfRasterizationOptions`.

### getRenderMode() {#getRenderMode--}
```
public int getRenderMode()
```


Получает или задает режим рендеринга WMF.

Значение: режим рендеринга WMF.

**Returns:**
int
### setRenderMode(int value) {#setRenderMode-int-}
```
public void setRenderMode(int value)
```


Получает или задает режим рендеринга WMF.

Значение: режим рендеринга WMF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Копирует это в `vectorRasterizationOptions`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | vectorRasterizationOptions |

