---
title: "XmpPackageBaseCollection"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una colección de XmpPackage."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.xmp/xmppackagebasecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class XmpPackageBaseCollection implements System.Collections.Generic.IGenericEnumerable<XmpPackage>
```

Representa la colección de `XmpPackage`.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmpPackageBaseCollection()](#XmpPackageBaseCollection--) | Inicializa una nueva instancia de la clase `XmpPackageBaseCollection`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene el número de elementos en la colección. |
| [add(XmpPackage package_)](#add-com.aspose.imaging.xmp.XmpPackage-) | Agrega una nueva instancia de `XmpPackage`. |
| [remove(XmpPackage package_)](#remove-com.aspose.imaging.xmp.XmpPackage-) | Elimina el paquete XMP especificado. |
| [getPackages()](#getPackages--) | Obtiene una matriz de `XmpPackage`. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Obtiene `XmpPackage` por su namespaceURI. |
| [clear()](#clear--) | Limpia todos los `XmpPackage` dentro de la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre una colección. |
### XmpPackageBaseCollection() {#XmpPackageBaseCollection--}
```
public XmpPackageBaseCollection()
```


Inicializa una nueva instancia de la clase `XmpPackageBaseCollection`.

### getCount() {#getCount--}
```
public int getCount()
```


Obtiene el número de elementos en la colección.

Valor: El número de elementos en la colección.

**Returns:**
int
### add(XmpPackage package_) {#add-com.aspose.imaging.xmp.XmpPackage-}
```
public void add(XmpPackage package_)
```


Agrega una nueva instancia de `XmpPackage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | El paquete XMP\_ a agregar. |

### remove(XmpPackage package_) {#remove-com.aspose.imaging.xmp.XmpPackage-}
```
public void remove(XmpPackage package_)
```


Elimina el paquete XMP especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | El paquete XMP\_ a eliminar. |

### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Obtiene una matriz de `XmpPackage`.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Devuelve una matriz de paquetes XMP.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Obtiene `XmpPackage` por su namespaceURI.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| namespaceUri | java.lang.String | El namespace URI para obtener el paquete\_. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns XMP package\_ for specified namespace Uri.
### clear() {#clear--}
```
public void clear()
```


Limpia todos los `XmpPackage` dentro de la colección.

### iterator() {#iterator--}
```
public System.Collections.Generic.List.Enumerator<XmpPackage> iterator()
```


Devuelve un enumerador que recorre una colección.

**Returns:**
com.aspose.ms.System.Collections.Generic.List.Enumerator<com.aspose.imaging.xmp.XmpPackage> - Un objeto `System.Collections.IEnumerator` que puede usarse para iterar a través de la colección.
