---
title: "TiffExifIfd"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс каталога файлов изображений TIFF Exif."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

Класс каталога файлов изображений TIFF Exif.

Инкапсулирует указатель на Exif IFD. Совместимость, Exif IFD имеет ту же структуру, что и IFD, указанную в TIFF. Однако обычно он не содержит данные изображения, как в случае с TIFF. См. http://www.exiv2.org/tags.html и http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html для получения более подробной информации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Инициализирует новый экземпляр класса `TiffExifIfd`. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Инициализирует новый экземпляр класса `TiffExifIfd`. |
## Методы

| Метод | Описание |
| --- | --- |
| [hasValue()](#hasValue--) | Возвращает значение, указывающее, имеет ли этот экземпляр значение. |
| [getOffset()](#getOffset--) | Получает или задает указатель на EXIF IFD. |
| [setOffset(long value)](#setOffset-long-) | Получает или задает указатель на EXIF IFD. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Инициализирует новый экземпляр класса `TiffExifIfd`.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Инициализирует новый экземпляр класса `TiffExifIfd`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | ifdOffset | long | Указатель на Exif IFD. |

Совместимость, Exif IFD имеет ту же структуру, что и IFD, указанную в TIFF. Однако обычно он не содержит данные изображения, как в случае с TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Возвращает значение, указывающее, имеет ли этот экземпляр значение.

**Returns:**
boolean - `true`, если у этого экземпляра есть значение; иначе `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Получает или задает указатель на EXIF IFD.

**Returns:**
long - Указатель на EXIF IFD.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Получает или задает указатель на EXIF IFD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long | Указатель на EXIF IFD. |

