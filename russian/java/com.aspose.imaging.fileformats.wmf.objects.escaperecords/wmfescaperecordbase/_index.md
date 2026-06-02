---
title: "WmfEscapeRecordBase"
second_title: "Справочник API Aspose.Imaging для Java"
description: "База записи escape."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfEscapeRecordBase extends WmfObject
```

База записи escape.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfEscapeRecordBase()](#WmfEscapeRecordBase--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getByteCount()](#getByteCount--) | Получает или задает количество байтов. |
| [setByteCount(int value)](#setByteCount-int-) | Получает или задает количество байтов. |
| [getData()](#getData--) | Получает или задаёт данные. |
| [setData(byte[] value)](#setData-byte---) | Получает или задаёт данные. |
| [getChecked()](#getChecked--) | Получает значение, указывающее, отмечен ли этот `WmfEscapeRecordBase`. |
| [setChecked(boolean value)](#setChecked-boolean-) | Получает значение, указывающее, отмечен ли этот `WmfEscapeRecordBase`. |
### WmfEscapeRecordBase() {#WmfEscapeRecordBase--}
```
public WmfEscapeRecordBase()
```


### getByteCount() {#getByteCount--}
```
public int getByteCount()
```


Получает или задает количество байтов.

Значение: 16-битное беззнаковое целое, указывающее размер в байтах последующих данных записи. Это значение ДОЛЖНО быть 34 плюс значение поля EnhancedMetafileDataSize.

**Returns:**
int
### setByteCount(int value) {#setByteCount-int-}
```
public void setByteCount(int value)
```


Получает или задает количество байтов.

Значение: 16-битное беззнаковое целое, указывающее размер в байтах последующих данных записи. Это значение ДОЛЖНО быть 34 плюс значение поля EnhancedMetafileDataSize.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задаёт данные.

Значение: данные.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задаёт данные.

Значение: данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getChecked() {#getChecked--}
```
public boolean getChecked()
```


Получает значение, указывающее, отмечен ли этот `WmfEscapeRecordBase`.

Значение: `true`, если отмечено; иначе `false`.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public void setChecked(boolean value)
```


Получает значение, указывающее, отмечен ли этот `WmfEscapeRecordBase`.

Значение: `true`, если отмечено; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

