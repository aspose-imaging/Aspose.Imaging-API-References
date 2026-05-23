---
title: "Класс EmfPlusPenOptionalData"
type: docs
weight: 560
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | Инициализирует новый экземпляр класса EmfPlusPenOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | Получает или задает необязательный объект EmfPlusCompoundLineData (section 2.2.2.9) <br/>            который определяет массив чисел с плавающей точкой, задающих <br/>            составную линию пера, состоящую из параллельных линий <br/>            и промежутков. Это поле ДОЛЖНО присутствовать, если <br/>            флаг PenDataCompoundLine установлен в поле PenDataFlags <br/>            объекта EmfPlusPenData |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | Получает или задает необязательный объект EmfPlusCustomEndCapData (section 2.2.2.11) <br/>            который определяет форму пользовательской конечной насадки, используемую <br/>            в конце линии, нарисованной этим пером. Это может быть любая из <br/>            различных форм, например квадрат, круг или ромб. Это <br/>            поле ДОЛЖНО присутствовать, если флаг PenDataCustomEndCap <br/>            установлен в поле PenDataFlags объекта EmfPlusPenData |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | Получает или задает необязательный объект EmfPlusCustomStartCapData (section 2.2.2.15) <br/>            который определяет форму пользовательской начальной насадки, используемую <br/>            в начале линии, нарисованной этим пером. Это может быть любая <br/>            из различных форм, например квадрат, круг или ромб. <br/>            Это поле ДОЛЖНО присутствовать, если флаг PenDataCustomStartCap <br/>            установлен в поле PenDataFlags объекта EmfPlusPenData |
| dash_offset | float | r/w | Получает или задает необязательное 32‑битное значение с плавающей точкой, которое определяет <br/>            расстояние от начала линии до начала <br/>            первого пробела в шаблоне пунктирной линии. Это поле ДОЛЖНО <br/>            присутствовать, если флаг PenDataDashedLineOffset установлен в <br/>            поле PenDataFlags объекта EmfPlusPenData. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | Получает или задает необязательное 32‑битное знаковое целое, которое определяет форму <br/>            обоих концов каждого штриха в пунктирной линии. Это поле ДОЛЖНО <br/>            присутствовать, если флаг PenDataDashedLineCap установлен в <br/>            поле PenDataFlags объекта EmfPlusPenData, и <br/>            значение ДОЛЖНО быть определено в перечислении DashedLineCapType <br/>            (section 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | Получает или задает необязательный объект EmfPlusDashedLineData (section 2.2.2.16) <br/>            который определяет длины штрихов и пробелов в пользовательской <br/>            пунктирной линии. Это поле ДОЛЖНО присутствовать, если флаг PenDataDashedLine <br/>            установлен в поле PenDataFlags объекта EmfPlusPenData<br/>            . |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Получает или задает необязательное 32‑битное знаковое целое, которое определяет форму<br/>             конца линии в поле CustomEndCapData. Это <br/>            поле ДОЛЖНО присутствовать, если флаг PenDataEndCap установлен в <br/>            поле PenDataFlags объекта EmfPlusPenData, и значение <br/>            ДОЛЖНО быть определено в перечислении LineCapType |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Получает или задает необязательное 32‑битное знаковое целое, которое определяет способ соединения<br/>             двух линий, нарисованных одним и тем же пером и чьи концы соприкасаются. <br/>            Это поле ДОЛЖНО присутствовать, если флаг PenDataJoin установлен в <br/>            поле PenDataFlags объекта EmfPlusPenData, и значение <br/>            ДОЛЖНО быть определено в перечислении LineJoinType <br/>            (section 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | Получает или задает необязательное 32‑битное знаковое целое, которое определяет стиль <br/>            используемый для линий, нарисованных этим объектом пера. Это поле ДОЛЖНО <br/>            присутствовать, если флаг PenDataLineStyle установлен в <br/>            поле PenDataFlags объекта EmfPlusPenData, и значение <br/>            ДОЛЖНО быть определено в перечислении LineStyle <br/>            (section 2.1.1.20). |
| miter_limit | float | r/w | Получает или задает необязательное 32‑разрядное значение с плавающей точкой, которое указывает предел miter <br/>            limit, определяющий максимальное допустимое отношение длины miter к<br/>            ширине линии. Длина miter — это расстояние от<br/>            пересечения стенок линии внутри соединения до <br/>            пересечения стенок линии снаружи соединения. <br/>            Длина miter может быть большой, когда угол между двумя <br/>            линиями мал. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | Получает или задает необязательное 32‑разрядное целое со знаком, которое определяет <br/>            распределение ширины пера относительно <br/>            координат линии, которая рисуется. Это поле ДОЛЖНО быть присутствующим, если флаг PenDataNonCenter установлен в поле PenDataFlags объекта EmfPlusPenData, и <br/>            значение ДОЛЖНО быть определено в перечислении PenAlignment (раздел 2.1.1.24). |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Получает или задает необязательное 32‑разрядное целое со знаком, которое определяет форму <br/>            начала линии в поле CustomStartCapData. <br/>            Это поле ДОЛЖНО присутствовать, если флаг PenDataStartCap установлен <br/>            в поле PenDataFlags объекта EmfPlusPenData, и <br/>            значение ДОЛЖНО быть определено в перечислении LineCapType (раздел 2.1.1.18). |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47) <br/>            который определяет преобразование из мирового пространства в пространство устройства для <br/>            пера. Это поле ДОЛЖНО присутствовать, если флаг PenDataTransform <br/>            установлен в поле PenDataFlags объекта EmfPlusPenData <br/>            . |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

Инициализирует новый экземпляр класса EmfPlusPenOptionalData

