---
title: "Класс EmfRegionDataHeader"
type: docs
weight: 250
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | Инициализирует новый экземпляр класса EmfRegionDataHeader |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Получает или задает 128‑битный объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет <br/>            границы области. |
| count_rects | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает количество прямоугольников в этой области. |
| rgn_size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает размер буфера прямоугольников в байтах. |
| size | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает размер этого объекта в байтах. ДОЛЖНО быть 0x00000020. |
| type | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает тип области. ДОЛЖНО быть <br/>            RDH_RECTANGLES (0x00000001). |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

Инициализирует новый экземпляр класса EmfRegionDataHeader

