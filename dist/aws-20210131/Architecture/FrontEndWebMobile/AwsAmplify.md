# Aws Amplify

```text
aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify
```

```text
include('aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify')
```

|icon|card|element|group|
|---|---|---|---|
|![](AwsAmplify.png)|![](AwsAmplify.card.png)|![](AwsAmplify.element.png)|![](AwsAmplify.group.png)|



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
' loads the AwsAmplify element
include('aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify')
AwsAmplifyCard('aws_amplify', 'Aws Amplify', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsAmplify element
include('aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify')
AwsAmplifyCard('aws_amplify', 'Aws Amplify', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the AwsAmplify element
include('aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify')
AwsAmplify('aws_amplify', 'Aws Amplify', 'an optional tech field')
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
' loads the AwsAmplify element
include('aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify')
AwsAmplify('aws_amplify', 'Aws Amplify', 'an optional tech field')
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
' loads the AwsAmplify element
include('aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify')
AwsAmplifyGroup('aws_amplify', 'Aws Amplify', 'an optional tech field'){
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
' loads the AwsAmplify element
include('aws-20210131/Architecture/FrontEndWebMobile/AwsAmplify')
AwsAmplifyGroup('aws_amplify', 'Aws Amplify', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
