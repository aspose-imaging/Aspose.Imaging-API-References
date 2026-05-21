---
title: "EmfEpsData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EpsData является контейнером для данных EPS."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfEpsData extends EmfObject
```

Объект EpsData является контейнером для данных EPS.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfEpsData()](#EmfEpsData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getSizeData()](#getSizeData--) | Получает или задает 32‑битное беззнаковое целое, которое указывает общий размер этого объекта в байтах |
| [setSizeData(int value)](#setSizeData-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает общий размер этого объекта в байтах |
| [getVersion()](#getVersion--) | Получает или задает 32‑битное беззнаковое целое, которое указывает уровень языка PostScript. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает уровень языка PostScript. |
| [getPoints()](#getPoints--) | Получает или задает массив из трёх объектов Point28\_4 (раздел 2.2.23), который определяет координаты выходного параллелограмма, используя 28.4‑битовую FIX‑нотацию. |
| [setPoints(EmfPoint28To4[] value)](#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---) | Получает или задает массив из трёх объектов Point28\_4 (раздел 2.2.23), который определяет координаты выходного параллелограмма, используя 28.4‑битовую FIX‑нотацию. |
| [getPostScriptData()](#getPostScriptData--) | Получает или задает массив байтов данных PostScript. |
| [setPostScriptData(byte[] value)](#setPostScriptData-byte---) | Получает или задает массив байтов данных PostScript. |
### EmfEpsData() {#EmfEpsData--}
```
public EmfEpsData()
```


### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает общий размер этого объекта в байтах

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает общий размер этого объекта в байтах

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает уровень языка PostScript. Это значение ДОЛЖНО быть 0x00000001.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает уровень языка PostScript. Это значение ДОЛЖНО быть 0x00000001.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public EmfPoint28To4[] getPoints()
```


Получает или задает массив из трёх объектов Point28\_4 (раздел 2.2.23), который определяет координаты выходного параллелограмма, используя 28.4‑битовую FIX‑нотацию.

Верхний левый угол параллелограмма — это первая точка в этом массиве, верхний правый угол — вторая точка, а нижний левый угол — третья точка. Нижний правый угол параллелограмма вычисляется из первых трёх точек (A, B и C), рассматривая их как векторы.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4[]
### setPoints(EmfPoint28To4[] value) {#setPoints-com.aspose.imaging.fileformats.emf.emf.objects.EmfPoint28To4---}
```
public void setPoints(EmfPoint28To4[] value)
```


Получает или задает массив из трёх объектов Point28\_4 (раздел 2.2.23), который определяет координаты выходного параллелограмма, используя 28.4‑битовую FIX‑нотацию.

Верхний левый угол параллелограмма — это первая точка в этом массиве, верхний правый угол — вторая точка, а нижний левый угол — третья точка. Нижний правый угол параллелограмма вычисляется из первых трёх точек (A, B и C), рассматривая их как векторы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPoint28To4\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4) |  |

### getPostScriptData() {#getPostScriptData--}
```
public byte[] getPostScriptData()
```


Получает или задает массив байтов данных PostScript. Длина этого массива может быть вычислена из поля SizeData. Эти данные МОГУТ использоваться для рендеринга изображения.

**Returns:**
byte[]
### setPostScriptData(byte[] value) {#setPostScriptData-byte---}
```
public void setPostScriptData(byte[] value)
```


Получает или задает массив байтов данных PostScript. Длина этого массива может быть вычислена из поля SizeData. Эти данные МОГУТ использоваться для рендеринга изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

