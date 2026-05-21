---
title: "DxfOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "API для создания векторных изображений в формате Drawing Interchange Format (DXF) предлагает адаптированные решения для генерации файлов чертежей AutoCAD с точностью и гибкостью."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.imageoptions/dxfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DxfOptions extends ImageOptionsBase
```

API для создания векторных изображений в формате Drawing Interchange Format (DXF) предлагает адаптированные решения для генерации файлов чертежей AutoCAD с точностью и гибкостью. Специально разработан для работы с текстовыми линиями и кривыми Безье, разработчики могут эффективно управлять этими элементами, подсчитывать точки Безье и преобразовывать кривые в полилинии для бесшовного экспорта, обеспечивая совместимость и достоверность в DXF‑векторных изображениях.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DxfOptions()](#DxfOptions--) |  |
| [DxfOptions(DxfOptions imageOptions)](#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-) | Конструктор копирования |
## Методы

| Метод | Описание |
| --- | --- |
| [getBezierPointCount()](#getBezierPointCount--) | Сколько точек генерировать при преобразовании кривых Безье в полилинии, минимум 4. |
| [setBezierPointCount(byte value)](#setBezierPointCount-byte-) | Сколько точек генерировать при преобразовании кривых Безье в полилинии, минимум 4. |
| [getConvertTextBeziers()](#getConvertTextBeziers--) | Работает, когда \#textAsLines установлен в `true`. |
| [setConvertTextBeziers(boolean value)](#setConvertTextBeziers-boolean-) | Работает, когда \#textAsLines установлен в `true`. |
| [getTextAsLines()](#getTextAsLines--) | Экспортировать ли текст как контуры, состоящие из полилиний (по умолчанию), или как редактируемые сущности Autocad TEXT. |
| [setTextAsLines(boolean value)](#setTextAsLines-boolean-) | Экспортировать ли текст как контуры, состоящие из полилиний (по умолчанию), или как редактируемые сущности Autocad TEXT. |

## Example: This example demonstrates export to Dxf format

``` java

//Создайте экземпляр Image и инициализируйте его существующим файлом изображения, расположенным на диске.
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load("input.svg"))
{
    com.aspose.imaging.imageoptions.DxfOptions options = new com.aspose.imaging.imageoptions.DxfOptions();
    options.setTextAsLines(true);
    options.setConvertTextBeziers(true);
    options.setBezierPointCount((byte)20);
    image.save("output.dxf", options);
}
```

### DxfOptions() {#DxfOptions--}
```
public DxfOptions()
```


### DxfOptions(DxfOptions imageOptions) {#DxfOptions-com.aspose.imaging.imageoptions.DxfOptions-}
```
public DxfOptions(DxfOptions imageOptions)
```


Конструктор копирования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [DxfOptions](../../com.aspose.imaging.imageoptions/dxfoptions) | Параметры источника для копирования |

### getBezierPointCount() {#getBezierPointCount--}
```
public final byte getBezierPointCount()
```


Сколько точек генерировать при преобразовании кривых Безье в полилинии, минимум 4. Используется, когда (/) и (/) оба /// установлены в `true`

**Returns:**
byte
### setBezierPointCount(byte value) {#setBezierPointCount-byte-}
```
public final void setBezierPointCount(byte value)
```


Сколько точек генерировать при преобразовании кривых Безье в полилинии, минимум 4. Используется, когда (/) и (/) оба /// установлены в `true`

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getConvertTextBeziers() {#getConvertTextBeziers--}
```
public final boolean getConvertTextBeziers()
```


Работает, когда \#textAsLines установлен в `true`. Нужно ли преобразовывать кривые Безье в контурах текста в многоточечные полилинии.

**Returns:**
boolean
### setConvertTextBeziers(boolean value) {#setConvertTextBeziers-boolean-}
```
public final void setConvertTextBeziers(boolean value)
```


Работает, когда \#textAsLines установлен в `true`. Нужно ли преобразовывать кривые Безье в контурах текста в многоточечные полилинии.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTextAsLines() {#getTextAsLines--}
```
public final boolean getTextAsLines()
```


Экспортировать ли текст как контуры, состоящие из полилиний (по умолчанию), или как редактируемые сущности Autocad TEXT. Если эта опция установлена

**Returns:**
boolean
### setTextAsLines(boolean value) {#setTextAsLines-boolean-}
```
public final void setTextAsLines(boolean value)
```


Экспортировать ли текст как контуры, состоящие из полилиний (по умолчанию), или как редактируемые сущности Autocad TEXT. Если эта опция установлена

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

