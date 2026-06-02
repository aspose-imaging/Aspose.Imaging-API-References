---
title: "EmfPlusCustomLineCapOptionalData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusCustomLineCapOptionalData указывает необязательные данные заливки и контура для пользовательского окончания линии."
type: docs
weight: 37
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCustomLineCapOptionalData extends EmfPlusStructureObjectType
```

Объект EmfPlusCustomLineCapOptionalData указывает необязательные данные заливки и контура для пользовательского окончания линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusCustomLineCapOptionalData()](#EmfPlusCustomLineCapOptionalData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getFillData()](#getFillData--) | Получает или задает необязательный объект EmfPlusFillPath (раздел 2.2.2.17), который определяет путь для заполнения пользовательского графического контура линии. |
| [setFillData(EmfPlusFillPath value)](#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-) | Получает или задает необязательный объект EmfPlusFillPath (раздел 2.2.2.17), который определяет путь для заполнения пользовательского графического контура линии. |
| [getOutlineData()](#getOutlineData--) | Получает или задает необязательный объект EmfPlusLinePath (раздел 2.2.2.26), который определяет путь для обводки пользовательского графического контура линии. |
| [setOutlineData(EmfPlusLinePath value)](#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-) | Получает или задает необязательный объект EmfPlusLinePath (раздел 2.2.2.26), который определяет путь для обводки пользовательского графического контура линии. |
### EmfPlusCustomLineCapOptionalData() {#EmfPlusCustomLineCapOptionalData--}
```
public EmfPlusCustomLineCapOptionalData()
```


### getFillData() {#getFillData--}
```
public EmfPlusFillPath getFillData()
```


Получает или задает необязательный объект EmfPlusFillPath (раздел 2.2.2.17), который определяет путь для заполнения пользовательского графического контура линии. Это поле ДОЛЖНО присутствовать, если флаг CustomLineCapDataFillPath установлен в поле CustomLineCapDataFlags объекта EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath)
### setFillData(EmfPlusFillPath value) {#setFillData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFillPath-}
```
public void setFillData(EmfPlusFillPath value)
```


Получает или задает необязательный объект EmfPlusFillPath (раздел 2.2.2.17), который определяет путь для заполнения пользовательского графического контура линии. Это поле ДОЛЖНО присутствовать, если флаг CustomLineCapDataFillPath установлен в поле CustomLineCapDataFlags объекта EmfPlusCustomLineCapData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusFillPath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfillpath) |  |

### getOutlineData() {#getOutlineData--}
```
public EmfPlusLinePath getOutlineData()
```


Получает или задает необязательный объект EmfPlusLinePath (раздел 2.2.2.26), который определяет путь для обводки пользовательского графического контура линии. Это поле ДОЛЖНО присутствовать, если флаг CustomLineCapDataLinePath установлен в поле CustomLineCapDataFlags объекта EmfPlusCustomLineCapData.

**Returns:**
[EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath)
### setOutlineData(EmfPlusLinePath value) {#setOutlineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinePath-}
```
public void setOutlineData(EmfPlusLinePath value)
```


Получает или задает необязательный объект EmfPlusLinePath (раздел 2.2.2.26), который определяет путь для обводки пользовательского графического контура линии. Это поле ДОЛЖНО присутствовать, если флаг CustomLineCapDataLinePath установлен в поле CustomLineCapDataFlags объекта EmfPlusCustomLineCapData.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusLinePath](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslinepath) |  |

