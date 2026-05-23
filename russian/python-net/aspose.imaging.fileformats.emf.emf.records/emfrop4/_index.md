---
title: "Класс EmfRop4"
type: docs
weight: 1010
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/
---

**Summary:** A quaternary raster operation, which specifies ternary raster operations for <br/>            the foreground and background colors of a bitmap. These values define how the color data of <br/>            the source rectangle is to be combined with the color data of the destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRop4

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRop4(dword_data)](#EmfRop4_dword_data_1) | Инициализирует новый экземпляр класса [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_rop3 | System.Byte | r | Получает фон ROP3.<br/>            Беззнаковые, старшие 8 бит 24‑битного тернарного <br/>            значения растровой операции из перечисления WMF Ternary Raster Operation ([MS-WMF] раздел 2.1.1.31). Этот код определяет, как комбинировать данные фонового цвета <br/>            исходных и целевых битмапов и шаблон кисти. |
| foreground_rop3 | System.Byte | r | Получает передний план ROP3.<br/>            Беззнаковые, старшие 8 бит 24‑битного тернарного <br/>            значения растровой операции из перечисления WMF Ternary Raster Operation. Этот <br/>            код определяет, как комбинировать данные переднего плана исходных и целевых битмапов и шаблон кисти. |


### Constructor: EmfRop4(dword_data) {#EmfRop4_dword_data_1}


```
 EmfRop4(dword_data) 
```

Инициализирует новый экземпляр класса [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dword_data | int | Данные dword. |

