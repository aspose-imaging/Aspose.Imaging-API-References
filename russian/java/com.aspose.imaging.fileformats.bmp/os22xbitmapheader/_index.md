---
title: "Os22XBitmapHeader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "OS/2 2.x OS22XBITMAPHEADER, также известный как BITMAPCOREHEADER2."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

OS/2 2.x OS22XBITMAPHEADER, также известный как BITMAPCOREHEADER2.
## Методы

| Метод | Описание |
| --- | --- |
| [getUnits()](#getUnits--) | Получает единицы измерения. |
| [getReserved()](#getReserved--) | Получает зарезервированное значение. |
| [getRecording()](#getRecording--) | Получает запись. |
| [getRendering()](#getRendering--) | Получает рендеринг. |
| [getSize1()](#getSize1--) | Получает size1. |
| [getSize2()](#getSize2--) | Получает size2. |
| [getColorEncoding()](#getColorEncoding--) | Получает кодировку цвета. |
| [getIdentifier()](#getIdentifier--) | Получает идентификатор. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Получает единицы измерения.

**Returns:**
int - тип единиц, используемых для измерения разрешения
### getReserved() {#getReserved--}
```
public int getReserved()
```


Получает зарезервированное значение.

**Returns:**
int - выравнивание структуры до границы в 4 байта
### getRecording() {#getRecording--}
```
public int getRecording()
```


Получает запись.

**Returns:**
int - алгоритм записи
### getRendering() {#getRendering--}
```
public int getRendering()
```


Получает рендеринг.

**Returns:**
int - используемый алгоритм полутонов
### getSize1() {#getSize1--}
```
public int getSize1()
```


Получает size1.

**Returns:**
int - зарезервировано для использования алгоритма полутонов
### getSize2() {#getSize2--}
```
public int getSize2()
```


Получает size2.

**Returns:**
int - зарезервировано для использования алгоритма полутонов
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Получает кодировку цвета.

**Returns:**
int - цветовая модель, используемая в битмапе
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Получает идентификатор.

**Returns:**
int - зарезервировано для использования приложением
