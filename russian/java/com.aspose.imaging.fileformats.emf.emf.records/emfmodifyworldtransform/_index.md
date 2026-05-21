---
title: "EmfModifyWorldTransform"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_MODIFYWORLDTRANSFORM изменяет текущую трансформацию из мирового пространства в пространство страницы в контексте устройства воспроизведения."
type: docs
weight: 73
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

Запись EMR\_MODIFYWORLDTRANSFORM изменяет текущую трансформацию из мирового пространства в пространство страницы в контексте устройства воспроизведения.

Для получения дополнительной информации о трансформациях и координатных пространствах см. [MSDN-WRLDPGSC]. Смотрите раздел 2.3.12 для спецификации других типов записей трансформаций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfModifyWorldTransform`. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Инициализирует новый экземпляр класса `EmfModifyWorldTransform`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как используется трансформация, указанная в Xform. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Получает или задает 32‑битное беззнаковое целое число, которое определяет, как используется трансформация, указанная в Xform. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfModifyWorldTransform`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Инициализирует новый экземпляр класса `EmfModifyWorldTransform`.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Получает или задает 32‑битное беззнаковое целое число, которое определяет, как используется трансформация, указанная в Xform. Это значение ДОЛЖНО находиться в перечислении ModifyWorldTransformMode (раздел 2.1.24).

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Получает или задает 32‑битное беззнаковое целое число, которое определяет, как используется трансформация, указанная в Xform. Это значение ДОЛЖНО находиться в перечислении ModifyWorldTransformMode (раздел 2.1.24).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

