---
title: Font
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neueFontaspose.imaging/font die die angegebene vorhandene verwendetFontaspose.imaging/font undFontStyleaspose.imaging/fontstyle Aufzählung.
type: docs
weight: 10
url: /de/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

Initialisiert eine neue[`Font`](../../font) die die angegebene vorhandene verwendet[`Font`](../../font) und[`FontStyle`](../../fontstyle) Aufzählung.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prototype | Font | Die bestehende[`Font`](../../font) aus der das Neue entsteht[`Font`](../../font). |
| newStyle | FontStyle | Das[`FontStyle`](../../fontstyle)auf das Neue anwenden[`Font`](../../font) . Mehrere Werte der[`FontStyle`](../../fontstyle) Enumeration kann mit dem OR-Operator kombiniert werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *prototype* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* namensraum [Aspose.Imaging](../../font)
* Montage [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

Initialisiert eine neue[`Font`](../../font) unter Verwendung einer bestimmten Größe. Der Zeichensatz ist eingestellt aufDefault , die Grafikeinheit anPoint , den Schriftstil zuRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../../font) Name. |
| emSize | Single | Die Em-Größe der neuen Schriftart in Punkt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* class [Font](../../font)
* namensraum [Aspose.Imaging](../../font)
* Montage [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initialisiert eine neue[`Font`](../../font) unter Verwendung einer bestimmten Größe und eines bestimmten Stils. Der Zeichensatz ist eingestellt aufDefault , die Grafikeinheit anPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../../font) Name. |
| emSize | Single | Die Em-Größe der neuen Schriftart in Punkt. |
| style | FontStyle | Das[`FontStyle`](../../fontstyle) der neuen Schriftart. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* namensraum [Aspose.Imaging](../../font)
* Montage [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initialisiert eine neue[`Font`](../../font) unter Verwendung einer bestimmten Größe und Einheit. Der Zeichensatz ist eingestellt aufDefault , der Stil ist eingestellt aufRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../../font) Name. |
| emSize | Single | Die em-Größe der neuen Schriftart in den von der angegebenen Einheiten*unit* Parameter. |
| unit | GraphicsUnit | Das[`GraphicsUnit`](../../graphicsunit) der neuen Schriftart. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* namensraum [Aspose.Imaging](../../font)
* Montage [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initialisiert eine neue[`Font`](../../font) Verwenden einer bestimmten Größe, eines Stils, einer Einheit und eines Zeichensatzes.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../../font) Name. |
| emSize | Single | Die em-Größe der neuen Schriftart in den von der angegebenen Einheiten*unit* Parameter. |
| style | FontStyle | Das[`FontStyle`](../../fontstyle) der neuen Schriftart. |
| unit | GraphicsUnit | Das[`GraphicsUnit`](../../graphicsunit) der neuen Schriftart. |
| characterSet | CharacterSet | Ein für diese Schriftart zu verwendender Zeichensatz. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* namensraum [Aspose.Imaging](../../font)
* Montage [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initialisiert eine neue[`Font`](../../font) unter Verwendung einer bestimmten Größe, eines Stils und einer Einheit.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../../font) Name. |
| emSize | Single | Die em-Größe der neuen Schriftart in den von der angegebenen Einheiten*unit* Parameter. |
| style | FontStyle | Das[`FontStyle`](../../fontstyle) der neuen Schriftart. |
| unit | GraphicsUnit | Das[`GraphicsUnit`](../../graphicsunit) der neuen Schriftart. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* namensraum [Aspose.Imaging](../../font)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
