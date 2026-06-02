---
title: "BitmapV5Header"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La structure BitmapV5Header est le fichier d'en-tête d'information bitmap."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.bmp/bitmapv5header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader), [com.aspose.imaging.fileformats.bmp.BitmapV4Header](../../com.aspose.imaging.fileformats.bmp/bitmapv4header)
```
public class BitmapV5Header extends BitmapV4Header
```

La structure BitmapV5Header est le fichier d'en-tête d'information bitmap. C'est une version étendue de la structure BITMAPINFOHEADER.

Si bV5Height est négatif, indiquant un DIB top‑down, bV5Compression doit être soit BI_RGB soit BI_BITFIELDS. Les DIB top‑down ne peuvent pas être compressés. L'interface Independent Color Management (ICM) 2.0 permet aux profils couleur International Color Consortium (ICC) d'être liés ou incorporés dans les DIB (DIB). Voir Using Structures pour plus d'informations. Lorsqu'un DIB est chargé en mémoire, les données de profil (si présentes) doivent suivre la table de couleurs, et bV5ProfileData doit fournir le décalage des données de profil depuis le début de la structure BITMAPV5HEADER. La valeur stockée dans bV5ProfileData sera différente de la valeur renvoyée par l'opérateur sizeof avec l'argument BITMAPV5HEADER, car bV5ProfileData est le décalage en octets depuis le début de la structure BITMAPV5HEADER jusqu'au début des données de profil. (Les bits du bitmap ne suivent pas la table de couleurs en mémoire). Les applications doivent modifier le membre bV5ProfileData après avoir chargé le DIB en mémoire. Pour les DIB empaquetés, les données de profil doivent suivre les bits du bitmap comme dans le format de fichier. Le membre bV5ProfileData doit toujours fournir le décalage des données de profil depuis le début de la BITMAPV5HEADER. Les applications ne doivent accéder aux données de profil que lorsque bV5Size est égal à la taille de la BITMAPV5HEADER et que bV5CSType est égal à PROFILE_EMBEDDED ou PROFILE_LINKED.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BitmapV5Header()](#BitmapV5Header--) | Initialise une nouvelle instance de la classe `BitmapV5Header`. |
| [BitmapV5Header(byte[] bytes)](#BitmapV5Header-byte---) | Initialise une nouvelle instance de la classe `BitmapV5Header`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIntent()](#getIntent--) | Obtient l'intention de rendu pour le bitmap. |
| [setIntent(long value)](#setIntent-long-) | Définit l'intention de rendu pour le bitmap. |
| [getProfileData()](#getProfileData--) | Obtient les données du profil. |
| [setProfileData(long value)](#setProfileData-long-) | Définit les données du profil. |
| [getProfileSize()](#getProfileSize--) | Obtient la taille du profil. |
| [setProfileSize(long value)](#setProfileSize-long-) | Définit la taille du profil. |
| [getReserved()](#getReserved--) | Obtient le membre réservé. |
| [setReserved(long value)](#setReserved-long-) | Définit le membre réservé. |
### BitmapV5Header() {#BitmapV5Header--}
```
public BitmapV5Header()
```


Initialise une nouvelle instance de la classe `BitmapV5Header`.

### BitmapV5Header(byte[] bytes) {#BitmapV5Header-byte---}
```
public BitmapV5Header(byte[] bytes)
```


Initialise une nouvelle instance de la classe `BitmapV5Header`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| octets | byte[] | Les octets. |

### getIntent() {#getIntent--}
```
public long getIntent()
```


Obtient l'intention de rendu pour le bitmap.

**Returns:**
long - L'intention.
### setIntent(long value) {#setIntent-long-}
```
public void setIntent(long value)
```


Définit l'intention de rendu pour le bitmap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | L'intention. |

### getProfileData() {#getProfileData--}
```
public long getProfileData()
```


Obtient les données du profil.

**Returns:**
long - Les données du profil.
### setProfileData(long value) {#setProfileData-long-}
```
public void setProfileData(long value)
```


Définit les données du profil.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | Les données du profil. |

### getProfileSize() {#getProfileSize--}
```
public long getProfileSize()
```


Obtient la taille du profil.

**Returns:**
long - La taille du profil.
### setProfileSize(long value) {#setProfileSize-long-}
```
public void setProfileSize(long value)
```


Définit la taille du profil.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La taille du profil. |

### getReserved() {#getReserved--}
```
public long getReserved()
```


Obtient le membre réservé.

**Returns:**
long - La valeur réservée.
### setReserved(long value) {#setReserved-long-}
```
public void setReserved(long value)
```


Définit le membre réservé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La valeur réservée. |

