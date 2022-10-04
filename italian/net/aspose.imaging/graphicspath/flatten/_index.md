---
title: Flatten
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati.
type: docs
weight: 90
url: /it/net/aspose.imaging/graphicspath/flatten/
---
## Flatten() {#flatten}

Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati.

```csharp
public void Flatten()
```

### Guarda anche

* class [GraphicsPath](../../graphicspath)
* spazio dei nomi [Aspose.Imaging](../../graphicspath)
* assemblea [Aspose.Imaging](../../../)

---

## Flatten(Matrix) {#flatten_1}

Applica la trasformazione specificata e quindi converte ogni curva in questa[`GraphicsPath`](../../graphicspath) in una sequenza di segmenti di linea collegati.

```csharp
public void Flatten(Matrix matrix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | Matrix | UN[`Matrix`](../../matrix) con cui trasformare questo[`GraphicsPath`](../../graphicspath) prima di appiattire. |

### Guarda anche

* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* spazio dei nomi [Aspose.Imaging](../../graphicspath)
* assemblea [Aspose.Imaging](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Converte ogni curva in questo[`GraphicsPath`](../../graphicspath) in una sequenza di segmenti di linea collegati.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | Matrix | UN[`Matrix`](../../matrix) con cui trasformare questo[`GraphicsPath`](../../graphicspath) prima di appiattire. |
| flatness | Single | Specifica l'errore massimo consentito tra la curva e la sua approssimazione appiattita. Il valore predefinito è 0,25. La riduzione del valore di planarità aumenterà il numero di segmenti di linea nell'approssimazione. |

### Guarda anche

* class [Matrix](../../matrix)
* class [GraphicsPath](../../graphicspath)
* spazio dei nomi [Aspose.Imaging](../../graphicspath)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->