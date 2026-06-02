---
title: "GifGraphicsControlBlock"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Блок управления графикой Gif."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Блок управления графикой Gif.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Инициализирует новый экземпляр класса `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Инициализирует новый экземпляр класса `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Инициализирует новый экземпляр класса `GifGraphicsControlBlock`. |
## Поля

| Поле | Описание |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Указывает размер заголовка блока. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Метка расширения. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Получает размер подблока. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Получает или задает время задержки кадра, выраженное в 1/100 секунды. |
| [setDelayTime(int value)](#setDelayTime-int-) | Получает или задает время задержки кадра, выраженное в 1/100 секунды. |
| [getFlags()](#getFlags--) | Получает или задаёт флаги. |
| [setFlags(byte value)](#setFlags-byte-) | Получает или задаёт флаги. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Получает или задает индекс прозрачного цвета. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Получает или задает индекс прозрачного цвета. |
| [getDisposalMethod()](#getDisposalMethod--) | Получает или задает метод утилизации. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Получает или задает метод утилизации. |
| [getUserInputExpected()](#getUserInputExpected--) | Получает или задает значение, указывающее, ожидается ли ввод пользователя. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Получает или задает значение, указывающее, ожидается ли ввод пользователя. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает или задает значение, указывающее, имеет ли блок управления графикой прозрачный цвет. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Получает или задает значение, указывающее, имеет ли блок управления графикой прозрачный цвет. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Создаёт флаги. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Инициализирует новый экземпляр класса `GifGraphicsControlBlock`.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Инициализирует новый экземпляр класса `GifGraphicsControlBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| флаги | byte | Флаги. |
| delayTime | int | Время задержки, выраженное в 1/100 секунды. |
| transparentColorIndex | byte | Индекс прозрачного цвета. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Инициализирует новый экземпляр класса `GifGraphicsControlBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| delayTime | int | Время задержки, выраженное в 1/100 секунды. |
| hasTransparentColor | boolean | если установлено `true`, `transparentColorIndex` действителен. |
| transparentColorIndex | byte | Индекс прозрачного цвета. |
| requiresUserInput | boolean | если установлено `true`, ожидается ввод пользователя. |
| disposalMethod | int | Метод утилизации. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Указывает размер заголовка блока.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Метка расширения.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Получает размер подблока.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Получает или задает время задержки кадра, выраженное в 1/100 секунды.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Получает или задает время задержки кадра, выраженное в 1/100 секунды.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Получает или задаёт флаги.

Значение: Флаги.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Получает или задаёт флаги.

Значение: Флаги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Получает или задает индекс прозрачного цвета.

Значение: Индекс прозрачного цвета.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Получает или задает индекс прозрачного цвета.

Значение: Индекс прозрачного цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Получает или задает метод утилизации.

Значение: Метод утилизации.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


Получает или задает метод утилизации.

Значение: Метод утилизации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Получает или задает значение, указывающее, ожидается ли ввод пользователя.

Значение: `true`, если ожидается ввод пользователя; иначе `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Получает или задает значение, указывающее, ожидается ли ввод пользователя.

Значение: `true`, если ожидается ввод пользователя; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Получает или задает значение, указывающее, имеет ли блок управления графикой прозрачный цвет.

Значение: `true`, если блок управления графикой имеет прозрачный цвет; иначе `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Получает или задает значение, указывающее, имеет ли блок управления графикой прозрачный цвет.

Значение: `true`, если блок управления графикой имеет прозрачный цвет; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Создаёт флаги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hasTransparentColor | boolean | если установлено `true`, у `GifGraphicsControlBlock` действителен индекс прозрачного цвета. |
| requiresUserInput | boolean | если установлено `true`, ожидается ввод пользователя. |
| disposalMethod | int | Метод утилизации. |

**Returns:**
byte — Сгенерированные флаги.
