---
title: "Classe XmpPackage"
type: docs
weight: 460
url: /it/python-net/aspose.imaging.xmp/xmppackage/
---

**Summary:** Represents base abstraction for XMP package.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackage

**Inheritance:** IXmlValue

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| count | int | r | Ottiene il conteggio delle chiavi XMP. |
| namespace_uri | string | r | Restituisce l'URI dello spazio dei nomi. |
| prefix | string | r | Restituisce il prefisso. |
| xml_namespace | string | r | Restituisce lo spazio dei nomi XML. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Aggiunge il valore alla chiave specificata. |
| [add_value(key, value)](#add_value_key_value_2) | Aggiunge il valore alla chiave specificata. |
| clear() | Cancella questa istanza. |
| [contains_key(key)](#contains_key_key_3) | Determina se questa collezione contiene la chiave specificata. |
| [get_prop_value(key)](#get_prop_value_key_4) | Restituisce l'oggetto con la chiave specificata. |
| [get_xml_value()](#get_xml_value__5) | Converte il valore XMP nella rappresentazione XML. |
| [remove(key)](#remove_key_6) | Rimuove il valore con la chiave specificata. |
| [set_prop_value(key, value)](#set_prop_value_key_value_7) | Restituisce o imposta l'oggetto con la chiave specificata. |
| [set_value(key, value)](#set_value_key_value_8) | Imposta il valore. |
| [set_value(key, value)](#set_value_key_value_9) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Imposta il valore del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_11) | Restituisce il valore per la _key_. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Aggiunge il valore alla chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| valore | string | Il valore a cui aggiungere. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Aggiunge il valore alla chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| valore | System.Object | Il valore a cui aggiungere. |

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


### Method: set_prop_value(key, value) {#set_prop_value_key_value_7}


```
 set_prop_value(key, value) 
```

Restituisce o imposta l'oggetto con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave che identifica il valore. |
| valore | System.Object | L'oggetto con la chiave specificata. |

### Method: set_value(key, value) {#set_value_key_value_8}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Il valore a cui aggiungere. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Il valore da impostare. |

### Method: try_get_value(key, value) {#try_get_value_key_value_11}


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


