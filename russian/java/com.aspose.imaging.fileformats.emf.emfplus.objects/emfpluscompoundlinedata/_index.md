---
title: "EmfPlusCompoundLineData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusCompoundLineData указывает данные о линиях и промежутках для составной линии."
type: docs
weight: 30
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusCompoundLineData extends EmfPlusStructureObjectType
```

Объект EmfPlusCompoundLineData указывает данные о линиях и промежутках для составной линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusCompoundLineData()](#EmfPlusCompoundLineData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompoundLineData()](#getCompoundLineData--) | Получает или задает массив чисел с плавающей запятой типа CompoundLineDataSize, которые определяют составную линию пера. |
| [setCompoundLineData(float[] value)](#setCompoundLineData-float---) | Получает или задает массив чисел с плавающей запятой типа CompoundLineDataSize, которые определяют составную линию пера. |
### EmfPlusCompoundLineData() {#EmfPlusCompoundLineData--}
```
public EmfPlusCompoundLineData()
```


### getCompoundLineData() {#getCompoundLineData--}
```
public float[] getCompoundLineData()
```


Получает или задает массив чисел с плавающей запятой типа CompoundLineDataSize, которые определяют составную линию пера. Элементы ДОЛЖНЫ располагаться в порядке возрастания, и их значения ДОЛЖНЫ находиться в диапазоне от 0.0 до 1.0 включительно.

**Returns:**
float[]
### setCompoundLineData(float[] value) {#setCompoundLineData-float---}
```
public void setCompoundLineData(float[] value)
```


Получает или задает массив чисел с плавающей запятой типа CompoundLineDataSize, которые определяют составную линию пера. Элементы ДОЛЖНЫ располагаться в порядке возрастания, и их значения ДОЛЖНЫ находиться в диапазоне от 0.0 до 1.0 включительно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

