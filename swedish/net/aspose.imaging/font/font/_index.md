---
title: Font
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en nyFontaspose.imaging/font som använder den angivna befintligaFontaspose.imaging/font ochFontStyleaspose.imaging/fontstyle uppräkning.
type: docs
weight: 10
url: /sv/net/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

Initierar en ny[`Font`](../../font) som använder den angivna befintliga[`Font`](../../font) och[`FontStyle`](../../fontstyle) uppräkning.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prototype | Font | Det existerande[`Font`](../../font) varifrån man skapar det nya[`Font`](../../font). |
| newStyle | FontStyle | De[`FontStyle`](../../fontstyle)att ansöka om det nya[`Font`](../../font) . Flera värden av[`FontStyle`](../../fontstyle) uppräkning kan kombineras med OR-operatorn. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *prototype* är inget. |

### Se även

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* namnutrymme [Aspose.Imaging](../../font)
* hopsättning [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

Initierar en ny[`Font`](../../font) med en angiven storlek. Teckenuppsättningen är inställd påDefault , grafikenheten tillPoint , teckensnittsstilen tillRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av[`Font`](../../font) namn. |
| emSize | Single | Em-storleken, i poäng, för det nya teckensnittet. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, värderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är inget. |

### Se även

* class [Font](../../font)
* namnutrymme [Aspose.Imaging](../../font)
* hopsättning [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initierar en ny[`Font`](../../font) med en specificerad storlek och stil. Teckenuppsättningen är inställd påDefault , grafikenheten tillPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av[`Font`](../../font) namn. |
| emSize | Single | Em-storleken, i poäng, för det nya teckensnittet. |
| style | FontStyle | De[`FontStyle`](../../fontstyle) av det nya typsnittet. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, värderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är inget. |

### Se även

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* namnutrymme [Aspose.Imaging](../../font)
* hopsättning [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initierar en ny[`Font`](../../font) med en specificerad storlek och enhet. Teckenuppsättningen är inställd påDefault , är stilen inställd påRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av[`Font`](../../font) namn. |
| emSize | Single | Em-storleken på det nya teckensnittet i de enheter som anges av*unit* parameter. |
| unit | GraphicsUnit | De[`GraphicsUnit`](../../graphicsunit) av det nya typsnittet. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, värderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är inget. |

### Se även

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* namnutrymme [Aspose.Imaging](../../font)
* hopsättning [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initierar en ny[`Font`](../../font) med en specificerad storlek, stil, enhet och teckenuppsättning.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av[`Font`](../../font) namn. |
| emSize | Single | Em-storleken på det nya teckensnittet i de enheter som anges av*unit* parameter. |
| style | FontStyle | De[`FontStyle`](../../fontstyle) av det nya typsnittet. |
| unit | GraphicsUnit | De[`GraphicsUnit`](../../graphicsunit) av det nya typsnittet. |
| characterSet | CharacterSet | En teckenuppsättning att använda för detta teckensnitt. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, värderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är inget. |

### Se även

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* namnutrymme [Aspose.Imaging](../../font)
* hopsättning [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initierar en ny[`Font`](../../font) använder en specificerad storlek, stil och enhet.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av[`Font`](../../font) namn. |
| emSize | Single | Em-storleken på det nya teckensnittet i de enheter som anges av*unit* parameter. |
| style | FontStyle | De[`FontStyle`](../../fontstyle) av det nya typsnittet. |
| unit | GraphicsUnit | De[`GraphicsUnit`](../../graphicsunit) av det nya typsnittet. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, värderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är inget. |

### Se även

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* namnutrymme [Aspose.Imaging](../../font)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
