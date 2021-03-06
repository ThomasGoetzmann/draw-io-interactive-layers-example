# draw-io-interactive-layers-example
Tutorial / Example on how to create an interactive map on draw.io
[Link to the example in draw.io](https://app.diagrams.net/#HThomasGoetzmann%2Fdraw-io-interactive-layers-example%2Fmain%2Finteractive-map-example.drawio)

## Layer toggling:

```
data:action/json,{"actions":[{"toggle": {"cells": ["REPLACE_WITH_ID_OF_YOUR_LAYER"]}}]}
```

![Toggle Layers Gif](toggle_layers.gif)

## Same but with Tags instead of Ids

1. Add the ```Tags``` plugin from ```Menu/Extras/Plugins```
2. Reload draw.io
3. Add tags to multiple shapes with ```Menu/Extras/HiddenTags```
```
data:action/json,{"actions":[{"toggle":{"tags":["REPLACE_WITH_ID_OF_YOUR_LAYER"]}}]}
```
![Tag multiple shapes Gif](tag_multiple_shapes.gif)

## Shapes highlighting: 

```
data:action/json,{"actions":[{"highlight": {"cells": ["SHAPE_ID_1", ""SHAPE_ID_2"]}}]}
```


