---
title: IsVisible
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Verifica se il punto specificato è contenuto allinterno di questoRegionaspose.imaging/region .
type: docs
weight: 90
url: /it/aspose.imaging/region/isvisible/
---
## IsVisible(float, float) {#isvisible_11}

Verifica se il punto specificato è contenuto all'interno di questo[`Region`](../../region) .

```csharp
public bool IsVisible(float x, float y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Single | La coordinata x del punto da verificare. |
| y | Single | La coordinata y del punto da verificare. |

### Valore di ritorno

Vero quando il punto specificato è contenuto all'interno di questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(PointF) {#isvisible_2}

Verifica se è specificato[`PointF`](../../pointf) la struttura è contenuta in questo[`Region`](../../region) .

```csharp
public bool IsVisible(PointF point)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | PointF | Il[`PointF`](../../pointf) struttura da testare. |

### Valore di ritorno

vero quando*point* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [PointF](../../pointf)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

Verifica se il punto specificato è contenuto all'interno di questo[`Region`](../../region)quando disegnato usando il specificato[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Single | La coordinata x del punto da verificare. |
| y | Single | La coordinata y del punto da verificare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

Vero quando il punto specificato è contenuto all'interno di questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

Verifica se è specificato[`PointF`](../../pointf) la struttura è contenuta in questo[`Region`](../../region)quando disegnato usando il specificato[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | PointF | Il[`PointF`](../../pointf) struttura da testare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

vero quando*point* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region) .

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Single | Coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | Single | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | Single | La larghezza del rettangolo da testare. |
| height | Single | L'altezza del rettangolo da testare. |

### Valore di ritorno

true quando una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region) oggetto; in caso contrario, falso.

### Guarda anche

* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

Verifica se qualsiasi parte dell'oggetto specificato[`RectangleF`](../../rectanglef) la struttura è contenuta in questo[`Region`](../../region) .

```csharp
public bool IsVisible(RectangleF rect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | RectangleF | Il[`RectangleF`](../../rectanglef) struttura da testare. |

### Valore di ritorno

true quando qualsiasi porzione di*rect* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [RectangleF](../../rectanglef)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region)quando disegnato usando il specificato[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Single | Coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | Single | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | Single | La larghezza del rettangolo da testare. |
| height | Single | L'altezza del rettangolo da testare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

true quando una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

Verifica se qualsiasi parte dell'oggetto specificato[`RectangleF`](../../rectanglef) la struttura è contenuta in questo[`Region`](../../region)quando disegnato usando il specificato[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | RectangleF | Il[`RectangleF`](../../rectanglef) struttura da testare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

vero quando*rect* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

Verifica se il punto specificato è contenuto all'interno di questo[`Region`](../../region) oggetto quando disegnato utilizzando l'oggetto specificato[`Graphics`](../../graphics) oggetto.

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Int32 | La coordinata x del punto da verificare. |
| y | Int32 | La coordinata y del punto da verificare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

true quando il punto specificato è contenuto all'interno di questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(Point) {#isvisible}

Verifica se è specificato[`Point`](../../point) la struttura è contenuta in questo[`Region`](../../region) .

```csharp
public bool IsVisible(Point point)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | Point | Il[`Point`](../../point) struttura da testare. |

### Valore di ritorno

vero quando*point* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [Point](../../point)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

Verifica se è specificato[`Point`](../../point) la struttura è contenuta in questo[`Region`](../../region)quando disegnato usando il specificato[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(Point point, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | Point | Il[`Point`](../../point) struttura da testare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

vero quando*point* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [Point](../../point)
* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region) .

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Int32 | Coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | Int32 | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | Int32 | La larghezza del rettangolo da testare. |
| height | Int32 | L'altezza del rettangolo da testare. |

### Valore di ritorno

true quando una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

Verifica se qualsiasi parte dell'oggetto specificato[`Rectangle`](../../rectangle) la struttura è contenuta in questo[`Region`](../../region) .

```csharp
public bool IsVisible(Rectangle rect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il[`Rectangle`](../../rectangle) struttura da testare. |

### Valore di ritorno

Questo metodo restituisce true quando qualsiasi parte di*rect* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [Rectangle](../../rectangle)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

Verifica se una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region)quando disegnato usando il specificato[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Int32 | Coordinata x dell'angolo superiore sinistro del rettangolo da testare. |
| y | Int32 | La coordinata y dell'angolo superiore sinistro del rettangolo da testare. |
| width | Int32 | La larghezza del rettangolo da testare. |
| height | Int32 | L'altezza del rettangolo da testare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

true quando una qualsiasi parte del rettangolo specificato è contenuta all'interno di questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

Verifica se qualsiasi parte dell'oggetto specificato[`Rectangle`](../../rectangle) la struttura è contenuta in questo[`Region`](../../region)quando disegnato usando il specificato[`Graphics`](../../graphics) .

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il[`Rectangle`](../../rectangle) struttura da testare. |
| g | Graphics | UN[`Graphics`](../../graphics) che rappresenta un contesto grafico. |

### Valore di ritorno

true quando qualsiasi parte del file*rect* è contenuto in questo[`Region`](../../region) ; in caso contrario, falso.

### Guarda anche

* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* class [Region](../../region)
* spazio dei nomi [Aspose.Imaging](../../region)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
