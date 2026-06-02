---
title: "EmfPlusLanguageIdentifier"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusLanguageIdentifier определяет идентификатор языка, соответствующий естественному языку в локали, включая страны, географические регионы и административные районы."
type: docs
weight: 50
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

Объект EmfPlusLanguageIdentifier определяет идентификатор языка, соответствующий естественному языку в локали, включая страны, географические регионы и административные районы. Каждый идентификатор языка представляет собой кодировку значения основного языка и значения подязыка.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 бит): Страна, географический регион или административный район для естественного языка, указанного в поле PrimaryLanguageId. |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 бит): Страна, географический регион или административный район для естественного языка, указанного в поле PrimaryLanguageId. |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


Получает или задает значение поля 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 бит): Страна, географический регион или административный район для естественного языка, указанного в поле PrimaryLanguageId. Идентификаторы подязыков расширяемы поставщиком. Идентификаторы подязыков, определённые поставщиком, ДОЛЖНЫ находиться в диапазоне от 0x20 до 0x3F включительно. PrimaryLanguageId (10 бит): Естественный язык. Идентификаторы основных языков расширяемы поставщиком. Идентификаторы основных языков, определённые поставщиком, ДОЛЖНЫ находиться в диапазоне от 0x0200 до 0x03FF включительно.

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


Получает или задает значение поля 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 бит): Страна, географический регион или административный район для естественного языка, указанного в поле PrimaryLanguageId. Идентификаторы подязыков расширяемы поставщиком. Идентификаторы подязыков, определённые поставщиком, ДОЛЖНЫ находиться в диапазоне от 0x20 до 0x3F включительно. PrimaryLanguageId (10 бит): Естественный язык. Идентификаторы основных языков расширяемы поставщиком. Идентификаторы основных языков, определённые поставщиком, ДОЛЖНЫ находиться в диапазоне от 0x0200 до 0x03FF включительно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

