# homecloud


## Presentation
This package is used to document the project [homecloud](https://github.com/tmorin/homecloud-ansible).

It implements elements based on :

- [Material Design Icons](https://github.com/google/material-design-icons)
- [Font Awesome](https://fontawesome.com)




## Bootstrap

The package handles its own bootstrap.

```plantuml
' loads the homecloud bootstrap
include('homecloud/bootstrap')
```



## Style

The package handles its own style.

The bootstrap loads the style too! ;)

```plantuml
' loads the homecloud style
include('homecloud/style')
```


# Modules

The package provides 4 modules.


- [Brand](Brand.md) with 13 elements
- [Container](Container.md) with 4 elements
- [Hardware](Hardware.md) with 6 elements
- [Network](Network.md) with 4 elements

# Examples

The package provides 1 examples.


## simple
![simple](../homecloud/examples/simple.png)<br>
[The source file.](../homecloud/examples/simple.puml)
