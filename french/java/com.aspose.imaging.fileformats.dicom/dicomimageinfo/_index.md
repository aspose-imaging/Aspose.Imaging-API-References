---
title: "DicomImageInfo"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Contient toutes les métadonnées de l'en-tête du fichier Dicom."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Contient toutes les métadonnées de l'en-tête du fichier Dicom.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Obtient les informations d'en-tête DICOM sous forme d'octets. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtient la configuration planaire. |
| [getSignedImage()](#getSignedImage--) | Obtient une valeur indiquant si "signedImage". |
| [getDicomInfo()](#getDicomInfo--) | Obtient les informations d'en-tête du fichier DICOM. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtient une valeur de "samplesPerPixel". |
| [getBitsAllocated()](#getBitsAllocated--) | Obtient une valeur de "bitsAllocated". |
| [getBitsStored()](#getBitsStored--) | Obtient le nombre de bits stockés. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | Obtient une valeur de "PhotoInterpretation". |
| [getWidth()](#getWidth--) | Obtient la largeur. |
| [getHeight()](#getHeight--) | Obtient la hauteur. |
| [getWindowCentre()](#getWindowCentre--) | Obtient le centre de la fenêtre. |
| [getWindowWidth()](#getWindowWidth--) | Obtient la largeur de la fenêtre. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Obtient une valeur du pixel "pixelRepresentation". |
| [getRescaleIntercept()](#getRescaleIntercept--) | Obtient une valeur de "rescaleIntercept". |
| [getRescaleSlope()](#getRescaleSlope--) | Obtient une valeur de "rescaleSlope". |
| [getNumberOfFrames()](#getNumberOfFrames--) | Obtient le nombre d'images. |
| [isLittleEndian()](#isLittleEndian--) | Obtient une valeur indiquant si cette instance est en little endian. |
| [getReds()](#getReds--) | Obtient les couleurs du tableau du rouge |
| [getGreens()](#getGreens--) | Obtient les couleurs du tableau du vert |
| [getBlues()](#getBlues--) | Obtient les couleurs du tableau du bleu |
| [getOffset()](#getOffset--) | Obtient le décalage. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Ajoute une nouvelle balise Dicom. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Ajoute une nouvelle balise Dicom. |
| [removeTagAt(int index)](#removeTagAt-int-) | Supprime une balise existante. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Supprime une balise existante. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Met à jour une balise existante. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Met à jour une balise existante. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Obtient les informations d'en-tête DICOM sous forme d'octets.

Valeur : les informations d'en-tête dicom en octets.

**Returns:**
byte[] - les informations d'en-tête dicom en octets.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtient la configuration planaire.

Valeur : La configuration planaire.

**Returns:**
int - la configuration planaire.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


Obtient une valeur indiquant si "signedImage".

**Returns:**
boolean - une valeur indiquant si "signedImage".
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


Obtient les informations d'en-tête du fichier DICOM.

**Returns:**
java.util.List<java.lang.String> - les informations d'en-tête du fichier DICOM.

**Example: The following example shows how to read the header information of a DICOM image.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1489\\";
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "ttfm.dcm");
try {
    for (String s : image.getFileInfo().getDicomInfo()) {
        System.out.println(s);
    }
}
finally {
    image.close();
}

// STDOUT:
//UID de classe SOP de stockage média : 1.2.840.10008.5.1.4.1.1.3.1
//UID d'instance SOP de stockage média : 2.16.840.1.114488.0.4.123489834087.1330071425.2
//UID de syntaxe de transfert : 1.2.840.10008.1.2.4.70
//UID de classe d'implémentation : 1.2.840.114236
//Jeu de caractères spécifique : ISO_IR 100
//Type d'image : \SECONDARY\INTRAOPERATIVE
//UID de classe SOP : 1.2.840.10008.5.1.4.1.1.3.1
//UID d'instance SOP : 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Date d'étude : 20110824
//Date de série : 20110824
//Date de contenu : 20110824
//Heure d'étude : 094836.214743984
//Heure de série : 094836.214743984
//Heure de contenu : 100451.214743816
//Modalité : US
//Fabricant : Medistim
//Nom de l'institution : Hospital Name
//Adresse de l'institution : Hospital Address or Department
//Nom de la station : VERIQ
//Nom du médecin exécutant : CA Prof. Debus
//Nom du modèle du fabricant : VeriQ C
//Fréquence d'images recommandée à l'affichage : 1
//Nom du patient : Femoral trombenarterectomy^Case Report:
//Identifiant du patient: Rapport de cas 1
//Sexe du patient: M
//Taille du patient: 0
//Poids du patient: 0
//Commentaires du patient: Voir le rapport de cas sur www.medistim.com
//Taux de cine: 1
//Durée effective: 1
//Numéro de série de l'appareil: 0
//Version(s) du logiciel: 3.3.0 RC0 construit le 02/23/12 09:50:45
//Temps de trame: 1000
//UID d'instance d'étude: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//UID d'instance de série: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Numéro de série: 1
//Numéro d'instance: 1
//Échantillons par pixel: 3
//Interprétation photométrique: RGB
//Configuration planaire: 0
//Nombre de trames: 1
//Pointeur d'incrément de trame:
//Lignes: 768
//Colonnes: 1024
//Bits alloués: 8
//Bits stockés: 8
//Bit de poids fort: 7
//Représentation du pixel: 0
//Compression d'image avec perte: 00
//Données de pixel: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtient une valeur de "samplesPerPixel".

Valeur : La valeur de "samplesPerPixel".

**Returns:**
int - une valeur de "samplesPerPixel".
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


Obtient une valeur de "bitsAllocated".

Valeur : La valeur de "bitsAllocated".

**Returns:**
int - une valeur de "bitsAllocated".
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Obtient le nombre de bits stockés.

**Returns:**
int - le nombre de bits stockés.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


Obtient une valeur de "PhotoInterpretation".

**Returns:**
java.lang.String - une valeur de "PhotoInterpretation".
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur.

Valeur : La valeur de la largeur.

**Returns:**
int - la largeur.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur.

Valeur : La valeur de la hauteur.

**Returns:**
int - la hauteur.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Obtient le centre de la fenêtre.

Valeur : La valeur du centre de la fenêtre.

**Returns:**
double - le centre de la fenêtre.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Obtient la largeur de la fenêtre.

Valeur : La largeur de la fenêtre.

**Returns:**
double - la largeur de la fenêtre.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Obtient une valeur du pixel "pixelRepresentation".

Valeur : La valeur de "pixelRepresentation".

**Returns:**
int - une valeur du pixel "pixelRepresentation".
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


Obtient une valeur de "rescaleIntercept".

Valeur : La valeur de "rescaleIntercept".

**Returns:**
double - une valeur de "rescaleIntercept".
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


Obtient une valeur de "rescaleSlope".

Valeur : La valeur de "rescaleSlope".

**Returns:**
double - une valeur de "rescaleSlope".
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Obtient le nombre d'images.

Valeur : Le nombre de cadres.

**Returns:**
int - le nombre de cadres.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Obtient une valeur indiquant si cette instance est en little endian.

Valeur : `true` si cette instance est en little endian ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si cette instance est en little endian.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Obtient les couleurs du tableau du rouge

Valeur : Les rouges.

**Returns:**
byte[] - le tableau des couleurs du rouge
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Obtient les couleurs du tableau du vert

Valeur : la couleur du rouge.

**Returns:**
byte[] - le tableau des couleurs du vert
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Obtient les couleurs du tableau du bleu

Valeur : le bleu.

**Returns:**
byte[] - le tableau des couleurs du bleu
### getOffset() {#getOffset--}
```
public int getOffset()
```


Obtient le décalage.

Valeur : la valeur du décalage.

**Returns:**
int - le décalage.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Ajoute une nouvelle balise Dicom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagDescription | java.lang.String | La description du tag. Ne peut pas être null ou vide. |
| valeur | java.lang.Object | La valeur du tag. Ne peut pas être null. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Ajoute une nouvelle balise Dicom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagDescription | java.lang.String | La description du tag. Ne peut pas être null ou vide. |
| valeur | java.lang.Object | La valeur du tag. Ne peut pas être null. |

**Returns:**
boolean - le résultat de l'opération.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Supprime une balise existante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index du tag à mettre à jour. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Supprime une balise existante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index du tag à mettre à jour. |

**Returns:**
boolean - le résultat de l'opération.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Met à jour une balise existante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index du tag à mettre à jour. |
| newValue | java.lang.Object | La valeur du tag. Ne peut pas être null. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Met à jour une balise existante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index du tag à mettre à jour. |
| newValue | java.lang.Object | La valeur du tag. Ne peut pas être null. |

**Returns:**
boolean - le résultat de l'opération.
