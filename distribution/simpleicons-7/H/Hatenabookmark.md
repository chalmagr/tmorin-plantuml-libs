# Hatenabookmark


```text
simpleicons-7/H/Hatenabookmark
```

```text
include('simpleicons-7/H/Hatenabookmark')
```



| Illustration | Hatenabookmark |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/H/Hatenabookmark.png) | ![illustration for Hatenabookmark](../../simpleicons-7/H/Hatenabookmark.Local.png) |




## Hatenabookmark

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Hatenabookmark
include('simpleicons-7/H/Hatenabookmark')

' renders the element
Hatenabookmark('Hatenabookmark', 'Hatenabookmark', 'an optional tech label')
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

' loads the Item which embeds the element Hatenabookmark
include('simpleicons-7/H/Hatenabookmark')

' renders the element
Hatenabookmark('Hatenabookmark', 'Hatenabookmark', 'an optional tech label')
@enduml
```
