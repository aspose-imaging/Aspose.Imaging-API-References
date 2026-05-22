---
title: "MetaImage.GetMissedFonts"
second_title: "Aspose.Imaging for .NET API 参考"
description: "MetaImage 方法。返回在元文件中使用但未找到的字体列表"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.emf/metaimage/getmissedfonts/
---
## MetaImage.GetMissedFonts method

返回在元文件中使用但未找到的字体列表。

```csharp
public string[] GetMissedFonts()
```

### 返回值

字体列表

## 示例

以下示例展示了如何打印 WMF/EMF 图像中已使用和缺失的字体信息。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3544";

// 使所有字体不可访问
string[] fontDirectories = Aspose.Imaging.FontSettings.GetFontsFolders();
Aspose.Imaging.FontSettings.SetFontsFolder("empty");
string[] files = new string[]
{
    "TestWmfText.wmf",
    "TestEmfFonts.emf",
    "TestEmfPlusFonts.emf",
};

try
{
    foreach (string file in files)
    {
        System.Console.WriteLine("========== {0} ==========", file);
        using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, file)))
        {
            string[] used = image.GetUsedFonts();
            foreach (string it in used)
            {
                System.Console.WriteLine("Used font: " + it);
            }

            string[] missed = image.GetMissedFonts();
            foreach (string it in missed)
            {
                System.Console.WriteLine("Missed font: " + it);
            }

            int ui = 0, mi = 0;
            foreach (string it in used)
            {
                if (it.Contains("Times"))
                {
                    ui++;
                    continue;
                }

                if (used[ui] != missed[mi])
                {
                    throw new System.Exception("Font lists must be equal!");
                }

                ui++; mi++;
            }
        }
    }
}
finally
{
    Aspose.Imaging.FontSettings.SetFontsFolders(fontDirectories, true);
}

// STDOUT 日志可能如下所示：
//========== TestWmfText.wmf ==========
//使用的字体：Garamond
//使用的字体：Arial
//使用的字体：Bookman Old Style
//使用的字体：Comic Sans MS
//使用的字体：Courier
//使用的字体：Courier New
//使用的字体：Impact
//使用的字体：Modern
//使用的字体：MS Sans Serif
//使用的字体：MS Serif
//使用的字体：Small Fonts
//使用的字体: Symbol
//使用的字体: Tahoma
//使用的字体: Times New Roman
//使用的字体: Verdana
//使用的字体: Wingdings
//缺失的字体: Garamond
//缺失的字体: Arial
//缺失的字体: Bookman Old Style
//缺失的字体: Comic Sans MS
//缺失的字体: Courier
//缺失的字体: Courier New
//缺失的字体: Impact
//缺失的字体: Modern
//缺失的字体: MS Sans Serif
//缺失的字体: MS Serif
//缺失的字体: Small Fonts
//缺失的字体: Symbol
//缺失的字体: Tahoma
//缺失的字体: Verdana
//缺失的字体: Wingdings
//========== TestEmfFonts.emf ==========
//使用的字体：Arial
//使用的字体: Verdana
//使用的字体: Times New Roman
//使用的字体: Symbol
//缺失的字体: Arial
//缺失的字体: Verdana
//缺失的字体: Symbol
//========== TestEmfPlusFonts.emf ==========
//使用的字体: MICROSOFT SANS SERIF
//缺失的字体: MICROSOFT SANS SERIF
```

### 另请参见

* class [MetaImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf](../../metaimage/)
* assembly [Aspose.Imaging](../../../)


