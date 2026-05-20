---
title: "WmfLogColorSpaceW"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet LogColorSpaceW spécifie un espace colorimétrique logique qui peut être défini par un fichier de profil couleur dont le nom est composé de caractères Unicode sur 16 bits."
type: docs
weight: 45
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

L'objet LogColorSpaceW spécifie un espace colorimétrique logique, qui peut être défini par un fichier de profil couleur dont le nom est composé de caractères Unicode sur 16 bits.

Voir l'objet `WmfLogColorSpace` (section 2.2.2.11) pour des détails supplémentaires concernant l'interprétation des valeurs des champs de cet objet.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la `signature` des objets d'espace colorimétrique ; il DOIT être fixé à la valeur 0x50534F43, qui est le codage ASCII de la chaîne "PSOC". |
| [setSignature(int value)](#setSignature-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la `signature` des objets d'espace colorimétrique ; il DOIT être fixé à la valeur 0x50534F43, qui est le codage ASCII de la chaîne "PSOC". |
| [getVersion()](#getVersion--) | Obtient ou définit un entier non signé de 32 bits qui définit un numéro de `version` ; il DOIT être 0x00000400. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit un entier non signé de 32 bits qui définit un numéro de `version` ; il DOIT être 0x00000400. |
| [getSize()](#getSize--) | Obtient ou définit un entier non signé de 32 bits qui définit la `size` de cet objet, en octets. |
| [setSize(int value)](#setSize-int-) | Obtient ou définit un entier non signé de 32 bits qui définit la `size` de cet objet, en octets. |
| [getColorSpaceType()](#getColorSpaceType--) | Obtient ou définit un entier signé de 32 bits qui spécifie le type d'espace colorimétrique. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le type d'espace colorimétrique. |
| [getIntent()](#getIntent--) | Obtient ou définit un entier signé de 32 bits qui définit l'intention de mappage du gamut. |
| [setIntent(int value)](#setIntent-int-) | Obtient ou définit un entier signé de 32 bits qui définit l'intention de mappage du gamut. |
| [getEndpoints()](#getEndpoints--) | Obtient ou définit un objet CIEXYZTriple (section 2.2.2.7) qui définit les coordonnées de chromaticité CIE x, y et z des trois couleurs correspondant aux `endpoints` RGB de l'espace colorimétrique logique associé au bitmap. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Obtient ou définit un objet CIEXYZTriple (section 2.2.2.7) qui définit les coordonnées de chromaticité CIE x, y et z des trois couleurs correspondant aux `endpoints` RGB de l'espace colorimétrique logique associé au bitmap. |
| [getGammaRed()](#getGammaRed--) | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le rouge. |
| [setGammaRed(int value)](#setGammaRed-int-) | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le rouge. |
| [getGammaGreen()](#getGammaGreen--) | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le vert. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le vert. |
| [getGammaBlue()](#getGammaBlue--) | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le bleu. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le bleu. |
| [getFilename()](#getFilename--) | Obtient ou définit une chaîne de caractères Unicode UTF16-LE terminée par un caractère nul, facultative, qui spécifie le nom d'un fichier contenant un profil colorimétrique. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Obtient ou définit une chaîne de caractères Unicode UTF16-LE terminée par un caractère nul, facultative, qui spécifie le nom d'un fichier contenant un profil colorimétrique. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la `signature` des objets d'espace colorimétrique ; il DOIT être fixé à la valeur 0x50534F43, qui est le codage ASCII de la chaîne "PSOC".

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la `signature` des objets d'espace colorimétrique ; il DOIT être fixé à la valeur 0x50534F43, qui est le codage ASCII de la chaîne "PSOC".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit un entier non signé de 32 bits qui définit un numéro de `version` ; il DOIT être 0x00000400.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit un entier non signé de 32 bits qui définit un numéro de `version` ; il DOIT être 0x00000400.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Obtient ou définit un entier non signé de 32 bits qui définit la `size` de cet objet, en octets.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui définit la `size` de cet objet, en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le type d'espace colorimétrique. Il DOIT être défini dans l'énumération LogicalColorSpace (section 2.1.1.14). Si cette valeur est LCS\_sRGB ou LCS\_WINDOWS\_COLOR\_SPACE, l'espace colorimétrique sRGB DOIT être utilisé.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le type d'espace colorimétrique. Il DOIT être défini dans l'énumération LogicalColorSpace (section 2.1.1.14). Si cette valeur est LCS\_sRGB ou LCS\_WINDOWS\_COLOR\_SPACE, l'espace colorimétrique sRGB DOIT être utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Obtient ou définit un entier signé de 32 bits qui définit l'intention de mappage du gamut. Il DOIT être défini dans l'énumération GamutMappingIntent (section 2.1.1.11).

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Obtient ou définit un entier signé de 32 bits qui définit l'intention de mappage du gamut. Il DOIT être défini dans l'énumération GamutMappingIntent (section 2.1.1.11).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Obtient ou définit un objet CIEXYZTriple (section 2.2.2.7) qui définit les coordonnées de chromaticité CIE x, y et z des trois couleurs correspondant aux `endpoints` RGB de l'espace colorimétrique logique associé au bitmap. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Obtient ou définit un objet CIEXYZTriple (section 2.2.2.7) qui définit les coordonnées de chromaticité CIE x, y et z des trois couleurs correspondant aux `endpoints` RGB de l'espace colorimétrique logique associé au bitmap. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le rouge. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le rouge. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le vert. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le vert. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le bleu. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Obtient ou définit une valeur à point fixe de 32 bits qui définit la courbe de réponse tonifiée pour le bleu. Si le champ `ColorSpaceType` ne spécifie pas LCS\_CALIBRATED\_RGB, ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Obtient ou définit une chaîne de caractères Unicode UTF16-LE terminée par un caractère nul, facultative, qui spécifie le nom d'un fichier contenant un profil colorimétrique. Si un nom de fichier est spécifié, et que le champ `ColorSpaceType` est réglé sur LCS\_CALIBRATED\_RGB, les autres champs de cette structure DEVRAIENT être ignorés.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Obtient ou définit une chaîne de caractères Unicode UTF16-LE terminée par un caractère nul, facultative, qui spécifie le nom d'un fichier contenant un profil colorimétrique. Si un nom de fichier est spécifié, et que le champ `ColorSpaceType` est réglé sur LCS\_CALIBRATED\_RGB, les autres champs de cette structure DEVRAIENT être ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

