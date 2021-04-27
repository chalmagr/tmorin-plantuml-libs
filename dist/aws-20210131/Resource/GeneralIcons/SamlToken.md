# Saml Token

```text
aws-20210131/Resource/GeneralIcons/SamlToken
```

```text
include('aws-20210131/Resource/GeneralIcons/SamlToken')
```

|icon|card|element|group|
|---|---|---|---|
|![](SamlToken.png)|![](SamlToken.card.png)|![](SamlToken.element.png)|![](SamlToken.group.png)|



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
' loads the SamlToken element
include('aws-20210131/Resource/GeneralIcons/SamlToken')
SamlTokenCard('saml_token', 'Saml Token', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the SamlToken element
include('aws-20210131/Resource/GeneralIcons/SamlToken')
SamlTokenCard('saml_token', 'Saml Token', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
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
' loads the SamlToken element
include('aws-20210131/Resource/GeneralIcons/SamlToken')
SamlToken('saml_token', 'Saml Token', 'an optional tech field')
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
' loads the SamlToken element
include('aws-20210131/Resource/GeneralIcons/SamlToken')
SamlToken('saml_token', 'Saml Token', 'an optional tech field')
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
' loads the SamlToken element
include('aws-20210131/Resource/GeneralIcons/SamlToken')
SamlTokenGroup('saml_token', 'Saml Token', 'an optional tech field'){
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
' loads the SamlToken element
include('aws-20210131/Resource/GeneralIcons/SamlToken')
SamlTokenGroup('saml_token', 'Saml Token', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
