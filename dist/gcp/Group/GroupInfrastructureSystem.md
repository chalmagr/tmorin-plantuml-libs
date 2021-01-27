# Group Infrastructure System

```text
gcp/Group/GroupInfrastructureSystem
```

```text
include('gcp/Group/GroupInfrastructureSystem')
```

|group|
|---|
|![](GroupInfrastructureSystem.group.local.png)|



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
' loads the GroupInfrastructureSystem element
include('gcp/Group/GroupInfrastructureSystem')
GroupInfrastructureSystem('group_infrastructure_system', 'Group Infrastructure System', 'an optional tech field')
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
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the GroupInfrastructureSystem element
include('gcp/Group/GroupInfrastructureSystem')
GroupInfrastructureSystem('group_infrastructure_system', 'Group Infrastructure System', 'an optional tech field')
@enduml
```
