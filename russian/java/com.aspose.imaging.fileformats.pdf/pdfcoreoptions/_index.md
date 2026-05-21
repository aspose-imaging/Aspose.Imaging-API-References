---
title: "PdfCoreOptions"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Общие параметры конвертации в PDF"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

Общие параметры конвертации в PDF
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Указывает, сколько уровней элементов оглавления включать в оглавление документа. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Указывает, сколько уровней элементов оглавления включать в оглавление документа. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Указывает, сколько уровней оглавления документа показывать развернутыми при просмотре PDF‑файла. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Указывает, сколько уровней оглавления документа показывать развернутыми при просмотре PDF‑файла. |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Указывает, на каком уровне оглавления документа отображать объекты закладок. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Указывает, на каком уровне оглавления документа отображать объекты закладок. |
| [getJpegQuality()](#getJpegQuality--) | Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). |
| [getPdfCompliance()](#getPdfCompliance--) | Получает соответствие PDF. |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Устанавливает соответствие PDF. |
| [getCompression()](#getCompression--) | Получает тип сжатия. |
| [setCompression(int value)](#setCompression-int-) | Задает тип сжатия. |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Указывает, сколько уровней элементов оглавления включать в оглавление документа. 0 — без оглавления, 1 — один уровень оглавления и т.д. По умолчанию 0.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Указывает, сколько уровней элементов оглавления включать в оглавление документа. 0 — без оглавления, 1 — один уровень оглавления и т.д. По умолчанию 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Указывает, сколько уровней оглавления документа показывать развернутыми при просмотре PDF‑файла. 0 — оглавление документа не развернуто. 1 — элементы первого уровня развернуты и т.д. По умолчанию 0.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Указывает, сколько уровней оглавления документа показывать развернутыми при просмотре PDF‑файла. 0 — оглавление документа не развернуто. 1 — элементы первого уровня развернуты и т.д. По умолчанию 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Указывает, на каком уровне оглавления документа отображать объекты закладок. 0 — не отображается. 1 — на первом уровне и т.д. По умолчанию 0.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Указывает, на каком уровне оглавления документа отображать объекты закладок. 0 — не отображается. 1 — на первом уровне и т.д. По умолчанию 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). По умолчанию 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). По умолчанию 95.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Получает соответствие PDF.

**Returns:**
int - соответствие PDF.
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Устанавливает соответствие PDF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | соответствие PDF. |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Получает тип сжатия.

Значение: Сжатие.

**Returns:**
int - сжатие.
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Задает тип сжатия.

Значение: Сжатие.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | сжатие. |

