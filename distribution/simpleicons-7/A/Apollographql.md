# Apollographql


```text
simpleicons-7/A/Apollographql
```

```text
include('simpleicons-7/A/Apollographql')
```



| Illustration | Apollographql |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Apollographql.png) | ![illustration for Apollographql](../../simpleicons-7/A/Apollographql.Local.png) |




## Apollographql

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Apollographql
include('simpleicons-7/A/Apollographql')

' renders the element
Apollographql('Apollographql', 'Apollographql', 'an optional tech label')
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

' loads the Item which embeds the element Apollographql
include('simpleicons-7/A/Apollographql')

' renders the element
Apollographql('Apollographql', 'Apollographql', 'an optional tech label')
@enduml
```
