# Tachometer Alt

```text
fontawesome-5.15/Solid/TachometerAlt
```

```text
include('fontawesome-5.15/Solid/TachometerAlt')
```

|icon|element|
|---|---|
|![](TachometerAlt.png)|![](TachometerAlt.element.png)|



## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the fontawesome-5.15 bootstrap
include('fontawesome-5.15/bootstrap')
' loads the TachometerAlt element
include('fontawesome-5.15/Solid/TachometerAlt')
TachometerAlt('tachometer_alt', 'Tachometer Alt', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the fontawesome-5.15 bootstrap
include('fontawesome-5.15/bootstrap')
' loads the TachometerAlt element
include('fontawesome-5.15/Solid/TachometerAlt')
TachometerAlt('tachometer_alt', 'Tachometer Alt', 'an optional tech field')
@enduml
```
