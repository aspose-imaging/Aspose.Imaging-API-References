---
title: "EmfPlusDrawDriverString"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawDriverString определяет вывод текста с позициями символов."
type: docs
weight: 20
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawDriverString определяет вывод текста с позициями символов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawDriverString`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectId()](#getObjectId--) | Получает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Задает идентификатор объекта. |
| [getBrushId()](#getBrushId--) | Получает идентификатор кисти. 32‑битное беззнаковое целое число, которое указывает либо цвет переднего плана текста, либо графическую кисть, в зависимости от значения флага S в поле Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Устанавливает идентификатор кисти — 32‑битное беззнаковое целое, которое указывает либо цвет переднего плана текста, либо графическую кисть, в зависимости от значения флага S в Flags. |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Получает флаги параметров строки драйвера — 32‑битное беззнаковое целое, которое определяет интервал, ориентацию и качество рендеринга строки. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Устанавливает флаги параметров строки драйвера — 32‑битное беззнаковое целое, которое определяет интервал, ориентацию и качество рендеринга строки. |
| [getGlyphCount()](#getGlyphCount--) | Получает количество глифов — 32‑битное беззнаковое целое, которое указывает число глифов в строке. |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Устанавливает количество глифов — 32‑битное беззнаковое целое, которое указывает число глифов в строке. |
| [getGlyphPos()](#getGlyphPos--) | Получает массив позиций глифов — массив объектов EmfPlusPointF (section 2.2.2.36), которые задают выходную позицию каждого глифа символа. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Устанавливает массив позиций глифов — массив объектов EmfPlusPointF (section 2.2.2.36), которые задают выходную позицию каждого глифа символа. |
| [getGlyphs()](#getGlyphs--) | Получает массив глифов — массив 16‑битных значений, определяющих текстовую строку для отрисовки. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Устанавливает массив глифов — массив 16‑битных значений, определяющих текстовую строку для отрисовки. |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [setColor(boolean value)](#setColor-boolean-) | Устанавливает значение, указывающее, является ли данный экземпляр цветным. |
| [getMatrixPresent()](#getMatrixPresent--) | Получает флаг наличия матрицы — 32‑битное беззнаковое целое, которое указывает, присутствует ли матрица преобразования в поле TransformMatrix (0 — матрица отсутствует). |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Устанавливает флаг наличия матрицы — 32‑битное беззнаковое целое, которое указывает, присутствует ли матрица преобразования в поле TransformMatrix (0 — матрица отсутствует). |
| [getTransformMatrix()](#getTransformMatrix--) | Получает матрицу преобразования — необязательный объект EmfPlusTransformMatrix (section 2.2.2.47), который задает трансформацию, применяемую к каждому значению в массиве текста. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Устанавливает матрицу преобразования — необязательный объект EmfPlusTransformMatrix (section 2.2.2.47), который задает трансформацию, применяемую к каждому значению в массиве текста. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawDriverString`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает идентификатор объекта. Индекс в таблице объектов EMF+ объекта `` (section 2.2.1.3) для отрисовки текста. Значение ДОЛЖНО быть от 0 до 63 включительно.

**Returns:**
byte — идентификатор объекта.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Устанавливает идентификатор объекта. Индекс в таблице объектов EMF+ объекта `` (section 2.2.1.3) для отрисовки текста. Значение ДОЛЖНО быть от 0 до 63 включительно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Идентификатор объекта. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Получает идентификатор кисти. 32‑битное беззнаковое целое число, которое указывает либо цвет переднего плана текста, либо графическую кисть, в зависимости от значения флага S в поле Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Устанавливает идентификатор кисти — 32‑битное беззнаковое целое, которое указывает либо цвет переднего плана текста, либо графическую кисть, в зависимости от значения флага S в Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Получает флаги параметров строки драйвера — 32‑битное беззнаковое целое, которое определяет интервал, ориентацию и качество рендеринга строки.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Устанавливает флаги параметров строки драйвера — 32‑битное беззнаковое целое, которое определяет интервал, ориентацию и качество рендеринга строки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Получает количество глифов — 32‑битное беззнаковое целое, которое указывает число глифов в строке.

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Устанавливает количество глифов — 32‑битное беззнаковое целое, которое указывает число глифов в строке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Получает массив позиций глифов — массив объектов EmfPlusPointF (section 2.2.2.36), которые задают выходную позицию каждого глифа символа. ДОЛЖНО быть GlyphCount элементов, которые имеют одно‑к‑одному соответствие с элементами массива Glyphs. Позиции глифов вычисляются из позиции первого глифа, если установлен флаг DriverStringOptionsRealizedAdvance в флагах DriverStringOptions. В этом случае GlyphPos указывает только позицию первого глифа.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Устанавливает массив позиций глифов — массив объектов EmfPlusPointF (section 2.2.2.36), которые задают выходную позицию каждого глифа символа. ДОЛЖНО быть GlyphCount элементов, которые имеют одно‑к‑одному соответствие с элементами массива Glyphs. Позиции глифов вычисляются из позиции первого глифа, если установлен флаг DriverStringOptionsRealizedAdvance в флагах DriverStringOptions. В этом случае GlyphPos указывает только позицию первого глифа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Получает массив глифов — массив 16‑битных значений, определяющих текстовую строку для отрисовки. Если установлен флаг DriverStringOptionsCmapLookup в поле DriverStringOptionsFlags, каждое значение в этом массиве указывает Unicode‑символ. В противном случае каждое значение указывает индекс к глифу символа в объекте EmfPlusFont, указанном значением ObjectId в поле Flags.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Устанавливает массив глифов — массив 16‑битных значений, определяющих текстовую строку для отрисовки. Если установлен флаг DriverStringOptionsCmapLookup в поле DriverStringOptionsFlags, каждое значение в этом массиве указывает Unicode‑символ. В противном случае каждое значение указывает индекс к глифу символа в объекте EmfPlusFont, указанном значением ObjectId в поле Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Получает или задает значение, указывающее, является ли данный экземпляр цветным. Этот бит указывает тип данных в поле BrushId. Если установлен, BrushId задает значение цвета в объекте EmfPlusARGB (section 2.2.2.1). Если сброшен, BrushId содержит индекс в таблице объектов EMF+ объекта EmfPlusBrush (section 2.2.1.1).

**Returns:**
boolean — `true`, если данный экземпляр цветной; иначе `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Устанавливает значение, указывающее, является ли данный экземпляр цветным. Этот бит указывает тип данных в поле BrushId. Если установлен, BrushId задает значение цвета в объекте EmfPlusARGB (section 2.2.2.1). Если сброшен, BrushId содержит индекс в таблице объектов EMF+ объекта EmfPlusBrush (section 2.2.1.1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true` если этот экземпляр является цветным; иначе `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


Получает флаг наличия матрицы. 32‑разрядное беззнаковое целое, указывающее, присутствует ли матрица преобразования в поле TransformMatrix: 0 — матрица отсутствует. 1 — матрица преобразования находится в поле TransformMatrix.

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


Устанавливает флаг наличия матрицы. 32‑разрядное беззнаковое целое, указывающее, присутствует ли матрица преобразования в поле TransformMatrix: 0 — матрица отсутствует. 1 — матрица преобразования находится в поле TransformMatrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Получает матрицу преобразования. Необъект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий трансформацию, применяемую к каждому значению в массиве текста. Наличие этих данных определяется полем MatrixPresent.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Устанавливает матрицу преобразования. Необъект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий трансформацию, применяемую к каждому значению в массиве текста. Наличие этих данных определяется полем MatrixPresent.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

