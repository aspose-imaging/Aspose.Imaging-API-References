---
title: "EmfCommentWindowsMetaFile"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COMMENT_WINDOWS_METAFILE указывает изображение во встроенном WMF метафайле."
type: docs
weight: 33
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentWindowsMetaFile extends EmfCommentPublicRecordType
```

Запись EMR\_COMMENT\_WINDOWS\_METAFILE указывает изображение во встроенном метафайле WMF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCommentWindowsMetaFile(EmfRecord source)](#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCommentWindowsMetaFile`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) | Получает или задает 16‑битное беззнаковое целое, которое определяет версию WMF метафайла с учётом поддержки независимых от устройства битовых карт (DIB), из перечисления WMF MetafileVersion ([MS-WMF] раздел 2.1.1.19). |
| [setVersion(short value)](#setVersion-short-) | Получает или задает 16‑битное беззнаковое целое, которое определяет версию WMF метафайла с учётом поддержки независимых от устройства битовых карт (DIB), из перечисления WMF MetafileVersion ([MS-WMF] раздел 2.1.1.19). |
| [getChecksum()](#getChecksum--) | Получает или задает 32‑битное беззнаковое целое, которое определяет контрольную сумму этой записи. |
| [setChecksum(int value)](#setChecksum-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет контрольную сумму этой записи. |
| [getFlags()](#getFlags--) | Получает или задает 32‑битное значение, которое ДОЛЖНО быть 0x00000000 и ДОЛЖНО игнорироваться. |
| [setFlags(int value)](#setFlags-int-) | Получает или задает 32‑битное значение, которое ДОЛЖНО быть 0x00000000 и ДОЛЖНО игнорироваться. |
| [getWinMetafileSize()](#getWinMetafileSize--) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер WMF метафайла в байтах в поле WinMetafile. |
| [setWinMetafileSize(int value)](#setWinMetafileSize-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер WMF метафайла в байтах в поле WinMetafile. |
| [getWinMetafile()](#getWinMetafile--) | Получает или задает буфер, содержащий WMF метафайл. |
| [setWinMetafile(MetaImage value)](#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-) | Получает или задает буфер, содержащий WMF метафайл. |
### EmfCommentWindowsMetaFile(EmfRecord source) {#EmfCommentWindowsMetaFile-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentWindowsMetaFile(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCommentWindowsMetaFile`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getVersion() {#getVersion--}
```
public short getVersion()
```


Получает или задает 16‑битное беззнаковое целое, которое определяет версию WMF метафайла с учётом поддержки независимых от устройства битовых карт (DIB), из перечисления WMF MetafileVersion ([MS-WMF] раздел 2.1.1.19).

**Returns:**
short
### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


Получает или задает 16‑битное беззнаковое целое, которое определяет версию WMF метафайла с учётом поддержки независимых от устройства битовых карт (DIB), из перечисления WMF MetafileVersion ([MS-WMF] раздел 2.1.1.19).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет контрольную сумму этой записи.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет контрольную сумму этой записи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Получает или задает 32‑битное значение, которое ДОЛЖНО быть 0x00000000 и ДОЛЖНО игнорироваться.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Получает или задает 32‑битное значение, которое ДОЛЖНО быть 0x00000000 и ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWinMetafileSize() {#getWinMetafileSize--}
```
public int getWinMetafileSize()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер WMF метафайла в байтах в поле WinMetafile.

**Returns:**
int
### setWinMetafileSize(int value) {#setWinMetafileSize-int-}
```
public void setWinMetafileSize(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер WMF метафайла в байтах в поле WinMetafile.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWinMetafile() {#getWinMetafile--}
```
public MetaImage getWinMetafile()
```


Получает или задает буфер, содержащий WMF метафайл.

**Returns:**
[MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
### setWinMetafile(MetaImage value) {#setWinMetafile-com.aspose.imaging.fileformats.emf.MetaImage-}
```
public void setWinMetafile(MetaImage value)
```


Получает или задает буфер, содержащий WMF метафайл.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage) |  |

