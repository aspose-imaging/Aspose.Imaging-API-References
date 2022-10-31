---
title: CdrObjectContainer
second_title: Aspose.Imaging for Java API Reference
description: The cdr object container
type: docs
weight: 28
url: /java/com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject)
```
public abstract class CdrObjectContainer extends CdrObject
```

The cdr object container
## Constructors

| Constructor | Description |
| --- | --- |
| [CdrObjectContainer()](#CdrObjectContainer--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getChilds()](#getChilds--) | Gets the objects. |
| [getLoadToLastChild()](#getLoadToLastChild--) | Gets a value indicating whether [load to last child]. |
| [setLoadToLastChild(boolean value)](#setLoadToLastChild-boolean-) | Sets a value indicating whether [load to last child]. |
| [getLastChild()](#getLastChild--) | Gets the last child. |
| [setLastChild(CdrObjectContainer value)](#setLastChild-com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer-) | Sets the last child. |
| [getHidden()](#getHidden--) | Gets a value indicating whether this [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) is visible. |
| [setHidden(boolean value)](#setHidden-boolean-) | Sets a value indicating whether this [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) is visible. |
| [addChildObject(CdrObject cdrObject)](#addChildObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-) | Adds the child object. |
| [insertObject(CdrObject cdrObject)](#insertObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-) | Inserts the object |
### CdrObjectContainer() {#CdrObjectContainer--}
```
public CdrObjectContainer()
```


### getChilds() {#getChilds--}
```
public final List<CdrObject> getChilds()
```


Gets the objects.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.cdr.objects.CdrObject> - the objects.
### getLoadToLastChild() {#getLoadToLastChild--}
```
public final boolean getLoadToLastChild()
```


Gets a value indicating whether [load to last child].

**Returns:**
boolean - a value indicating whether [load to last child].
### setLoadToLastChild(boolean value) {#setLoadToLastChild-boolean-}
```
public final void setLoadToLastChild(boolean value)
```


Sets a value indicating whether [load to last child].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether [load to last child]. |

### getLastChild() {#getLastChild--}
```
public final CdrObjectContainer getLastChild()
```


Gets the last child.

**Returns:**
[CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) - the last child.
### setLastChild(CdrObjectContainer value) {#setLastChild-com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer-}
```
public final void setLastChild(CdrObjectContainer value)
```


Sets the last child.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) | the last child. |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Gets a value indicating whether this [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) is visible.

Value: `true` if visible; otherwise, `false`.

**Returns:**
boolean - a value indicating whether this [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) is visible.
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Sets a value indicating whether this [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) is visible.

Value: `true` if visible; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether this [CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer) is visible. |

### addChildObject(CdrObject cdrObject) {#addChildObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-}
```
public final void addChildObject(CdrObject cdrObject)
```


Adds the child object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cdrObject | [CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject) | The CDR object. |

### insertObject(CdrObject cdrObject) {#insertObject-com.aspose.imaging.fileformats.cdr.objects.CdrObject-}
```
public final void insertObject(CdrObject cdrObject)
```


Inserts the object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cdrObject | [CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject) | The CDR object. |

