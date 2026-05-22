---
title: "Classe XmpBasicPackage"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initialise une nouvelle instance de la classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initialise une nouvelle instance de la classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Valeur maximale de la note. |
| RATING_MIN [static] | int | r | Valeur minimale de la note. |
| RATING_REJECTED [static] | int | r | Valeur de note rejetée. |
| count | int | r | Obtient le nombre de clés XMP. |
| namespace_uri | string | r | Obtient l'URI de l'espace de noms. |
| prefix | string | r | Obtient le préfixe. |
| xml_namespace | string | r | Obtient l'espace de noms XML. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Ajoute une propriété de chaîne. |
| [add_value(key, value)](#add_value_key_value_2) | Ajoute une propriété de chaîne. |
| clear() | Efface cette instance. |
| [contains_key(key)](#contains_key_key_3) | Détermine si cette collection possède la clé spécifiée. |
| [get_prop_value(key)](#get_prop_value_key_4) | Obtient l'objet avec la clé spécifiée. |
| [get_xml_value()](#get_xml_value__5) | Convertit la valeur XMP en représentation XML. |
| [remove(key)](#remove_key_6) | Supprime la valeur avec la clé spécifiée. |
| [set_created_date(created_date)](#set_created_date_created_date_7) | Ajoute la date de création de la ressource. |
| [set_created_date(created_date)](#set_created_date_created_date_8) | Ajoute la date de création de la ressource. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | Ajoute la date de création de la ressource. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | Définit l'outil du créateur. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | Définit l'identifiant. |
| [set_label(label)](#set_label_label_12) | Définit l'étiquette. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Ajoute la date de dernière modification des métadonnées. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | Ajoute la date de dernière modification des métadonnées. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | Ajoute la date de dernière modification des métadonnées. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Ajoute la date de dernière modification de la ressource. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | Ajoute la date de dernière modification de la ressource. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | Ajoute la date de dernière modification de la ressource. |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | Obtient ou définit l'objet avec la clé spécifiée. |
| [set_rating(choise)](#set_rating_choise_20) | Définit la note. |
| [set_value(key, value)](#set_value_key_value_21) | Définit la valeur. |
| [set_value(key, value)](#set_value_key_value_22) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | Définit la valeur du type XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_24) | Obtient la valeur par la _key_. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initialise une nouvelle instance de la classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initialise une nouvelle instance de la classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| prefix | string | Le préfixe. |
| namespace_uri | string | L'URI de l'espace de noms. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Ajoute une propriété de chaîne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | string | La valeur de chaîne. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Ajoute une propriété de chaîne.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | System.Object | La valeur de chaîne. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Ajoute la date de création de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| created_date | System.DateTime | Date de création. |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

Ajoute la date de création de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| created_date | string | Date de création. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

Ajoute la date de création de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| created_date | string | Date de création. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

Définit l'outil du créateur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| creator_tool | string | Nom de l'outil. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

Définit l'identifiant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| identifiant | string[] | L'identifiant. |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

Définit l'étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| étiquette | string | L'étiquette. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Ajoute la date de dernière modification des métadonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata_date | System.DateTime | Date des métadonnées. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

Ajoute la date de dernière modification des métadonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata_date | string | Date des métadonnées. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

Ajoute la date de dernière modification des métadonnées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata_date | string | Date des métadonnées. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Ajoute la date de dernière modification de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| modified_date | System.DateTime | Date de dernière modification. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

Ajoute la date de dernière modification de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| modified_date | string | Date de dernière modification. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

Ajoute la date de dernière modification de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| modified_date | string | Date de dernière modification. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

Obtient ou définit l'objet avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé qui identifie la valeur. |
| value | System.Object | L'objet avec la clé spécifiée. |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

Définit la note.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| choix | int | De -1 à 5 |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | La valeur à ajouter à. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | La valeur à définir à. |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


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


