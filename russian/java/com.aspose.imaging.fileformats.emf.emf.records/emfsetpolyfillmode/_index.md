---
title: "EmfSetPolyFillMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETPOLYFILLMODE определяет режим заполнения полигона."
type: docs
weight: 136
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetPolyFillMode extends EmfStateRecordType
```

Запись EMR\_SETPOLYFILLMODE задает режим заливки полигонов.

Как правило, режимы различаются только в случаях, когда сложный, перекрывающийся полигон MUST быть заполнен; например, пятиугольник, образующий пятиконечную звезду с пятиугольником в центре. В таких случаях режим ALTERNATE SHOULD заполнять каждый второй замкнутый регион внутри полигона (концы звезды), а режим WINDING SHOULD заполнять все регионы (концы звезды и пятиугольник). Когда режим заполнения ALTERNATE, область между нечетными и четными сторонами полигона на каждой строке сканирования SHOULD быть заполнена. То есть область между первой и второй стороной SHOULD быть заполнена, между третьей и четвертой стороной и т.д. Когда режим заполнения WINDING, любой регион, имеющий ненулевое значение winding, SHOULD быть заполнен. Значение winding — это количество раз, которое перо, использованное для рисования полигона, обходит регион. Направление каждой грани полигона имеет значение.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetPolyFillMode(EmfRecord source)](#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetPolyFillMode`. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode--) | Инициализирует новый экземпляр класса `EmfSetPolyFillMode`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPolygonFillMode()](#getPolygonFillMode--) | Получает или задает 32-битное беззнаковое целое, которое определяет режим заполнения полигона и MUST быть в перечислении PolygonFillMode (section 2.1.27). |
| [setPolygonFillMode(int value)](#setPolygonFillMode-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет режим заполнения полигона и MUST быть в перечислении PolygonFillMode (section 2.1.27). |
### EmfSetPolyFillMode(EmfRecord source) {#EmfSetPolyFillMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPolyFillMode(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetPolyFillMode`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode--}
```
public EmfSetPolyFillMode()
```


Инициализирует новый экземпляр класса `EmfSetPolyFillMode`.

### getPolygonFillMode() {#getPolygonFillMode--}
```
public int getPolygonFillMode()
```


Получает или задает 32-битное беззнаковое целое, которое определяет режим заполнения полигона и MUST быть в перечислении PolygonFillMode (section 2.1.27).

**Returns:**
int
### setPolygonFillMode(int value) {#setPolygonFillMode-int-}
```
public void setPolygonFillMode(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет режим заполнения полигона и MUST быть в перечислении PolygonFillMode (section 2.1.27).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

