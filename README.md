# CreateTemplateKtJvm

A Tool for create template

### Usage

```sh
java -jar CreateTemplateKtJvm-0.0.0.jar [configFolderPath]
```

### Prerequirement

Need following file under config folder

```
<configFolderPath>/
    src.json
    dist.json
```

The format of `src.json` and `dist.json` is refer to [CascadeJson.kt](https://github.com/CWKSC/CascadeJson.kt)

```json
{
    "src": "key"
}
```

```json
{
    "dist": "key"
}
```

This will convert to a map, value of those map is a unique key

src file or content in directory will copy to dist by key

### Project environment

Open folder `CreateTemplateKt/` by IntelliJ IDEA

### License

MIT
