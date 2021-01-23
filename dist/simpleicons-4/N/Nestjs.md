# Nestjs

```text
simpleicons-4/N/Nestjs
```

```text
include('simpleicons-4/N/Nestjs')
```

|icon|element|
|---|---|
|![](Nestjs.png)|![](Nestjs.element.png)|



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
' loads the Nestjs element
include('simpleicons-4/N/Nestjs')
Nestjs('nestjs', 'Nestjs', 'an optional tech field')
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
' loads the Nestjs element
include('simpleicons-4/N/Nestjs')
Nestjs('nestjs', 'Nestjs', 'an optional tech field')
@enduml
```
