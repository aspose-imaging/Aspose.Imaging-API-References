---
title: "Classe PdfPackage"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Inizializza una nuova istanza della classe [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/). |
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
| [add_value(key, value)](#add_value_key_value_1) | Aggiunge la proprietà stringa. |
| [add_value(key, value)](#add_value_key_value_2) | Aggiunge la proprietà stringa. |
| clear() | Cancella questa istanza. |
| [contains_key(key)](#contains_key_key_3) | Determina se questa collezione contiene la chiave specificata. |
| [get_prop_value(key)](#get_prop_value_key_4) | Restituisce l'oggetto con la chiave specificata. |
| [get_xml_value()](#get_xml_value__5) | Converte il valore XMP nella rappresentazione XML. |
| [remove(key)](#remove_key_6) | Rimuove il valore con la chiave specificata. |
| [set_keywords(keywords)](#set_keywords_keywords_7) | Imposta le parole chiave. |
| [set_pdf_version(version)](#set_pdf_version_version_8) | Imposta la versione PDF. |
| [set_producer(producer)](#set_producer_producer_9) | Imposta il nome dello strumento che ha creato il PDF. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Restituisce o imposta l'oggetto con la chiave specificata. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | Imposta il trapped. |
| [set_value(key, value)](#set_value_key_value_12) | Imposta il valore. |
| [set_value(key, value)](#set_value_key_value_13) | Imposta il valore. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | Imposta il valore del tipo XMP. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | Restituisce il valore per la _key_. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Inizializza una nuova istanza della classe [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/).

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

Imposta le parole chiave.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| parole chiave | string | Le parole chiave. |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

Imposta la versione PDF.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| versione | string | Versione PDF, ad esempio: 1.0, 1.3 ecc. |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

Imposta il nome dello strumento che ha creato il PDF.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| produttore | string | Il nome del produttore. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

Restituisce o imposta l'oggetto con la chiave specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La chiave che identifica il valore. |
| valore | System.Object | L'oggetto con la chiave specificata. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

Imposta il trapped.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| is_trapped | bool | se impostato su <c>true</c> il documento è stato trappato. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Il valore a cui aggiungere. |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

Imposta il valore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave che è identificata con il valore aggiunto. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Il valore a cui aggiungere. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

Imposta il valore del tipo XMP.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | string | La rappresentazione stringa della chiave identificata con il valore impostato. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Il valore da impostare. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


