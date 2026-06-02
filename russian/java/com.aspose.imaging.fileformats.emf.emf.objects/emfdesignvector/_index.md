---
title: "EmfDesignVector"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект DesignVector раздела 2.2.3 определяет вектор дизайна, который задает значения осей шрифта многомастерного шрифта."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

Объект DesignVector (раздел 2.2.3) определяет вектор дизайна, который задает значения осей шрифта многомастерового шрифта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getSignature()](#getSignature--) | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО быть установлено в значение 0x08007664. |
| [setSignature(int value)](#setSignature-int-) | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО быть установлено в значение 0x08007664. |
| [getNumAxes()](#getNumAxes--) | Получает или задает 32-битное беззнаковое целое, которое указывает количество элементов в массиве Values. |
| [setNumAxes(int value)](#setNumAxes-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает количество элементов в массиве Values. |
| [getValues()](#getValues--) | Получает или задает необязательный массив 32-битных знаковых целых, который указывает значения осей шрифта многомастерного шрифта OpenType. |
| [setValues(int[] value)](#setValues-int---) | Получает или задает необязательный массив 32-битных знаковых целых, который указывает значения осей шрифта многомастерного шрифта OpenType. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО быть установлено в значение 0x08007664.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО быть установлено в значение 0x08007664.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


Получает или задает 32-битное беззнаковое целое, которое указывает количество элементов в массиве Values. Оно ДОЛЖНО находиться в диапазоне от 0 до 16 включительно.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает количество элементов в массиве Values. Оно ДОЛЖНО находиться в диапазоне от 0 до 16 включительно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Получает или задает необязательный массив 32-битных знаковых целых, который указывает значения осей шрифта многомастерного шрифта OpenType. Максимальное количество значений в массиве — 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Получает или задает необязательный массив 32-битных знаковых целых, который указывает значения осей шрифта многомастерного шрифта OpenType. Максимальное количество значений в массиве — 16.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

