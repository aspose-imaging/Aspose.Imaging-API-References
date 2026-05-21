---
title: "EmfPlusSetCompositingMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetCompositingMode указывает, как исходные цвета комбинируются с цветами фона."
type: docs
weight: 58
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

Запись EmfPlusSetCompositingMode указывает, как исходные цвета комбинируются с цветами фона.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetCompositingMode`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | Получает или задаёт значение режима композитинга из перечисления CompositingMode (раздел 2.1.1.5). |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Получает или задаёт значение режима композитинга из перечисления CompositingMode (раздел 2.1.1.5). |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetCompositingMode`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Получает или задаёт значение режима композитинга из перечисления CompositingMode (раздел 2.1.1.5). Композитинг может быть выражен как состояние альфа‑смешивания, которое может быть включено или выключено.

Значение: режим композитинга.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Получает или задаёт значение режима композитинга из перечисления CompositingMode (раздел 2.1.1.5). Композитинг может быть выражен как состояние альфа‑смешивания, которое может быть включено или выключено.

Значение: режим композитинга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

