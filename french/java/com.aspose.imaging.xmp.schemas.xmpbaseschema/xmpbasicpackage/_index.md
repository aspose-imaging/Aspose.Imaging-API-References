---
title: "XmpBasicPackage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente l'espace de noms de base XMP."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Représente l'espace de noms de base XMP.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initialise une nouvelle instance de la classe `XmpBasicPackage`. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe `XmpBasicPackage`. |
## Champs

| Champ | Description |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Valeur rejetée de l'évaluation. |
| [RATING_MIN](#RATING-MIN) | Valeur minimale de l'évaluation. |
| [RATING_MAX](#RATING-MAX) | Valeur maximale de l'évaluation. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Définit l'étiquette. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Ajoute une propriété de chaîne. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Ajoute la date de création de la ressource. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Ajoute la date de création de la ressource. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Définit l'outil du créateur. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Définit l'identifiant. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Ajoute la date de dernière modification des métadonnées. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Ajoute la date de dernière modification des métadonnées. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Ajoute la date de dernière modification de la ressource. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Ajoute la date de dernière modification de la ressource. |
| [setRating(int choice)](#setRating-int-) | Définit l'évaluation. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initialise une nouvelle instance de la classe `XmpBasicPackage`.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initialise une nouvelle instance de la classe `XmpBasicPackage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | java.lang.String | Le préfixe. |
| namespaceUri | java.lang.String | L'URI de l'espace de noms. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Valeur rejetée de l'évaluation.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Valeur minimale de l'évaluation.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Valeur maximale de l'évaluation.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Définit l'étiquette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| étiquette | java.lang.String | L'étiquette. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Ajoute une propriété de chaîne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La représentation sous forme de chaîne de la clé identifiée avec la valeur ajoutée. |
| valeur | java.lang.String | La valeur de chaîne. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Ajoute la date de création de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createdDate | java.util.Date | Date de création. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Ajoute la date de création de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| createdDate | java.lang.String | Date de création. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Définit l'outil du créateur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| creatorTool | java.lang.String | Nom de l'outil. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Définit l'identifiant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| identifiant | java.lang.String[] | L'identifiant. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Ajoute la date de dernière modification des métadonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadataDate | java.util.Date | Date des métadonnées. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Ajoute la date de dernière modification des métadonnées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| metadataDate | java.lang.String | Date des métadonnées. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Ajoute la date de dernière modification de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| modifiedDate | java.util.Date | Date de dernière modification. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Ajoute la date de dernière modification de la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| modifiedDate | java.lang.String | Date de dernière modification. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Définit l'évaluation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| choix | int | De -1 à 5 |

