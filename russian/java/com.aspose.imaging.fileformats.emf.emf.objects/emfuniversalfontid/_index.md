---
title: "EmfUniversalFontId"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект UniversalFontId определяет механизм идентификации шрифтов в метафайлах EMF."
type: docs
weight: 37
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

Объект UniversalFontId определяет механизм идентификации шрифтов в метафайлах EMF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getChecksum()](#getChecksum--) | Получает или задает 32‑битное беззнаковое целое, являющееся контрольной суммой шрифта. |
| [setChecksum(int value)](#setChecksum-int-) | Получает или задает 32‑битное беззнаковое целое, являющееся контрольной суммой шрифта. |
| [getIndex()](#getIndex--) | Получает или задает 32‑битное беззнаковое целое, являющееся индексом, связанным с объектом шрифта. |
| [setIndex(int value)](#setIndex-int-) | Получает или задает 32‑битное беззнаковое целое, являющееся индексом, связанным с объектом шрифта. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Получает или задает 32‑битное беззнаковое целое, являющееся контрольной суммой шрифта. Значение контрольной суммы имеет следующее значение. 0x00000000 Объект является шрифтом устройства. 0x00000001 Объект является шрифтом Type 1, установленным на клиентском компьютере и перечисляемым драйвером принтера PostScript как шрифт устройства. 0x00000002 Объект не является шрифтом, а представляет собой растеризатор Type 1. 3 \\u2264 value Объект является растровым, векторным или TrueType‑шрифтом, либо растеризованным шрифтом Type 1, созданным растеризатором Type 1.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Получает или задает 32‑битное беззнаковое целое, являющееся контрольной суммой шрифта. Значение контрольной суммы имеет следующее значение. 0x00000000 Объект является шрифтом устройства. 0x00000001 Объект является шрифтом Type 1, установленным на клиентском компьютере и перечисляемым драйвером принтера PostScript как шрифт устройства. 0x00000002 Объект не является шрифтом, а представляет собой растеризатор Type 1. 3 \\u2264 value Объект является растровым, векторным или TrueType‑шрифтом, либо растеризованным шрифтом Type 1, созданным растеризатором Type 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Получает или задает 32‑битное беззнаковое целое, являющееся индексом, связанным с объектом шрифта. Значение этого поля определяется типом шрифта.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Получает или задает 32‑битное беззнаковое целое, являющееся индексом, связанным с объектом шрифта. Значение этого поля определяется типом шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

