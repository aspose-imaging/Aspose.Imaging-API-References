---
title: "XmpTrailerPi"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'instruction de traitement du pied de page XMP."
type: docs
weight: 23
url: /fr/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Représente l'instruction de traitement du pied de page XMP.

La partie end=\"w\" ou end=\"r\" doit être utilisée par les processeurs d'analyse de paquets pour déterminer si le XMP peut être modifié sur place.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Initialise une nouvelle instance de la classe `XmpTrailerPi`. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Initialise une nouvelle instance de la classe `XmpTrailerPi`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isWritable()](#isWritable--) | Obtient ou définit une valeur indiquant si cette instance est modifiable. |
| [setWritable(boolean value)](#setWritable-boolean-) | Obtient ou définit une valeur indiquant si cette instance est modifiable. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur xmp en représentation xml. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le `System.Object` spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Initialise une nouvelle instance de la classe `XmpTrailerPi`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isWritable | boolean | Indique si le trailer est modifiable. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Initialise une nouvelle instance de la classe `XmpTrailerPi`.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Obtient ou définit une valeur indiquant si cette instance est modifiable.

Valeur : `true` si cette instance est modifiable ; sinon, `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est modifiable.

Valeur : `true` si cette instance est modifiable ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur xmp en représentation xml.

**Returns:**
java.lang.String - Retourne la représentation XML de XMP.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | Un objet à comparer avec cet objet. |

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
