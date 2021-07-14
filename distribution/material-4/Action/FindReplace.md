# FindReplace


```text
material-4/Action/FindReplace
```

```text
include('material-4/Action/FindReplace')
```



| Illustration | FindReplace |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Action/FindReplace.png) | ![illustration for FindReplace](../../material-4/Action/FindReplace.Local.png) |




## FindReplace

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FindReplace
include('material-4/Action/FindReplace')

' renders the element
FindReplace('FindReplace', 'Find Replace', 'an optional tech label')
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
include('material-4/bootstrap')

' loads the Item which embeds the element FindReplace
include('material-4/Action/FindReplace')

' renders the element
FindReplace('FindReplace', 'Find Replace', 'an optional tech label')
@enduml
```
