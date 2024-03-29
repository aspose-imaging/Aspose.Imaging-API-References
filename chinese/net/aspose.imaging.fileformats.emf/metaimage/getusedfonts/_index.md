---
title: GetUsedFonts
second_title: Aspose.Imaging for .NET API 参考
description: 返回在元文件中使用的字体列表
type: docs
weight: 40
url: /zh/net/aspose.imaging.fileformats.emf/metaimage/getusedfonts/
---
## MetaImage.GetUsedFonts method

返回在元文件中使用的字体列表。

```csharp
public abstract string[] GetUsedFonts()
```

### 返回值

字体列表

### 例子

以下示例显示如何在 WMF/EMF 图像中打印有关已使用和未使用字体的信息。

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
//使用字体：Comic Sans MS
//使用字体：Courier
//使用字体：Courier New
//使用的字体：Impact
//使用的字体：现代
//使用的字体：MS Sans Serif
//使用的字体：MS Serif
//使用的字体：小字体
//使用的字体：符号
//使用的字体：Tahoma
//使用字体：Times New Roman
//使用的字体：Verdana
//使用的字体：Wingdings
//错过的字体：Garamond
//错过的字体：Arial
//错过的字体：Bookman Old Style
//错过的字体：Comic Sans MS
//错过的字体：Courier
//错过的字体：Courier New
//错过的字体：Impact
//错过的字体：现代
//错过的字体：MS Sans Serif
//错过的字体：MS Serif
//错过的字体：小字体
//错过的字体：符号
//错过的字体：Tahoma
//错过的字体：Verdana
//错过的字体：Wingdings
//========== TestEmfFonts.emf ==========
//使用的字体：Arial
//使用的字体：Verdana
//使用字体：Times New Roman
//使用的字体：符号
//错过的字体：Arial
//错过的字体：Verdana
//错过的字体：符号
//========== TestEmfPlusFonts.emf ==========
//使用的字体：MICROSOFT SANS SERIF
//错过的字体：MICROSOFT SANS SERIF
```

### 也可以看看

* class [MetaImage](../../metaimage)
* 命名空间 [Aspose.Imaging.FileFormats.Emf](../../metaimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
