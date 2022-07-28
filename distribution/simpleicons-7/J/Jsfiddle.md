# Jsfiddle


```text
simpleicons-7/J/Jsfiddle
```

```text
include('simpleicons-7/J/Jsfiddle')
```



| Illustration | Jsfiddle |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/J/Jsfiddle.png) | ![illustration for Jsfiddle](../../simpleicons-7/J/Jsfiddle.Local.png) |




## Jsfiddle

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Jsfiddle
include('simpleicons-7/J/Jsfiddle')

' renders the element
Jsfiddle('Jsfiddle', 'Jsfiddle', 'an optional tech label')
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

' loads the Item which embeds the element Jsfiddle
include('simpleicons-7/J/Jsfiddle')

' renders the element
Jsfiddle('Jsfiddle', 'Jsfiddle', 'an optional tech label')
@enduml
```
