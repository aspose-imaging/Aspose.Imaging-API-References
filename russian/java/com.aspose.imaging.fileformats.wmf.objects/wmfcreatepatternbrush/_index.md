---
title: "WmfCreatePatternBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись META_CREATEPATTERNBRUSH создаёт объект кисти с узором, указанным в виде растрового изображения."
type: docs
weight: 23
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepatternbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePatternBrush extends WmfGraphicObject
```

Запись META\_CREATEPATTERNBRUSH создает объект кисти с узором, заданным растровым изображением.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfCreatePatternBrush()](#WmfCreatePatternBrush--) | WMFs запись. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitmap()](#getBitmap--) | Получает или задает растровое изображение. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Получает или задает растровое изображение. |
| [getReserved()](#getReserved--) | Получает или задает зарезервированное значение. |
| [setReserved(byte[] value)](#setReserved-byte---) | Получает или задает зарезервированное значение. |
| [getPattern()](#getPattern--) | Получает или задаёт узор. |
| [setPattern(byte[] value)](#setPattern-byte---) | Получает или задаёт узор. |
### WmfCreatePatternBrush() {#WmfCreatePatternBrush--}
```
public WmfCreatePatternBrush()
```


WMFs запись.

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Получает или задает растровое изображение.

Значение: Растровое изображение, определяющее узор кисти.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Получает или задает растровое изображение.

Значение: Растровое изображение, определяющее узор кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

### getReserved() {#getReserved--}
```
public byte[] getReserved()
```


Получает или задает зарезервированное значение.

Значение: Зарезервировано. Это поле ДОЛЖНО игнорироваться.

**Returns:**
byte[]
### setReserved(byte[] value) {#setReserved-byte---}
```
public void setReserved(byte[] value)
```


Получает или задает зарезервированное значение.

Значение: Зарезервировано. Это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getPattern() {#getPattern--}
```
public byte[] getPattern()
```


Получает или задаёт узор.

Значение: Переменного размера массив байтов, определяющий пиксельные данные растрового изображения, составляющие узор кисти. Длина этого поля в байтах может быть вычислена из параметров растрового изображения следующим образом.

**Returns:**
byte[]
### setPattern(byte[] value) {#setPattern-byte---}
```
public void setPattern(byte[] value)
```


Получает или задаёт узор.

Значение: Переменного размера массив байтов, определяющий пиксельные данные растрового изображения, составляющие узор кисти. Длина этого поля в байтах может быть вычислена из параметров растрового изображения следующим образом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

