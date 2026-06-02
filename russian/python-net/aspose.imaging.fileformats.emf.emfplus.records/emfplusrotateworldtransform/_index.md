---
title: "Класс EmfPlusRotateWorldTransform"
type: docs
weight: 410
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---

**Summary:** The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRotateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusRotateWorldTransform(source)](#EmfPlusRotateWorldTransform_source_1) | Инициализирует новый экземпляр класса [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| угол | float | r/w | Получает или задает 32‑битное значение с плавающей запятой, которое задаёт угол вращения в градусах.<br/>            Операция выполняется построением новой матрицы преобразования по следующей<br/>            диаграмме:<br/>            ---------------------------------<br/> | sin(Angle) | cos(Angle) | 0 | <br/> | cos(Angle) | sin(Angle) | 0 | <br/>            ---------------------------------<br/>            Рисунок 2: Матрица преобразования вращения<br/>            Текущий трансформ мирового пространства умножается на эту матрицу, и результат становится<br/>            новым текущим трансформом мирового пространства. Поле Flags определяет порядок умножения. |
| data_size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битно‑выравненное количество<br/>            байтов данных в последующем поле RecordData. Это число не включает 12‑байтовый заголовок записи. |
| flags | int | r/w | Получает или задает 16-битное беззнаковое целое, содержащее информацию для некоторых записей о том, как<br/>            должна выполняться операция и о структуре записи. |
| post_multiplied_matrix | bool | r | Получает значение, указывающее, является ли [post multiplied matrix].<br/>            Если установлен, матрица преобразования должна быть пост‑умножена. Если сброшен, она должна быть предумножена. |
| size | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает 32-битно‑выравненное количество байтов<br/>            во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Получает 16-битное беззнаковое целое, которое идентифицирует тип записи. |


### Constructor: EmfPlusRotateWorldTransform(source) {#EmfPlusRotateWorldTransform_source_1}


```
 EmfPlusRotateWorldTransform(source) 
```

Инициализирует новый экземпляр класса [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Источник. |

