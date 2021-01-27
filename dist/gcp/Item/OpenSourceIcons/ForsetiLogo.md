# Forseti Logo

```text
gcp/Item/OpenSourceIcons/ForsetiLogo
```

```text
include('gcp/Item/OpenSourceIcons/ForsetiLogo')
```

|icon|card|element|group|
|---|---|---|---|
|![](ForsetiLogo.png)|![](ForsetiLogo.card.png)|![](ForsetiLogo.element.png)|![](ForsetiLogo.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the ForsetiLogo element
include('gcp/Item/OpenSourceIcons/ForsetiLogo')
ForsetiLogoCard('forseti_logo', 'Forseti Logo', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the ForsetiLogo element
include('gcp/Item/OpenSourceIcons/ForsetiLogo')
ForsetiLogoCard('forseti_logo', 'Forseti Logo', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```


## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the ForsetiLogo element
include('gcp/Item/OpenSourceIcons/ForsetiLogo')
ForsetiLogo('forseti_logo', 'Forseti Logo', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the ForsetiLogo element
include('gcp/Item/OpenSourceIcons/ForsetiLogo')
ForsetiLogo('forseti_logo', 'Forseti Logo', 'an optional tech field')
@enduml
```


## group
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the ForsetiLogo element
include('gcp/Item/OpenSourceIcons/ForsetiLogo')
ForsetiLogoGroup('forseti_logo', 'Forseti Logo', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the ForsetiLogo element
include('gcp/Item/OpenSourceIcons/ForsetiLogo')
ForsetiLogoGroup('forseti_logo', 'Forseti Logo', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
