# copatag

```sh
Copatag is a command line tool that generates container images tags for Copacetic.

Usage:
  copatag [command]

Available Commands:
  help        Help about any command
  list
  version     Print the version number

Flags:
  -h, --help   help for copatag

Use "copatag [command] --help" for more information about a command.
```

```sh
Usage:
  copatag list [flags]

Flags:
  -h, --help            help for list
  -n, --next-tag        Include next patch tag information
  -o, --output string   Output file path
```

```sh
copatag list <registry>
copatag list <registry> -n -o matrix.json
```

[GH-Action](https://github.com/sahma19/copatag-action)
