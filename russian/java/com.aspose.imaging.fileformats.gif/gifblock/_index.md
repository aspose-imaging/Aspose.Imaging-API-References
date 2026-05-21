---
title: "GifBlock"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Реализация блока gif по умолчанию."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

Реализация блока gif по умолчанию.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Ввод расширения. |
## Методы

| Метод | Описание |
| --- | --- |
| [isChanged()](#isChanged--) | Получает или задаёт значение, указывающее, изменён ли блок и требует ли сохранения. |
| [setChanged(boolean value)](#setChanged-boolean-) | Получает или задаёт значение, указывающее, изменён ли блок и требует ли сохранения. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Сохраняет блок в указанный поток. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Ввод расширения.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Получает или задаёт значение, указывающее, изменён ли блок и требует ли сохранения.

Значение: `true`, если блок изменён; иначе `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Получает или задаёт значение, указывающее, изменён ли блок и требует ли сохранения.

Значение: `true`, если блок изменён; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Сохраняет блок в указанный поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Поток, в который сохраняются данные. |

