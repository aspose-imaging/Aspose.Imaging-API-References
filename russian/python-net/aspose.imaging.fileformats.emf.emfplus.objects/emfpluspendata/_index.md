---
title: "Класс EmfPlusPenData"
type: docs
weight: 550
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | Инициализирует новый экземпляр класса EmfPlusPenData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | Получает или задает необязательный объект EmfPlusPenOptionalData (раздел 2.2.2.34) <br/>            который определяет дополнительные данные для объекта пера. Конкретное <br/>            содержание этого поля определяется значением поля <br/>            PenDataFlags. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает данные в поле <br/>            OptionalData. Это значение ДОЛЖНО состоять из флагов PenData <br/>            (раздел 2.1.2.7). |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает единицы измерения <br/>            для пера. Значение ДОЛЖНО быть из перечисления UnitType <br/>            (раздел 2.1.1.33). |
| pen_width | float | r/w | Получает или задает 32‑битное значение с плавающей точкой, которое указывает ширину <br/>            линии, рисуемой пером, в единицах, указанных полем PenUnit <br/>            . Если указана нулевая ширина, используется минимальное значение, <br/>            которое определяется единицами измерения. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

Инициализирует новый экземпляр класса EmfPlusPenData

