---
Title: "Examples of VBA Constants"
layout: single
classes: wide
categories:
  - vba
tags:
  - developer
date: 2018-11-16
sidebar:
  title: "Popular Links"
  nav: sidebar-sample

---
Some examples of VBA constants, useful when developing programs / add-ins.

```vb
' Using a double line when creating a string in code, just type vbDoubleLine
Public Const vbDoubleLine = vbNewLine & vbNewLine

' Using Named Colours for set colour schemes
Note that the colour values are Longs

' ## Colour Constants
Public Enum RGBLongColour
    rgbExcelGreen = 4551200
    rgbWordBlue = 9522462
    rgbOutlookBlue = 11956254
    rgbPowerPointRed = 4551200
End Enum

' ## Example
Sub SelectionFill()
    Selection.Interior.Color = rgbExcelGreen
End Sub
```
