---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusMultiplyWorldTransform умножает текущую трансформацию мирового пространства на указанную матрицу преобразования."
type: docs
weight: 41
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusMultiplyWorldTransform умножает текущую трансформацию мирового пространства на указанную матрицу преобразования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusMultiplyWorldTransform`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Получает значение, указывающее, является ли [post multiplied matrix]. |
| [getMatrixData()](#getMatrixData--) | Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий матрицу умножения. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий матрицу умножения. |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusMultiplyWorldTransform`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Получает значение, указывающее, является ли [post multiplied matrix]. Если установлено, матрица преобразования должна быть пост‑умножена. Если сброшено, она должна быть премультиплицирована.

Значение: `true`, если [post multiplied matrix]; иначе `false`.

**Returns:**
boolean
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий матрицу умножения.

Значение: данные матрицы.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), определяющий матрицу умножения.

Значение: данные матрицы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

