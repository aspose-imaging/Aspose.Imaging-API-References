---
title: Records
second_title: Aspose.Imaging para la referencia de la API de .NET
description: Obtiene o establece los registros.
type: docs
weight: 10
url: /es/net/aspose.imaging.fileformats.emf/metaimage/records/
---
## MetaImage.Records property

Obtiene o establece los registros.

```csharp
public virtual MetaObjectList Records { get; set; }
```

### El valor de la propiedad

Los registros.

### Ejemplos

Este ejemplo muestra cómo cargar una imagen WMF desde un archivo y enumerar todos sus registros.

```csharp
[C#]

string dir = "c:\\temp\\";

// El uso de Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    // Caché de datos para cargar todos los registros.
    wmfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", wmfImage.Records.Count);

    // La clave es un tipo de registro, el valor es el número de registros de ese tipo en la imagen WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Reunir estadísticas 
    foreach (Aspose.Imaging.FileFormats.Wmf.Objects.WmfObject obj in wmfImage.Records)
    {
        System.Type objType = obj.GetType();
        if (!types.ContainsKey(objType))
        {
            types.Add(objType, 1);
        }
        else
        {
            types[objType]++;
        }
    }

    // Imprimir estadísticas
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//La salida puede verse así:
//El número total de registros: 613
//Recuento de tipos de registro
//----------------------------------------------
//WmfSetBkMode: 1
//WmfSetTextAlign: 1
//WmfSetRop2: 1
//WmfSetWindowOrg: 1
//WmfEstablecerVentanaExt: 1
//WmfCreateBrushInDirect: 119
//WmfSeleccionarObjeto: 240
//WmfCreatePenInDirecto: 119
//WmfSetPolyFillMode: 1
//WmfPolyPolygon: 114
//WmfPolyLine: 7
//WmfEstablecerTextoColor: 2
//WmfCreateFontInDirect: 2
//WmfExtTextOut: 2
//WmfDibStrechBlt: 1
//WmfEof: 1
```

Este ejemplo muestra cómo cargar una imagen EMF desde un archivo y enumerar todos sus registros.

```csharp
[C#]

string dir = "c:\\temp\\";

// El uso de Aspose.Imaging.Image.Load es una forma unificada de cargar todo tipo de imágenes, incluido WMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    // Caché de datos para cargar todos los registros.
    emfImage.CacheData();
    System.Console.WriteLine("The total number of records: {0}", emfImage.Records.Count);

    // La clave es un tipo de registro, el valor es el número de registros de ese tipo en la imagen WMF.
    System.Collections.Generic.Dictionary<System.Type, int> types =
        new System.Collections.Generic.Dictionary<System.Type, int>();

    // Reunir estadísticas 
    foreach (Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRecord obj in emfImage.Records)
    {
        System.Type objType = obj.GetType();
        if (!types.ContainsKey(objType))
        {
            types.Add(objType, 1);
        }
        else
        {
            types[objType]++;
        }
    }

    // Imprimir estadísticas
    System.Console.WriteLine("Record Type                              Count");
    System.Console.WriteLine("----------------------------------------------");
    foreach (System.Collections.Generic.KeyValuePair<System.Type, int> entry in types)
    {
        string objectType = entry.Key.Name;
        string alignmentGap = new string(' ', 40 - objectType.Length);
        System.Console.WriteLine("{0}:{1}{2}", entry.Key.Name, alignmentGap, entry.Value);
    }
}

//La salida puede verse así:
// El número total de registros: 1188
//Recuento de tipos de registro
//----------------------------------------------
//EmfMetafileHeader: 1
//EmfSetBkMode: 1
//EmfSetTextAlign: 1
//EmfSetRop2: 1
//EmfSetWorldTransform: 1
//EmfExtSeleccionarClipRgn: 1
//EmfCreateBrushIndirecto: 113
//EmfSeleccionarObjeto: 240
//EmfCreatePluma: 116
//EmfSetPolyFillMode: 1
//EmfBeginPath: 120
//FemMoveToEx: 122
//FemPolyBezierTo16: 36
//LíneaEmfA: 172
//EmfCerrarFigura: 14
//EmfEndPath: 120
//EmfStrokeAndFillPath: 113
//EmfStrokePath: 7
//EmfEstablecerTextoColor: 2
//EmfExtCreateFontIndirectW: 2
//EmfExtTextOutW: 2
//EmfStretchBlt: 1
//FemEof: 1
```

### Ver también

* class [MetaObjectList](../../metaobjectlist)
* class [MetaImage](../../metaimage)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* asamblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
