---
title: EmfPlusGraphicsVersion
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusGraphicsVersion object specifies the version of operating system graphics that is used to create an EMF metafile.
type: docs
weight: 44
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

The EmfPlusGraphicsVersion object specifies the version of operating system graphics that is used to create an EMF+ metafile.

Graphics versions are vendor-extensible; however, to ensure inter-operability, any such extension MUST be implemented in both clients and servers of EMF+ metafiles.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | Gets a MetafileSignature (20 bits): A value that identifies the type of metafile. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | Gets a MetafileSignature (20 bits): A value that identifies the type of metafile. |
| [getGraphicsVersion()](#getGraphicsVersion--) | Gets a GraphicsVersion (12 bits): The version of operating system graphics. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | Gets a GraphicsVersion (12 bits): The version of operating system graphics. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


Gets a MetafileSignature (20 bits): A value that identifies the type of metafile. The value for an EMF+ metafile is 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


Gets a MetafileSignature (20 bits): A value that identifies the type of metafile. The value for an EMF+ metafile is 0xDBC01.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


Gets a GraphicsVersion (12 bits): The version of operating system graphics. This value MUST be defined in the `EmfPlusGraphicsVersion` enumeration

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


Gets a GraphicsVersion (12 bits): The version of operating system graphics. This value MUST be defined in the `EmfPlusGraphicsVersion` enumeration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

