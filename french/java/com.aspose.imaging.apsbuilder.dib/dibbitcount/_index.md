---
title: "DibBitCount"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération BitCount spécifie le nombre de bits qui définissent chaque pixel et le nombre maximal de couleurs dans un bitmap indépendant du dispositif (DIB)."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

L'énumération BitCount spécifie le nombre de bits qui définissent chaque pixel et le nombre maximal de couleurs dans un bitmap indépendant du dispositif (DIB).
## Champs

| Champ | Description |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | Le nombre de bits par pixel est indéfini. |
| [BIT_COUNT_1](#BIT-COUNT-1) | L'image est spécifiée avec deux couleurs. Chaque pixel du bitmap est représenté par un seul bit. |
| [BIT_COUNT_2](#BIT-COUNT-2) | L'image est spécifiée avec un maximum de 16 couleurs. |
| [BIT_COUNT_3](#BIT-COUNT-3) | L'image est spécifiée avec un maximum de 256 couleurs. |
| [BIT_COUNT_4](#BIT-COUNT-4) | L'image est spécifiée avec un maximum de 2^16 couleurs. |
| [BIT_COUNT_5](#BIT-COUNT-5) | Le bitmap a un maximum de 2^24 couleurs, et le champ Colors du DIB est NULL. |
| [BIT_COUNT_6](#BIT-COUNT-6) | Le bitmap a un maximum de 2^24 couleurs |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


Le nombre de bits par pixel est indéfini. L'image DOIT être au format JPEG ou PNG. Aucun de ces formats n'inclut de table de couleurs, ainsi cette valeur indique qu'aucune table de couleurs n'est présente. Voir [JFIF] et [RFC2083] pour plus d'informations concernant les formats de compression JPEG et PNG.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


L'image est spécifiée avec deux couleurs. Chaque pixel du bitmap est représenté par un seul bit. Si le bit est à 0, le pixel est affiché avec la couleur de la première entrée de la table de couleurs ; si le bit est à 1, le pixel a la couleur de la deuxième entrée de la table.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


L'image est spécifiée avec un maximum de 16 couleurs. Chaque pixel du bitmap est représenté par un index de 4 bits dans la table de couleurs, et chaque octet contient 2 pixels.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


L'image est spécifiée avec un maximum de 256 couleurs. Chaque pixel du bitmap est représenté par un index de 8 bits dans la table de couleurs, et chaque octet contient 1 pixel.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


L'image est spécifiée avec un maximum de 2^16 couleurs. Chaque pixel du bitmap est représenté par une valeur de 16 bits.

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


Le bitmap a un maximum de 2^24 couleurs, et le champ Colors du DIB est NULL. Chaque triplet de 3 octets dans le tableau bitmap représente les intensités relatives du bleu, du vert et du rouge, respectivement, pour un pixel. La table de couleurs Colors est utilisée pour optimiser les couleurs employées sur les appareils à palette, et DOIT contenir le nombre d'entrées spécifié par le champ ColorUsed de l'objet BitmapInfoHeader.

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


Le bitmap a un maximum de 2^24 couleurs

