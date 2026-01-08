# zThemes Improvements

> [!NOTE]
> All new icons for **`zDark`** and **`zLight`** are included in the **`New-Icons.zip`** file.

During **`zThemes`** development—from the initial **`zDark`** through the final **`zLight`** revision—I discovered several enhancements that could improve FontForge's theme customization system. Though time-intensive, these changes would significantly benefit future theme developers.

## Unify tool palettes appearance and behavior

The tool pallets on the BitmapView should have the same appearance and behavior as the ones on the OutlineView.

![Tool palletes icons](Support-Images/zThemes_Improvements-1.png)

## Correct some icons usages and drop using duplicate icons

Make and share use of the icon files for the menus options `Set Color` and `Select by Color`

![Duplicated icons](Support-Images/zThemes_Improvements-2.png)

Set a different icon file (hintsclearhints.png) for the menu option `Clear Hints`

![Clear Hints icon](Support-Images/zThemes_Improvements-3.png)

Set the same icon file (overlaprm.png) to the menu option `Remove Overlap` in MetricsView (this option is currently using a duplicated icon file rmoverlap.png).

![Remove Overlap icon](Support-Images/zThemes_Improvements-4.png)

Below a list of files icnos that seem not used:

|    changeweight.png    |  fileclose2.png  |    paletteselectedbg.png    |
|:----------------------:|:----------------:|:---------------------------:|
| elementtilepath.png    | fliphor.png      | palettespirodisabled.png    |
| elementtilepattern.png | flipvert.png     | palettespiroup-selected.png |
| exclude.png            | inline.png       | rotate180.png               |
| extendcondense.png     | intersection.png | rotateccw.png               |
| fflogo.png             | oblique.png      | rotatecw.png                |
| fflogo13.png           | outline.png      | shadow.png                  |
| ffsplash1.png          | text12210.png    | skew.png                    |
| ffsplash2.png          | wireframe.png    | splash2019.png              |
| ffsplash3.png          |                  | rmoverlap.png*              |

> `rmoverlap.png` is in use, but is duplicate of `overlaprm.png`

## Apply the same icon for the same options on all views

Apply icon file viewlayers.png to `Layers` menu option on MetricsView.

![Menu Layers icon](Support-Images/zThemes_Improvements-5.png)

Apply icon file editrmundoes.png to `Remove Undoes` on BitmapView.

![Remove Undoes icon](Support-Images/zThemes_Improvements-6.png)

## Enable new interface icon customization

Apply new custom icons for the pointer and point indicators on the info bar in the CharView and the BitmapView.

![Info Bar indicator icons](Support-Images/zThemes_Improvements-7.png)

Replace and add new custom icons for `Expand Stroke` dialog.

![Expand Stroke icons](Support-Images/zThemes_Improvements-8.png)

---

[Released under MIT License](https://github.com/adolfo-ovalles/zThemes/blob/941fb1096e81c23282a2dec6c4c4e3698c5104c5/LICENSE) © 2025 Adolfo Ovalles.
