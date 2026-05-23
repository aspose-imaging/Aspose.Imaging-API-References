---
title: "BezierShape Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Yeni bir [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) sınıfı örneği başlatır. |
| [BezierShape(points)](#BezierShape_points_2) | Yeni bir [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) sınıfı örneği başlatır. |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Yeni bir [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) sınıfı örneği başlatır. |
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
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| reverse() | Bu şekil için nokta sırasını tersine çevirir. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Yeni bir [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) sınıfı örneği başlatır.

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Yeni bir [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Yeni bir [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Nokta dizisi. |
| is_closed | bool | Eğer <c>true</c> olarak ayarlanırsa bezier spline kapatılır. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Belirtilen dönüşümü şekle uygular.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Uygulanacak dönüşüm. |

