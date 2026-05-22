---
title: "الفئة EmfPlusPath"
type: docs
weight: 490
url: /ar/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---

**Summary:** The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The<br/>            order for Bezier data points is the start point, control point 1, control point 2, and end point.For<br/>            more information see[MSDN - DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPath

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPlusPath()](#EmfPlusPath__1) | يُنشئ مثيلاً جديدًا من الفئة EmfPlusPath |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| path_point_flags | [EmfPlusPathPointFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/) | r/w | يحصل أو يعيّن عدد نقاط المسار <br/>            عدد صحيح غير موقع 32‑بت يحدد كيفية تفسير النقاط وأنواع النقاط المرتبطة التي يعرفها هذا الكائن. |
| path_point_types | [EmfPlusBasePointType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype/) | r/w | يحصل أو يعيّن مصفوفة تحدد كيفية استخدام النقاط في حقل PathPoints لرسم المسار. <br/>            يتم تحديد نوع الكائنات في هذه المصفوفة بواسطة العلم R في حقل PathPointFlags |
| path_points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن مصفوفة من نقاط المسار<br/>            مصفوفة من نقاط PathPointCount التي تحدد المسار. يتم تحديد نوع الكائنات في هذه المصفوفة بواسطة حقل PathPointFlags، كما يلي:<br/>            إذا كان العلم P مفعلاً، فإن النقاط هي مواقع نسبية يتم تحديدها بواسطة كائنات EmfPlusPointR (القسم 2.2.2.37).<br/>            إذا كان العلم P غير مفعّل والعلم C مفعلاً، فإن النقاط هي مواقع مطلقة يتم تحديدها بواسطة كائنات EmfPlusPoint (القسم 2.2.2.35).<br/>            إذا كان العلم P غير مفعّل والعلم C غير مفعّل، فإن النقاط هي مواقع مطلقة يتم تحديدها بواسطة كائنات EmfPlusPointF (القسم 2.2.2.36). |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | يحصل أو يضبط الإصدار. |


### Constructor: EmfPlusPath() {#EmfPlusPath__1}


```
 EmfPlusPath() 
```

يُنشئ مثيلاً جديدًا من الفئة EmfPlusPath

