---
title: "الفئة EmfVertexData"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfVertexData. الكائنات التي تحدد رؤوس إما المستطيلات أو المثلثات والألوان المقابلة لها"
type: docs
weight: 4770
url: /ar/net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
## EmfVertexData class

الكائنات التي تحدد رؤوس المستطيلات أو المثلثات والألوان المقابلة لها.

```csharp
public sealed class EmfVertexData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfVertexData](emfvertexdata/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [VertexIndexes](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexindexes/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات nTri GradientRectangle (القسم 2.2.7) أو كائنات GradientTriangle (القسم 2.2.8)، اعتمادًا على قيمة الحقل ulMode. كل كائن يحدد فهارس في مصفوفة كائنات TriVertex في حقل VertexObjects. |
| [VertexObjects](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexobjects/) { get; set; } | يحصل أو يعيّن مصفوفة من كائنات nVer TriVertex (القسم 2.2.26). كل كائن يحدد موضع ولون رأس إما لمستطيل أو لمثلث، اعتمادًا على قيمة الحقل ulMode. |
| [VertexPadding](../../aspose.imaging.fileformats.emf.emf.records/emfvertexdata/vertexpadding/) { get; set; } | يحصل أو يعيّن مصفوفة اختيارية ذات طول متغير من nTri مضروبًا في أربعة بايتات يجب أن تكون موجودة إذا أشارت قيمة الحقل ulMode إلى كائنات GradientRectangle (القسم 2.2.7). إذا أشارت قيمة الحقل ulMode إلى كائنات GradientTriangle (القسم 2.2.8)، لا يكون هناك VertexPadding. يجب تجاهل هذا الحقل. |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


