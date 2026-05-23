---
title: "Clase XmpPacketWrapper"
type: docs
weight: 480
url: /es/python-net/aspose.imaging.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPacketWrapper

**Inheritance:** IXmlValue, IImageMetadataFormat

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Inicializa una nueva instancia de la clase [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Inicializa una nueva instancia de la clase [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | r | Obtiene la instrucción de procesamiento del encabezado. |
| meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | r/w | Obtiene los metadatos XMP. Opcional. |
| packages | [XmpPackage[]](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | r | Obtiene la matriz de [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) dentro de XMP. |
| packages_count | int | r | Obtiene la cantidad de paquetes dentro de la estructura XMP. |
| trailer_pi | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | r | Obtiene la instrucción de procesamiento del trailer. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Agrega el paquete. |
| clear_packages() | Elimina todos los [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) dentro de XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Determina si el paquete existe en el contenedor xmp. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Obtiene el paquete por URI del espacio de nombres. |
| [get_xml_value()](#get_xml_value__4) | Convierte el valor XMP a la representación XML. |
| [remove_package(package)](#remove_package_package_5) | Elimina el paquete XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Inicializa una nueva instancia de la clase [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Inicializa una nueva instancia de la clase [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| header | [XmpHeaderPi](/imaging/python-net/aspose.imaging.xmp/xmpheaderpi/) | El encabezado XMP de la instrucción de procesamiento. |
| trailer | [XmpTrailerPi](/imaging/python-net/aspose.imaging.xmp/xmptrailerpi/) | El tráiler XMP de la instrucción de procesamiento. |
| xmp_meta | [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) | Los metadatos XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Agrega el paquete.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | El paquete. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Determina si el paquete existe en el contenedor xmp.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| namespace_uri | string | URI del esquema del paquete. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve true si el paquete con el URI de espacio de nombres especificado existe en el contenedor XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Obtiene el paquete por URI del espacio de nombres.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| namespace_uri | string | El URI del esquema del paquete. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | Devuelve el paquete XMP para el URI de espacio de nombres especificado. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Convierte el valor XMP a la representación XML.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve el valor XMP convertido a XML. |


### Method: remove_package(package) {#remove_package_package_5}


```
 remove_package(package) 
```

Elimina el paquete XMP.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| package | [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/) | El paquete. |

