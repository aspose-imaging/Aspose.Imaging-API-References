---
title: "EmfSetIcmMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETICMMODE задает режим управления цветом изображения ICM для графических операций."
type: docs
weight: 125
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

Запись EMR\_SETICMMODE указывает режим управления цветом изображения (ICM) для графических операций.

Когда режим ICM включён, цвета, указанные в записях EMF, ДОЛЖНЫ быть согласованы по цвету, тогда как профиль цвета по умолчанию в контексте устройства воспроизведения ДОЛЖЕН использоваться при выполнении побитовой передачи. Если профиль цвета по умолчанию не требуется, режим ICM ДОЛЖЕН быть отключён перед выполнением побитовой передачи.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetIcmMode`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | Получает или задает 32‑битное беззнаковое целое, определяющее включение или отключение ICM, из перечисления ICMMode (раздел 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее включение или отключение ICM, из перечисления ICMMode (раздел 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetIcmMode`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


Получает или задает 32‑битное беззнаковое целое, определяющее включение или отключение ICM, из перечисления ICMMode (раздел 2.1.18). Это значение является частью состояния контекста устройства воспроизведения.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее включение или отключение ICM, из перечисления ICMMode (раздел 2.1.18). Это значение является частью состояния контекста устройства воспроизведения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

