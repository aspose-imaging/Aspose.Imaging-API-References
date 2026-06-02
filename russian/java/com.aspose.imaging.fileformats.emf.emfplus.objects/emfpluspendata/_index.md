---
title: "EmfPlusPenData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusPenData задает свойства графической ручки."
type: docs
weight: 64
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

Объект EmfPlusPenData задает свойства графической ручки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. |
| [getPenUnit()](#getPenUnit--) | Получает или задает 32-битное беззнаковое целое, которое указывает единицы измерения для пера. |
| [setPenUnit(int value)](#setPenUnit-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает единицы измерения для пера. |
| [getPenWidth()](#getPenWidth--) | Получает или задает 32-битное значение с плавающей точкой, которое указывает ширину линии, рисуемой пером, в единицах, указанных в поле PenUnit. |
| [setPenWidth(float value)](#setPenWidth-float-) | Получает или задает 32-битное значение с плавающей точкой, которое указывает ширину линии, рисуемой пером, в единицах, указанных в поле PenUnit. |
| [getOptionalData()](#getOptionalData--) | Получает или задает необязательный объект EmfPlusPenOptionalData (раздел 2.2.2.34), который указывает дополнительные данные для объекта пера. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Получает или задает необязательный объект EmfPlusPenOptionalData (раздел 2.2.2.34), который указывает дополнительные данные для объекта пера. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. Это значение ДОЛЖНО состоять из флагов PenData (раздел 2.1.2.7).

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. Это значение ДОЛЖНО состоять из флагов PenData (раздел 2.1.2.7).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Получает или задает 32-битное беззнаковое целое, которое указывает единицы измерения для пера. Значение ДОЛЖНО быть из перечисления UnitType (раздел 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает единицы измерения для пера. Значение ДОЛЖНО быть из перечисления UnitType (раздел 2.1.1.33).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


Получает или задает 32-битное значение с плавающей точкой, которое указывает ширину линии, рисуемой пером, в единицах, указанных в поле PenUnit. Если указана нулевая ширина, используется минимальное значение, определяемое единицами.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


Получает или задает 32-битное значение с плавающей точкой, которое указывает ширину линии, рисуемой пером, в единицах, указанных в поле PenUnit. Если указана нулевая ширина, используется минимальное значение, определяемое единицами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Получает или задает необязательный объект EmfPlusPenOptionalData (раздел 2.2.2.34), который указывает дополнительные данные для объекта пера. Конкретное содержание этого поля определяется значением поля PenDataFlags.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Получает или задает необязательный объект EmfPlusPenOptionalData (раздел 2.2.2.34), который указывает дополнительные данные для объекта пера. Конкретное содержание этого поля определяется значением поля PenDataFlags.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

