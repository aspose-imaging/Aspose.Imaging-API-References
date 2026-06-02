---
title: "CmxImageSpec"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет информацию, указанную для растровых изображений."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxImageSpec implements ICmxObjectSpec
```

Представляет информацию, указанную для растровых изображений.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CmxImageSpec()](#CmxImageSpec--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBoundBox()](#getBoundBox--) | Получает ограничивающий прямоугольник. |
| [setBoundBox(RectangleF value)](#setBoundBox-com.aspose.imaging.RectangleF-) | Устанавливает ограничивающий прямоугольник. |
| [getCropBox()](#getCropBox--) | Получает область обрезки. |
| [setCropBox(RectangleF value)](#setCropBox-com.aspose.imaging.RectangleF-) | Устанавливает область обрезки. |
| [getMatrix()](#getMatrix--) | Получает матрицу преобразования. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.imaging.Matrix-) | Устанавливает матрицу преобразования. |
| [getImageType()](#getImageType--) | Получает тип изображения. |
| [setImageType(int value)](#setImageType-int-) | Устанавливает тип изображения. |
| [getImages()](#getImages--) | Получает изображения. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Устанавливает изображения. |
| [isCmx3Image()](#isCmx3Image--) | Получает значение, указывающее, является ли этот экземпляр изображением CMX3. |
| [setCmx3Image(boolean value)](#setCmx3Image-boolean-) | Устанавливает значение, указывающее, является ли этот экземпляр изображением CMX3. |
| [toString()](#toString--) | Возвращает строку, представляющую этот экземпляр. |
| [toArray()](#toArray--) |  |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### CmxImageSpec() {#CmxImageSpec--}
```
public CmxImageSpec()
```


### getBoundBox() {#getBoundBox--}
```
public final RectangleF getBoundBox()
```


Получает ограничивающий прямоугольник.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bound box.
### setBoundBox(RectangleF value) {#setBoundBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundBox(RectangleF value)
```


Устанавливает ограничивающий прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | ограничивающий прямоугольник. |

### getCropBox() {#getCropBox--}
```
public final RectangleF getCropBox()
```


Получает область обрезки.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the crop box.
### setCropBox(RectangleF value) {#setCropBox-com.aspose.imaging.RectangleF-}
```
public final void setCropBox(RectangleF value)
```


Устанавливает область обрезки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | обрезная рамка. |

### getMatrix() {#getMatrix--}
```
public final Matrix getMatrix()
```


Получает матрицу преобразования.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - the transformation matrix.
### setMatrix(Matrix value) {#setMatrix-com.aspose.imaging.Matrix-}
```
public final void setMatrix(Matrix value)
```


Устанавливает матрицу преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | матрица преобразования. |

### getImageType() {#getImageType--}
```
public final int getImageType()
```


Получает тип изображения.

**Returns:**
int - тип изображения.
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Устанавливает тип изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | тип изображения. |

### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Получает изображения.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - изображения.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Устанавливает изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | изображения. |

### isCmx3Image() {#isCmx3Image--}
```
public final boolean isCmx3Image()
```


Получает значение, указывающее, является ли этот экземпляр изображением CMX3.

Значение: `true`, если данный экземпляр является изображением CMX3; в противном случае `false`.

**Returns:**
boolean - значение, указывающее, является ли данный экземпляр изображением CMX3.
### setCmx3Image(boolean value) {#setCmx3Image-boolean-}
```
public final void setCmx3Image(boolean value)
```


Устанавливает значение, указывающее, является ли этот экземпляр изображением CMX3.

Значение: `true`, если данный экземпляр является изображением CMX3; в противном случае `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, является ли данный экземпляр изображением CMX3. |

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую этот экземпляр.

**Returns:**
java.lang.String - Строка, представляющая этот экземпляр.
### toArray() {#toArray--}
```
public CmxRasterImage[] toArray()
```




**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[]
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Проверяет, равны ли объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Другой объект. |

**Returns:**
boolean - Результат сравнения на равенство.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код текущего объекта.

**Returns:**
int - Хеш-код.
