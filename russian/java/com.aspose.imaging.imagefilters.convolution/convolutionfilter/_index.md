---
title: "ConvolutionFilter"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс поставщика ядровой матрицы."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.imagefilters.convolution/convolutionfilter/
---
**Inheritance:**
java.lang.Object
```
public final class ConvolutionFilter
```

Класс поставщика ядровой матрицы.
## Методы

| Метод | Описание |
| --- | --- |
| [getSharpen3x3()](#getSharpen3x3--) | Получает ядро резкости 3x3. |
| [getSharpen5x5()](#getSharpen5x5--) | Получает ядро резкости 5x5. |
| [getEmboss3x3()](#getEmboss3x3--) | Получает ядро рельефа 3x3. |
| [getEmboss5x5()](#getEmboss5x5--) | Получает ядро рельефа 5x5. |
| [getBlurMotion(int size, double angle)](#getBlurMotion-int-double-) | Получает ядро размытия движения. |
| [getGaussian(int size, double sigma)](#getGaussian-int-double-) | Получает гауссово ядро. |
| [getBlurBox(int size)](#getBlurBox-int-) | Получает ядро бокса размытия. |
| [toComplex(double[][] kernel)](#toComplex-double-----) | Преобразует `kernel` в ядро [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex). |
### getSharpen3x3() {#getSharpen3x3--}
```
public static double[][] getSharpen3x3()
```


Получает ядро резкости 3x3.

**Returns:**
double[][] - ядро резкости 3x3.
### getSharpen5x5() {#getSharpen5x5--}
```
public static double[][] getSharpen5x5()
```


Получает ядро резкости 5x5.

**Returns:**
double[][] - ядро резкости 5x5.
### getEmboss3x3() {#getEmboss3x3--}
```
public static double[][] getEmboss3x3()
```


Получает ядро рельефа 3x3.

**Returns:**
double[][] - ядро рельефа 3x3.
### getEmboss5x5() {#getEmboss5x5--}
```
public static double[][] getEmboss5x5()
```


Получает ядро рельефа 5x5.

**Returns:**
double[][] - ядро рельефа 5x5.
### getBlurMotion(int size, double angle) {#getBlurMotion-int-double-}
```
public static double[][] getBlurMotion(int size, double angle)
```


Получает ядро размытия движения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Размер ядра. |
| angle | double | Угол движения. |

**Returns:**
double[][] - ядро размытия движения.
### getGaussian(int size, double sigma) {#getGaussian-int-double-}
```
public static double[][] getGaussian(int size, double sigma)
```


Получает гауссово ядро.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Размер ядра. |
| sigma | double | Значение сигмы в диапазоне (0...]. |

**Returns:**
double[][] - Гауссово ядро.
### getBlurBox(int size) {#getBlurBox-int-}
```
public static double[][] getBlurBox(int size)
```


Получает ядро бокса размытия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | int | Размер ядра. |

**Returns:**
double[][] - Ядро боксового размытия.
### toComplex(double[][] kernel) {#toComplex-double-----}
```
public static Complex[][] toComplex(double[][] kernel)
```


Преобразует `kernel` в ядро [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ядро | double[][] | Ядро. |

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - Ядро [Complex](../../com.aspose.imaging.imagefilters.complexutils/complex).
