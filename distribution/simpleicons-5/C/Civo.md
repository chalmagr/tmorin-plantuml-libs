# Civo


```text
simpleicons-5/C/Civo
```

```text
include('simpleicons-5/C/Civo')
```



| Illustration | Civo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-5/C/Civo.png) | ![illustration for Civo](../../simpleicons-5/C/Civo.Local.png) |




## Civo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-5/bootstrap')

' loads the Item which embeds the element Civo
include('simpleicons-5/C/Civo')

' renders the element
Civo('Civo', 'Civo', 'an optional tech label')
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

' loads the Item which embeds the element Civo
include('simpleicons-5/C/Civo')

' renders the element
Civo('Civo', 'Civo', 'an optional tech label')
@enduml
```
