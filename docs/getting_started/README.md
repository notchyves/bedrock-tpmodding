## Basic Resource Pack Path

The most essential component in any texture pack is the ```manifest.json``` file. This file defines the resource pack to Minecraft and it is where you define the title and description.

This is the basic syntax for the file:
```json
{
    "format_version": 1,
    "header": {
        "description": "Description",
        "name": "Name",
        "uuid": "[uuid]",
        "version": [1, 0, 0], // version of pack
        "min_engine_version": [1, 16, 0] // meaning this pack will only work on 1.16.0+
    },
    "modules": [
        {
            "description": "Description",
            "type": "resources",
            "uuid": "[uuid]",
            "version": [1, 0, 0] // version of pack
        }
    ]
}
```

For the ```[uuid]``` text, you can replace it with a random UUID that can be found [here](http://uuidgenerator.net/).

### pack_icon.png

This will be the pack icon on default without this file.

![Missing Texture Icon](https://user-images.githubusercontent.com/82107846/182984531-b83a9d23-1495-4d75-94e4-711778ce128b.png)

However, if you have your own image that you would like instead rename it to ```pack_icon.png```, as it will replace the missing texture. It is recommended to have something with a 1:1 aspect ratio, meaning the width and height are the same size (e.g. 16x16, 32x32, 64x64).
