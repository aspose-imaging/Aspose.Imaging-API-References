---
title: "EmfPlusSetWorldTransform"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetWorldTransform задает мировое преобразование в соответствии со значениями в указанной матрице преобразования."
type: docs
weight: 68
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusSetWorldTransform задает мировое преобразование в соответствии со значениями в указанной матрице преобразования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetWorldTransform`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет новое текущее мировое преобразование. |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет новое текущее мировое преобразование. |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetWorldTransform`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет новое текущее мировое преобразование.

Значение: данные матрицы.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


Получает или задает объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет новое текущее мировое преобразование.

Значение: данные матрицы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

