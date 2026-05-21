---
title: "EmfPlusSetPageTransform"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetPageTransform указывает коэффициенты масштабирования и единицы измерения для преобразования координат в пространстве страницы в координаты в пространстве устройства."
type: docs
weight: 61
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusSetPageTransform указывает коэффициенты масштабирования и единицы измерения для преобразования координат в пространстве страницы в координаты в пространстве устройства.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetPageTransform`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Получает единицу измерения координат пространства страницы из перечисления UnitType (раздел 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Получает или задает 32‑разрядное число с плавающей точкой, определяющее коэффициент масштабирования при преобразовании координат пространства страницы в координаты пространства устройства. |
| [setPageScale(float value)](#setPageScale-float-) | Получает или задает 32‑разрядное число с плавающей точкой, определяющее коэффициент масштабирования при преобразовании координат пространства страницы в координаты пространства устройства. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetPageTransform`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Получает единицу измерения координат пространства страницы из перечисления UnitType (раздел 2.1.1.33). Это значение НЕ ДОЛЖНО быть UnitTypeDisplay или UnitTypeWorld.

Значение: единица измерения страницы.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Получает или задает 32‑разрядное число с плавающей точкой, определяющее коэффициент масштабирования при преобразовании координат пространства страницы в координаты пространства устройства.

Значение: масштаб страницы.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Получает или задает 32‑разрядное число с плавающей точкой, определяющее коэффициент масштабирования при преобразовании координат пространства страницы в координаты пространства устройства.

Значение: масштаб страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

