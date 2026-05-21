---
title: "XmpBasicPackage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar XMP basic-namnutrymme."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpPackage](../../com.aspose.imaging.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Representerar XMP basic-namnutrymme.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Initierar en ny instans av klassen `XmpBasicPackage`. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen `XmpBasicPackage`. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [RATING_REJECTED](#RATING-REJECTED) | Avvisat betygsvärde. |
| [RATING_MIN](#RATING-MIN) | Minimalt betygsvärde. |
| [RATING_MAX](#RATING-MAX) | Maximalt betygsvärde. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setLabel(String label)](#setLabel-java.lang.String-) | Ställer in etiketten. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Lägger till en strängegenskap. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Lägger till resursens skapandedatum. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Lägger till resursens skapandedatum. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Ställer in skapandeverktyget. |
| [setIdentifier(String[] identifier)](#setIdentifier-java.lang.String---) | Ställer in identifieraren. |
| [setMetadataDate(Date metadataDate)](#setMetadataDate-java.util.Date-) | Lägger till metadata senast ändrade datum. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Lägger till metadata senast ändrade datum. |
| [setModifyDate(Date modifiedDate)](#setModifyDate-java.util.Date-) | Lägger till resursens senast modifierade datum. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Lägger till resursens senast modifierade datum. |
| [setRating(int choice)](#setRating-int-) | Ställer in betyg. |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Initierar en ny instans av klassen `XmpBasicPackage`.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Initierar en ny instans av klassen `XmpBasicPackage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | java.lang.String | Prefixet. |
| namespaceUri | java.lang.String | Namnområdets URI. |

### RATING_REJECTED {#RATING-REJECTED}
```
public static final int RATING_REJECTED
```


Avvisat betygsvärde.

### RATING_MIN {#RATING-MIN}
```
public static final int RATING_MIN
```


Minimalt betygsvärde.

### RATING_MAX {#RATING-MAX}
```
public static final int RATING_MAX
```


Maximalt betygsvärde.

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Ställer in etiketten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| etikett | java.lang.String | Etiketten. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Lägger till en strängegenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Strängrepresentationen av nyckeln som identifieras med det tillagda värdet. |
| värde | java.lang.String | Strängvärdet. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Lägger till resursens skapandedatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createdDate | java.util.Date | Skapandedatum. |

### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Lägger till resursens skapandedatum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createdDate | java.lang.String | Skapandedatum. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Ställer in skapandeverktyget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| creatorTool | java.lang.String | Namn på verktyg. |

### setIdentifier(String[] identifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] identifier)
```


Ställer in identifieraren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| identifier | java.lang.String[] | Identifieraren. |

### setMetadataDate(Date metadataDate) {#setMetadataDate-java.util.Date-}
```
public void setMetadataDate(Date metadataDate)
```


Lägger till metadata senast ändrade datum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadataDate | java.util.Date | Metadata datum. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Lägger till metadata senast ändrade datum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| metadataDate | java.lang.String | Metadata datum. |

### setModifyDate(Date modifiedDate) {#setModifyDate-java.util.Date-}
```
public void setModifyDate(Date modifiedDate)
```


Lägger till resursens senast modifierade datum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| modifiedDate | java.util.Date | Senast ändrad datum. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Lägger till resursens senast modifierade datum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| modifiedDate | java.lang.String | Senast ändrad datum. |

### setRating(int choice) {#setRating-int-}
```
public void setRating(int choice)
```


Ställer in betyg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| choice | int | Från -1 till 5 |

