# batch the same spine node for spine-cocos2dx v3.2

The spine-cocos2dx runtime can batch one spine node, no matter how many slots a node has, it's one draw call. But it can't batch multiple nodes with the same create files(json, atlas).

## Setup
1. Place the contents of a cocos2d-x version 3.2 distribution into the `spine-cocos2dx/3.2/cocos2dx` directory.