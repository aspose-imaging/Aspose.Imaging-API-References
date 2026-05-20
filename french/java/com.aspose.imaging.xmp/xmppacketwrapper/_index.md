---
title: "XmpPacketWrapper"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Contient le paquet XMP sérialisé incluant l'en-tête et le pied de page."
type: docs
weight: 21
url: /fr/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

Contient le paquet XMP sérialisé incluant l'en-tête et le pied de page.

Un wrapper composé d'une paire d'instructions de traitement XML (PI) peut être placé autour de l'élément rdf:RDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | Initialise une nouvelle instance de la classe `XmpPacketWrapper`. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initialise une nouvelle instance de la classe `XmpPacketWrapper`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | Obtient l'instruction de traitement d'en-tête. |
| [getMeta()](#getMeta--) | Obtient les métadonnées XMP. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | Définit les métadonnées XMP. |
| [getTrailerPi()](#getTrailerPi--) | Obtient l'instruction de traitement du trailer. |
| [getPackages()](#getPackages--) | Obtient le tableau de `XmpPackage` à l'intérieur du XMP. |
| [getPackagesCount()](#getPackagesCount--) | Obtient le nombre de packages à l'intérieur de la structure XMP. |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | Ajoute le paquet. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Obtient le paquet par URI d'espace de noms. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Détermine si le paquet existe dans l'enveloppe XMP. |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | Supprime le paquet XMP. |
| [clearPackages()](#clearPackages--) | Supprime tous les `XmpPackage` à l'intérieur de XMP. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [toString()](#toString--) | Renvoie une chaîne XML qui représente l'objet actuel. |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initialise une nouvelle instance de la classe `XmpPacketWrapper`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | L'en-tête XMP de l'instruction de traitement. |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Le pied de page XMP de l'instruction de traitement. |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Les métadonnées XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initialise une nouvelle instance de la classe `XmpPacketWrapper`.

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Obtient l'instruction de traitement d'en-tête.

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Obtient les métadonnées XMP. Optionnel.

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Définit les métadonnées XMP. Optionnel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Les métadonnées XMP. Optionnel. |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Obtient l'instruction de traitement du trailer.

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Obtient le tableau de `XmpPackage` à l'intérieur du XMP.

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - Le tableau de `XmpPackage` à l'intérieur de XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Obtient le nombre de packages à l'intérieur de la structure XMP.

**Returns:**
int - Le nombre de paquets dans la structure XMP.
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Ajoute le paquet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Le paquet. |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Obtient le paquet par URI d'espace de noms.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | L'URI du schéma du paquet. |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Détermine si le paquet existe dans l'enveloppe XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI du schéma du paquet. |

**Returns:**
boolean - Renvoie true si le paquet avec l'URI d'espace de noms spécifié existe dans l'enveloppe XMP.
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Supprime le paquet XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | Le paquet. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Supprime tous les `XmpPackage` à l'intérieur de XMP.

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Renvoie la valeur XMP convertie en XML.
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne XML qui représente l'objet actuel.

**Returns:**
java.lang.String - Une chaîne XML qui représente l'objet actuel.
