---
title: "EmfSaveDc"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Сохраняет текущее состояние контекста устройства воспроизведения в стек состояний, сохранённых предыдущими записями EMR_SAVEDC, если такие имеются."
type: docs
weight: 112
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Сохраняет текущее состояние контекста устройства воспроизведения в стек состояний, сохранённых предыдущими записями EMR\_SAVEDC, если такие имеются. Состояние состоит из графических свойств и объектов, включая текущий выбранный битмап, кисть, палитру, шрифт, перо и регион. Запись EMR\_RESTOREDC используется для восстановления состояния. Эта запись EMF не задаёт параметров.

Стек может содержать информацию о состоянии для нескольких экземпляров контекста устройства воспроизведения. При восстановлении состояния все более недавно сохранённые экземпляры состояния ДОЛЖНЫ быть отброшены.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSaveDc`. |
| [EmfSaveDc()](#EmfSaveDc--) | Инициализирует новый экземпляр класса `EmfSaveDc`. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSaveDc`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


Инициализирует новый экземпляр класса `EmfSaveDc`.

