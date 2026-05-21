---
title: "WmfPitchAndFamily"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект PitchAndFamily задает свойства pitch и family объекта Font (раздел 2.2.1.2)."
type: docs
weight: 54
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class WmfPitchAndFamily extends Struct<WmfPitchAndFamily>
```

Объект PitchAndFamily задает свойства pitch и family объекта Font (раздел 2.2.1.2). Pitch относится к ширине символов, а family — к общему внешнему виду шрифта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfPitchAndFamily()](#WmfPitchAndFamily--) |  |
| [WmfPitchAndFamily(byte byteData)](#WmfPitchAndFamily-byte-) | Инициализирует новый экземпляр структуры `WmfPitchAndFamily`. |
| [WmfPitchAndFamily(byte pitch, byte family)](#WmfPitchAndFamily-byte-byte-) | Инициализирует новый экземпляр структуры `WmfPitchAndFamily`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamily()](#getFamily--) | Получает свойство шрифта, описывающее его общий внешний вид. |
| [getPitch()](#getPitch--) | Получает свойство шрифта, описывающее pitch символов. |
| [getByteData()](#getByteData--) | Устанавливает данные ``. |
| [setByteData(byte value)](#setByteData-byte-) | Устанавливает данные ``. |
| [toByte()](#toByte--) | К байту. |
| [CloneTo(WmfPitchAndFamily that)](#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)](#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) |  |
### WmfPitchAndFamily() {#WmfPitchAndFamily--}
```
public WmfPitchAndFamily()
```


### WmfPitchAndFamily(byte byteData) {#WmfPitchAndFamily-byte-}
```
public WmfPitchAndFamily(byte byteData)
```


Инициализирует новый экземпляр структуры `WmfPitchAndFamily`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| byteData | byte | Данные ``. |

### WmfPitchAndFamily(byte pitch, byte family) {#WmfPitchAndFamily-byte-byte-}
```
public WmfPitchAndFamily(byte pitch, byte family)
```


Инициализирует новый экземпляр структуры `WmfPitchAndFamily`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pitch | byte | Тот pitch. |
| семья | byte | Семья. |

### getFamily() {#getFamily--}
```
public byte getFamily()
```


Получает свойство шрифта, описывающее его общий внешний вид. Это ДОЛЖНО быть значением в перечислении FamilyFont

Значение: Семья.

**Returns:**
byte
### getPitch() {#getPitch--}
```
public byte getPitch()
```


Получает свойство шрифта, описывающее шаг символов. Это ДОЛЖНО быть значением в перечислении PitchFont.

Значение: Шаг.

**Returns:**
byte
### getByteData() {#getByteData--}
```
public byte getByteData()
```


Устанавливает данные ``.

Значение: `` data.

**Returns:**
byte
### setByteData(byte value) {#setByteData-byte-}
```
public void setByteData(byte value)
```


Устанавливает данные ``.

Значение: `` data.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### toByte() {#toByte--}
```
public byte toByte()
```


К байту.

**Returns:**
byte - Значение байта.
### CloneTo(WmfPitchAndFamily that) {#CloneTo-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void CloneTo(WmfPitchAndFamily that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### Clone() {#Clone--}
```
public WmfPitchAndFamily Clone()
```




**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2) {#isEquals-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public static boolean isEquals(WmfPitchAndFamily obj1, WmfPitchAndFamily obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |
| obj2 | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

**Returns:**
boolean
