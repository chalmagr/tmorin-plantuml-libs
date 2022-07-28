# Elasticcloud


```text
simpleicons-7/E/Elasticcloud
```

```text
include('simpleicons-7/E/Elasticcloud')
```



| Illustration | Elasticcloud |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/E/Elasticcloud.png) | ![illustration for Elasticcloud](../../simpleicons-7/E/Elasticcloud.Local.png) |




## Elasticcloud

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Elasticcloud
include('simpleicons-7/E/Elasticcloud')

' renders the element
Elasticcloud('Elasticcloud', 'Elasticcloud', 'an optional tech label')
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

' loads the Item which embeds the element Elasticcloud
include('simpleicons-7/E/Elasticcloud')

' renders the element
Elasticcloud('Elasticcloud', 'Elasticcloud', 'an optional tech label')
@enduml
```
