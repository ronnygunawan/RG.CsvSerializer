[![NuGet](https://img.shields.io/nuget/v/RG.CsvSerializer.svg)](https://www.nuget.org/packages/RG.CsvSerializer/)

# Installation
Package Manager Console:
```
Install-Package RG.CsvSerializer
```

# Usage
```csharp
using Csv;

// Serialize collection to CSV string
string csv = CsvSerializer.Serialize(items, withHeaders: true);

// Deserialize CSV string to array
Item[] items = CsvSerializer.Deserialize<Item>(csv, hasHeaders: true);
```
