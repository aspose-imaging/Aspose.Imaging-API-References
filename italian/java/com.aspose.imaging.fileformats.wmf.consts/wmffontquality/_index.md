---
title: "WmfFontQuality"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione FontQuality specifica quanto strettamente gli attributi del font logico debbano corrispondere a quelli del font fisico durante il rendering del testo."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

L'enumerazione FontQuality specifica quanto strettamente gli attributi del font logico debbano corrispondere a quelli del font fisico durante il rendering del testo.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Default](#Default) | Specifica che la qualità dei caratteri del font non è importante, quindi può essere usato DRAFT. |
| [Draft](#Draft) | Specifica che la qualità dei caratteri del font è meno importante rispetto alla corrispondenza degli attributi logici. |
| [Proof](#Proof) | Specifica che la qualità dei caratteri del font è più importante rispetto alla corrispondenza degli attributi logici. |
| [Nonantialiased](#Nonantialiased) | Specifica che l'anti-aliasing NON DEVE essere usato durante il rendering del testo |
| [Antialiased](#Antialiased) | Specifica che l'anti-aliasing DEVE essere usato durante il rendering del testo, se il font lo supporta. |
| [Cleartype](#Cleartype) | Specifica che l'anti-aliasing ClearType DEVE essere usato durante il rendering del testo, se il font lo supporta. |
### Default {#Default}
```
public static final byte Default
```


Specifica che la qualità dei caratteri del font non è importante, quindi può essere usato DRAFT.

### Draft {#Draft}
```
public static final byte Draft
```


Specifica che la qualità dei caratteri del font è meno importante rispetto alla corrispondenza degli attributi logici. Per i font rasterizzati, la scalatura DEVE essere abilitata, il che significa che sono disponibili più dimensioni del font.

### Proof {#Proof}
```
public static final byte Proof
```


Specifica che la qualità dei caratteri del font è più importante rispetto alla corrispondenza degli attributi logici. Per i font rasterizzati, la scalatura DEVE essere disabilitata e il font più vicino in dimensione DEVE essere scelto.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


Specifica che l'anti-aliasing NON DEVE essere usato durante il rendering del testo

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


Specifica che l'anti-aliasing DEVE essere usato durante il rendering del testo, se il font lo supporta.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


Specifica che l'anti-aliasing ClearType DEVE essere usato durante il rendering del testo, se il font lo supporta.

