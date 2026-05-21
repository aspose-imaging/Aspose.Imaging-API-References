---
title: "DibBitCount"
second_title: "Aspose.Imaging för Java API-referens"
description: "BitCount-enumerationen specificerar antalet bitar som definierar varje pixel och det maximala antalet färger i en enhetsoberoende bitmap DIB."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

BitCount‑enumerationen anger antalet bitar som definierar varje pixel och det maximala antalet färger i en enhetoberoende bitmap (DIB).
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | Antalet bitar per pixel är odefinierat. |
| [BIT_COUNT_1](#BIT-COUNT-1) | Bilden är specificerad med två färger. Varje pixel i bitmapen representeras av en enda bit. |
| [BIT_COUNT_2](#BIT-COUNT-2) | Bilden är specificerad med högst 16 färger. |
| [BIT_COUNT_3](#BIT-COUNT-3) | Bilden är specificerad med högst 256 färger. |
| [BIT_COUNT_4](#BIT-COUNT-4) | Bilden är specificerad med högst 2^16 färger. |
| [BIT_COUNT_5](#BIT-COUNT-5) | Bitmapen har högst 2^24 färger, och färgfältet i DIB är NULL. |
| [BIT_COUNT_6](#BIT-COUNT-6) | Bitmapen har högst 2^24 färger |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


Antalet bitar per pixel är odefinierat. Bilden SKA vara i antingen JPEG- eller PNG-format. Ingen av dessa format innehåller en färgtabell, så detta värde anger att ingen färgtabell finns. Se [JFIF] och [RFC2083] för mer information om JPEG- och PNG-komprimeringsformat.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


Bilden är specificerad med två färger. Varje pixel i bitmapen representeras av en enda bit. Om biten är nollställd visas pixeln med färgen från den första posten i färgtabellen; om biten är satt har pixeln färgen från den andra posten i tabellen.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


Bilden är specificerad med högst 16 färger. Varje pixel i bitmapen representeras av ett 4-bitars index i färgtabellen, och varje byte innehåller 2 pixlar.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


Bilden är specificerad med högst 256 färger. Varje pixel i bitmapen representeras av ett 8-bitars index i färgtabellen, och varje byte innehåller 1 pixel.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


Bilden är specificerad med högst 2^16 färger. Varje pixel i bitmapen representeras av ett 16-bitars värde

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


Bitmapen har högst 2^24 färger, och Colors-fältet i DIB är NULL. Varje 3-byte-trippel i bitmap‑arrayen representerar de relativa intensiteterna för blå, grön och röd, i den ordningen, för en pixel. Colors-färgtabellen används för att optimera färger som används på palettbaserade enheter, och MÅSTE innehålla det antal poster som anges av ColorUsed-fältet i BitmapInfoHeader‑objektet.

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


Bitmapen har högst 2^24 färger

