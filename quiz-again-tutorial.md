# Robot Quiz Coding Assignment

## Make code which reaches the goal @unplugged

This coding assignment is worth 5 points:
1. 1 Point Earned if Code Runs without Errors
2. 1 Point Earned if Robot Reaches the Goal and Collects all the Coins.
3. 2 Points for using 2 of the following: Function, For Loop or If statement
4. 1 Point Earned if Function, For Loop or If Statement help to shorten your code significantly


## Make code which reaches the goal

This coding assignment is worth 5 points:
1. 1 Point Earned if Code Runs without Errors
2. 1 Point Earned if Robot Reaches the Goal and Collects all the Coins.
3. 2 Points for using 2 of the following: Function, For Loop or If statement
4. 1 Point Earned if Function, For Loop or If Statement help to shorten your code significantly
   
Use the commands and conditions in the robot category.
```python
    robot.begin_screen()
    robot.move_forward()
    robot.turn_right()
    robot.turn_left()
    robot.place_coin()
    robot.collect_coin()
    robot.detect_coin()
    robot.can_move("")
```

## Functions, Loops and If Statements

2 Points are Earned For for using 2 of the following: Function, For Loop or If statement

```python
  def do_something():
    pass

  for i in range(4):
    pass

  if robot.detect_coin():
    pass

  if robot.can_move("forward"):
    pass
  else:
    pass

  #Update Test 8:49
```

## Share your work to Google Classroom  

