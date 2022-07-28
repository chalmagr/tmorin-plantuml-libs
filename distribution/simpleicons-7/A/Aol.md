# Aol


```text
simpleicons-7/A/Aol
```

```text
include('simpleicons-7/A/Aol')
```



| Illustration | Aol |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Aol.png) | ![illustration for Aol](../../simpleicons-7/A/Aol.Local.png) |




## Aol

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Aol
include('simpleicons-7/A/Aol')

' renders the element
Aol('Aol', 'Aol', 'an optional tech label')
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
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Aol
include('simpleicons-7/A/Aol')

' renders the element
Aol('Aol', 'Aol', 'an optional tech label')
@enduml
```
