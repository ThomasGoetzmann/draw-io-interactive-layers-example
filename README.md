# draw-io-interactive-layers-example
Tutorial / Example on how to create an interactive map on draw.io

## Layer toggling:

```
data:action/json,{"actions":[{"toggle": {"cells": ["REPLACE_WITH_ID_OF_YOUR_LAYER"]}}]}
```

## Same but with Tags instead of Ids

1. Add the ```Tags``` plugin from ```Menu/Extras/Plugins```
2. Reload draw.io
3. Add tags to multiple shapes with ```Menu/Extras/HiddenTags```
```
data:action/json,{"actions":[{"toggle":{"tags":["REPLACE_WITH_ID_OF_YOUR_LAYER"]}}]}
```

## Shapes highlighting: 

```
data:action/json,{"actions":[{"highlight": {"cells": ["SHAPE_ID_1", ""SHAPE_ID_2"]}}]}
```


