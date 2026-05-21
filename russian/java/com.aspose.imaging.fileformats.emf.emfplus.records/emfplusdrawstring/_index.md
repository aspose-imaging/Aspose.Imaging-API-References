---
title: "EmfPlusDrawString"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawString определяет вывод текста с форматированием строки"
type: docs
weight: 28
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawString определяет вывод текста с форматированием строки
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawString`. |
## Методы

| Метод | Описание |
| --- | --- |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [setColor(boolean value)](#setColor-boolean-) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getBrushId()](#getBrushId--) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое число, которое указывает кисть, содержимое которой определяется битом S в поле Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Получает или задает идентификатор кисти — 32-битное беззнаковое целое число, которое указывает кисть, содержимое которой определяется битом S в поле Flags. |
| [getFormatId()](#getFormatId--) | Получает или задает идентификатор формата — 32-битное беззнаковое целое число, которое указывает индекс необязательного объекта EmfPlusStringFormat (раздел 2.2.1.9) в таблице объектов EMF+. |
| [setFormatId(int value)](#setFormatId-int-) | Получает или задает идентификатор формата — 32-битное беззнаковое целое число, которое указывает индекс необязательного объекта EmfPlusStringFormat (раздел 2.2.1.9) в таблице объектов EMF+. |
| [getLength()](#getLength--) | Получает или задает длину — 32-битное беззнаковое целое число, которое указывает количество символов в строке. |
| [setLength(int value)](#setLength-int-) | Получает или задает длину — 32-битное беззнаковое целое число, которое указывает количество символов в строке. |
| [getLayoutRect()](#getLayoutRect--) | Получает или задает прямоугольник макета — объект EmfPlusRectF (раздел 2.2.2.39), который определяет ограничивающую область назначения, получающего строку. |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Получает или задает прямоугольник макета — объект EmfPlusRectF (раздел 2.2.2.39), который определяет ограничивающую область назначения, получающего строку. |
| [getStringData()](#getStringData--) | Получает или задает данные строки — массив 16-битных символов Unicode, который определяет строку для отрисовки. |
| [setStringData(String value)](#setStringData-java.lang.String-) | Получает или задает данные строки — массив 16-битных символов Unicode, который определяет строку для отрисовки. |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawString`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задает цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задает цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusFont (раздел 2.2.1.3) в таблице объектов EMF+, используемый для отображения текста. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusFont (раздел 2.2.1.3) в таблице объектов EMF+, используемый для отображения текста. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Получает или задает идентификатор кисти — 32-битное беззнаковое целое число, которое указывает кисть, содержимое которой определяется битом S в поле Flags. Это определение используется для окрашивания цвета переднего текста; то есть только самих глифов.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Получает или задает идентификатор кисти — 32-битное беззнаковое целое число, которое указывает кисть, содержимое которой определяется битом S в поле Flags. Это определение используется для окрашивания цвета переднего текста; то есть только самих глифов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Получает или задает идентификатор формата — 32-битное беззнаковое целое число, которое указывает индекс необязательного объекта EmfPlusStringFormat (раздел 2.2.1.9) в таблице объектов EMF+. Этот объект задает информацию о макете текста и манипуляции отображения, применяемые к строке.

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Получает или задает идентификатор формата — 32-битное беззнаковое целое число, которое указывает индекс необязательного объекта EmfPlusStringFormat (раздел 2.2.1.9) в таблице объектов EMF+. Этот объект задает информацию о макете текста и манипуляции отображения, применяемые к строке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Получает или задает длину — 32-битное беззнаковое целое число, которое указывает количество символов в строке.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Получает или задает длину — 32-битное беззнаковое целое число, которое указывает количество символов в строке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Получает или задает прямоугольник макета — объект EmfPlusRectF (раздел 2.2.2.39), который определяет ограничивающую область назначения, получающего строку.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Получает или задает прямоугольник макета — объект EmfPlusRectF (раздел 2.2.2.39), который определяет ограничивающую область назначения, получающего строку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Получает или задает данные строки — массив 16-битных символов Unicode, который определяет строку для отрисовки.

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Получает или задает данные строки — массив 16-битных символов Unicode, который определяет строку для отрисовки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

