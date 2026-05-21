---
title: "RdOptimizerSettings"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс настроек оптимизатора RD."
type: docs
weight: 42
url: /ru/java/com.aspose.imaging.imageoptions/rdoptimizersettings/
---
**Inheritance:**
java.lang.Object
```
public class RdOptimizerSettings
```

Класс настроек оптимизатора RD.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RdOptimizerSettings()](#RdOptimizerSettings--) | Инициализирует новый экземпляр класса `RdOptimizerSettings`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBppScale()](#getBppScale--) | Получает коэффициент масштабирования BPP (бит на пиксель). |
| [setBppScale(int value)](#setBppScale-int-) | Задает коэффициент масштабирования BPP (бит на пиксель). |
| [getBppMax()](#getBppMax--) | Получает максимальное значение R для учета в битах на пиксель |
| [setBppMax(double value)](#setBppMax-double-) | Задает максимальное значение R для учета в битах на пиксель |
| [getMaxQ()](#getMaxQ--) | Получает максимальное значение квантования. |
| [setMaxQ(int value)](#setMaxQ-int-) | Задает максимальное значение квантования. |
| [getMinQ()](#getMinQ--) | Получает минимально допустимое значение квантования. |
| [getMaxPixelValue()](#getMaxPixelValue--) | Получает максимальное значение пикселя. |
| [getPsnrMax()](#getPsnrMax--) | Получает ожидаемое максимальное значение PSNR. |
| [getDiscretizedBppMax()](#getDiscretizedBppMax--) | Получает максимальное значение R для учета. |
| [create()](#create--) | Создает этот экземпляр. |
### RdOptimizerSettings() {#RdOptimizerSettings--}
```
public RdOptimizerSettings()
```


Инициализирует новый экземпляр класса `RdOptimizerSettings`.

### getBppScale() {#getBppScale--}
```
public int getBppScale()
```


Получает коэффициент масштабирования BPP (бит на пиксель).

**Returns:**
int - масштаб BPP.
### setBppScale(int value) {#setBppScale-int-}
```
public void setBppScale(int value)
```


Задает коэффициент масштабирования BPP (бит на пиксель).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Масштаб BPP. |

### getBppMax() {#getBppMax--}
```
public double getBppMax()
```


Получает максимальное значение R для учета в битах на пиксель

**Returns:**
double - максимальное значение R для учета в битах на пиксель.
### setBppMax(double value) {#setBppMax-double-}
```
public void setBppMax(double value)
```


Задает максимальное значение R для учета в битах на пиксель

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Максимальное значение R для рассмотрения в битах на пиксель. |

### getMaxQ() {#getMaxQ--}
```
public int getMaxQ()
```


Получает максимальное значение квантования.

**Returns:**
int - Максимальное значение квантизации.
### setMaxQ(int value) {#setMaxQ-int-}
```
public void setMaxQ(int value)
```


Задает максимальное значение квантования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Максимальное значение квантизации. |

### getMinQ() {#getMinQ--}
```
public int getMinQ()
```


Получает минимально допустимое значение квантования.

**Returns:**
int - Минимальное разрешённое значение квантизации.
### getMaxPixelValue() {#getMaxPixelValue--}
```
public int getMaxPixelValue()
```


Получает максимальное значение пикселя.

**Returns:**
int - Максимальное значение пикселя.
### getPsnrMax() {#getPsnrMax--}
```
public int getPsnrMax()
```


Получает ожидаемое максимальное значение PSNR.

**Returns:**
int - Максимальное значение пикселя.
### getDiscretizedBppMax() {#getDiscretizedBppMax--}
```
public int getDiscretizedBppMax()
```


Получает максимальное значение R для учета.

**Returns:**
int - Максимальное значение R для рассмотрения.
### create() {#create--}
```
public static RdOptimizerSettings create()
```


Создает этот экземпляр.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - returns RDOptimizerSettings class instance
