---
title: "EmfGradientRectangle"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект GradientRectangle определяет прямоугольник, используя объекты TriVertex раздел 2.2.26 в записи EMR_GRADIENTFILL раздел 2.3.5.12."
type: docs
weight: 16
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfGradientRectangle extends EmfObject
```

Объект GradientRectangle определяет прямоугольник с использованием объектов TriVertex (раздел 2.2.26) в записи EMR\_GRADIENTFILL (раздел 2.3.5.12).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfGradientRectangle()](#EmfGradientRectangle--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getUpperLeft()](#getUpperLeft--) | Получает или задает индекс в массиве объектов TriVertex, который указывает верхнюю‑левую вершину прямоугольника. |
| [setUpperLeft(int value)](#setUpperLeft-int-) | Получает или задает индекс в массиве объектов TriVertex, который указывает верхнюю‑левую вершину прямоугольника. |
| [getLowerRight()](#getLowerRight--) | Получает или задает индекс в массиве объектов TriVertex, который указывает нижнюю‑правую вершину прямоугольника. |
| [setLowerRight(int value)](#setLowerRight-int-) | Получает или задает индекс в массиве объектов TriVertex, который указывает нижнюю‑правую вершину прямоугольника. |
### EmfGradientRectangle() {#EmfGradientRectangle--}
```
public EmfGradientRectangle()
```


### getUpperLeft() {#getUpperLeft--}
```
public int getUpperLeft()
```


Получает или задает индекс в массиве объектов TriVertex, который указывает верхнюю‑левую вершину прямоугольника. Индекс ДОЛЖЕН быть меньше размера массива, определяемого полем nVer записи EMR\_GRADIENTFILL.

**Returns:**
int
### setUpperLeft(int value) {#setUpperLeft-int-}
```
public void setUpperLeft(int value)
```


Получает или задает индекс в массиве объектов TriVertex, который указывает верхнюю‑левую вершину прямоугольника. Индекс ДОЛЖЕН быть меньше размера массива, определяемого полем nVer записи EMR\_GRADIENTFILL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLowerRight() {#getLowerRight--}
```
public int getLowerRight()
```


Получает или задает индекс в массиве объектов TriVertex, который указывает нижнюю‑правую вершину прямоугольника. Индекс ДОЛЖЕН быть меньше размера массива, определяемого полем nVer записи EMR\_GRADIENTFILL.

**Returns:**
int
### setLowerRight(int value) {#setLowerRight-int-}
```
public void setLowerRight(int value)
```


Получает или задает индекс в массиве объектов TriVertex, который указывает нижнюю‑правую вершину прямоугольника. Индекс ДОЛЖЕН быть меньше размера массива, определяемого полем nVer записи EMR\_GRADIENTFILL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

