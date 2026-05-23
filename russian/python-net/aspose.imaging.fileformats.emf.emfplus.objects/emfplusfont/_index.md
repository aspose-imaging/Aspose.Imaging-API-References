---
title: "EmfPlusFont Class"
type: docs
weight: 330
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---

**Summary:** The EmfPlusFont object specifies properties that determine the appearance of text, including<br/>            typeface, size, and style.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFont

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFont()](#EmfPlusFont__1) | Инициализирует новый экземпляр класса EmfPlusFont |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| em_size | float | r/w | Получает или задает 32-битное число с плавающей точкой, которое определяет размер em шрифта <br/>            в единицах, указанных в поле SizeUnit. |
| family_name | string | r/w | Получает или задает строку длиной Length Unicode символов, содержащую<br/>            название семейства шрифта |
| font_style_flags | [EmfPlusFontStyleFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfontstyleflags/) | r/w | Получает или задает 32-битное знаковое целое, которое определяет атрибуты глифов символов, влияющие на внешний вид шрифта, <br/>            такие как полужирный и курсив. Это значение ДОЛЖНО состоять из флагов FontStyle (раздел 2.1.2.4). |
| size_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Получает или задает 32-битное беззнаковое целое, которое определяет единицы измерения, используемые для <br/>            поля EmSize. Обычно это единицы, которые были <br/>            применены при проектировании шрифта. Значение ДОЛЖНО быть в <br/>            перечислении UnitType (раздел 2.1.1.33). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Получает или задает версию. |


### Constructor: EmfPlusFont() {#EmfPlusFont__1}


```
 EmfPlusFont() 
```

Инициализирует новый экземпляр класса EmfPlusFont

