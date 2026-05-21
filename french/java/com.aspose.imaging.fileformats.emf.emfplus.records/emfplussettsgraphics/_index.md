---
title: "EmfPlusSetTsGraphics"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetTSGraphics spécifie l'état d'un contexte de dispositif graphique pour un serveur terminal."
type: docs
weight: 67
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsGraphics extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusSetTSGraphics spécifie l'état d'un contexte de dispositif graphique pour un serveur terminal.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetTsGraphics(EmfPlusRecord source)](#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetTsGraphics`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBasicVgaColors()](#getBasicVgaColors--) | Obtient une valeur indiquant si [basic vga colors]. |
| [getHavePalette()](#getHavePalette--) | Obtient une valeur indiquant si [have palette]. |
| [getAntiAliasMode()](#getAntiAliasMode--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu des lignes, y compris le type d'anticrénelage des lignes. |
| [setAntiAliasMode(byte value)](#setAntiAliasMode-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu des lignes, y compris le type d'anticrénelage des lignes. |
| [getTextRenderHint()](#getTextRenderHint--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu du texte, y compris le type d'anticrénelage du texte. |
| [setTextRenderHint(byte value)](#setTextRenderHint-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu du texte, y compris le type d'anticrénelage du texte. |
| [getCompositingMode()](#getCompositingMode--) | Obtient ou définit un entier non signé de 8 bits qui spécifie comment les couleurs sources sont combinées avec les couleurs d'arrière-plan. |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie comment les couleurs sources sont combinées avec les couleurs d'arrière-plan. |
| [getCompositingQuality()](#getCompositingQuality--) | Obtient ou définit un entier non signé de 8 bits qui spécifie le degré de lissage à appliquer aux lignes, courbes et aux bords des zones remplies afin de les rendre plus continues ou nettement définies. |
| [setCompositingQuality(byte value)](#setCompositingQuality-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie le degré de lissage à appliquer aux lignes, courbes et aux bords des zones remplies afin de les rendre plus continues ou nettement définies. |
| [getRenderOriginX()](#getRenderOriginX--) | Obtient ou définit un entier signé de 16 bits, qui est la coordonnée horizontale de l'origine pour le rendu des matrices de demi-teinte et de dithering. |
| [setRenderOriginX(short value)](#setRenderOriginX-short-) | Obtient ou définit un entier signé de 16 bits, qui est la coordonnée horizontale de l'origine pour le rendu des matrices de demi-teinte et de dithering. |
| [getRenderOriginY()](#getRenderOriginY--) | Obtient ou définit un entier signé de 16 bits, qui est la coordonnée verticale de l'origine pour le rendu des matrices de demi-teinte et de dithering. |
| [setRenderOriginY(short value)](#setRenderOriginY-short-) | Obtient ou définit un entier signé de 16 bits, qui est la coordonnée verticale de l'origine pour le rendu des matrices de demi-teinte et de dithering. |
| [getTextContrast()](#getTextContrast--) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma utilisée pour le rendu du texte anti-aliasé et ClearType. |
| [setTextContrast(short value)](#setTextContrast-short-) | Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma utilisée pour le rendu du texte anti-aliasé et ClearType. |
| [getFilterType()](#getFilterType--) | Obtient ou définit un entier non signé de 8 bits qui spécifie comment le redimensionnement, y compris l'étirement et la réduction, est effectué. |
| [setFilterType(byte value)](#setFilterType-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie comment le redimensionnement, y compris l'étirement et la réduction, est effectué. |
| [getPixelOffset()](#getPixelOffset--) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité globale de l'image et du processus de rendu du texte. |
| [setPixelOffset(byte value)](#setPixelOffset-byte-) | Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité globale de l'image et du processus de rendu du texte. |
| [getWorldToDevice()](#getWorldToDevice--) | Obtient ou définit un objet EmfPlusTransformMatrix de 192 bits (section 2.2.2.47) qui spécifie les transformations de l'espace mondial vers l'espace dispositif. |
| [setWorldToDevice(Matrix value)](#setWorldToDevice-com.aspose.imaging.Matrix-) | Obtient ou définit un objet EmfPlusTransformMatrix de 192 bits (section 2.2.2.47) qui spécifie les transformations de l'espace mondial vers l'espace dispositif. |
| [getPalette()](#getPalette--) | Obtient ou définit un objet EmfPlusPalette facultatif. |
| [setPalette(EmfPlusPalette value)](#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-) | Obtient ou définit un objet EmfPlusPalette facultatif. |
### EmfPlusSetTsGraphics(EmfPlusRecord source) {#EmfPlusSetTsGraphics-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsGraphics(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetTsGraphics`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getBasicVgaColors() {#getBasicVgaColors--}
```
public boolean getBasicVgaColors()
```


Obtient une valeur indiquant si [basic vga colors]. Si défini, la palette ne contient que les couleurs VGA de base.

Valeur : `true` si [basic vga colors] ; sinon, `false`.

**Returns:**
boolean
### getHavePalette() {#getHavePalette--}
```
public boolean getHavePalette()
```


Obtient une valeur indiquant si [have palette]. Si défini, cet enregistrement contient un objet EmfPlusPalette (section 2.2.2.28) dans le champ Palette suivant les données d'état graphique.

Valeur : `true` si [have palette] ; sinon, `false`.

**Returns:**
boolean
### getAntiAliasMode() {#getAntiAliasMode--}
```
public byte getAntiAliasMode()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu des lignes, y compris le type d'anticrénelage des lignes. Il DOIT être défini dans l'énumération SmoothingMode (section 2.1.1.28).

Valeur : le mode d'anticrénelage.

**Returns:**
byte
### setAntiAliasMode(byte value) {#setAntiAliasMode-byte-}
```
public void setAntiAliasMode(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu des lignes, y compris le type d'anticrénelage des lignes. Il DOIT être défini dans l'énumération SmoothingMode (section 2.1.1.28).

Valeur : le mode d'anticrénelage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getTextRenderHint() {#getTextRenderHint--}
```
public byte getTextRenderHint()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu du texte, y compris le type d'anticrénelage du texte. Il DOIT être défini dans l'énumération TextRenderingHint (section 2.1.1.32).

Valeur : l'indice de rendu du texte.

**Returns:**
byte
### setTextRenderHint(byte value) {#setTextRenderHint-byte-}
```
public void setTextRenderHint(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité du rendu du texte, y compris le type d'anticrénelage du texte. Il DOIT être défini dans l'énumération TextRenderingHint (section 2.1.1.32).

Valeur : l'indice de rendu du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan. Il DOIT être une valeur de l'énumération CompositingMode (section 2.1.1.5).

Valeur : le mode de composition.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan. Il DOIT être une valeur de l'énumération CompositingMode (section 2.1.1.5).

Valeur : le mode de composition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCompositingQuality() {#getCompositingQuality--}
```
public byte getCompositingQuality()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le degré de lissage à appliquer aux lignes, courbes et bords des zones remplies afin de les rendre plus continues ou nettement définies. Il DOIT être une valeur de l'énumération CompositingQuality (section 2.1.1.6).

Valeur : la qualité de composition.

**Returns:**
byte
### setCompositingQuality(byte value) {#setCompositingQuality-byte-}
```
public void setCompositingQuality(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie le degré de lissage à appliquer aux lignes, courbes et bords des zones remplies afin de les rendre plus continues ou nettement définies. Il DOIT être une valeur de l'énumération CompositingQuality (section 2.1.1.6).

Valeur : la qualité de composition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getRenderOriginX() {#getRenderOriginX--}
```
public short getRenderOriginX()
```


Obtient ou définit un entier signé de 16 bits, qui est la coordonnée horizontale de l'origine pour le rendu des matrices de demi-teinte et de dithering.

Valeur : l'origine du rendu x.

**Returns:**
short
### setRenderOriginX(short value) {#setRenderOriginX-short-}
```
public void setRenderOriginX(short value)
```


Obtient ou définit un entier signé de 16 bits, qui est la coordonnée horizontale de l'origine pour le rendu des matrices de demi-teinte et de dithering.

Valeur : l'origine du rendu x.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getRenderOriginY() {#getRenderOriginY--}
```
public short getRenderOriginY()
```


Obtient ou définit un entier signé de 16 bits, qui est la coordonnée verticale de l'origine pour le rendu des matrices de demi-teinte et de dithering.

Valeur : l'origine du rendu y.

**Returns:**
short
### setRenderOriginY(short value) {#setRenderOriginY-short-}
```
public void setRenderOriginY(short value)
```


Obtient ou définit un entier signé de 16 bits, qui est la coordonnée verticale de l'origine pour le rendu des matrices de demi-teinte et de dithering.

Valeur : l'origine du rendu y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma utilisée pour le rendu du texte antialiasé et ClearType. Cette valeur DOIT être comprise entre 0 et 12, inclus.

Valeur : le contraste du texte.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Obtient ou définit un entier non signé de 16 bits qui spécifie la valeur de correction gamma utilisée pour le rendu du texte antialiasé et ClearType. Cette valeur DOIT être comprise entre 0 et 12, inclus.

Valeur : le contraste du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getFilterType() {#getFilterType--}
```
public byte getFilterType()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie comment le redimensionnement, y compris l'étirement et la réduction, est effectué. Il DOIT être une valeur de l'énumération FilterType (section 2.1.1.11).

Valeur : le type du filtre.

**Returns:**
byte
### setFilterType(byte value) {#setFilterType-byte-}
```
public void setFilterType(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie comment le redimensionnement, y compris l'étirement et la réduction, est effectué. Il DOIT être une valeur de l'énumération FilterType (section 2.1.1.11).

Valeur : le type du filtre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getPixelOffset() {#getPixelOffset--}
```
public byte getPixelOffset()
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité globale de l'image et du processus de rendu du texte. Il DOIT être une valeur de l'énumération PixelOffsetMode (section 2.1.1.26).

Valeur : le décalage de pixel.

**Returns:**
byte
### setPixelOffset(byte value) {#setPixelOffset-byte-}
```
public void setPixelOffset(byte value)
```


Obtient ou définit un entier non signé de 8 bits qui spécifie la qualité globale de l'image et du processus de rendu du texte. Il DOIT être une valeur de l'énumération PixelOffsetMode (section 2.1.1.26).

Valeur : le décalage de pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getWorldToDevice() {#getWorldToDevice--}
```
public Matrix getWorldToDevice()
```


Obtient ou définit un objet EmfPlusTransformMatrix de 192 bits (section 2.2.2.47) qui spécifie les transformations de l'espace mondial vers l'espace dispositif.

Valeur : le monde vers dispositif.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setWorldToDevice(Matrix value) {#setWorldToDevice-com.aspose.imaging.Matrix-}
```
public void setWorldToDevice(Matrix value)
```


Obtient ou définit un objet EmfPlusTransformMatrix de 192 bits (section 2.2.2.47) qui spécifie les transformations de l'espace mondial vers l'espace dispositif.

Valeur : le monde vers dispositif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getPalette() {#getPalette--}
```
public EmfPlusPalette getPalette()
```


Obtient ou définit un objet EmfPlusPalette facultatif.

Valeur : la palette.

**Returns:**
[EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette)
### setPalette(EmfPlusPalette value) {#setPalette-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPalette-}
```
public void setPalette(EmfPlusPalette value)
```


Obtient ou définit un objet EmfPlusPalette facultatif.

Valeur : la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfPlusPalette](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette) |  |

