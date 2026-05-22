---
title: "فئة EmfVertexData"
type: docs
weight: 1460
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---

**Summary:** Objects that specify the vertexes of either rectangles or triangles and <br/>            the colors that correspond to them.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfVertexData

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfVertexData()](#EmfVertexData__1) | ينشئ نسخة جديدة من الفئة EmfVertexData |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| vertex_indexes | [EmfGradientRectangle[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle/) | r/w | يحصل أو يعيّن مصفوفة من كائنات nTri GradientRectangle (القسم 2.2.7) أو <br/>            كائنات GradientTriangle (القسم 2.2.8)، اعتمادًا على قيمة الحقل ulMode. <br/>            كل كائن يحدد فهارس في مصفوفة كائنات TriVertex الموجودة في حقل VertexObjects. |
| vertex_objects | [EmfTriVertex[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emftrivertex/) | r/w | يحصل أو يعيّن مصفوفة من كائنات nVer TriVertex (القسم 2.2.26). كل <br/>            كائن يحدد موضع ولون رأس إما لمستطيل أو مثلث، <br/>            اعتمادًا على قيمة الحقل ulMode. |
| vertex_padding | System.Byte | r/w | يحصل أو يعيّن مصفوفة اختيارية ذات طول متغير من nTri مضروبًا في أربعة بايتات <br/>            يجب أن تكون موجودة إذا أشارت قيمة الحقل ulMode إلى كائنات GradientRectangle <br/>            (القسم 2.2.7). إذا أشارت قيمة الحقل ulMode إلى كائنات GradientTriangle <br/>            (القسم 2.2.8)، لا يوجد VertexPadding. يجب تجاهل هذا الحقل. |


### Constructor: EmfVertexData() {#EmfVertexData__1}


```
 EmfVertexData() 
```

ينشئ نسخة جديدة من الفئة EmfVertexData

