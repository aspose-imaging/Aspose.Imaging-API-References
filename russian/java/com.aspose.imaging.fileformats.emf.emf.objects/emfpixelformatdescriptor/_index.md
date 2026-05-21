---
title: "EmfPixelFormatDescriptor"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект PixelFormatDescriptor может использоваться в записях EMR_HEADER раздел 2.3.4.2 для указания формата пикселей выходной поверхности для контекста устройства воспроизведения."
type: docs
weight: 31
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

Объект PixelFormatDescriptor может использоваться в записях EMR\_HEADER (раздел 2.3.4.2) для указания пиксельного формата выходной поверхности контекста устройства воспроизведения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getNSize()](#getNSize--) | Получает или задает 16‑битное целое, которое указывает размер этой структуры данных в байтах. |
| [setNSize(short value)](#setNSize-short-) | Получает или задает 16‑битное целое, которое указывает размер этой структуры данных в байтах. |
| [getNVersion()](#getNVersion--) | Получает или задает 16‑битное целое, которое ДОЛЖНО быть установлено в 0x0001. |
| [setNVersion(short value)](#setNVersion-short-) | Получает или задает 16‑битное целое, которое ДОЛЖНО быть установлено в 0x0001. |
| [getDwFlags()](#getDwFlags--) | Получает или задает битовые флаги, которые указывают свойства буфера пикселей, используемого для вывода на поверхность рисования. |
| [setDwFlags(int value)](#setDwFlags-int-) | Получает или задает битовые флаги, которые указывают свойства буфера пикселей, используемого для вывода на поверхность рисования. |
| [getIPixelType()](#getIPixelType--) | Получает или задает тип данных пикселей PFD\_TYPE\_RGBA 0x00. Формат пикселей — RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | Получает или задает тип данных пикселей PFD\_TYPE\_RGBA 0x00. Формат пикселей — RGBA. |
| [getCColorBits()](#getCColorBits--) | Получает или задает количество битов на пиксель для типов пикселей RGBA, исключая альфа‑битовые плоскости. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Получает или задает количество битов на пиксель для типов пикселей RGBA, исключая альфа‑битовые плоскости. |
| [getCRedBits()](#getCRedBits--) | Получает или задает количество красных битовых плоскостей в каждом цветном буфере RGBA. |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Получает или задает количество красных битовых плоскостей в каждом цветном буфере RGBA. |
| [getCRedShift()](#getCRedShift--) | Получает или задает количество сдвига в битах для красных битовых плоскостей в каждом цветном буфере RGBA. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Получает или задает количество сдвига в битах для красных битовых плоскостей в каждом цветном буфере RGBA. |
| [getCGreenBits()](#getCGreenBits--) | Получает или задает количество зеленых битовых плоскостей в каждом цветном буфере RGBA. |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Получает или задает количество зеленых битовых плоскостей в каждом цветном буфере RGBA. |
| [getCGreenShift()](#getCGreenShift--) | Получает или задает количество сдвига для зеленых битовых плоскостей в каждом цветном буфере RGBA. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Получает или задает количество сдвига для зеленых битовых плоскостей в каждом цветном буфере RGBA. |
| [getCBlueBits()](#getCBlueBits--) | Получает или задает количество синих битовых плоскостей в каждом цветном буфере RGBA. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Получает или задает количество синих битовых плоскостей в каждом цветном буфере RGBA. |
| [getCBlueShift()](#getCBlueShift--) | Получает или задает количество сдвига для синих битовых плоскостей в каждом цветном буфере RGBA. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Получает или задает количество сдвига для синих битовых плоскостей в каждом цветном буфере RGBA. |
| [getCAlphaBits()](#getCAlphaBits--) | Получает или задает количество альфа‑битовых плоскостей в каждом цветном буфере RGBA. |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Получает или задает количество альфа‑битовых плоскостей в каждом цветном буфере RGBA. |
| [getCAlphaShift()](#getCAlphaShift--) | Получает или задает количество сдвига для альфа‑битовых плоскостей в каждом цветном буфере RGBA. |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Получает или задает количество сдвига для альфа‑битовых плоскостей в каждом цветном буфере RGBA. |
| [getCAccumBits()](#getCAccumBits--) | Получает или задает общее количество битовых плоскостей в буфере накопления. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Получает или задает общее количество битовых плоскостей в буфере накопления. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Получает или задает количество красных битовых плоскостей в буфере накопления. |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Получает или задает количество красных битовых плоскостей в буфере накопления. |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Получает или задает количество зеленых битовых плоскостей в накоплении. |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Получает или задает количество зеленых битовых плоскостей в накоплении. |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Получает или задает количество синих битовых плоскостей в буфере накопления. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Получает или задает количество синих битовых плоскостей в буфере накопления. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Получает или задает количество альфа‑битовых плоскостей в буфере накопления. |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Получает или задает количество альфа‑битовых плоскостей в буфере накопления. |
| [getCDepthBits()](#getCDepthBits--) | Получает или задает глубину буфера глубины (ось Z). |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Получает или задает глубину буфера глубины (ось Z). |
| [getCStencilBits()](#getCStencilBits--) | Получает или задает глубину буфера трафарета. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Получает или задает глубину буфера трафарета. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Получает или задает количество вспомогательных буферов. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Получает или задает количество вспомогательных буферов. |
| [getILayerType()](#getILayerType--) | Получает или задает Это поле МОЖЕТ быть проигнорировано |
| [setILayerType(byte value)](#setILayerType-byte-) | Получает или задает Это поле МОЖЕТ быть проигнорировано |
| [getBReserved()](#getBReserved--) | Получает или задает количество наложенных и подложенных плоскостей. |
| [setBReserved(byte value)](#setBReserved-byte-) | Получает или задает количество наложенных и подложенных плоскостей. |
| [getDwLayerMask()](#getDwLayerMask--) | Получает или задает Это поле МОЖЕТ быть проигнорировано. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Получает или задает Это поле МОЖЕТ быть проигнорировано. |
| [getDwVisibleMask()](#getDwVisibleMask--) | Получает или задает прозрачный цвет или индекс подложенной плоскости. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Получает или задает прозрачный цвет или индекс подложенной плоскости. |
| [getDwDamageMask()](#getDwDamageMask--) | Получает или задает Это поле МОЖЕТ быть проигнорировано |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Получает или задает Это поле МОЖЕТ быть проигнорировано |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Получает или задает 16‑битное целое, которое указывает размер этой структуры данных в байтах.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Получает или задает 16‑битное целое, которое указывает размер этой структуры данных в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


Получает или задает 16‑битное целое, которое ДОЛЖНО быть установлено в 0x0001.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


Получает или задает 16‑битное целое, которое ДОЛЖНО быть установлено в 0x0001.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Получает или задает битовые флаги, определяющие свойства буфера пикселей, используемого для вывода на поверхность рисования. Эти свойства не являются взаимоисключающими; допускаются комбинации флагов, за исключением случаев, отмеченных иначе.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Получает или задает битовые флаги, определяющие свойства буфера пикселей, используемого для вывода на поверхность рисования. Эти свойства не являются взаимоисключающими; допускаются комбинации флагов, за исключением случаев, отмеченных иначе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Получает или задает тип данных пикселей PFD\_TYPE\_RGBA 0x00 Формат пикселей — RGBA. PFD\_TYPE\_COLORINDEX 0x01 Каждый пикель является индексом в таблице цветов.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Получает или задает тип данных пикселей PFD\_TYPE\_RGBA 0x00 Формат пикселей — RGBA. PFD\_TYPE\_COLORINDEX 0x01 Каждый пикель является индексом в таблице цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Получает или задает количество бит на пиксель для типов пикселей RGBA, исключая альфа‑битовые плоскости. Для пикселей с таблицей цветов это размер каждого индекса таблицы цветов.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Получает или задает количество бит на пиксель для типов пикселей RGBA, исключая альфа‑битовые плоскости. Для пикселей с таблицей цветов это размер каждого индекса таблицы цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Получает или задает количество красных битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Получает или задает количество красных битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Получает или задает количество сдвига в битах для красных битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Получает или задает количество сдвига в битах для красных битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Получает или задает количество зеленых битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Получает или задает количество зеленых битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Получает или задает количество сдвига для зеленых битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Получает или задает количество сдвига для зеленых битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Получает или задает количество синих битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Получает или задает количество синих битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Получает или задает количество сдвига для синих битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Получает или задает количество сдвига для синих битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Получает или задает количество альфа‑битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Получает или задает количество альфа‑битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Получает или задает количество сдвига для альфа‑битовых плоскостей в каждом цветном буфере RGBA.

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Получает или задает количество сдвига для альфа‑битовых плоскостей в каждом цветном буфере RGBA.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Получает или задает общее количество битовых плоскостей в буфере накопления.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Получает или задает общее количество битовых плоскостей в буфере накопления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Получает или задает количество красных битовых плоскостей в буфере накопления.

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Получает или задает количество красных битовых плоскостей в буфере накопления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Получает или задает количество зеленых битовых плоскостей в накоплении.

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Получает или задает количество зеленых битовых плоскостей в накоплении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Получает или задает количество синих битовых плоскостей в буфере накопления.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Получает или задает количество синих битовых плоскостей в буфере накопления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Получает или задает количество альфа‑битовых плоскостей в буфере накопления.

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Получает или задает количество альфа‑битовых плоскостей в буфере накопления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Получает или задает глубину буфера глубины (ось Z).

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Получает или задает глубину буфера глубины (ось Z).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Получает или задает глубину буфера трафарета.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Получает или задает глубину буфера трафарета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Получает или задает количество вспомогательных буферов. Вспомогательные буферы не поддерживаются.

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Получает или задает количество вспомогательных буферов. Вспомогательные буферы не поддерживаются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Получает или задает Это поле МОЖЕТ быть проигнорировано

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Получает или задает Это поле МОЖЕТ быть проигнорировано

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Получает или задает количество наложенных и подложенных плоскостей. Биты 0‑3 задают до 15 наложенных плоскостей, а биты 4‑7 — до 15 подложенных плоскостей.

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Получает или задает количество наложенных и подложенных плоскостей. Биты 0‑3 задают до 15 наложенных плоскостей, а биты 4‑7 — до 15 подложенных плоскостей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Получает или задает Это поле МОЖЕТ быть проигнорировано.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Получает или задает Это поле МОЖЕТ быть проигнорировано.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Получает или задает прозрачный цвет или индекс подложенной плоскости. Когда тип пикселя RGBA, dwVisibleMask представляет собой прозрачное значение цвета RGB. Когда тип пикселя — индекс цвета, это прозрачное значение индекса.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Получает или задает прозрачный цвет или индекс подложенной плоскости. Когда тип пикселя RGBA, dwVisibleMask представляет собой прозрачное значение цвета RGB. Когда тип пикселя — индекс цвета, это прозрачное значение индекса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Получает или задает Это поле МОЖЕТ быть проигнорировано

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Получает или задает Это поле МОЖЕТ быть проигнорировано

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

