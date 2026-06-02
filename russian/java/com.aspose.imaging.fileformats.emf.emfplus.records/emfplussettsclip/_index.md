---
title: "EmfPlusSetTsClip"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetTSClip указывает области отсечения в контексте графического устройства для терминального сервера."
type: docs
weight: 66
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

Запись EmfPlusSetTSClip указывает области отсечения в контексте графического устройства для терминального сервера.

Схема сжатия данных в этой записи использует следующий алгоритм. Каждая точка каждого прямоугольника кодируется либо одним байтом, либо 2 байтами. Если точка кодируется одним байтом, старший бит (0x80) байта ДОЛЖЕН быть установлен, а значение представляет собой знаковое число, закодированное в нижних 7 битах. Если старший бит не установлен, значение кодируется 2 байтами: старший байт кодируется в 7 нижних битах первого байта, а значение младшего байта кодируется во втором байте. Каждая точка кодируется как разница между точкой в текущем прямоугольнике и точкой в предыдущем прямоугольнике. Нижняя точка прямоугольника кодируется как разница между нижней координатой и верхней координатой в текущем прямоугольнике.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetTsClip`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Получает значение, указывающее, сжат ли этот `EmfPlusSetTsClip`. |
| [getNumRects()](#getNumRects--) | Получает количество прямоугольников. |
| [getRects()](#getRects--) | Получает или задает массив прямоугольников NumRects, определяющих области отсечения. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Получает или задает массив прямоугольников NumRects, определяющих области отсечения. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetTsClip`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Получает значение, указывающее, сжат ли этот `EmfPlusSetTsClip`. Этот бит определяет формат данных прямоугольников в поле rects. Если установлен, каждый прямоугольник задаётся в 4 байта. Если сброшен, каждый прямоугольник задаётся в 8 байт.

Значение: `true`, если сжато; иначе `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Получает количество прямоугольников. Это поле указывает количество прямоугольников, определённых в поле rect.

Значение: количество прямоугольников.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Получает или задает массив прямоугольников NumRects, определяющих области отсечения. Формат этих данных определяется битом C в поле Flags.

Значение: прямоугольники.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Получает или задает массив прямоугольников NumRects, определяющих области отсечения. Формат этих данных определяется битом C в поле Flags.

Значение: прямоугольники.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

