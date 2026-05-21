---
title: "BitmapV4Header"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Структура BitmapV4Header является файлом заголовка информации о битмапе."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

Структура BitmapV4Header является файлом заголовка информации битмапа. Это расширенная версия структуры BITMAPINFOHEADER.
## Методы

| Метод | Описание |
| --- | --- |
| [getRedMask()](#getRedMask--) | Получает или задает маску цвета, указывающую красный компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | Получает или задает маску цвета, указывающую красный компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | Получает или задает маску цвета, указывающую зеленый компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | Получает или задает маску цвета, указывающую зеленый компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | Получает или задает маску цвета, указывающую синий компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | Получает или задает маску цвета, указывающую синий компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | Получает или задает маску цвета, указывающую альфа‑компонент каждого пикселя. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Получает или задает маску цвета, указывающую альфа‑компонент каждого пикселя. |
| [getCSType()](#getCSType--) | Получает или задает цветовое пространство DIB. |
| [setCSType(int value)](#setCSType-int-) | Получает или задает цветовое пространство DIB. |
| [getEndpoints()](#getEndpoints--) | Получает или задает класс CoordinatesTriple. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | Получает или задает класс CoordinatesTriple. |
| [getGammaRed()](#getGammaRed--) | Получает или задает гамму красного. |
| [setGammaRed(int value)](#setGammaRed-int-) | Получает или задает гамму красного. |
| [getGammaGreen()](#getGammaGreen--) | Получает или задает гамму зеленого. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Получает или задает гамму зеленого. |
| [getGammaBlue()](#getGammaBlue--) | Получает или задает гамму синего. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Получает или задает гамму синего. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Получает или задает маску цвета, указывающую красный компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Получает или задает маску цвета, указывающую красный компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Получает или задает маску цвета, указывающую зеленый компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Получает или задает маску цвета, указывающую зеленый компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Получает или задает маску цвета, указывающую синий компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Получает или задает маску цвета, указывающую синий компонент каждого пикселя, действительна только если bV4Compression установлен в BI\_BITFIELDS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Получает или задает маску цвета, указывающую альфа‑компонент каждого пикселя.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Получает или задает маску цвета, указывающую альфа‑компонент каждого пикселя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


Получает или задает цветовое пространство DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


Получает или задает цветовое пространство DIB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


Получает или задает класс CoordinatesTriple.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


Получает или задает класс CoordinatesTriple.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | Конечные точки. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Получает или задает гамму красного.

**Returns:**
int - Гамма красного.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Получает или задает гамму красного.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Гамма красного. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Получает или задает гамму зеленого.

**Returns:**
int - Гамма зеленого.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Получает или задает гамму зеленого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Гамма зеленого. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Получает или задает гамму синего.

**Returns:**
int - Гамма синего.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Получает или задает гамму синего.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Гамма синего. |

