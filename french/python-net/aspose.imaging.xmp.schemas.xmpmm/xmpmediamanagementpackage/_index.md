---
title: "Classe XmpMediaManagementPackage"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpmm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initialise une nouvelle instance de la classe [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/) |
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
| [add_value(key, value)](#add_value_key_value_1) | Ajoute une propriété de chaîne. |
| [add_value(key, value)](#add_value_key_value_2) | Ajoute une propriété de chaîne. |
| clear() | Efface cette instance. |
| [contains_key(key)](#contains_key_key_3) | Détermine si cette collection possède la clé spécifiée. |
| [get_prop_value(key)](#get_prop_value_key_4) | Obtient l'objet avec la clé spécifiée. |
| [get_xml_value()](#get_xml_value__5) | Convertit la valeur XMP en représentation XML. |
| [remove(key)](#remove_key_6) | Supprime la valeur avec la clé spécifiée. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_7) | Définit le dérivé de. |
| [set_document_id(guid)](#set_document_id_guid_8) | Définit l'identifiant du document. |
| [set_document_id(guid)](#set_document_id_guid_9) | Définit l'identifiant du document. |
| [set_document_id_as_guid(guid)](#set_document_id_as_guid_guid_10) | Définit l'identifiant du document. |
| [set_instance_id(guid)](#set_instance_id_guid_11) | Définit l'ID d'instance. |
| [set_instance_id(guid)](#set_instance_id_guid_12) | Définit l'ID d'instance. |
| [set_instance_id_as_guid(guid)](#set_instance_id_as_guid_guid_13) | Définit l'ID d'instance. |
| [set_original_document_id(guid)](#set_original_document_id_guid_14) | Définit l'ID du document original. |
| [set_original_document_id(guid)](#set_original_document_id_guid_15) | Définit l'ID du document original. |
| [set_original_document_id_as_guid(guid)](#set_original_document_id_as_guid_guid_16) | Définit l'ID du document original. |
| [set_prop_value(key, value)](#set_prop_value_key_value_17) | Obtient ou définit l'objet avec la clé spécifiée. |
| [set_value(key, value)](#set_value_key_value_18) | Définit la valeur. |
| [set_value(key, value)](#set_value_key_value_19) | Définit la valeur. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_20) | Définit la valeur du type XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_21) | Obtient la valeur par la _key_. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initialise une nouvelle instance de la classe [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/)

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_7}


```
 set_derived_from(resource_ref) 
```

Définit le dérivé de.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| resource_ref | [ResourceRef](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceref/resourceref/) | La référence de la ressource. |

### Method: set_document_id(guid) {#set_document_id_guid_8}


```
 set_document_id(guid) 
```

Définit l'identifiant du document.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | System.Guid | L'identifiant unique. |

### Method: set_document_id(guid) {#set_document_id_guid_9}


```
 set_document_id(guid) 
```

Définit l'identifiant du document.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | string | L'identifiant unique. |

### Method: set_document_id_as_guid(guid) {#set_document_id_as_guid_guid_10}


```
 set_document_id_as_guid(guid) 
```

Définit l'identifiant du document.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | System.Guid | L'identifiant unique. |

### Method: set_instance_id(guid) {#set_instance_id_guid_11}


```
 set_instance_id(guid) 
```

Définit l'ID d'instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | System.Guid | L'identifiant unique. |

### Method: set_instance_id(guid) {#set_instance_id_guid_12}


```
 set_instance_id(guid) 
```

Définit l'ID d'instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | string | L'identifiant unique. |

### Method: set_instance_id_as_guid(guid) {#set_instance_id_as_guid_guid_13}


```
 set_instance_id_as_guid(guid) 
```

Définit l'ID d'instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | System.Guid | L'identifiant unique. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_14}


```
 set_original_document_id(guid) 
```

Définit l'ID du document original.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | System.Guid | L'identifiant unique. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_15}


```
 set_original_document_id(guid) 
```

Définit l'ID du document original.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | string | L'identifiant unique. |

### Method: set_original_document_id_as_guid(guid) {#set_original_document_id_as_guid_guid_16}


```
 set_original_document_id_as_guid(guid) 
```

Définit l'ID du document original.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| guid | System.Guid | L'identifiant unique. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_17}


```
 set_prop_value(key, value) 
```

Obtient ou définit l'objet avec la clé spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La clé qui identifie la valeur. |
| value | System.Object | L'objet avec la clé spécifiée. |

### Method: set_value(key, value) {#set_value_key_value_18}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | La valeur à ajouter à. |

### Method: set_value(key, value) {#set_value_key_value_19}


```
 set_value(key, value) 
```

Définit la valeur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé qui est identifiée avec la valeur ajoutée. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | La valeur à ajouter à. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_20}


```
 set_xmp_type_value(key, value) 
```

Définit la valeur du type XMP.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key | string | La représentation sous forme de chaîne de la clé identifiée avec la valeur définie. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | La valeur à définir à. |

### Method: try_get_value(key, value) {#try_get_value_key_value_21}


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


