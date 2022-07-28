# Tsnode


```text
simpleicons-7/T/Tsnode
```

```text
include('simpleicons-7/T/Tsnode')
```



| Illustration | Tsnode |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/T/Tsnode.png) | ![illustration for Tsnode](../../simpleicons-7/T/Tsnode.Local.png) |




## Tsnode

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Tsnode
include('simpleicons-7/T/Tsnode')

' renders the element
Tsnode('Tsnode', 'Tsnode', 'an optional tech label')
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

' loads the Item which embeds the element Tsnode
include('simpleicons-7/T/Tsnode')

' renders the element
Tsnode('Tsnode', 'Tsnode', 'an optional tech label')
@enduml
```
