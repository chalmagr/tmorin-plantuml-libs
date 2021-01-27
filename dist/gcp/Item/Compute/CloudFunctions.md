# Cloud Functions

```text
gcp/Item/Compute/CloudFunctions
```

```text
include('gcp/Item/Compute/CloudFunctions')
```

|icon|card|element|group|
|---|---|---|---|
|![](CloudFunctions.png)|![](CloudFunctions.card.png)|![](CloudFunctions.element.png)|![](CloudFunctions.group.png)|



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
' loads the CloudFunctions element
include('gcp/Item/Compute/CloudFunctions')
CloudFunctionsCard('cloud_functions', 'Cloud Functions', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the CloudFunctions element
include('gcp/Item/Compute/CloudFunctions')
CloudFunctionsCard('cloud_functions', 'Cloud Functions', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the CloudFunctions element
include('gcp/Item/Compute/CloudFunctions')
CloudFunctions('cloud_functions', 'Cloud Functions', 'an optional tech field')
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
' loads the CloudFunctions element
include('gcp/Item/Compute/CloudFunctions')
CloudFunctions('cloud_functions', 'Cloud Functions', 'an optional tech field')
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
' loads the CloudFunctions element
include('gcp/Item/Compute/CloudFunctions')
CloudFunctionsGroup('cloud_functions', 'Cloud Functions', 'an optional tech field'){
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
' loads the CloudFunctions element
include('gcp/Item/Compute/CloudFunctions')
CloudFunctionsGroup('cloud_functions', 'Cloud Functions', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
