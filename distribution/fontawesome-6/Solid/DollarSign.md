# DollarSign


```text
fontawesome-6/Solid/DollarSign
```

```text
include('fontawesome-6/Solid/DollarSign')
```



| Illustration | DollarSign |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/DollarSign.png) | ![illustration for DollarSign](../../fontawesome-6/Solid/DollarSign.Local.png) |




## DollarSign

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element DollarSign
include('fontawesome-6/Solid/DollarSign')

' renders the element
DollarSign('DollarSign', 'Dollar Sign', 'an optional tech label')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element DollarSign
include('fontawesome-6/Solid/DollarSign')

' renders the element
DollarSign('DollarSign', 'Dollar Sign', 'an optional tech label')
@enduml
```
