---
title: "EmfMetafileHeader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les types d'enregistrement EMR_HEADER définissent les points de départ des métafichiers EMF et spécifient les propriétés du dispositif sur lequel l'image du métafichier a été créée."
type: docs
weight: 70
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

Les types d'enregistrement EMR\_HEADER définissent les points de départ des métafichiers EMF et spécifient les propriétés du dispositif sur lequel l'image du métafichier a été créée. Les informations de l'enregistrement d'en-tête permettent aux métafichiers EMF d'être indépendants de tout dispositif de sortie spécifique. La valeur du champ Size peut être utilisée pour distinguer les différents types d'enregistrement EMR\_HEADER listés plus haut dans cette section. Il existe trois en-têtes possibles : l'en-tête de base, qui est l'enregistrement EmfMetafileHeader. La partie à taille fixe de cet en-tête fait 88 octets et contient un objet Header. Le premier en-tête d'extension, qui est l'enregistrement EmfMetafileHeaderExtension1. La partie à taille fixe de cet en-tête fait 100 octets et contient un objet Header et un objet HeaderExtension1 (section 2.2.10). Le deuxième en-tête d'extension, qui est l'enregistrement EmfMetafileHeaderExtension2. La partie à taille fixe de cet en-tête fait 108 octets et contient un objet Header, un objet HeaderExtension1 et un objet HeaderExtension2 (section 2.2.11).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfMetafileHeader`. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Initialise une nouvelle instance de la classe `EmfMetafileHeader`. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initialise une nouvelle instance de la classe `EmfMetafileHeader`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Obtient un objet Header (section 2.2.9), qui contient des informations sur le contenu et la structure du métafichier |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Définit un objet Header (section 2.2.9), qui contient des informations sur le contenu et la structure du métafichier |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | Obtient un tableau d'octets optionnel qui contient le reste de l'enregistrement d'en-tête EMF. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | Définit un tableau d'octets optionnel qui contient le reste de l'enregistrement d'en-tête EMF. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | Obtient le tampon de description EMF Un tableau d'octets optionnel qui contient la chaîne de description EMF, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeader. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | Définit le tampon de description EMF Un tableau d'octets optionnel qui contient la chaîne de description EMF, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeader. |
| [getEmfDescription()](#getEmfDescription--) | Obtient la description EMF Une chaîne Unicode UTF16-LE terminée par null, optionnelle, de longueur et de contenu arbitraires. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | Définit la description EMF Une chaîne Unicode UTF16-LE terminée par null, optionnelle, de longueur et de contenu arbitraires. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Initialise une nouvelle instance de la classe `EmfMetafileHeader`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | L'enregistrement. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Initialise une nouvelle instance de la classe `EmfMetafileHeader`.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Initialise une nouvelle instance de la classe `EmfMetafileHeader`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | L'en-tête. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Obtient un objet Header (section 2.2.9), qui contient des informations sur le contenu et la structure du métafichier

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Définit un objet Header (section 2.2.9), qui contient des informations sur le contenu et la structure du métafichier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


Obtient un tableau d'octets optionnel qui contient le reste de l'enregistrement d'en-tête EMF. La taille de ce champ DOIT être un multiple de 4 octets

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


Définit un tableau d'octets optionnel qui contient le reste de l'enregistrement d'en-tête EMF. La taille de ce champ DOIT être un multiple de 4 octets

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


Obtient le tampon de description EMF Un tableau d'octets optionnel qui contient la chaîne de description EMF, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeader. En conséquence, le champ de ce tampon nommé "UndefinedSpace" est optionnel et DOIT être ignoré.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


Définit le tampon de description EMF Un tableau d'octets optionnel qui contient la chaîne de description EMF, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EmfMetafileHeader. En conséquence, le champ de ce tampon nommé "UndefinedSpace" est optionnel et DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


Obtient la description EMF Une chaîne Unicode UTF16-LE terminée par null, optionnelle, de longueur et de contenu arbitraires. Son emplacement dans l'enregistrement et le nombre de caractères sont spécifiés par les champs offDescription et nDescription, respectivement, dans EmfHeader. Si la valeur de l'un ou l'autre champ est zéro, aucune chaîne de description n'est présente.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


Définit la description EMF Une chaîne Unicode UTF16-LE terminée par null, optionnelle, de longueur et de contenu arbitraires. Son emplacement dans l'enregistrement et le nombre de caractères sont spécifiés par les champs offDescription et nDescription, respectivement, dans EmfHeader. Si la valeur de l'un ou l'autre champ est zéro, aucune chaîne de description n'est présente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

