---
title: "Класс EmfBlendFunction"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---

**Summary:** A structure that specifies the blending operations for source and destination bitmaps.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfBlendFunction()](#EmfBlendFunction__1) | Инициализирует новый экземпляр класса EmfBlendFunction |
| [EmfBlendFunction(dword_data)](#EmfBlendFunction_dword_data_2) | Инициализирует новый экземпляр класса [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_format | [EmfBlendFunction+AlphaFormatEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction+alphaformatenum/) | r | Получает структуру, определяющую, как исходные и целевые пиксели <br/>            интерпретируются с учётом альфа-прозрачности. |
| blend_flags | System.Byte | r | Получает флаги смешивания.<br/>            Это значение ДОЛЖНО быть 0x00 и ДОЛЖНО игнорироваться. |
| blend_operation | System.Byte | r | Получает код операции смешивания. <br/>            Единственная определённая операция смешивания источника и назначения <br/>            имеет значение 0x00, что указывает, что исходный битмап <br/>            ДОЛЖЕН быть объединён с битмапом назначения на основе значений альфа‑прозрачности <br/>            пикселей источника. См. следующие уравнения для получения подробностей. |
| src_constant_alpha | System.Byte | r | Получает 8‑битное беззнаковое целое, которое задаёт альфа‑прозрачность, <br/>            определяющую смешивание исходного и целевого битмапов. Это значение ДОЛЖНО быть <br/>            использовано для всего исходного битмапа. Минимальное значение альфа‑прозрачности, ноль, <br/>            соответствует полной прозрачности, максимальное значение, 0xFF, соответствует <br/>            полной непрозрачности. По сути, значение 0xFF указывает, что альфа‑значения каждого пикселя <br/>            определяют смешивание исходного и целевого битмапов. См. уравнения далее в <br/>            этом разделе для получения подробностей. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_int()](#to_int__1) | Converts the string representation of a number to an integer. |


### Constructor: EmfBlendFunction() {#EmfBlendFunction__1}


```
 EmfBlendFunction() 
```

Инициализирует новый экземпляр класса EmfBlendFunction

### Constructor: EmfBlendFunction(dword_data) {#EmfBlendFunction_dword_data_2}


```
 EmfBlendFunction(dword_data) 
```

Инициализирует новый экземпляр класса [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) class.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dword_data | int | Данные dword. |

### Method: to_int() {#to_int__1}


```
 to_int() 
```

Converts the string representation of a number to an integer.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Значение DWORD структуры. |


