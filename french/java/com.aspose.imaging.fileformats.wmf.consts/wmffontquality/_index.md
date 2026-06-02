---
title: "WmfFontQuality"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération FontQuality spécifie à quel point les attributs de la police logique doivent correspondre à ceux de la police physique lors du rendu du texte."
type: docs
weight: 19
url: /fr/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

L'énumération FontQuality spécifie à quel point les attributs de la police logique doivent correspondre à ceux de la police physique lors du rendu du texte.
## Champs

| Champ | Description |
| --- | --- |
| [Default](#Default) | Spécifie que la qualité des caractères de la police n'a pas d'importance, donc DRAFT peut être utilisée. |
| [Draft](#Draft) | Spécifie que la qualité des caractères de la police est moins importante que la correspondance des attributs logiques. |
| [Proof](#Proof) | Spécifie que la qualité des caractères de la police est plus importante que la correspondance des attributs logiques. |
| [Nonantialiased](#Nonantialiased) | Spécifie que l'anticrénelage NE DOIT PAS être utilisé lors du rendu du texte |
| [Antialiased](#Antialiased) | Spécifie que l'anticrénelage DOIT être utilisé lors du rendu du texte, si la police le supporte. |
| [Cleartype](#Cleartype) | Spécifie que l'anticrénelage ClearType DOIT être utilisé lors du rendu du texte, si la police le supporte. |
### Default {#Default}
```
public static final byte Default
```


Spécifie que la qualité des caractères de la police n'a pas d'importance, donc DRAFT peut être utilisée.

### Draft {#Draft}
```
public static final byte Draft
```


Spécifie que la qualité des caractères de la police est moins importante que la correspondance des attributs logiques. Pour les polices rasterisées, le redimensionnement DOIT être activé, ce qui signifie que davantage de tailles de police sont disponibles.

### Proof {#Proof}
```
public static final byte Proof
```


Spécifie que la qualité des caractères de la police est plus importante que la correspondance des attributs logiques. Pour les polices rasterisées, le redimensionnement DOIT être désactivé, et la police la plus proche en taille DOIT être choisie.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


Spécifie que l'anticrénelage NE DOIT PAS être utilisé lors du rendu du texte

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


Spécifie que l'anticrénelage DOIT être utilisé lors du rendu du texte, si la police le supporte.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


Spécifie que l'anticrénelage ClearType DOIT être utilisé lors du rendu du texte, si la police le supporte.

