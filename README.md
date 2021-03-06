# Scrap Mechanic Image Maker

## How to use:

```java
  File imageFile = File.loadFromClasspath("Image.png");
  Blueprint blueprint = SMIM.createBlueprint(imageFile);
  blueprint.export(ExportFormat.JSON, File.create("Blueprint.json"));
```
### External libraries:
- [JSON-Simple](https://code.google.com/archive/p/json-simple/ "JSON-Simple")
