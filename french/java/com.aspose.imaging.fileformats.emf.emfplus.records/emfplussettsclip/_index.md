---
title: "EmfPlusSetTsClip"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetTSClip spécifie les zones de découpage dans le contexte du dispositif graphique pour un serveur terminal."
type: docs
weight: 66
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

L'enregistrement EmfPlusSetTSClip spécifie les zones de découpage dans le contexte du dispositif graphique pour un serveur terminal.

Le schéma de compression des données de cet enregistrement utilise l’algorithme suivant. Chaque point de chaque rectangle est encodé soit sur un octet, soit sur deux octets. Si le point est encodé sur un octet, le bit de poids fort (0x80) de l’octet DOIT être réglé, et la valeur est un nombre signé représenté par les 7 bits de poids faible. Si le bit de poids fort n’est pas réglé, la valeur est encodée sur deux octets, le premier octet contenant les 7 bits de poids faible du byte de poids fort, et le second octet contenant la valeur du byte de poids faible. Chaque point est encodé comme la différence entre le point du rectangle actuel et le point du rectangle précédent. Le point inférieur du rectangle est encodé comme la différence entre la coordonnée inférieure et la coordonnée supérieure du rectangle actuel.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetTsClip`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtient une valeur indiquant si ce `EmfPlusSetTsClip` est compressé. |
| [getNumRects()](#getNumRects--) | Obtient le nombre de rectangles. |
| [getRects()](#getRects--) | Obtient ou définit un tableau de rectangles NumRects qui définissent les zones de découpage. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Obtient ou définit un tableau de rectangles NumRects qui définissent les zones de découpage. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetTsClip`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtient une valeur indiquant si ce `EmfPlusSetTsClip` est compressé. Ce bit spécifie le format des données de rectangle dans le champ rects. S'il est défini, chaque rectangle est défini sur 4 octets. S'il est désactivé, chaque rectangle est défini sur 8 octets.

Valeur : `true` si compressé ; sinon, `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Obtient le nombre de rectangles. Ce champ spécifie le nombre de rectangles qui sont définis dans le champ rect.

Valeur : le nombre de rectangles.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Obtient ou définit un tableau de rectangles NumRects qui définissent les zones de découpage. Le format de ces données est déterminé par le bit C dans le champ Flags.

Valeur : les rectangles.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Obtient ou définit un tableau de rectangles NumRects qui définissent les zones de découpage. Le format de ces données est déterminé par le bit C dans le champ Flags.

Valeur : les rectangles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

