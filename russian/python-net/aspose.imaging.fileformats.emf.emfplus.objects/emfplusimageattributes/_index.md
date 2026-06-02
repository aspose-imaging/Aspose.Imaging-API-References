---
title: "Класс EmfPlusImageAttributes"
type: docs
weight: 390
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | Инициализирует новый экземпляр класса EmfPlusImageAttributes |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | Получает или задает объект EmfPlusARGB (section 2.2.2.1), который определяет цвет края, используемый <br/>            когда значение WrapMode равно WrapModeClamp. Этот цвет виден, когда <br/>            исходный прямоугольник, обрабатываемый записью EmfPlusDrawImage (section 2.3.4.8), <br/>            больше самого изображения. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | Получает или задает 32‑битное знаковое целое, которое определяет поведение зажима объекта.<br/>            Оно не используется, пока объект не будет применён к рисуемому изображению.<br/>            Это значение ДОЛЖНО быть одним из значений, определённых в <br/>            следующей таблице. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Получает или задает версию. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Получает или задает 32‑битное беззнаковое целое, которое определяет, как обрабатывать граничные условия с <br/>            значением из перечисления WrapMode (section 2.1.1.34). |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

Инициализирует новый экземпляр класса EmfPlusImageAttributes

