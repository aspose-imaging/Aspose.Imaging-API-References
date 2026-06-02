---
title: "WmfEscapeEnhancedMetafile"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись Escape Enhanced Meta file."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

Запись Escape Enhanced Meta file.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Получает или задает идентификатор комментария. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Получает или задает идентификатор комментария. |
| [getCommentType()](#getCommentType--) | Получает или задает тип комментария. |
| [setCommentType(int value)](#setCommentType-int-) | Получает или задает тип комментария. |
| [getVersion()](#getVersion--) | Получает или задает версию. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает версию. |
| [getChecksum()](#getChecksum--) | Получает или задает контрольную сумму. |
| [setChecksum(int value)](#setChecksum-int-) | Получает или задает контрольную сумму. |
| [getFlags()](#getFlags--) | Получает или задаёт флаги. |
| [setFlags(int value)](#setFlags-int-) | Получает или задаёт флаги. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Получает или задает количество записей комментариев. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Получает или задает количество записей комментариев. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Получает или задает размер текущей записи. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Получает или задает размер текущей записи. |
| [getRemainingBytes()](#getRemainingBytes--) | Получает или задает оставшиеся байты. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Получает или задает оставшиеся байты. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Получает или задает размер данных расширенного метафайла. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Получает или задает размер данных расширенного метафайла. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Получает или задает данные расширенного метафайла. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Получает или задает данные расширенного метафайла. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Получает или задает идентификатор комментария.

Значение: 32-битное беззнаковое целое, определяющее эту запись как запись WMF Comment. Это значение ДОЛЖНО быть 0x43464D57.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Получает или задает идентификатор комментария.

Значение: 32-битное беззнаковое целое, определяющее эту запись как запись WMF Comment. Это значение ДОЛЖНО быть 0x43464D57.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Получает или задает тип комментария.

Значение: 32-битное беззнаковое целое, идентифицирующее тип комментария в этой записи. Это значение ДОЛЖНО быть 0x00000001.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Получает или задает тип комментария.

Значение: 32-битное беззнаковое целое, идентифицирующее тип комментария в этой записи. Это значение ДОЛЖНО быть 0x00000001.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает версию.

Значение: 32-битное беззнаковое целое, указывающее на совместимость метафайла EMF. Это ДОЛЖНО быть 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает версию.

Значение: 32-битное беззнаковое целое, указывающее на совместимость метафайла EMF. Это ДОЛЖНО быть 0x00010000.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Получает или задает контрольную сумму.

Значение: 16-битное беззнаковое целое, используемое для проверки корректности встроенного потока EMF. Это значение ДОЛЖНО быть дополнением до единицы результата применения операции XOR ко всем WORD в потоке EMF.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Получает или задает контрольную сумму.

Значение: 16-битное беззнаковое целое, используемое для проверки корректности встроенного потока EMF. Это значение ДОЛЖНО быть дополнением до единицы результата применения операции XOR ко всем WORD в потоке EMF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Получает или задаёт флаги.

Значение: Это 32-битное беззнаковое целое не используется и ДОЛЖНО быть установлено в ноль.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Получает или задаёт флаги.

Значение: Это 32-битное беззнаковое целое не используется и ДОЛЖНО быть установлено в ноль.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Получает или задает количество записей комментариев.

Значение: 32-битное беззнаковое целое, указывающее общее количество последовательных записей META_ESCAPE_ENHANCED_METAFILE, содержащих встроенный метафайл EMF.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Получает или задает количество записей комментариев.

Значение: 32-битное беззнаковое целое, указывающее общее количество последовательных записей META_ESCAPE_ENHANCED_METAFILE, содержащих встроенный метафайл EMF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Получает или задает размер текущей записи.

Значение: 32-битное беззнаковое целое, указывающее размер в байтах поля EnhancedMetafileData. Это значение ДОЛЖНО быть меньше или равно 8 192.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Получает или задает размер текущей записи.

Значение: 32-битное беззнаковое целое, указывающее размер в байтах поля EnhancedMetafileData. Это значение ДОЛЖНО быть меньше или равно 8 192.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Получает или задает оставшиеся байты.

Значение: 32-битное беззнаковое целое, указывающее количество байтов в потоке EMF, которые остаются для обработки после этой записи. Эти дополнительные байты EMF ДОЛЖНЫ следовать в полях EnhancedMetafileData последующих записей escape META_ESCAPE_ENHANDED_METAFILE.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Получает или задает оставшиеся байты.

Значение: 32-битное беззнаковое целое, указывающее количество байтов в потоке EMF, которые остаются для обработки после этой записи. Эти дополнительные байты EMF ДОЛЖНЫ следовать в полях EnhancedMetafileData последующих записей escape META_ESCAPE_ENHANDED_METAFILE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Получает или задает размер данных расширенного метафайла.

Значение: 32-битное беззнаковое целое, указывающее общий размер потока EMF, встроенного в эту последовательность записей META_ESCAPE_ENHANCED_METAFILE.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Получает или задает размер данных расширенного метафайла.

Значение: 32-битное беззнаковое целое, указывающее общий размер потока EMF, встроенного в эту последовательность записей META_ESCAPE_ENHANCED_METAFILE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Получает или задает данные расширенного метафайла.

Значение: Сегмент файла EMF. Байты в последовательных записях META_ESCAPE_ENHANCED_METAFILE ДОЛЖНЫ быть объединены, чтобы представить весь встроенный файл EMF.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Получает или задает данные расширенного метафайла.

Значение: Сегмент файла EMF. Байты в последовательных записях META_ESCAPE_ENHANCED_METAFILE ДОЛЖНЫ быть объединены, чтобы представить весь встроенный файл EMF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

