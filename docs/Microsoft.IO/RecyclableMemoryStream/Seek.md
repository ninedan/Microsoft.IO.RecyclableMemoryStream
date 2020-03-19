# RecyclableMemoryStream.Seek method

Sets the position to the offset from the seek location

```csharp
public override long Seek(long offset, SeekOrigin loc)
```

| parameter | description |
| --- | --- |
| offset | How many bytes to move |
| loc | From where |

## Return Value

The new position

## Exceptions

| exception | condition |
| --- | --- |
| ObjectDisposedException | Object has been disposed |
| ArgumentOutOfRangeException | offset is larger than MaxStreamLength |
| ArgumentException | Invalid seek origin |
| IOException | Attempt to set negative position |

## See Also

* class [RecyclableMemoryStream](../RecyclableMemoryStream.md)
* namespace [Microsoft.IO](../../Microsoft.IO.RecyclableMemoryStream.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.IO.RecyclableMemoryStream.dll -->