Be sure to share your code by clicking the share icon and sharing the link to Google Classroom.
![Share Icon](https://github.com/MrDGuy/robot-quiz-code-assignment-1/blob/24c88c502ccd146fc1be1352949c18ee918a8f30/share-icon.png "Share Icon" )

```assetjson
{
  "README.md": " ",
  "assets.json": "",
  "main.blocks": "<xml xmlns=\"https://developers.google.com/blockly/xml\"><block type=\"pxt-on-start\" x=\"0\" y=\"0\"></block></xml>",
  "main.py": "tiles.load_map(tiles.create_map(tilemap(\"\"\"level1\"\"\")))\nrobot.begin_screen()\nrobot.turn_right()\nrobot.move_forward()\n",
  "main.ts": "tiles.loadMap(tiles.createMap(tilemap`level1`))\nrobot.beginScreen()\nrobot.turnRight()\nrobot.moveForward()\n",
  "pxt.json": "{\n    \"name\": \"Robot Quiz Again coding Assignment Assets\",\n    \"description\": \"\",\n    \"dependencies\": {\n        \"device\": \"*\",\n        \"Robot Extension\": \"github:MrDGuy/robot-extension#9c77349a3fe19cbb531500cdbc71c8ad1443b174\"\n    },\n    \"files\": [\n        \"main.blocks\",\n        \"main.ts\",\n        \"README.md\",\n        \"assets.json\",\n        \"tilemap.g.jres\",\n        \"tilemap.g.ts\",\n        \"main.py\"\n    ],\n    \"targetVersions\": {\n        \"branch\": \"v1.13.34\",\n        \"tag\": \"v1.13.34\",\n        \"commits\": \"https://github.com/microsoft/pxt-arcade/commits/e71dac8f868571e88292e0425471636294d16b32\",\n        \"target\": \"1.13.34\",\n        \"pxt\": \"9.1.8\"\n    },\n    \"preferredEditor\": \"pyprj\"\n}\n",
  "tilemap.g.jres": "{\n    \"tile1\": {\n        \"data\": \"hwQQABAAAAD//////////09ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPRPRERERERE9E9ERERERET0T0RERERERPT//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"startTile\"\n    },\n    \"tile2\": {\n        \"data\": \"hwQQABAAAAD//////////393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/d/d3d3d3d39393d3d3d3f3f3d3d3d3d/f//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"coinTile\"\n    },\n    \"tile3\": {\n        \"data\": \"hwQQABAAAAD//////////4+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPiPiIiIiIiI+I+IiIiIiIj4j4iIiIiIiPj//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"goalTile\"\n    },\n    \"transparency16\": {\n        \"data\": \"hwQQABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true\n    },\n    \"tile4\": {\n        \"data\": \"hwQQABAAAAD//////////x8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfEfERERERER8R8RERERERHxHxEREREREfH//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"floorTile\"\n    },\n    \"tile5\": {\n        \"data\": \"hwQQABAAAAD//////////7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/u/u7u7u7u7+7+7u7u7u7v7v7u7u7u7u/v//////////w==\",\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"tilemapTile\": true,\n        \"displayName\": \"wallTile\"\n    },\n    \"level1\": {\n        \"id\": \"level1\",\n        \"mimeType\": \"application/mkcd-tilemap\",\n        \"data\": \"MTAwYTAwMDcwMDA2MDcwNzBlMDcwNzBlMDcwNzA4MGMwNDAyMDQwNTA0MDIwNDA1MDkwYzA0MDUwNDA1MDQwNTA0MDUwOTExMDQwNTA0MDUwNDA1MDQwNTEwMGMwNDA1MDQwNTA0MDUwNDA1MDkwYzAxMDUwNDAyMDQwNTA0MDMwOTBiMGQwZDBmMGQwZDBmMGQwZDBhMjIyMjIyMjIyMjAyMDAwMjAwMjIwMjAyMDIwMjIyMDIwMjAyMDIyMjAyMDIwMjAyMjIwMjAyMDAwMjIwMjIyMjIyMjIyMg==\",\n        \"tileset\": [\n            \"myTiles.transparency16\",\n            \"myTiles.tile1\",\n            \"myTiles.tile2\",\n            \"myTiles.tile3\",\n            \"myTiles.tile4\",\n            \"myTiles.tile5\",\n            \"sprites.dungeon.greenOuterNorthWest\",\n            \"sprites.dungeon.greenOuterNorth0\",\n            \"sprites.dungeon.greenOuterNorthEast\",\n            \"sprites.dungeon.greenOuterEast0\",\n            \"sprites.dungeon.greenOuterSouthWest\",\n            \"sprites.dungeon.greenOuterSouthEast\",\n            \"sprites.dungeon.greenOuterWest0\",\n            \"sprites.dungeon.greenOuterSouth1\",\n            \"sprites.dungeon.greenOuterNorth2\",\n            \"sprites.dungeon.greenOuterSouth2\",\n            \"sprites.dungeon.greenOuterEast2\",\n            \"sprites.dungeon.greenOuterWest2\"\n        ],\n        \"displayName\": \"level1\"\n    },\n    \"level2\": {\n        \"id\": \"level2\",\n        \"mimeType\": \"application/mkcd-tilemap\",\n        \"data\": \"MTAxMDAwMTAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMA==\",\n        \"tileset\": [\n            \"myTiles.transparency16\"\n        ],\n        \"displayName\": \"level2\"\n    },\n    \"*\": {\n        \"mimeType\": \"image/x-mkcd-f4\",\n        \"dataEncoding\": \"base64\",\n        \"namespace\": \"myTiles\"\n    }\n}",
  "tilemap.g.ts": "// Auto-generated code. Do not edit.\nnamespace myTiles {\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile1 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile2 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile3 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const transparency16 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile4 = image.ofBuffer(hex``);\n    //% fixedInstance jres blockIdentity=images._tile\n    export const tile5 = image.ofBuffer(hex``);\n\n    helpers._registerFactory(\"tilemap\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n            case \"level1\":\n            case \"level1\":return tiles.createTilemap(hex`0a0007000607070e07070e0707080c0402040504020405090c040504050405040509110405040504050405100c0405040504050405090c0105040204050403090b0d0d0f0d0d0f0d0d0a`, img`\n2 2 2 2 2 2 2 2 2 2 \n2 . . . 2 . . . 2 2 \n2 . 2 . 2 . 2 . 2 2 \n2 . 2 . 2 . 2 . 2 2 \n2 . 2 . 2 . 2 . 2 2 \n2 . 2 . . . 2 . . 2 \n2 2 2 2 2 2 2 2 2 2 \n`, [myTiles.transparency16,myTiles.tile1,myTiles.tile2,myTiles.tile3,myTiles.tile4,myTiles.tile5,sprites.dungeon.greenOuterNorthWest,sprites.dungeon.greenOuterNorth0,sprites.dungeon.greenOuterNorthEast,sprites.dungeon.greenOuterEast0,sprites.dungeon.greenOuterSouthWest,sprites.dungeon.greenOuterSouthEast,sprites.dungeon.greenOuterWest0,sprites.dungeon.greenOuterSouth1,sprites.dungeon.greenOuterNorth2,sprites.dungeon.greenOuterSouth2,sprites.dungeon.greenOuterEast2,sprites.dungeon.greenOuterWest2], TileScale.Sixteen);\n            case \"level2\":\n            case \"level2\":return tiles.createTilemap(hex`1000100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000`, img`\n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n. . . . . . . . . . . . . . . . \n`, [myTiles.transparency16], TileScale.Sixteen);\n        }\n        return null;\n    })\n\n    helpers._registerFactory(\"tile\", function(name: string) {\n        switch(helpers.stringTrim(name)) {\n            case \"startTile\":\n            case \"tile1\":return tile1;\n            case \"coinTile\":\n            case \"tile2\":return tile2;\n            case \"goalTile\":\n            case \"tile3\":return tile3;\n            case \"transparency16\":return transparency16;\n            case \"floorTile\":\n            case \"tile4\":return tile4;\n            case \"wallTile\":\n            case \"tile5\":return tile5;\n        }\n        return null;\n    })\n\n}\n// Auto-generated code. Do not edit.\n"
}
```
```customts
tiles.loadMap(tiles.createMap(tilemap`level1`))
robot.beginScreen()
game.onUpdate(function () {
    if (robot.goalReached()) {
        music.play(music.melodyPlayable(music.powerUp), music.PlaybackMode.UntilDone)
        game.splash("You reached the goal!")
        game.reset()
    }
})
```
