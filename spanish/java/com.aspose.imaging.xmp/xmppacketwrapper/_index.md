---
title: "XmpPacketWrapper"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Contiene el paquete XMP serializado, incluyendo encabezado y pie."
type: docs
weight: 21
url: /es/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Contiene el paquete XMP serializado, incluyendo encabezado y pie.

Un contenedor que consiste en un par de instrucciones de procesamiento XML (PIs) puede colocarse alrededor del elemento rdf:RDF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | Inicializa una nueva instancia de la clase `XmpPacketWrapper`. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Inicializa una nueva instancia de la clase `XmpPacketWrapper`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Obtiene la instrucción de procesamiento del encabezado. |
| [getMeta()](#getMeta--) | Obtiene los metadatos XMP. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | Establece los metadatos XMP. |
| [getTrailerPi()](#getTrailerPi--) | Obtiene la instrucción de procesamiento del tráiler. |
| [getPackages()](#getPackages--) | Obtiene la matriz de `XmpPackage` dentro de XMP. |
| [getPackagesCount()](#getPackagesCount--) | Obtiene la cantidad de paquetes dentro de la estructura XMP. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Agrega el paquete. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Obtiene el paquete por URI del espacio de nombres. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Determina si el paquete existe en el contenedor XMP. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | Elimina el paquete XMP. |
| [clearPackages()](#clearPackages--) | Elimina todos los `XmpPackage` dentro de XMP. |
| [getXmlValue()](#getXmlValue--) | Convierte el valor XMP a la representación XML. |
| [toString()](#toString--) | Devuelve una cadena XML que representa el objeto actual. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Inicializa una nueva instancia de la clase `XmpPacketWrapper`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | El encabezado XMP de la instrucción de procesamiento. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | El trailer XMP de la instrucción de procesamiento. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Los metadatos XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Inicializa una nueva instancia de la clase `XmpPacketWrapper`.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Obtiene la instrucción de procesamiento del encabezado.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Obtiene los metadatos XMP. Opcional.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Establece los metadatos XMP. Opcional.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Los metadatos XMP. Opcional. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Obtiene la instrucción de procesamiento del tráiler.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Obtiene la matriz de `XmpPackage` dentro de XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - La matriz de `XmpPackage` dentro de XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Obtiene la cantidad de paquetes dentro de la estructura XMP.

**Returns:**
int - La cantidad de paquetes dentro de la estructura XMP.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Agrega el paquete.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | El paquete. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Obtiene el paquete por URI del espacio de nombres.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceUri | java.lang.String | El URI del esquema del paquete. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Determina si el paquete existe en el contenedor XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI del esquema del paquete. |

**Returns:**
boolean - Devuelve true si el paquete con el URI de espacio de nombres especificado existe en el contenedor XMP.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Elimina el paquete XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | El paquete. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Elimina todos los `XmpPackage` dentro de XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convierte el valor XMP a la representación XML.

**Returns:**
java.lang.String - Devuelve el valor XMP convertido a XML.
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena XML que representa el objeto actual.

**Returns:**
java.lang.String - Una cadena XML que representa el objeto actual.
