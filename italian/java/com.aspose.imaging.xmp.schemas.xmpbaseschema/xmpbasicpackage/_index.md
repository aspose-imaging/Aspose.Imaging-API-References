---
title: "XmpBasicPackage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta lo spazio dei nomi base XMP."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Rappresenta lo spazio dei nomi base XMP.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Inizializza una nuova istanza della classe `XmpBasicPackage`. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Inizializza una nuova istanza della classe `XmpBasicPackage`. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Valore di rating rifiutato. |
| [RATING_MIN](#RATING-MIN) | Valore minimo di rating. |
| [RATING_MAX](#RATING-MAX) | Valore massimo di rating. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Imposta l'etichetta. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Aggiunge una proprietà stringa. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Aggiunge la data di creazione della risorsa. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Aggiunge la data di creazione della risorsa. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Imposta lo strumento creatore. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Imposta l'identificatore. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Aggiunge la data dell'ultima modifica dei metadati. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Aggiunge la data dell'ultima modifica dei metadati. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Aggiunge la data dell'ultima modifica della risorsa. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Aggiunge la data dell'ultima modifica della risorsa. |
| [setRating(int choice)](#setRating-int-) | Imposta il rating. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Inizializza una nuova istanza della classe `XmpBasicPackage`.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Inizializza una nuova istanza della classe `XmpBasicPackage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefisso | java.lang.String | Il prefisso. |
| namespaceUri | java.lang.String | L'URI dello spazio dei nomi. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Valore di rating rifiutato.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Valore minimo di rating.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Valore massimo di rating.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Imposta l'etichetta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| etichetta | java.lang.String | L'etichetta. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Aggiunge una proprietà stringa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | java.lang.String | Il valore stringa. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Aggiunge la data di creazione della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createdDate | java.util.Date | Data di creazione. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Aggiunge la data di creazione della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createdDate | java.lang.String | Data di creazione. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Imposta lo strumento creatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| creatorTool | java.lang.String | Nome dello strumento. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Imposta l'identificatore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| identificatore | java.lang.String[] | L'identificatore. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| metadataDate | java.util.Date | Data dei metadati. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Aggiunge la data dell'ultima modifica dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| metadataDate | java.lang.String | Data dei metadati. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modifiedDate | java.util.Date | Data dell'ultima modifica. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Aggiunge la data dell'ultima modifica della risorsa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modifiedDate | java.lang.String | Data dell'ultima modifica. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Imposta il rating.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scelta | int | Da -1 a 5 |

