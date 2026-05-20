---
title: "XmpMeta"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente les métadonnées XMP."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Représente les métadonnées xmp. Facultatif. Le but de cet élément est d'identifier les métadonnées XMP dans un texte XML général qui pourrait contenir d'autres utilisations non XMP de RDF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initialise une nouvelle instance de la classe `XmpMeta`. |
| [XmpMeta()](#XmpMeta--) | Initialise une nouvelle instance de la classe `XmpMeta`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Obtient ou définit la version de la boîte à outils Adobe Xmp. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Obtient ou définit la version de la boîte à outils Adobe Xmp. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Ajoute l'attribut. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [equals(Object other)](#equals-java.lang.Object-) | Détermine si le `System.Object` spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initialise une nouvelle instance de la classe `XmpMeta`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Version de la boîte à outils Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initialise une nouvelle instance de la classe `XmpMeta`.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Obtient ou définit la version de la boîte à outils Adobe Xmp.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Obtient ou définit la version de la boîte à outils Adobe Xmp.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Ajoute l'attribut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| attribut | java.lang.String | L'attribut. |
| valeur | java.lang.String | La valeur. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en représentation XML.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | Un objet à comparer avec cet objet. |

**Returns:**
boolean - vrai si l'objet actuel est égal au paramètre `other` ; sinon, faux.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Détermine si le `System.Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autre | java.lang.Object | Le `System.Object` à comparer avec cette instance. |

**Returns:**
boolean - `true` si le `System.Object` spécifié est égal à cette instance; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
