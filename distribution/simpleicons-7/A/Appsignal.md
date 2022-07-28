# Appsignal


```text
simpleicons-7/A/Appsignal
```

```text
include('simpleicons-7/A/Appsignal')
```



| Illustration | Appsignal |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Appsignal.png) | ![illustration for Appsignal](../../simpleicons-7/A/Appsignal.Local.png) |




## Appsignal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Appsignal
include('simpleicons-7/A/Appsignal')

' renders the element
Appsignal('Appsignal', 'Appsignal', 'an optional tech label')
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

' loads the Item which embeds the element Appsignal
include('simpleicons-7/A/Appsignal')

' renders the element
Appsignal('Appsignal', 'Appsignal', 'an optional tech label')
@enduml
```
