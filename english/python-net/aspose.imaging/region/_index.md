---
title: Region Class
type: docs
weight: 750
url: /python-net/api-reference/aspose.imaging/region/
---

Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Class Name:** aspose.imaging.Region

**Assembly:**  Aspose.Imaging Version: 23.3.0

The Region type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Region()|Initializes a new [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|Region(rect)|Initializes a new instance of the Region class|
|Region(rect)|Initializes a new instance of the Region class|
|Region(path)|Initializes a new instance of the Region class|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|intersect(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|intersect(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|intersect(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|intersect(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|union(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|union(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|union(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|union(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|xor(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|xor(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|xor(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|xor(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|exclude(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|exclude(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|exclude(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|exclude(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|complement(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|complement(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|complement(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|complement(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|translate(dx, dy)|Offsets the coordinates of this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) by the specified amount.|
|translate(dx, dy)|Offsets the coordinates of this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) by the specified amount.|
|is_visible(x, y)|Tests whether the specified point is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible(point)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible(x, y, g)|Tests whether the specified point is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible(point, g)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible(x, y, width, height)|Tests whether the specified point is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible(rect)|Tests whether any portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible(x, y, width, height, g)|Tests whether the specified point is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible(rect, g)|Tests whether any portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible(x, y, g)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible(point)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible(point, g)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible(x, y, width, height)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible(rect)|Tests whether any portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible(x, y, width, height, g)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible(rect, g)|Tests whether any portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|create_with_rect_f(rect)|Initializes a new [Region](/imaging/python-net/api-reference/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|create_with_rect(rect)|Initializes a new [Region](/imaging/python-net/api-reference/aspose.imaging/region/) from the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|create_with_path(path)|Initializes a new [Region](/imaging/python-net/api-reference/aspose.imaging/region/) with the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|deep_clone()|Creates an exact deep copy of this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|make_infinite()|Initializes this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) object to an infinite interior.|
|make_empty()|Initializes this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to an empty interior.|
|intersect_rect_f(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|intersect_rect(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|intersect_path(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|intersect_rgn(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the intersection of itself with the specified [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|union_rect_f(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|union_rect(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|union_path(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|union_rgn(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union of itself and the specified [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|xor_rect_f(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|xor_rect(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|xor_path(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|xor_rgn(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to the union minus the intersection of itself with the specified [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|exclude_rect_f(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|exclude_rect(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure.|
|exclude_path(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/).|
|exclude_rgn(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain only the portion of its interior that does not intersect with the specified [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|complement_rect_f(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|complement_rect(rect)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|complement_path(path)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [GraphicsPath](/imaging/python-net/api-reference/aspose.imaging/graphicspath/) that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|complement_rgn(region)|Updates this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) to contain the portion of the specified [Region](/imaging/python-net/api-reference/aspose.imaging/region/) that does not intersect with this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|translate_f(dx, dy)|Offsets the coordinates of this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) by the specified amount.|
|transform(matrix)|Transforms this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) by the specified [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/).|
|is_empty(g)|Tests whether this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) has an empty interior on the specified drawing surface.|
|is_infinite(g)|Tests whether this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) has an infinite interior on the specified drawing surface.|
|is_visible_f(x, y)|Tests whether the specified point is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible_point_f(point)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible_with_graphics_f(x, y, g)|Tests whether the specified point is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible_point_f_with_graphics(point, g)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible_xywhf(x, y, width, height)|Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible_rect_f(rect)|Tests whether any portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible_xywh_graphics_f(x, y, width, height, g)|Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible_rect_f_with_graphics(rect, g)|Tests whether any portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible_with_graphics(x, y, g)|Tests whether the specified point is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) object when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/) object.|
|is_visible_point(point)|Tests whether the specified [PointF](/imaging/python-net/api-reference/aspose.imaging/pointf/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible_point_with_graphics(point, g)|Tests whether the specified [Point](/imaging/python-net/api-reference/aspose.imaging/point/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible_xywh(x, y, width, height)|Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible_rect(rect)|Tests whether any portion of the specified [RectangleF](/imaging/python-net/api-reference/aspose.imaging/rectanglef/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/).|
|is_visible_xywh_graphics(x, y, width, height, g)|Tests whether any portion of the specified rectangle is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
|is_visible_rect_with_graphics(rect, g)|Tests whether any portion of the specified [Rectangle](/imaging/python-net/api-reference/aspose.imaging/rectangle/) structure is contained within this [Region](/imaging/python-net/api-reference/aspose.imaging/region/) when drawn using the specified [Graphics](/imaging/python-net/api-reference/aspose.imaging/graphics/).|
