---
title: "EmfEof"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_EOF indique la fin du métafichier et spécifie une palette."
type: docs
weight: 48
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

L'enregistrement EMR\_EOF indique la fin du métafichier et spécifie une palette.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfEof`. |
| [EmfEof()](#EmfEof--) | Initialise une nouvelle instance de la classe `EmfEof`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Obtient un tampon optionnel contenant les données de palette, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_EOF. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Définit un tampon optionnel contenant les données de palette, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_EOF. |
| [getSizeLast()](#getSizeLast--) | Obtient un entier non signé de 32 bits qui DOIT être identique à Size et DOIT être le dernier champ de l'enregistrement et donc du métafichier. |
| [setSizeLast(int value)](#setSizeLast-int-) | Définit un entier non signé de 32 bits qui DOIT être identique à Size et DOIT être le dernier champ de l'enregistrement et donc du métafichier. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


Initialise une nouvelle instance de la classe `EmfEof`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | L'enregistrement. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


Initialise une nouvelle instance de la classe `EmfEof`.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Obtient un tampon optionnel contenant les données de palette, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_EOF. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés. La taille de ce champ DOIT être un multiple de 4 octets.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Définit un tampon optionnel contenant les données de palette, qui n'est pas requis d'être contigu avec la partie fixe de l'enregistrement EMR\_EOF. En conséquence, les champs de ce tampon étiquetés "UndefinedSpace" sont optionnels et DOIVENT être ignorés. La taille de ce champ DOIT être un multiple de 4 octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Obtient un entier non signé de 32 bits qui DOIT être identique à Size et DOIT être le dernier champ de l'enregistrement et donc du métafichier. Les objets LogPaletteEntry, s'ils existent, DOIVENT précéder ce champ.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Définit un entier non signé de 32 bits qui DOIT être identique à Size et DOIT être le dernier champ de l'enregistrement et donc du métafichier. Les objets LogPaletteEntry, s'ils existent, DOIVENT précéder ce champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

