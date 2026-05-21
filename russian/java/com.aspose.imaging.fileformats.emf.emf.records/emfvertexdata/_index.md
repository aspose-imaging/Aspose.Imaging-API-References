---
title: "EmfVertexData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объекты, которые задают вершины прямоугольников или треугольников и соответствующие им цвета."
type: docs
weight: 155
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Объекты, которые задают вершины прямоугольников или треугольников и соответствующие им цвета.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | Получает или задает массив объектов nVer TriVertex (раздел 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | Получает или задает массив объектов nVer TriVertex (раздел 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | Получает или задает массив объектов nTri GradientRectangle (раздел 2.2.7) или GradientTriangle (раздел 2.2.8) в зависимости от значения поля ulMode. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | Получает или задает массив объектов nTri GradientRectangle (раздел 2.2.7) или GradientTriangle (раздел 2.2.8) в зависимости от значения поля ulMode. |
| [getVertexPadding()](#getVertexPadding--) | Получает или задает необязательный массив переменной длины, состоящий из nTri по четыре байта, который ДОЛЖЕН присутствовать, если значение поля ulMode указывает на объекты GradientRectangle (раздел 2.2.7). |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | Получает или задает необязательный массив переменной длины, состоящий из nTri по четыре байта, который ДОЛЖЕН присутствовать, если значение поля ulMode указывает на объекты GradientRectangle (раздел 2.2.7). |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


Получает или задает массив объектов nVer TriVertex (раздел 2.2.26). Каждый объект определяет позицию и цвет вершины прямоугольника или треугольника в зависимости от значения поля ulMode.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


Получает или задает массив объектов nVer TriVertex (раздел 2.2.26). Каждый объект определяет позицию и цвет вершины прямоугольника или треугольника в зависимости от значения поля ulMode.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


Получает или задает массив объектов nTri GradientRectangle (раздел 2.2.7) или GradientTriangle (раздел 2.2.8) в зависимости от значения поля ulMode. Каждый объект указывает индексы в массиве объектов TriVertex в поле VertexObjects.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


Получает или задает массив объектов nTri GradientRectangle (раздел 2.2.7) или GradientTriangle (раздел 2.2.8) в зависимости от значения поля ulMode. Каждый объект указывает индексы в массиве объектов TriVertex в поле VertexObjects.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


Получает или задает необязательный массив переменной длины, состоящий из nTri по четыре байта, который ДОЛЖЕН присутствовать, если значение поля ulMode указывает на объекты GradientRectangle (раздел 2.2.7). Если значение поля ulMode указывает на объекты GradientTriangle (раздел 2.2.8), поле VertexPadding отсутствует. Это поле ДОЛЖНО игнорироваться.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


Получает или задает необязательный массив переменной длины, состоящий из nTri по четыре байта, который ДОЛЖЕН присутствовать, если значение поля ulMode указывает на объекты GradientRectangle (раздел 2.2.7). Если значение поля ulMode указывает на объекты GradientTriangle (раздел 2.2.8), поле VertexPadding отсутствует. Это поле ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

