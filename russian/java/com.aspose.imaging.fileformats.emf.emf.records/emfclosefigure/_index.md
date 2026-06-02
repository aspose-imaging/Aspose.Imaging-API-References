---
title: "EmfCloseFigure"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Эта запись закрывает открытую фигуру в пути."
type: docs
weight: 22
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPathBracketRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfpathbracketrecordtype)
```
public final class EmfCloseFigure extends EmfPathBracketRecordType
```

Эта запись закрывает открытую фигуру в пути. Обработка записи EMR\_CLOSEFIGURE ДОЛЖНА закрывать фигуру, рисуя линию от текущей позиции до первой точки фигуры, а затем ДОЛЖНА соединять линии, используя стиль соединения линий. Если фигура закрывается обработкой записи EMR\_LINETO вместо записи EMR\_CLOSEFIGURE, для создания угла используются концевые заглушки вместо соединения. EMR\_LINETO указана в разделе 2.3.5.13. Запись EMR\_CLOSEFIGURE СЛЕДУЕТ использовать только в том случае, если в контексте устройства воспроизведения есть открывающая скобка пути. Фигура в пути считается открытой, если она явно не закрыта обработкой этой записи.

Примечание: Фигура может быть открытой, даже если текущая точка и начальная точка фигуры совпадают. После обработки записи EMR\_CLOSEFIGURE добавление линии или кривой в путь ДОЛЖНО начинать новую фигуру.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCloseFigure()](#EmfCloseFigure--) | Инициализирует новый экземпляр класса `EmfCloseFigure`. |
### EmfCloseFigure() {#EmfCloseFigure--}
```
public EmfCloseFigure()
```


Инициализирует новый экземпляр класса `EmfCloseFigure`.

