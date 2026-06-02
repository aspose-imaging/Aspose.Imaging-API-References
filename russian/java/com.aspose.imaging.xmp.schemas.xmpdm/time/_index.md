---
title: "Time"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представление временного значения в секундах."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Представление временного значения в секундах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | Инициализирует новый экземпляр класса `Time`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getScale()](#getScale--) | Получает или задаёт масштаб для значения времени. |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | Получает или задаёт масштаб для значения времени. |
| [getValue()](#getValue--) | Получает или задает значение времени в указанной шкале. |
| [setValue(int value)](#setValue-int-) | Получает или задает значение времени в указанной шкале. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Получает строковое значение в формате XMP. |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Инициализирует новый экземпляр класса `Time`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | Шкала. |
| value | int | Значение. |

### getScale() {#getScale--}
```
public Rational getScale()
```


Получает или задаёт масштаб для значения времени.

Для NTSC используйте 1001/30000 или менее точный 100/2997. Для PAL используйте 1/25. Значение: Шкала для значения времени.

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Получает или задаёт масштаб для значения времени.

Для NTSC используйте 1001/30000 или менее точный 100/2997. Для PAL используйте 1/25. Значение: Шкала для значения времени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


Получает или задает значение времени в указанной шкале.

Значение: Значение времени в указанной шкале.

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Получает или задает значение времени в указанной шкале.

Значение: Значение времени в указанной шкале.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Получает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
