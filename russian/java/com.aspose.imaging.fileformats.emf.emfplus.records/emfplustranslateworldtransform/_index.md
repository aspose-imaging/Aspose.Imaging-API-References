---
title: "EmfPlusTranslateWorldTransform"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusTranslateWorldTransform выполняет трансляцию текущего мирового преобразования."
type: docs
weight: 72
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusTranslateWorldTransform выполняет трансляцию текущего мирового преобразования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusTranslateWorldTransform`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Получает значение, указывающее, является ли [post multiplied matrix]. |
| [getDx()](#getDx--) | Получает или задает 32‑битное значение с плавающей точкой, определяющее горизонтальное расстояние. |
| [setDx(float value)](#setDx-float-) | Получает или задает 32‑битное значение с плавающей точкой, определяющее горизонтальное расстояние. |
| [getDy()](#getDy--) | Получает или задает 32‑битное значение с плавающей точкой, определяющее значение вертикального расстояния. |
| [setDy(float value)](#setDy-float-) | Получает или задает 32‑битное значение с плавающей точкой, определяющее значение вертикального расстояния. |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusTranslateWorldTransform`.

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
### getDx() {#getDx--}
```
public float getDx()
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее горизонтальное расстояние. Перемещение выполняется путем построения новой матрицы мирового преобразования из полей dx и dy.

Значение: dx.

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее горизонтальное расстояние. Перемещение выполняется путем построения новой матрицы мирового преобразования из полей dx и dy.

Значение: dx.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее значение вертикального расстояния.

Значение: dy.

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


Получает или задает 32‑битное значение с плавающей точкой, определяющее значение вертикального расстояния.

Значение: dy.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

