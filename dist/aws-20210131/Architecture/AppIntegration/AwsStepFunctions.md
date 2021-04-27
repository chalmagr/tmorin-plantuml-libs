# Aws Step Functions

```text
aws-20210131/Architecture/AppIntegration/AwsStepFunctions
```

```text
include('aws-20210131/Architecture/AppIntegration/AwsStepFunctions')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsStepFunctions.png)|![](AwsStepFunctions.card.png)|![](AwsStepFunctions.element.png)|![](AwsStepFunctions.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AwsStepFunctions element
include('aws-20210131/Architecture/AppIntegration/AwsStepFunctions')
AwsStepFunctionsCard('aws_step_functions', 'Aws Step Functions', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AwsStepFunctions element
include('aws-20210131/Architecture/AppIntegration/AwsStepFunctions')
AwsStepFunctionsCard('aws_step_functions', 'Aws Step Functions', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AwsStepFunctions element
include('aws-20210131/Architecture/AppIntegration/AwsStepFunctions')
AwsStepFunctions('aws_step_functions', 'Aws Step Functions', 'an optional tech field')
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
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AwsStepFunctions element
include('aws-20210131/Architecture/AppIntegration/AwsStepFunctions')
AwsStepFunctions('aws_step_functions', 'Aws Step Functions', 'an optional tech field')
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
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AwsStepFunctions element
include('aws-20210131/Architecture/AppIntegration/AwsStepFunctions')
AwsStepFunctionsGroup('aws_step_functions', 'Aws Step Functions', 'an optional tech field'){
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
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AwsStepFunctions element
include('aws-20210131/Architecture/AppIntegration/AwsStepFunctions')
AwsStepFunctionsGroup('aws_step_functions', 'Aws Step Functions', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
