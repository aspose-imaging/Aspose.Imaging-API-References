---
title: "Класс EmfPlusCustomLineCapData"
type: docs
weight: 270
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | Инициализирует новый экземпляр класса EmfPlusCustomLineCapData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает значение из перечисления LineCap (section 2.1.1.18) <br/>            на котором основана пользовательская конечная линия. |
| base_inset | float | r/w | Получает или задает 32‑битное число с плавающей точкой, которое указывает расстояние между началом <br/>            line cap и концом линии. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает данные в поле OptionalData |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в {0.0, 0.0}. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Получает или задает необязательный объект EmfPlusCustomLineCapOptionalData (section 2.2.2.14)<br/>             который указывает дополнительные данные для пользовательской графической line cap. T<br/>            he конкретное содержание этого поля определяется <br/>            значением поля CustomLineCapDataFlags. |
| stroke_end_cap | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает значение в перечислении LineCap, определяющее, какой <br/>            line cap использовать в конце рисуемой линии. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает объект EmfPlusPointF, который в настоящее время не используется. Он ДОЛЖЕН быть установлен в {0.0, 0.0}. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает значение в перечислении LineJoin <br/>            (section 2.1.1.19), определяющее, как соединять две линии, нарисованные<br/>            одним и тем же пером и имеющие совпадающие концы. На пересечении концов двух линий <br/>            соединение линий делает соединение более непрерывным. |
| stroke_miter_limit | float | r/w | Получает или задает 32‑битное число с плавающей точкой, которое содержит предел толщины<br/>            соединения на скошенном угле, задавая максимальное допустимое соотношение<br/>            длины скошенного угла к ширине линии. |
| stroke_start_cap | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает значение в перечислении LineCap, определяющее <br/>            line cap, используемый в начале рисуемой линии. |
| width_scale | float | r/w | Получает или задает 32‑битное число с плавающей точкой, которое указывает величину, на которую необходимо<br/>            масштабировать пользовательскую line cap относительно ширины объекта EmfPlusPen <br/>            (section 2.2.1.7), используемого для рисования линий. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

Инициализирует новый экземпляр класса EmfPlusCustomLineCapData

