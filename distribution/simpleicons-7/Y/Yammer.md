# Yammer


```text
simpleicons-7/Y/Yammer
```

```text
include('simpleicons-7/Y/Yammer')
```



| Illustration | Yammer |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/Y/Yammer.png) | ![illustration for Yammer](../../simpleicons-7/Y/Yammer.Local.png) |




## Yammer

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Yammer
include('simpleicons-7/Y/Yammer')

' renders the element
Yammer('Yammer', 'Yammer', 'an optional tech label')
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

' loads the Item which embeds the element Yammer
include('simpleicons-7/Y/Yammer')

' renders the element
Yammer('Yammer', 'Yammer', 'an optional tech label')
@enduml
```
