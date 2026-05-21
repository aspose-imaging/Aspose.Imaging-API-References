---
title: "XmpBasicPackage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt den XMP-Basis-Namespace dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Stellt den XMP-Basis-Namespace dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initialisiert eine neue Instanz der `XmpBasicPackage`-Klasse. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der `XmpBasicPackage`-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Bewertung abgelehnter Wert. |
| [RATING_MIN](#RATING-MIN) | Bewertung Minimalwert. |
| [RATING_MAX](#RATING-MAX) | Bewertung Maximalwert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Setzt das Label. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Fügt eine String-Eigenschaft hinzu. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Setzt das Erstellungswerkzeug. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Setzt den Bezeichner. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Fügt das Datum der letzten Metadatenänderung hinzu. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Fügt das Datum der letzten Metadatenänderung hinzu. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Fügt das Datum der letzten Ressourceneränderung hinzu. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Fügt das Datum der letzten Ressourceneränderung hinzu. |
| [setRating(int choice)](#setRating-int-) | Setzt die Bewertung. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initialisiert eine neue Instanz der `XmpBasicPackage`-Klasse.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initialisiert eine neue Instanz der `XmpBasicPackage`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präfix | java.lang.String | Das Präfix. |
| namespaceUri | java.lang.String | Die Namespace-URI. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Bewertung abgelehnter Wert.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Bewertung Minimalwert.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Bewertung Maximalwert.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Setzt das Label.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Label | java.lang.String | Das Label. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Fügt eine String-Eigenschaft hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | java.lang.String | Die String-Darstellung des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | java.lang.String | Der String-Wert. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createdDate | java.util.Date | Erstellungsdatum. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createdDate | java.lang.String | Erstellungsdatum. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Setzt das Erstellungswerkzeug.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| creatorTool | java.lang.String | Name des Werkzeugs. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Setzt den Bezeichner.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Bezeichner | java.lang.String[] | Der Bezeichner. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Fügt das Datum der letzten Metadatenänderung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadataDate | java.util.Date | Metadaten-Datum. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Fügt das Datum der letzten Metadatenänderung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| metadataDate | java.lang.String | Metadaten-Datum. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Fügt das Datum der letzten Ressourceneränderung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| modifiedDate | java.util.Date | Letztes Änderungsdatum. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Fügt das Datum der letzten Ressourceneränderung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| modifiedDate | java.lang.String | Letztes Änderungsdatum. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Setzt die Bewertung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Auswahl | int | Von -1 bis 5 |

