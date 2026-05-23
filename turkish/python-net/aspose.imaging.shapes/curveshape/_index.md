---
title: "CurveShape Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. |
| [CurveShape(points)](#CurveShape_points_2) | [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Nesnenin sınırlarını alır. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin merkezini alır. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin son noktasını alır. |
| has_segments | bool | r | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| is_closed | bool | r/w | Şeklin kapalı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Eğri noktalarını alır veya ayarlar. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Şeklin segmentlerini alır. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin başlangıç noktasını alır. |
| gerilim | float | r/w | Eğri gerilimini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Nesnenin sınırlarını alır. |
| reverse() | Bu şekil için nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_5) | Belirtilen dönüşümü şekle uygular. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

[CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır.

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

[CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

[CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa eğri kapalıdır. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

[CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |
| gerilim | float | Eğri gerilimi. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

[CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |
| gerilim | float | Eğri gerilimi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa eğri kapalıdır. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

[CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır. Varsayılan 0.5 gerilim kullanılır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa eğri kapalıdır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

[CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |
| gerilim | float | Eğri gerilimi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Sınırlar hesaplanmadan önce uygulanacak matris. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Tahmini nesne sınırları. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Nesnenin sınırlarını alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Sınırlar hesaplanmadan önce uygulanacak matris. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Nesne için kullanılacak kalem. Bu, nesnenin sınır boyutunu etkileyebilir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Tahmini nesne sınırları. |


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Belirtilen dönüşümü şekle uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Uygulanacak dönüşüm. |

