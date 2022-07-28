# Cloudsmith


```text
simpleicons-7/C/Cloudsmith
```

```text
include('simpleicons-7/C/Cloudsmith')
```



| Illustration | Cloudsmith |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/C/Cloudsmith.png) | ![illustration for Cloudsmith](../../simpleicons-7/C/Cloudsmith.Local.png) |




## Cloudsmith

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Cloudsmith
include('simpleicons-7/C/Cloudsmith')

' renders the element
Cloudsmith('Cloudsmith', 'Cloudsmith', 'an optional tech label')
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

' loads the Item which embeds the element Cloudsmith
include('simpleicons-7/C/Cloudsmith')

' renders the element
Cloudsmith('Cloudsmith', 'Cloudsmith', 'an optional tech label')
@enduml
```
