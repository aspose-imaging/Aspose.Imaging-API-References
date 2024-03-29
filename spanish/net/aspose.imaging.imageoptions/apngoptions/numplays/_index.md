---
title: NumPlays
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece el número de veces que se repite la animación. 0 indica un bucle infinito.
type: docs
weight: 30
url: /es/net/aspose.imaging.imageoptions/apngoptions/numplays/
---
## ApngOptions.NumPlays property

Obtiene o establece el número de veces que se repite la animación. 0 indica un bucle infinito.

```csharp
public int NumPlays { get; set; }
```

### El valor de la propiedad

El número de veces que se repite.

### Ejemplos

El siguiente ejemplo muestra cómo exportar al formato de archivo APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Exportar a animación APNG con ciclos de animación ilimitados por defecto
    image.Save("Animation1.webp.png", new ApngOptions());
    // Configuración de ciclos de animación
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 ciclos
}
```

### Ver también

* class [ApngOptions](../../apngoptions)
* espacio de nombres [Aspose.Imaging.ImageOptions](../../apngoptions)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
