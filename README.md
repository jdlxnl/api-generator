###### Package

Add the package by loading it through composer.

```json

{
    "require": {
        "jdlx/jdlx": "*"
    },
    
    "require-dev" : {
        "jdlx/generator": "*",
        "jdlx/api-generator": "*"
    },
    
    "repositories": [
        {
            "type": "path",
            "url": "./jdlx/Foundation"
        },
        {
            "type": "path",
            "url": "./jdlx/Generator"
        },
        {
            "type": "path",
            "url": "./jdlx/ApiGenerator"
        }
    ]
}
```
