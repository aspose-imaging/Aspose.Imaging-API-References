---
title: "EmfPlusGraphicsVersion"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusGraphicsVersion especifica la versión de los gráficos del sistema operativo que se utiliza para crear un metafichero EMF."
type: docs
weight: 44
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusGraphicsVersion extends EmfPlusStructureObjectType
```

El objeto EmfPlusGraphicsVersion especifica la versión de los gráficos del sistema operativo que se utiliza para crear un metafichero EMF+.

Las versiones de gráficos son extensibles por el proveedor; sin embargo, para garantizar la interoperabilidad, cualquier extensión de este tipo DEBE implementarse tanto en los clientes como en los servidores de los metaficheros EMF+.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusGraphicsVersion()](#EmfPlusGraphicsVersion--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMetafileSignature()](#getMetafileSignature--) | Obtiene una MetafileSignature (20 bits): un valor que identifica el tipo de metafichero. |
| [setMetafileSignature(int value)](#setMetafileSignature-int-) | Obtiene una MetafileSignature (20 bits): un valor que identifica el tipo de metafichero. |
| [getGraphicsVersion()](#getGraphicsVersion--) | Obtiene una GraphicsVersion (12 bits): la versión de los gráficos del sistema operativo. |
| [setGraphicsVersion(int value)](#setGraphicsVersion-int-) | Obtiene una GraphicsVersion (12 bits): la versión de los gráficos del sistema operativo. |
### EmfPlusGraphicsVersion() {#EmfPlusGraphicsVersion--}
```
public EmfPlusGraphicsVersion()
```


### getMetafileSignature() {#getMetafileSignature--}
```
public int getMetafileSignature()
```


Obtiene una MetafileSignature (20 bits): un valor que identifica el tipo de metafichero. El valor para un metafichero EMF+ es 0xDBC01.

**Returns:**
int
### setMetafileSignature(int value) {#setMetafileSignature-int-}
```
public void setMetafileSignature(int value)
```


Obtiene una MetafileSignature (20 bits): un valor que identifica el tipo de metafichero. El valor para un metafichero EMF+ es 0xDBC01.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGraphicsVersion() {#getGraphicsVersion--}
```
public int getGraphicsVersion()
```


Obtiene una GraphicsVersion (12 bits): la versión de los gráficos del sistema operativo. Este valor DEBE estar definido en la enumeración `EmfPlusGraphicsVersion`

**Returns:**
int
### setGraphicsVersion(int value) {#setGraphicsVersion-int-}
```
public void setGraphicsVersion(int value)
```


Obtiene una GraphicsVersion (12 bits): la versión de los gráficos del sistema operativo. Este valor DEBE estar definido en la enumeración `EmfPlusGraphicsVersion`

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

