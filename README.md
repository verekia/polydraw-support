# 🔺 PolyDraw.app

[**PolyDraw**](https://polydraw.app) is currently not open source, but you can submit issues and feedback in this repository.

## Resolving your JSON data

Here is what a PolyDraw exported JSON file looks like:

```json
{
  "points": [
    { "id": "IXXp8", "x": 21.4, "y": 54.6 },
    { "id": "h8axL", "x": 25.4, "y": 71.6 },
    { "id": "A8LYy", "x": 42.8, "y": 82.4 },
    { "id": "05EtD", "x": 69.6, "y": 81.2 }
  ],
  "pointGroups": [
    {
      "id": "G5kjN",
      "pointIds": ["IXXp8", "h8axL", "A8LYy", "05EtD"],
      "name": "forest1"
    }
  ],
  "superGroups": [{ "pointGroupIds": ["G5kjN"], "name": "forests" }]
}
```

In your application code, you will likely want to resolve `pointIds` and `pointGroupIds` to have direct access to the point and point group objects.

TODO: Add code sample.
