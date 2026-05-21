---
title: "JpegLsPresetCodingParameters"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет предустановленные параметры кодирования JPEG-LS, как определено в ISO/IEC 14495-1 C.2.4.1.1."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/
---
**Inheritance:**
java.lang.Object
```
public class JpegLsPresetCodingParameters
```

Определяет предустановленные параметры кодирования JPEG-LS, как указано в ISO/IEC 14495-1, C.2.4.1.1. JPEG-LS определяет набор параметров по умолчанию, но могут использоваться пользовательские параметры. При их использовании эти параметры записываются в закодированный битовый поток, поскольку они необходимы для процесса декодирования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [JpegLsPresetCodingParameters()](#JpegLsPresetCodingParameters--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getMaximumSampleValue()](#getMaximumSampleValue--) | Получает или задает максимальное возможное значение для любого образца изображения в сканировании. |
| [setMaximumSampleValue(int value)](#setMaximumSampleValue-int-) | Получает или задает максимальное возможное значение для любого образца изображения в сканировании. |
| [getThreshold1()](#getThreshold1--) | Получает или задает значение первого порога квантования для локальных градиентов. |
| [setThreshold1(int value)](#setThreshold1-int-) | Получает или задает значение первого порога квантования для локальных градиентов. |
| [getThreshold2()](#getThreshold2--) | Получает или задает значение второго порога квантования для локальных градиентов. |
| [setThreshold2(int value)](#setThreshold2-int-) | Получает или задает значение второго порога квантования для локальных градиентов. |
| [getThreshold3()](#getThreshold3--) | Получает или задает значение третьего порога квантования для локальных градиентов. |
| [setThreshold3(int value)](#setThreshold3-int-) | Получает или задает значение третьего порога квантования для локальных градиентов. |
| [getResetValue()](#getResetValue--) | Получает или задает значение, при котором счетчики A, B и N делятся пополам. |
| [setResetValue(int value)](#setResetValue-int-) | Получает или задает значение, при котором счетчики A, B и N делятся пополам. |
### JpegLsPresetCodingParameters() {#JpegLsPresetCodingParameters--}
```
public JpegLsPresetCodingParameters()
```


### getMaximumSampleValue() {#getMaximumSampleValue--}
```
public int getMaximumSampleValue()
```


Получает или задает максимальное возможное значение для любого образца изображения в сканировании. Оно должно быть больше или равно фактическому максимальному значению компонентов в сканировании.

**Returns:**
int
### setMaximumSampleValue(int value) {#setMaximumSampleValue-int-}
```
public void setMaximumSampleValue(int value)
```


Получает или задает максимальное возможное значение для любого образца изображения в сканировании. Оно должно быть больше или равно фактическому максимальному значению компонентов в сканировании.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getThreshold1() {#getThreshold1--}
```
public int getThreshold1()
```


Получает или задает значение первого порога квантования для локальных градиентов.

**Returns:**
int
### setThreshold1(int value) {#setThreshold1-int-}
```
public void setThreshold1(int value)
```


Получает или задает значение первого порога квантования для локальных градиентов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getThreshold2() {#getThreshold2--}
```
public int getThreshold2()
```


Получает или задает значение второго порога квантования для локальных градиентов.

**Returns:**
int
### setThreshold2(int value) {#setThreshold2-int-}
```
public void setThreshold2(int value)
```


Получает или задает значение второго порога квантования для локальных градиентов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getThreshold3() {#getThreshold3--}
```
public int getThreshold3()
```


Получает или задает значение третьего порога квантования для локальных градиентов.

**Returns:**
int
### setThreshold3(int value) {#setThreshold3-int-}
```
public void setThreshold3(int value)
```


Получает или задает значение третьего порога квантования для локальных градиентов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getResetValue() {#getResetValue--}
```
public int getResetValue()
```


Получает или задает значение, при котором счетчики A, B и N делятся пополам.

**Returns:**
int
### setResetValue(int value) {#setResetValue-int-}
```
public void setResetValue(int value)
```


Получает или задает значение, при котором счетчики A, B и N делятся пополам.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

