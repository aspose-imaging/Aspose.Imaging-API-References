---
title: "Classe XmpPackage"
type: docs
weight: 460
url: /fr/python-net/aspose.imaging.xmp/xmppackage/
---

**Summary:** Represents base abstraction for XMP package.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackage

**Inheritance:** IXmlValue

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Obtient le nombre de clés XMP. |
| namespace_uri | string | r | Obtient l'URI de l'espace de noms. |
| prefix | string | r | Obtient le préfixe. |
| xml_namespace | string | r | Obtient l'espace de noms XML. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Ajoute la valeur à la clé spécifiée. |
| [add_value(key, value)](#add_value_key_value_2) | Ajoute la valeur à la clé spécifiée. |
| clear() | Efface cette instance. |
| [contains_key(key)](#contains_key_key_3) | Détermine si cette collection possède la clé spécifiée. |
| [get_prop_value(key)](#get_prop_value_key_4) | Obtient l'objet avec la clé spécifiée. |
| [get_xml_value()](#get_xml_value__5) | Convertit la valeur XMP en représentation XML. |
| [remove(key)](#remove_key_6) | Supprime la valeur avec la clé spécifiée. |
| [set_prop_value(key, value)](#set_prop_value_key_value_7) | Obtient ou définit l'objet avec la clé spécifiée. |
| [set_value(key, value)](#set_value_key_value_8) | Définit la valeur. |
| [set_value(key, value)](#set_value_key_value_9) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Définit la valeur du type XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_11) | Obtient la valeur par la _key_. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Ajoute la valeur à la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | string | La valeur à ajouter à. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Ajoute la valeur à la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | System.Object | La valeur à ajouter à. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Détermine si cette collection possède la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé à vérifier. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** si le  contient la clé spécifiée ; sinon, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Obtient l'objet avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé qui identifie la valeur. |

**Returns**

| Type | Description |
| :- | :- |
| System.Object | Renvoie l'objet avec la clé spécifiée. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Convertit la valeur XMP en représentation XML.

**Returns**

| Type | Description |
| :- | :- |
| string | Renvoie la valeur XMP convertie en représentation XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Supprime la valeur avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé identifiée avec la valeur supprimée. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie true si la valeur avec la clé spécifiée a été supprimée. |


### Method: set_prop_value(key, value) {#set_prop_value_key_value_7}


```
 set_prop_value(key, value) 
```

Obtient ou définit l'objet avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé qui identifie la valeur. |
| value | System.Object | L'objet avec la clé spécifiée. |

### Method: set_value(key, value) {#set_value_key_value_8}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | La valeur à ajouter à. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | La valeur à définir à. |

### Method: try_get_value(key, value) {#try_get_value_key_value_11}


```
 try_get_value(key, value) 
```

Obtient la valeur par la _key_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé de l'élément XMP. |
| value | System.Object | La valeur XMP. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True**, si le  contient la _key_; sinon, **False**. |


