---
title: "EmfPlusSetAntiAliasMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetAntiAliasMode указывает режим сглаживания для вывода текста."
type: docs
weight: 54
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

Запись EmfPlusSetAntiAliasMode указывает режим сглаживания для вывода текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetAntiAliasMode`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Получает или задает режим сглаживания. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Получает или задает режим сглаживания. |
| [getAntiAliasing()](#getAntiAliasing--) | Получает или задает значение, указывающее, включено ли [anti aliasing]. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Получает или задает значение, указывающее, включено ли [anti aliasing]. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetAntiAliasMode`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Получает или задает режим сглаживания. (7 бит): Значение режима сглаживания из перечисления SmoothingMode (раздел 2.1.1.28).

Значение: Режим сглаживания.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Получает или задает режим сглаживания. (7 бит): Значение режима сглаживания из перечисления SmoothingMode (раздел 2.1.1.28).

Значение: Режим сглаживания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Получает или задает значение, указывающее, включено ли [anti aliasing]. Если установлено, антиалиасинг ДОЛЖЕН выполняться. Если сброшено, антиалиасинг НЕ ДОЛЖЕН выполняться.

Значение: `true`, если [anti aliasing]; иначе `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Получает или задает значение, указывающее, включено ли [anti aliasing]. Если установлено, антиалиасинг ДОЛЖЕН выполняться. Если сброшено, антиалиасинг НЕ ДОЛЖЕН выполняться.

Значение: `true`, если [anti aliasing]; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

