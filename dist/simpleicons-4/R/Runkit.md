# Runkit

```text
simpleicons-4/R/Runkit
```

```text
include('simpleicons-4/R/Runkit')
```

|icon|element|
|---|---|
|![](Runkit.png)|![](Runkit.element.png)|



## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the simpleicons-4 bootstrap
include('simpleicons-4/bootstrap')
' loads the Runkit element
include('simpleicons-4/R/Runkit')
Runkit('runkit', 'Runkit', 'an optional tech field')
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
' loads the simpleicons-4 bootstrap
include('simpleicons-4/bootstrap')
' loads the Runkit element
include('simpleicons-4/R/Runkit')
Runkit('runkit', 'Runkit', 'an optional tech field')
@enduml
```
