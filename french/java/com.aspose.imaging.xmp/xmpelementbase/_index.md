---
title: "XmpElementBase"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'élément XMP de base contenant des attributs."
type: docs
weight: 16
url: /fr/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Représente l'élément XMP de base contenant des attributs.
## Méthodes

| Méthode | Description |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Ajoute l'attribut. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Obtient l'attribut. |
| [clearAttributes()](#clearAttributes--) | Supprime tous les attributs. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | Indique si l'objet actuel est égal à un autre objet du même type. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'`Object` spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
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

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Obtient l'attribut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| attribut | java.lang.String | L'attribut. |

**Returns:**
java.lang.String - Retourne l'attribut pour le nom d'attribut spécifié.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Supprime tous les attributs.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indique si l'objet actuel est égal à un autre objet du même type.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | Un objet à comparer avec cet objet. |

**Returns:**
boolean - vrai si l'objet actuel est égal au paramètre `other` ; sinon, faux.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'`Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'`Object` à comparer avec cette instance. |

**Returns:**
booléen - `true` si l'`Object` spécifié est égal à cette instance ; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
