---
title: "EmfPlusFillPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись Fill path FLAGS — 16‑битное беззнаковое целое, предоставляющее информацию о том, как должна выполняться операция, и о структуре записи."
type: docs
weight: 34
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Запись Fill path FLAGS: 16‑битное беззнаковое целое, предоставляющее информацию о том, как должна выполняться операция, и о структуре записи. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 бит): Этот бит указывает тип данных в поле BrushId. Если установлен, BrushId задаёт цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшен, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+. X (1 бит): Зарезервировано и ДОЛЖНО игнорироваться. ObjectId (1 байт): Индекс объекта EmfPlusPath (раздел 2.2.1.6), который следует заполнить, в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusFillPath`. |
## Методы

| Метод | Описание |
| --- | --- |
| [isColor()](#isColor--) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [setColor(boolean value)](#setColor-boolean-) | Получает или задает значение, указывающее, является ли этот экземпляр цветовым. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getBrushId()](#getBrushId--) | Получает или задает идентификатор кисти Brush ID — 32‑битное беззнаковое целое, определяющее кисть, содержимое которой определяется битом S в поле Flags. |
| [setBrushId(int value)](#setBrushId-int-) | Получает или задает идентификатор кисти Brush ID — 32‑битное беззнаковое целое, определяющее кисть, содержимое которой определяется битом S в поле Flags. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusFillPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задаёт цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Получает или задает значение, указывающее, является ли этот экземпляр цветовым. Если установлено, BrushId задаёт цвет как объект EmfPlusARGB (раздел 2.2.2.1). Если сброшено, BrushId содержит индекс объекта EmfPlusBrush (раздел 2.2.1.1) в таблице объектов EMF+.

Значение: `true`, если этот экземпляр цветовой; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPath (раздел 2.2.1.6), который следует заполнить, в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPath (раздел 2.2.1.6), который следует заполнить, в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Получает или задает идентификатор кисти Brush ID — 32‑битное беззнаковое целое, определяющее кисть, содержимое которой определяется битом S в поле Flags.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Получает или задает идентификатор кисти Brush ID — 32‑битное беззнаковое целое, определяющее кисть, содержимое которой определяется битом S в поле Flags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

