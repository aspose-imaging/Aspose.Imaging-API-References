---
title: "XmpHeaderPi"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'instruction de traitement de l'en-tête XMP."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Représente l'instruction de traitement de l'en-tête XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initialise une nouvelle instance de la classe `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initialise une nouvelle instance de la classe `XmpHeaderPi`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getGuid()](#getGuid--) | Représente le GUID d'en-tête. |
| [setGuid(String value)](#setGuid-java.lang.String-) | Représente le GUID d'en-tête. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le `System.Object` spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initialise une nouvelle instance de la classe `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initialise une nouvelle instance de la classe `XmpHeaderPi`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| guid | java.lang.String | L'identifiant unique. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


Représente le GUID d'en-tête.

Le texte de l'PI d'en-tête contient un GUID, ce qui rend peu probable qu'il apparaisse accidentellement dans le flux de données.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Représente le GUID d'en-tête.

Le texte de l'PI d'en-tête contient un GUID, ce qui rend peu probable qu'il apparaisse accidentellement dans le flux de données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en représentation XML.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | Un objet à comparer avec cet objet. |

**Returns:**
boolean - vrai si l'objet actuel est égal au paramètre `other` ; sinon, faux.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si le `System.Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le `System.Object` à comparer avec cette instance. |

**Returns:**
boolean - `true` si le `System.Object` spécifié est égal à cette instance; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
