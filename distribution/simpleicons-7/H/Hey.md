# Hey


```text
simpleicons-7/H/Hey
```

```text
include('simpleicons-7/H/Hey')
```



| Illustration | Hey |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/H/Hey.png) | ![illustration for Hey](../../simpleicons-7/H/Hey.Local.png) |




## Hey

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Hey
include('simpleicons-7/H/Hey')

' renders the element
Hey('Hey', 'Hey', 'an optional tech label')
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

' loads the Item which embeds the element Hey
include('simpleicons-7/H/Hey')

' renders the element
Hey('Hey', 'Hey', 'an optional tech label')
@enduml
```
