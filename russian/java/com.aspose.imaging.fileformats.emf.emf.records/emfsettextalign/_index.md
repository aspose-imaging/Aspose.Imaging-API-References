---
title: "EmfSetTextAlign"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETTEXTALIGN задаёт выравнивание текста."
type: docs
weight: 139
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextAlign extends EmfStateRecordType
```

Запись EMR\_SETTEXTALIGN указывает выравнивание текста.

Записи EMR\_SMALLTEXTOUT, EMR\_EXTTEXTOUTA и EMR\_EXTTEXTOUTW используют значения выравнивания текста для позиционирования строки текста на носителе вывода. Эти значения определяют взаимосвязь между опорной точкой и прямоугольником, ограничивающим текст. Опорная точка может быть текущей позицией или точкой, переданной в запись вывода текста. Прямоугольник, ограничивающий текст, формируется ячейками символов в строке текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetTextAlign(EmfRecord source)](#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetTextAlign`. |
| [EmfSetTextAlign()](#EmfSetTextAlign--) | Инициализирует новый экземпляр класса `EmfSetTextAlign`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getTextAlignmentMode()](#getTextAlignmentMode--) | Получает или задаёт 32‑битное беззнаковое целое, которое задаёт выравнивание текста с помощью маски флагов выравнивания. |
| [setTextAlignmentMode(int value)](#setTextAlignmentMode-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое задаёт выравнивание текста с помощью маски флагов выравнивания. |
### EmfSetTextAlign(EmfRecord source) {#EmfSetTextAlign-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextAlign(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetTextAlign`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSetTextAlign() {#EmfSetTextAlign--}
```
public EmfSetTextAlign()
```


Инициализирует новый экземпляр класса `EmfSetTextAlign`.

### getTextAlignmentMode() {#getTextAlignmentMode--}
```
public int getTextAlignmentMode()
```


Получает или задаёт 32‑битное беззнаковое целое, которое задаёт выравнивание текста с помощью маски флагов выравнивания. Это либо `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] раздел 2.1.2.3) для текста с горизонтальной базовой линией, либо `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] раздел 2.1.2.4) для текста с вертикальной базовой линией. Можно выбрать только одно значение из тех, которые влияют на горизонтальное и вертикальное выравнивание.

**Returns:**
int
### setTextAlignmentMode(int value) {#setTextAlignmentMode-int-}
```
public void setTextAlignmentMode(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое задаёт выравнивание текста с помощью маски флагов выравнивания. Это либо `Wmf.Consts.WmfTextAlignmentModeFlags` ([MS-WMF] раздел 2.1.2.3) для текста с горизонтальной базовой линией, либо `Wmf.Consts.WmfVerticalTextAlignmentModeFlags` ([MS-WMF] раздел 2.1.2.4) для текста с вертикальной базовой линией. Можно выбрать только одно значение из тех, которые влияют на горизонтальное и вертикальное выравнивание.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

