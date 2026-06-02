---
title: "EmfPlusGraphicsVersion"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusGraphicsVersion nesnesi, bir EMF metafilesi oluşturmak için kullanılan işletim sistemi grafik sürümünü belirtir."
type: docs
weight: 44
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

EmfPlusGraphicsVersion nesnesi, EMF+ metafili oluşturmak için kullanılan işletim sistemi grafik sürümünü belirtir.

Grafik sürümleri satıcı tarafından genişletilebilir; ancak, birlikte çalışabilirliği sağlamak için, bu tür bir uzantı EMF+ metafilelerinin hem istemcilerinde hem de sunucularında uygulanmalıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | MetafileSignature (20 bit) alır: Metafile tipini tanımlayan bir değer. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | MetafileSignature (20 bit) alır: Metafile tipini tanımlayan bir değer. |
| [getGraphicsVersion()](#getGraphicsVersion--) | GraphicsVersion (12 bit) alır: İşletim sistemi grafik sürümü. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | GraphicsVersion (12 bit) alır: İşletim sistemi grafik sürümü. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


MetafileSignature (20 bit) alır: Metafile tipini tanımlayan bir değer. EMF+ metafilesi için değer 0xDBC01'dir.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


MetafileSignature (20 bit) alır: Metafile tipini tanımlayan bir değer. EMF+ metafilesi için değer 0xDBC01'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


GraphicsVersion (12 bit) alır: İşletim sistemi grafik sürümü. Bu değer `EmfPlusGraphicsVersion` sayımında TANIMLANMALIDIR.

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


GraphicsVersion (12 bit) alır: İşletim sistemi grafik sürümü. Bu değer `EmfPlusGraphicsVersion` sayımında TANIMLANMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

