---
title: "Classe XmpBasicPackage"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Inizializza una nuova istanza della classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Inizializza una nuova istanza della classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Valore massimo della valutazione. |
| RATING_MIN [static] | int | r | Valore minimo della valutazione. |
| RATING_REJECTED [static] | int | r | Valore di valutazione rifiutato. |
| count | int | r | Ottiene il conteggio delle chiavi XMP. |
| namespace_uri | string | r | Restituisce l'URI dello spazio dei nomi. |
| prefix | string | r | Restituisce il prefisso. |
| xml_namespace | string | r | Restituisce lo spazio dei nomi XML. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Aggiunge la proprietà stringa. |
| [add_value(key, value)](#add_value_key_value_2) | Aggiunge la proprietà stringa. |
| clear() | Cancella questa istanza. |
| [contains_key(key)](#contains_key_key_3) | Determina se questa collezione contiene la chiave specificata. |
| [get_prop_value(key)](#get_prop_value_key_4) | Restituisce l'oggetto con la chiave specificata. |
| [get_xml_value()](#get_xml_value__5) | Converte il valore XMP nella rappresentazione XML. |
| [remove(key)](#remove_key_6) | Rimuove il valore con la chiave specificata. |
| [set_created_date(created_date)](#set_created_date_created_date_7) | Aggiunge la data di creazione della risorsa. |
| [set_created_date(created_date)](#set_created_date_created_date_8) | Aggiunge la data di creazione della risorsa. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | Aggiunge la data di creazione della risorsa. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | Imposta lo strumento creatore. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | Imposta l'identificatore. |
| [set_label(label)](#set_label_label_12) | Imposta l'etichetta. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Aggiunge la data dell'ultima modifica dei metadati. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | Aggiunge la data dell'ultima modifica dei metadati. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | Aggiunge la data dell'ultima modifica dei metadati. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Aggiunge la data dell'ultima modifica della risorsa. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | Aggiunge la data dell'ultima modifica della risorsa. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | Aggiunge la data dell'ultima modifica della risorsa. |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | Restituisce o imposta l'oggetto con la chiave specificata. |
| [set_rating(choise)](#set_rating_choise_20) | Imposta la valutazione. |
| [set_value(key, value)](#set_value_key_value_21) | Imposta il valore. |
| [set_value(key, value)](#set_value_key_value_22) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | Imposta il valore del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_24) | Restituisce il valore per la _key_. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Inizializza una nuova istanza della classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Inizializza una nuova istanza della classe [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| prefix | string | Il prefisso. |
| namespace_uri | string | L'URI dello spazio dei nomi. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Aggiunge la proprietà stringa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| valore | string | Il valore della stringa. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Aggiunge la proprietà stringa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| valore | System.Object | Il valore della stringa. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Determina se questa collezione contiene la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave da verificare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | **True** se il  contiene la chiave specificata; altrimenti, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Restituisce l'oggetto con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave che identifica il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Object | Restituisce l'oggetto con la chiave specificata. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Converte il valore XMP nella rappresentazione XML.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce il valore XMP convertito nella rappresentazione XML. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Rimuove il valore con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore rimosso. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce true se il valore con la chiave specificata è stato rimosso. |


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Aggiunge la data di creazione della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| created_date | System.DateTime | Data di creazione. |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

Aggiunge la data di creazione della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| created_date | string | Data di creazione. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

Aggiunge la data di creazione della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| created_date | string | Data di creazione. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

Imposta lo strumento creatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| creator_tool | string | Nome dello strumento. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

Imposta l'identificatore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| idenfifier | string[] | L'idenfifier. |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

Imposta l'etichetta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| etichetta | string | L'etichetta. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata_date | System.DateTime | Data dei metadati. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata_date | string | Data dei metadati. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata_date | string | Data dei metadati. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| modified_date | System.DateTime | Data dell'ultima modifica. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| modified_date | string | Data dell'ultima modifica. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| modified_date | string | Data dell'ultima modifica. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

Restituisce o imposta l'oggetto con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave che identifica il valore. |
| valore | System.Object | L'oggetto con la chiave specificata. |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

Imposta la valutazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scelta | int | Da -1 a 5 |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Il valore a cui aggiungere. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Il valore da impostare. |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


```
 try_get_value(key, value) 
```

Restituisce il valore per la _key_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave dell'elemento XMP. |
| valore | System.Object | Il valore XMP. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | **True**, se il  contiene la _key_; altrimenti, **False**. |


