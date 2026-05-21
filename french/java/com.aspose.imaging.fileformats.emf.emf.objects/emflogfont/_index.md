---
title: "EmfLogFont"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet LogFont spécifie les attributs de base d'une police logique."
type: docs
weight: 22
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

L'objet LogFont spécifie les attributs de base d'une police logique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur, en unités logiques, de la cellule de caractère ou du caractère de la police. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur, en unités logiques, de la cellule de caractère ou du caractère de la police. |
| [getWidth()](#getWidth--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur moyenne, en unités logiques, des caractères de la police. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur moyenne, en unités logiques, des caractères de la police. |
| [getEscapement()](#getEscapement--) | Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre le vecteur d'échappement et l'axe x de l'appareil. |
| [setEscapement(int value)](#setEscapement-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre le vecteur d'échappement et l'axe x de l'appareil. |
| [getOrientation()](#getOrientation--) | Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre la ligne de base de chaque caractère et l'axe x de l'appareil. |
| [setOrientation(int value)](#setOrientation-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre la ligne de base de chaque caractère et l'axe x de l'appareil. |
| [getWeight()](#getWeight--) | Obtient ou définit un entier signé de 32 bits qui spécifie le poids de la police dans la plage de zéro à 1000. |
| [setWeight(int value)](#setWeight-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le poids de la police dans la plage de zéro à 1000. |
| [getItalic()](#getItalic--) | Obtient ou définit un entier non signé de 8 bits qui indique une police italique si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00. |
| [setItalic(byte value)](#setItalic-byte-) | Obtient ou définit un entier non signé de 8 bits qui indique une police italique si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00. |
| [getUnderline()](#getUnderline--) | Obtient ou définit un entier non signé de 8 bits qui indique une police soulignée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00. |
| [setUnderline(byte value)](#setUnderline-byte-) | Obtient ou définit un entier non signé de 8 bits qui indique une police soulignée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00. |
| [getStrikeout()](#getStrikeout--) | Obtient ou définit un entier non signé de 8 bits qui indique une police barrée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | Obtient ou définit un entier non signé de 8 bits qui indique une police barrée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00. |
| [getCharSet()](#getCharSet--) | Obtient ou définit un entier non signé de 8 bits qui spécifie l'ensemble des glyphes de caractères. |
| [setCharSet(byte value)](#setCharSet-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie l'ensemble des glyphes de caractères. |
| [getOutPrecision()](#getOutPrecision--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de sortie. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de sortie. |
| [getClipPrecision()](#getClipPrecision--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de découpage. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de découpage. |
| [getQuality()](#getQuality--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité de sortie. |
| [setQuality(byte value)](#setQuality-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité de sortie. |
| [getPitchAndFamily()](#getPitchAndFamily--) | Obtient ou définit un objet WMF PitchAndFamily ([MS-WMF] section 2.2.2.14) qui spécifie le pas et la famille de la police. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | Obtient ou définit un objet WMF PitchAndFamily ([MS-WMF] section 2.2.2.14) qui spécifie le pas et la famille de la police. |
| [getFacename()](#getFacename--) | Obtient ou définit un Facename (64 octets) : une chaîne de maximum 32 caractères Unicode qui spécifie le nom de la police. |
| [setFacename(String value)](#setFacename-java.lang.String-) | Obtient ou définit un Facename (64 octets) : une chaîne de maximum 32 caractères Unicode qui spécifie le nom de la police. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur, en unités logiques, de la cellule de caractère ou du caractère de la police. La valeur de hauteur du caractère, également appelée taille em, correspond à la valeur de hauteur de la cellule de caractère moins la valeur de l'interligne interne. Le mappeur de polices DOIT interpréter la valeur spécifiée dans le champ Height de la manière suivante.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur, en unités logiques, de la cellule de caractère ou du caractère de la police. La valeur de hauteur du caractère, également appelée taille em, correspond à la valeur de hauteur de la cellule de caractère moins la valeur de l'interligne interne. Le mappeur de polices DOIT interpréter la valeur spécifiée dans le champ Height de la manière suivante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur moyenne, en unités logiques, des caractères de la police. Si la valeur du champ Width est zéro, une valeur appropriée DOIT être calculée à partir des autres valeurs LogFont afin de trouver une police correspondant au rapport d'aspect souhaité par le typographe.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur moyenne, en unités logiques, des caractères de la police. Si la valeur du champ Width est zéro, une valeur appropriée DOIT être calculée à partir des autres valeurs LogFont afin de trouver une police correspondant au rapport d'aspect souhaité par le typographe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre le vecteur d'échappement et l'axe x du dispositif. Le vecteur d'échappement est parallèle à la ligne de base d'une rangée de texte.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre le vecteur d'échappement et l'axe x du dispositif. Le vecteur d'échappement est parallèle à la ligne de base d'une rangée de texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre la ligne de base de chaque caractère et l'axe x de l'appareil.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie l'angle, en dixièmes de degré, entre la ligne de base de chaque caractère et l'axe x de l'appareil.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le poids de la police dans la plage de zéro à 1000. Par exemple, 400 est normal et 700 est gras. Si cette valeur est zéro, un poids par défaut peut être utilisé.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le poids de la police dans la plage de zéro à 1000. Par exemple, 400 est normal et 700 est gras. Si cette valeur est zéro, un poids par défaut peut être utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


Obtient ou définit un entier non signé de 8 bits qui indique une police italique si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui indique une police italique si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


Obtient ou définit un entier non signé de 8 bits qui indique une police soulignée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui indique une police soulignée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


Obtient ou définit un entier non signé de 8 bits qui indique une police barrée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui indique une police barrée si la valeur est 0x01 ; sinon, il DOIT être réglé sur 0x00.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie l'ensemble des glyphes de caractères. Il DOIT être une valeur de l'énumération WMF CharacterSet ([MS-WMF] section 2.1.1.5). Si le jeu de caractères est inconnu, le traitement du métafichier NE DOIT PAS tenter de traduire ou d'interpréter les chaînes rendues avec cette police.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie l'ensemble des glyphes de caractères. Il DOIT être une valeur de l'énumération WMF CharacterSet ([MS-WMF] section 2.1.1.5). Si le jeu de caractères est inconnu, le traitement du métafichier NE DOIT PAS tenter de traduire ou d'interpréter les chaînes rendues avec cette police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de sortie. La précision de sortie définit à quel point la police doit correspondre étroitement à la hauteur, la largeur, l'orientation des caractères, l'échappement, le pas et le type de police demandés. Elle DOIT être une valeur de l'énumération WMF OutPrecision.

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de sortie. La précision de sortie définit à quel point la police doit correspondre étroitement à la hauteur, la largeur, l'orientation des caractères, l'échappement, le pas et le type de police demandés. Elle DOIT être une valeur de l'énumération WMF OutPrecision.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de découpage. La précision de découpage définit comment découper les caractères qui sont partiellement en dehors de la région de découpage. Elle peut être une ou plusieurs des indicateurs WMF ClipPrecision.

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la précision de découpage. La précision de découpage définit comment découper les caractères qui sont partiellement en dehors de la région de découpage. Elle peut être une ou plusieurs des indicateurs WMF ClipPrecision.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité de sortie. La qualité de sortie définit dans quelle mesure il faut tenter de faire correspondre les attributs de police logique à ceux d'une police physique réelle. Elle DOIT être l'une des valeurs de l'énumération WMF FontQuality ([MS-WMF] section 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité de sortie. La qualité de sortie définit dans quelle mesure il faut tenter de faire correspondre les attributs de police logique à ceux d'une police physique réelle. Elle DOIT être l'une des valeurs de l'énumération WMF FontQuality ([MS-WMF] section 2.1.1.10).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


Obtient ou définit un objet WMF PitchAndFamily ([MS-WMF] section 2.2.2.14) qui spécifie le pas et la famille de la police. Les familles de polices décrivent l'apparence d'une police de manière générale. Elles sont destinées à spécifier une police lorsque la police spécifiée n'est pas disponible.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


Obtient ou définit un objet WMF PitchAndFamily ([MS-WMF] section 2.2.2.14) qui spécifie le pas et la famille de la police. Les familles de polices décrivent l'apparence d'une police de manière générale. Elles sont destinées à spécifier une police lorsque la police spécifiée n'est pas disponible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


Obtient ou définit un Facename (64 octets) : une chaîne de maximum 32 caractères Unicode qui spécifie le nom de la police. Si la longueur de cette chaîne est inférieure à 32 caractères, un NULL terminateur DOIT être présent, après quoi le reste de ce champ DOIT être ignoré.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


Obtient ou définit un Facename (64 octets) : une chaîne de maximum 32 caractères Unicode qui spécifie le nom de la police. Si la longueur de cette chaîne est inférieure à 32 caractères, un NULL terminateur DOIT être présent, après quoi le reste de ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

