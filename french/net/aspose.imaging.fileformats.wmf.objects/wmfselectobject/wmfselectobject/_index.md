---
title: WmfSelectObject
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Initialise une nouvelle instance duWmfSelectObjectaspose.imaging.fileformats.wmf.objects/wmfselectobject classe.
type: docs
weight: 10
url: /fr/net/aspose.imaging.fileformats.wmf.objects/wmfselectobject/wmfselectobject/
---
## WmfSelectObject(WmfGraphicObject) {#constructor_1}

Initialise une nouvelle instance du[`WmfSelectObject`](../../wmfselectobject) classe.

```csharp
public WmfSelectObject(WmfGraphicObject wmfObject)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| wmfObject | WmfGraphicObject | L'objet WMF. |

### Voir également

* class [WmfGraphicObject](../../wmfgraphicobject)
* class [WmfSelectObject](../../wmfselectobject)
* espace de noms [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfselectobject)
* Assemblée [Aspose.Imaging](../../../)

---

## WmfSelectObject() {#constructor}

Initialise une nouvelle instance du[`WmfSelectObject`](../../wmfselectobject) classe.

```csharp
public WmfSelectObject()
```

### Exemples

L'exemple suivant montre comment définir la couleur d'arrière-plan pour WMF. En fait, il dessine un rectangle de la couleur d'arrière-plan avant de dessiner tous les autres objets.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string inputFilePath = dir + "image2.wmf";
string outputFilePath = dir + "ChangeBackground_" + "image2.wmf";

using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    AddBackgroundRectangleWmf((Aspose.Imaging.FileFormats.Wmf.WmfImage)image, Aspose.Imaging.Color.Blue);
    image.Save(outputFilePath);
}

/// <summary>
/// Méthode d'assistance pour changer l'arrière-plan WMF. 
/// </summary>
public static void AddBackgroundRectangleWmf(Aspose.Imaging.FileFormats.Wmf.WmfImage image, Aspose.Imaging.Color color)
{
    image.CacheData();
    if (image.Records.Count < 1)
    {
        return;
    }

    //Définir le rectangle
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle rectangle = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfRectangle();
    rectangle.Rectangle = image.FrameBounds;

    //Définir le pinceau
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect brush = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfCreateBrushInDirect();
    brush.LogBrush = new Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogBrushEx();
    brush.LogBrush.Argb32ColorRef = color.ToArgb();

    //Sélectionner le pinceau
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject selectObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfSelectObject(brush);

    //Retirer le pinceau
    Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject deleteObject = new Aspose.Imaging.FileFormats.Wmf.Objects.WmfDeleteObject(brush);

    //Ajouter des enregistrements
    image.Records.Insert(0, brush);
    image.Records.Insert(1, selectObject);
    image.Records.Insert(2, rectangle);
    image.Records.Insert(3, deleteObject);
}
```

### Voir également

* class [WmfSelectObject](../../wmfselectobject)
* espace de noms [Aspose.Imaging.FileFormats.Wmf.Objects](../../wmfselectobject)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->