---
title: "EmfLogPenEx"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet LogPenEx spécifie la largeur du style et la couleur d'un crayon logique étendu."
type: docs
weight: 28
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

L'objet LogPenEx spécifie le style, la largeur et la couleur d'un stylo logique étendu.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Obtient ou définit le style du crayon |
| [setPenStyle(int value)](#setPenStyle-int-) | Obtient ou définit le style du crayon |
| [getWidth()](#getWidth--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la largeur de la ligne tracée par le crayon. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la largeur de la ligne tracée par le crayon. |
| [getBrushStyle()](#getBrushStyle--) | Obtient ou définit un entier non signé de 32 bits qui spécifie un style de brosse pour le crayon à partir de l'énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie un style de brosse pour le crayon à partir de l'énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | Obtient ou définit le motif de hachure de la brosse. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Obtient ou définit le motif de hachure de la brosse. |
| [getNumStyleEntities()](#getNumStyleEntities--) | Obtient le nombre d'éléments dans le tableau spécifié dans le champ StyleEntry. |
| [getStyleEntry()](#getStyleEntry--) | Obtient ou définit un tableau optionnel d'entiers non signés de 32 bits qui définit les longueurs des tirets et des espaces dans la ligne tracée par ce crayon, lorsque la valeur de PenStyle est PS\_USERSTYLE style de ligne pour le crayon. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | Obtient ou définit un tableau optionnel d'entiers non signés de 32 bits qui définit les longueurs des tirets et des espaces dans la ligne tracée par ce crayon, lorsque la valeur de PenStyle est PS\_USERSTYLE style de ligne pour le crayon. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Obtient ou définit le motif dib de la brosse. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit le motif dib de la brosse. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Obtient ou définit le style du crayon

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Obtient ou définit le style du crayon

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la largeur de la ligne tracée par le crayon. Si le type de crayon dans le champ PenStyle est PS\_GEOMETRIC, cette valeur est la largeur en unités logiques ; sinon, la largeur est spécifiée en unités de dispositif. Si le type de crayon dans le champ PenStyle est PS\_COSMETIC, cette valeur DOIT être 0x00000001.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la largeur de la ligne tracée par le crayon. Si le type de crayon dans le champ PenStyle est PS\_GEOMETRIC, cette valeur est la largeur en unités logiques ; sinon, la largeur est spécifiée en unités de dispositif. Si le type de crayon dans le champ PenStyle est PS\_COSMETIC, cette valeur DOIT être 0x00000001.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un style de brosse pour le crayon à partir de l'énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). Si le type de crayon dans le champ PenStyle est PS\_GEOMETRIC, cette valeur DOIT être soit BS\_SOLID soit BS\_HATCHED. La valeur de ce champ peut être BS\_NULL, mais uniquement si le style de ligne spécifié dans PenStyle est PS\_NULL. Le style BS\_NULL DOIT être utilisé pour spécifier une brosse qui n'a aucun effet.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un style de brosse pour le crayon à partir de l'énumération WMF BrushStyle ([MS-WMF] section 2.1.1.4). Si le type de crayon dans le champ PenStyle est PS\_GEOMETRIC, cette valeur DOIT être soit BS\_SOLID soit BS\_HATCHED. La valeur de ce champ peut être BS\_NULL, mais uniquement si le style de ligne spécifié dans PenStyle est PS\_NULL. Le style BS\_NULL DOIT être utilisé pour spécifier une brosse qui n'a aucun effet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8). L'interprétation de ce champ dépend de la valeur BrushStyle, comme indiqué dans le tableau plus loin dans cette section.

Valeur : la couleur ARGB de 32 bits

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Obtient ou définit un objet WMF ColorRef ([MS-WMF] section 2.2.2.8). L'interprétation de ce champ dépend de la valeur BrushStyle, comme indiqué dans le tableau plus loin dans cette section.

Valeur : la couleur ARGB de 32 bits

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Obtient ou définit le motif de hachure de la brosse. La définition de ce champ dépend de la valeur BrushStyle, comme indiqué dans le tableau plus loin dans cette section.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Obtient ou définit le motif de hachure de la brosse. La définition de ce champ dépend de la valeur BrushStyle, comme indiqué dans le tableau plus loin dans cette section.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


Obtient le nombre d'éléments dans le tableau spécifié dans le champ StyleEntry. Cette valeur DOIT être zéro si PenStyle ne spécifie pas PS\_USERSTYLE.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


Obtient ou définit un tableau optionnel d'entiers non signés de 32 bits qui définit les longueurs des tirets et des espaces dans la ligne tracée par ce crayon, lorsque la valeur de PenStyle est PS\_USERSTYLE style de ligne pour le crayon. Le tableau contient un nombre d'entrées spécifié par NumStyleEntries, mais il est utilisé comme s'il se répétait indéfiniment. La première entrée du tableau spécifie la longueur du premier tiret. La deuxième entrée spécifie la longueur du premier espace. Par la suite, les longueurs des tirets et des espaces alternent. Si le type de crayon dans le champ PenStyle est PS\_GEOMETRIC, les longueurs sont spécifiées en unités logiques ; sinon, les longueurs sont spécifiées en unités de dispositif.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


Obtient ou définit un tableau optionnel d'entiers non signés de 32 bits qui définit les longueurs des tirets et des espaces dans la ligne tracée par ce crayon, lorsque la valeur de PenStyle est PS\_USERSTYLE style de ligne pour le crayon. Le tableau contient un nombre d'entrées spécifié par NumStyleEntries, mais il est utilisé comme s'il se répétait indéfiniment. La première entrée du tableau spécifie la longueur du premier tiret. La deuxième entrée spécifie la longueur du premier espace. Par la suite, les longueurs des tirets et des espaces alternent. Si le type de crayon dans le champ PenStyle est PS\_GEOMETRIC, les longueurs sont spécifiées en unités logiques ; sinon, les longueurs sont spécifiées en unités de dispositif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Obtient ou définit le motif dib de la brosse.

Valeur : Le motif de brosse dib.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Obtient ou définit le motif dib de la brosse.

Valeur : Le motif de brosse dib.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

