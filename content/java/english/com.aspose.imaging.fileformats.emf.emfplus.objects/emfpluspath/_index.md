---
title: EmfPlusPath
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPath object specifies a series of line and curve segments that form a graphics path.
type: docs
weight: 58
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusPath extends EmfPlusGraphicsObjectType
```

The EmfPlusPath object specifies a series of line and curve segments that form a graphics path. The order for Bezier data points is the start point, control point 1, control point 2, and end point.For more information see[MSDN - DrawBeziers].
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPath()](#EmfPlusPath--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPathPointFlags()](#getPathPointFlags--) | Gets or sets Path points count A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object |
| [setPathPointFlags(short value)](#setPathPointFlags-short-) | Gets or sets Path points count A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object |
| [getPathPoints()](#getPathPoints--) | Gets or sets array of path points An array of PathPointCount points that specify the path. |
| [setPathPoints(PointF[] value)](#setPathPoints-com.aspose.imaging.PointF---) | Gets or sets array of path points An array of PathPointCount points that specify the path. |
| [getPathPointTypes()](#getPathPointTypes--) | Gets or sets an array that specifies how the points in the PathPoints field are used to draw the path. |
| [setPathPointTypes(EmfPlusBasePointType[] value)](#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---) | Gets or sets an array that specifies how the points in the PathPoints field are used to draw the path. |
### EmfPlusPath() {#EmfPlusPath--}
```
public EmfPlusPath()
```


### getPathPointFlags() {#getPathPointFlags--}
```
public short getPathPointFlags()
```


Gets or sets Path points count A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object

**Returns:**
short
### setPathPointFlags(short value) {#setPathPointFlags-short-}
```
public void setPathPointFlags(short value)
```


Gets or sets Path points count A 32-bit unsigned integer that specifies how to interpret the points and associated point types that are defined by this object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Gets or sets array of path points An array of PathPointCount points that specify the path. The type of objects in this array are specified by the PathPointFlags field, as follows: If the P flag is set, the points are relative locations that are specified by EmfPlusPointR objects (section 2.2.2.37). If the P flag is clear and the C flag is set, the points are absolute locations that are specified by EmfPlusPoint objects (section 2.2.2.35). If the P flag is clear and the C flag is clear, the points are absolute locations that are specified by EmfPlusPointF objects (section 2.2.2.36).

**Returns:**
com.aspose.imaging.PointF[]
### setPathPoints(PointF[] value) {#setPathPoints-com.aspose.imaging.PointF---}
```
public void setPathPoints(PointF[] value)
```


Gets or sets array of path points An array of PathPointCount points that specify the path. The type of objects in this array are specified by the PathPointFlags field, as follows: If the P flag is set, the points are relative locations that are specified by EmfPlusPointR objects (section 2.2.2.37). If the P flag is clear and the C flag is set, the points are absolute locations that are specified by EmfPlusPoint objects (section 2.2.2.35). If the P flag is clear and the C flag is clear, the points are absolute locations that are specified by EmfPlusPointF objects (section 2.2.2.36).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getPathPointTypes() {#getPathPointTypes--}
```
public EmfPlusBasePointType[] getPathPointTypes()
```


Gets or sets an array that specifies how the points in the PathPoints field are used to draw the path. The type of objects in this array is specified by the R flag in the PathPointFlags field

Value: The path point types.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType[]
### setPathPointTypes(EmfPlusBasePointType[] value) {#setPathPointTypes-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType---}
```
public void setPathPointTypes(EmfPlusBasePointType[] value)
```


Gets or sets an array that specifies how the points in the PathPoints field are used to draw the path. The type of objects in this array is specified by the R flag in the PathPointFlags field

Value: The path point types.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBasePointType\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype) |  |

