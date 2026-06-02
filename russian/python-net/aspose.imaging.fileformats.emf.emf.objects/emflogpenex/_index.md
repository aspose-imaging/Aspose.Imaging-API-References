---
title: "Класс EmfLogPenEx"
type: docs
weight: 190
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---

**Summary:** The LogPenEx object specifies the style, width, and color of an extended logical pen.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx

**Inheritance:** EmfBasePen

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogPenEx()](#EmfLogPenEx__1) | Инициализирует новый экземпляр класса EmfLogPenEx |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8). Интерпретация этого<br/>            поля зависит от значения BrushStyle, как показано в таблице ниже в этом разделе. |
| brush_dib_pattern | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Получает или задает шаблон кисти dib. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Получает или задает штриховой узор кисти. Определение этого поля зависит от значения <br/>            BrushStyle, как показано в таблице ниже в этом разделе. |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает стиль кисти для пера из<br/>            перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). <br/>            Если тип пера в поле PenStyle равен PS_GEOMETRIC, это значение ДОЛЖНО быть либо <br/>            BS_SOLID, либо BS_HATCHED. Значение этого поля может быть BS_NULL, но только если <br/>            стиль линии, указанный в PenStyle, равен PS_NULL. Стиль BS_NULL ДОЛЖЕН использоваться <br/>            для указания кисти, не оказывающей влияния. |
| num_style_entities | int | r | Получает количество элементов в массиве, указанном в поле StyleEntry. <br/>            Это значение ДОЛЖНО быть нулём, если PenStyle не указывает PS_USERSTYLE. |
| pen_style | [EmfPenStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/) | r/w | Получает или задает стиль пера |
| style_entry | int[] | r/w | Получает или задает необязательный массив 32‑битных беззнаковых целых, определяющий длины <br/>            штрихов и промежутков в линии, рисуемой этим пером, когда значение PenStyle <br/>            является стилем линии PS_USERSTYLE для пера. Массив содержит количество <br/>            элементов, указанное в NumStyleEntries, но используется так, как будто повторяется бесконечно <br/>            Первый элемент массива задаёт длину первого штриха. Второй <br/>            элемент задаёт длину первого промежутка. Далее длины штрихов и промежутков чередуются.<br/>            Если тип пера в поле PenStyle равен PS_GEOMETRIC, длины указываются в <br/>            логических единицах; в противном случае — в единицах устройства. |
| width | int | r/w | Получает или задает 32‑битное беззнаковое целое, которое указывает ширину линии, рисуемой пером.<br/>            Если тип пера в поле PenStyle равен PS_GEOMETRIC, это значение представляет ширину в<br/>            логических единицах; в противном случае ширина указывается в единицах устройства. <br/>            Если тип пера в поле PenStyle равен PS_COSMETIC, это значение ДОЛЖНО быть 0x00000001. |


### Constructor: EmfLogPenEx() {#EmfLogPenEx__1}


```
 EmfLogPenEx() 
```

Инициализирует новый экземпляр класса EmfLogPenEx

