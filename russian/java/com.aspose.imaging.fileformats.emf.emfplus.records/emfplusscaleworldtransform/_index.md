---
title: "EmfPlusScaleWorldTransform"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusScaleWorldTransform выполняет масштабирование текущей трансформации мирового пространства."
type: docs
weight: 52
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusScaleWorldTransform выполняет масштабирование текущей трансформации мирового пространства.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusScaleWorldTransform`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | Получает значение, указывающее, является ли [post multiplied matrix]. |
| [getSx()](#getSx--) | Получает или задает 32-битное число с плавающей запятой, определяющее горизонтальный коэффициент масштабирования. |
| [setSx(float value)](#setSx-float-) | Получает или задает 32-битное число с плавающей запятой, определяющее горизонтальный коэффициент масштабирования. |
| [getSy()](#getSy--) | Получает или задает 32-битное число с плавающей запятой, определяющее вертикальный коэффициент масштабирования. |
| [setSy(float value)](#setSy-float-) | Получает или задает 32-битное число с плавающей запятой, определяющее вертикальный коэффициент масштабирования. |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusScaleWorldTransform`.

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
### getSx() {#getSx--}
```
public float getSx()
```


Получает или задает 32-битное число с плавающей запятой, определяющее горизонтальный коэффициент масштабирования. Масштабирование выполняется путем построения новой матрицы преобразования из значений полей Sx и Sy, как показано в следующей таблице. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Рисунок 3: Матрица масштабирования

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


Получает или задает 32-битное число с плавающей запятой, определяющее горизонтальный коэффициент масштабирования. Масштабирование выполняется путем построения новой матрицы преобразования из значений полей Sx и Sy, как показано в следующей таблице. ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- Рисунок 3: Матрица масштабирования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


Получает или задает 32-битное число с плавающей запятой, определяющее вертикальный коэффициент масштабирования.

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


Получает или задает 32-битное число с плавающей запятой, определяющее вертикальный коэффициент масштабирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

