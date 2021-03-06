
# Application.PointsToPixels Method (Word)

Converts a measurement from points to pixels. Returns the converted measurement as a  **Single** .


## Syntax

 _expression_ . **PointsToPixels**( **_Points_** , **_fVertical_** )

 _expression_ Required. A variable that represents an **[Application](d1cf6f8f-4e88-bf01-93b4-90a83f79cb44.md)** object.


### Parameters



|**Name**|**Required/Optional**|**Data Type**|**Description**|
|:-----|:-----|:-----|:-----|
| _Points_|Required| **Single**|The point value to be converted to pixels.|
| _fVertical_|Optional| **Variant**| **True** to return the result as vertical pixels; **False** to return the result as horizontal pixels.|

### Return Value

Single


## Example

This example displays the height and width in pixels of an object measured in points.


```vb
MsgBox "180x120 points is equivalent to " _ 
 &; PointsToPixels(180, False) &; "x" _ 
 &; PointsToPixels(120, True) _ 
 &; " pixels on this display."
```


## See also


#### Concepts


[Application Object](d1cf6f8f-4e88-bf01-93b4-90a83f79cb44.md)
