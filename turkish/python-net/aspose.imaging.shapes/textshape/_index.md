---
title: "TextShape Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TextShape()](#TextShape__1) | [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) sınıfının yeni bir örneğini başlatır. |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Nesnenin sınırlarını alır. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Şeklin merkezini alır. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | Metni çizerken kullanılan yazı tipini alır veya ayarlar. |
| has_segments | bool | r | Şeklin segmentlere sahip olup olmadığını gösteren bir değer alır. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sol alt dikdörtgen noktasını alır. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sol üst dikdörtgen noktasını alır. |
| rectangle_height | float | r | Dikdörtgen yüksekliğini alır. |
| rectangle_width | float | r | Dikdörtgen genişliğini alır. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sağ alt dikdörtgen noktasını alır. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Sağ üst dikdörtgen noktasını alır. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Şeklin segmentlerini alır. |
| text | string | r/w | Çizilen metni alır veya ayarlar. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | Metin biçimini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Nesnenin sınırlarını alır. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Nesnenin sınırlarını alır. |
| [transform(transform)](#transform_transform_3) | Belirtilen dönüşümü şekle uygular. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

[TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) sınıfının yeni bir örneğini başlatır.

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

[TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| text | string | Çizilecek metin. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Metin dikdörtgeni. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | Kullanılacak yazı tipi. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Dize biçimi. |

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

