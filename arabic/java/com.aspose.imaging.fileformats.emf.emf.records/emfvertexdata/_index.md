---
title: "EmfVertexData"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الكائنات التي تحدد رؤوس إما المستطيلات أو المثلثات والألوان المقابلة لها."
type: docs
weight: 155
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

الكائنات التي تحدد رؤوس إما المستطيلات أو المثلثات والألوان المقابلة لها.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | يحصل أو يعيّن مصفوفة من كائنات nVer TriVertex (القسم 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | يحصل أو يعيّن مصفوفة من كائنات nVer TriVertex (القسم 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | يحصل أو يعيّن مصفوفة من كائنات nTri GradientRectangle (القسم 2.2.7) أو كائنات GradientTriangle (القسم 2.2.8)، اعتمادًا على قيمة الحقل ulMode. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | يحصل أو يعيّن مصفوفة من كائنات nTri GradientRectangle (القسم 2.2.7) أو كائنات GradientTriangle (القسم 2.2.8)، اعتمادًا على قيمة الحقل ulMode. |
| [getVertexPadding()](#getVertexPadding--) | يحصل أو يعيّن مصفوفة اختيارية ذات طول متغيّر من nTri مضروبًا في أربعة بايتات يجب أن تكون موجودة إذا كانت قيمة الحقل ulMode تشير إلى كائنات GradientRectangle (القسم 2.2.7). |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | يحصل أو يعيّن مصفوفة اختيارية ذات طول متغيّر من nTri مضروبًا في أربعة بايتات يجب أن تكون موجودة إذا كانت قيمة الحقل ulMode تشير إلى كائنات GradientRectangle (القسم 2.2.7). |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


يحصل أو يعيّن مصفوفة من كائنات nVer TriVertex (القسم 2.2.26). كل كائن يحدد موضع ولون رأس إما لمستطيل أو مثلث، اعتمادًا على قيمة الحقل ulMode.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


يحصل أو يعيّن مصفوفة من كائنات nVer TriVertex (القسم 2.2.26). كل كائن يحدد موضع ولون رأس إما لمستطيل أو مثلث، اعتمادًا على قيمة الحقل ulMode.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


يحصل أو يعيّن مصفوفة من كائنات nTri GradientRectangle (القسم 2.2.7) أو كائنات GradientTriangle (القسم 2.2.8)، اعتمادًا على قيمة الحقل ulMode. كل كائن يحدد فهارس في مصفوفة كائنات TriVertex في الحقل VertexObjects.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


يحصل أو يعيّن مصفوفة من كائنات nTri GradientRectangle (القسم 2.2.7) أو كائنات GradientTriangle (القسم 2.2.8)، اعتمادًا على قيمة الحقل ulMode. كل كائن يحدد فهارس في مصفوفة كائنات TriVertex في الحقل VertexObjects.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


يحصل أو يعيّن مصفوفة اختيارية ذات طول متغيّر من nTri مضروبًا في أربعة بايتات يجب أن تكون موجودة إذا كانت قيمة الحقل ulMode تشير إلى كائنات GradientRectangle (القسم 2.2.7). إذا كانت قيمة الحقل ulMode تشير إلى كائنات GradientTriangle (القسم 2.2.8)، لا يوجد VertexPadding. يجب تجاهل هذا الحقل.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


يحصل أو يعيّن مصفوفة اختيارية ذات طول متغيّر من nTri مضروبًا في أربعة بايتات يجب أن تكون موجودة إذا كانت قيمة الحقل ulMode تشير إلى كائنات GradientRectangle (القسم 2.2.7). إذا كانت قيمة الحقل ulMode تشير إلى كائنات GradientTriangle (القسم 2.2.8)، لا يوجد VertexPadding. يجب تجاهل هذا الحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] |  |

