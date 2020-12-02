# Gas Pump

```text
fontawesome-5.15/Solid/GasPump
```

```text
include('fontawesome-5.15/Solid/GasPump')
```

|icon|element|
|---|---|
|![](GasPump.png)|![](GasPump.element.png)|



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
' loads the GasPump element
include('fontawesome-5.15/Solid/GasPump')
GasPump('gas_pump', 'Gas Pump', 'an optional tech field')
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
' loads the GasPump element
include('fontawesome-5.15/Solid/GasPump')
GasPump('gas_pump', 'Gas Pump', 'an optional tech field')
@enduml
```
