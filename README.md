# Scrap Mechanic Image Maker [![License](https://img.shields.io/github/license/EddeDev/SMIM.svg)](https://github.com/EddeDev/SMIM/blob/main/LICENSE)

## How to use:

```java
  File imageFile = File.loadFromClasspath("Image.png");
  Blueprint blueprint = SMIM.createBlueprint(imageFile);
  blueprint.export(ExportFormat.JSON, File.create("Blueprint.json"));
```
### External libraries:
- [JSON-Simple](https://code.google.com/archive/p/json-simple/ "JSON-Simple")
