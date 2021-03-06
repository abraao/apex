
The `alias` command allows you to alias one or more function versions to a given alias.

## Examples

Alias all functions as "prod":

```
$ apex alias prod
```

Alias all "api_*" functions to "prod":

```
$ apex alias prod api_*
```

Alias all functions of version 5 to "prod":

```
$ apex alias -v v5 prod
```

Alias specific function to "stage":

```
$ apex alias stage myfunction
```

Alias specific function's version 10 to "stage":

```
$ apex alias -v v10 stage myfunction
```
