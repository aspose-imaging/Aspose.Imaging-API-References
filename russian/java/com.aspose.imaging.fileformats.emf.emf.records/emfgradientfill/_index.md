---
title: "EmfGradientFill"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_GRADIENTFILL определяет заполнение прямоугольников или треугольников градиентами цвета."
type: docs
weight: 65
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

Запись EMR\_GRADIENTFILL определяет заполнение прямоугольников или треугольников градиентами цвета.

Запись EMR\_GRADIENTFILL, которая указывает, что три вершины треугольника ДОЛЖНЫ заполнять фигуру плавными градиентами цветов.[85] Запись EMR\_GRADIENTFILL, которая указывает, что верхняя‑левая и нижняя‑правая вершины прямоугольника ДОЛЖНЫ заполнять фигуру плавными градиентами цвета. В перечислении GradientFill существует два режима градиентного заполнения, которые могут использоваться при рисовании прямоугольника. В режиме GRADIENT\_FILL\_RECT\_H прямоугольник заполняется слева направо. В режиме GRADIENT\_FILL\_RECT\_V прямоугольник заполняется сверху вниз. Примечание: запись EMR\_GRADIENTFILL ДОЛЖНА игнорировать поля Alpha в объектах TriVertex. Запись EMR\_ALPHABLEND (раздел 2.3.1.1), непосредственно следующая за записью EMR\_GRADIENTFILL, может использоваться для применения альфа‑прозрачного градиента к заполненной области.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfGradientFill`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в включительно‑включительных единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в включительно‑включительных единицах устройства. |
| [getNVer()](#getNVer--) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество вершин. |
| [setNVer(int value)](#setNVer-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество вершин. |
| [getNTri()](#getNTri--) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество прямоугольников или треугольников для заполнения. |
| [setNTri(int value)](#setNTri-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество прямоугольников или треугольников для заполнения. |
| [getUlMode()](#getUlMode--) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет режим градиентного заполнения. |
| [setUlMode(int value)](#setUlMode-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет режим градиентного заполнения. |
| [getVertexData()](#getVertexData--) | Получает или задает объекты, определяющие вершины прямоугольников или треугольников и соответствующие им цвета. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Получает или задает объекты, определяющие вершины прямоугольников или треугольников и соответствующие им цвета. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfGradientFill`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в включительно‑включительных единицах устройства.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в включительно‑включительных единицах устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество вершин.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество вершин.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество прямоугольников или треугольников для заполнения.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое определяет количество прямоугольников или треугольников для заполнения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Получает или задает 32‑битное беззнаковое целое, определяющее режим градиентного заполнения. Значение ДОЛЖНО находиться в перечислении GradientFill (раздел 2.1.15).

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее режим градиентного заполнения. Значение ДОЛЖНО находиться в перечислении GradientFill (раздел 2.1.15).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Получает или задает объекты, определяющие вершины прямоугольников или треугольников и соответствующие им цвета.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Получает или задает объекты, определяющие вершины прямоугольников или треугольников и соответствующие им цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

