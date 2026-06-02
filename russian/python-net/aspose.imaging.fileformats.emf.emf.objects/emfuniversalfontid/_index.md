---
title: "Класс EmfUniversalFontId"
type: docs
weight: 280
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | Инициализирует новый экземпляр класса EmfUniversalFontId |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| checksum | int | r/w | Получает или задает 32-битное беззнаковое целое, являющееся контрольной суммой шрифта.<br/>            Значение контрольной суммы имеет следующее значение.<br/>            0x00000000  Объект является шрифтом устройства. <br/>            0x00000001  Объект — шрифт Type 1, установленный на клиентской машине и <br/>            перечисленный драйвером принтера PostScript как шрифт устройства. <br/>            0x00000002  Объект не является шрифтом, а является растером Type 1. <br/>            3 ≤ value   Объект — растровый, векторный или TrueType шрифт, либо растровый шрифт Type 1, <br/>            созданный растером Type 1. |
| index | int | r/w | Получает или задает 32-битное беззнаковое целое, являющееся индексом, связанным с объектом шрифта. <br/>            Значение этого поля определяется типом шрифта. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

Инициализирует новый экземпляр класса EmfUniversalFontId

