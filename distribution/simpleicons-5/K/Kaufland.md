# Kaufland


```text
simpleicons-5/K/Kaufland
```

```text
include('simpleicons-5/K/Kaufland')
```



| Illustration | Kaufland |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-5/K/Kaufland.png) | ![illustration for Kaufland](../../simpleicons-5/K/Kaufland.Local.png) |




## Kaufland

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-5/bootstrap')

' loads the Item which embeds the element Kaufland
include('simpleicons-5/K/Kaufland')

' renders the element
Kaufland('Kaufland', 'Kaufland', 'an optional tech label')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-5/bootstrap')

' loads the Item which embeds the element Kaufland
include('simpleicons-5/K/Kaufland')

' renders the element
Kaufland('Kaufland', 'Kaufland', 'an optional tech label')
@enduml
```
