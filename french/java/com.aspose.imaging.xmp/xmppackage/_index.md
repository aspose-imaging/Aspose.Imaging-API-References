---
title: "XmpPackage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'abstraction de base pour le paquet XMP."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging.xmp/xmppackage/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Représente l'abstraction de base pour le paquet XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe `XmpPackage`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXmlNamespace()](#getXmlNamespace--) | Obtient l'espace de noms XML. |
| [getPrefix()](#getPrefix--) | Obtient le préfixe. |
| [getNamespaceUri()](#getNamespaceUri--) | Obtient l'URI de l'espace de noms. |
| [getKeys()](#getKeys--) | Obtient les clés dans le package XMP. |
| [getCount()](#getCount--) | Obtient le nombre de clés XMP. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Détermine si cette collection possède la clé spécifiée. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Obtient ou définit l'`Object` avec la clé spécifiée. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Définit l'`Object` avec la clé spécifiée. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Ajoute la valeur à la clé spécifiée. |
| [addValue(String key, Object value)](#addValue-java.lang.String-java.lang.Object-) | Ajoute la valeur à la clé spécifiée. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Obtient la valeur par la `key`. |
| [remove(String key)](#remove-java.lang.String-) | Supprime la valeur avec la clé spécifiée. |
| [clear()](#clear--) | Efface cette instance. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-) | Définit la valeur. |
| [setValue(String key, IXmpType value)](#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-) | Définit la valeur. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-) | Définit la valeur du type XMP. |
| [getXmlValue()](#getXmlValue--) | Convertit la valeur XMP en représentation XML. |
| [iterator()](#iterator--) | Retourne un énumérateur qui parcourt la collection. |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


Initialise une nouvelle instance de la classe `XmpPackage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | java.lang.String | Le préfixe. |
| namespaceUri | java.lang.String | L'URI de l'espace de noms. |

### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Obtient l'espace de noms XML.

Valeur : l'espace de noms XML.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Obtient le préfixe.

Valeur : le préfixe.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Obtient l'URI de l'espace de noms.

Valeur : l'URI de l'espace de noms.

**Returns:**
java.lang.String
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Obtient les clés dans le package XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getCount() {#getCount--}
```
public final int getCount()
```


Obtient le nombre de clés XMP.

**Returns:**
int - le nombre de clés XMP.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Détermine si cette collection possède la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé à vérifier. |

**Returns:**
booléen - `true` si la collection contient la clé spécifiée ; sinon, `false`.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Obtient ou définit l'`Object` avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé qui identifie la valeur. |

**Returns:**
java.lang.Object - Retourne l'`Object` avec la clé spécifiée.
### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Définit l'`Object` avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé qui identifie la valeur. |
| valeur | java.lang.Object | La valeur de l'`Object`. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Ajoute la valeur à la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| valeur | java.lang.String | La valeur à ajouter. |

### addValue(String key, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String key, Object value)
```


Ajoute la valeur à la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| valeur | java.lang.Object | La valeur à ajouter. |

### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public final boolean tryGetValue(String key, Object[] value)
```


Obtient la valeur par la `key`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé d'élément XMP. |
| valeur | java.lang.Object[] | La valeur XMP. |

**Returns:**
booléen - `true`, si la collection contient la `key` ; sinon, `false`.
### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Supprime la valeur avec la clé spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur supprimée. |

**Returns:**
booléen - Retourne true si la valeur avec la clé spécifiée a été supprimée.
### clear() {#clear--}
```
public void clear()
```


Efface cette instance.

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.imaging.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Définit la valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| value | [IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue) | La valeur à ajouter. |

### setValue(String key, IXmpType value) {#setValue-java.lang.String-com.aspose.imaging.xmp.types.IXmpType-}
```
public void setValue(String key, IXmpType value)
```


Définit la valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| value | [IXmpType](../../com.aspose.imaging.xmp.types/ixmptype) | La valeur à ajouter. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.imaging.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Définit la valeur du type XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase) | La valeur à définir. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Convertit la valeur XMP en représentation XML.

**Returns:**
java.lang.String - Retourne la valeur XMP convertie en représentation XML.
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Retourne un énumérateur qui parcourt la collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Un `T:System.Collections.Generic.IEnumerator\\\`1` qui peut être utilisé pour parcourir la collection.
