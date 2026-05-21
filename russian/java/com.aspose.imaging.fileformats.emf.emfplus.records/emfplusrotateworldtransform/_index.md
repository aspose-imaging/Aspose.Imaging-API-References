---
title: "EmfPlusRotateWorldTransform"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusRotateWorldTransform выполняет вращение текущей трансформации мирового пространства."
type: docs
weight: 50
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusRotateWorldTransform extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusRotateWorldTransform выполняет вращение текущей трансформации мирового пространства.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusRotateWorldTransform(EmfPlusRecord source)](#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusRotateWorldTransform`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Получает значение, указывающее, является ли [post multiplied matrix]. |
| [getAngle()](#getAngle--) | Получает или задает 32‑битное значение с плавающей точкой, определяющее угол вращения в градусах. |
| [setAngle(float value)](#setAngle-float-) | Получает или задает 32‑битное значение с плавающей точкой, определяющее угол вращения в градусах. |
### EmfPlusRotateWorldTransform(EmfPlusRecord source) {#EmfPlusRotateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRotateWorldTransform(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusRotateWorldTransform`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


Получает значение, указывающее, является ли [post multiplied matrix]. Если установлено, матрица преобразования должна быть пост‑умножена. Если сброшено, она должна быть предумножена.

Значение: `true`, если [post multiplied matrix]; иначе `false`.

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public float getAngle()
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее угол вращения в градусах. Операция выполняется построением новой матрицы преобразования по следующей схеме: ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Рисунок 2: Rotation Transform Matrix Текущий трансформ мирового пространства умножается на эту матрицу, и результат становится новым текущим трансформом мирового пространства. Поле Flags определяет порядок умножения.

Значение: угол.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее угол вращения в градусах. Операция выполняется построением новой матрицы преобразования по следующей схеме: ---------------------------------
| sin(Angle) | cos(Angle) | 0 |
| cos(Angle) | sin(Angle) | 0 |
---------------------------------
Рисунок 2: Rotation Transform Matrix Текущий трансформ мирового пространства умножается на эту матрицу, и результат становится новым текущим трансформом мирового пространства. Поле Flags определяет порядок умножения.

Значение: угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

