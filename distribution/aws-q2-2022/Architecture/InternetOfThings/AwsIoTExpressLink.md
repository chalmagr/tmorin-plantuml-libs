# AwsIoTExpressLink


```text
aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink
```

```text
include('aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink')
```



| Illustration | AwsIoTExpressLink | AwsIoTExpressLinkCard | AwsIoTExpressLinkGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink.png) | ![illustration for AwsIoTExpressLink](../../../aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink.Local.png) | ![illustration for AwsIoTExpressLinkCard](../../../aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLinkCard.Local.png) | ![illustration for AwsIoTExpressLinkGroup](../../../aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLinkGroup.Local.png) |




## AwsIoTExpressLink

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsIoTExpressLink
include('aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink')

' renders the element
AwsIoTExpressLink('AwsIoTExpressLink', 'Aws Io T Express Link', 'an optional tech label')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsIoTExpressLink
include('aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink')

' renders the element
AwsIoTExpressLink('AwsIoTExpressLink', 'Aws Io T Express Link', 'an optional tech label')
@enduml
```

## AwsIoTExpressLinkCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsIoTExpressLinkCard
include('aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink')

' renders the element
AwsIoTExpressLinkCard('AwsIoTExpressLinkCard', 'Aws Io T Express Link Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsIoTExpressLinkCard
include('aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink')

' renders the element
AwsIoTExpressLinkCard('AwsIoTExpressLinkCard', 'Aws Io T Express Link Card', 'an optional description')
@enduml
```

## AwsIoTExpressLinkGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsIoTExpressLinkGroup
include('aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink')

' renders the element
AwsIoTExpressLinkGroup('AwsIoTExpressLinkGroup', 'Aws Io T Express Link Group', 'an optional tech label') {
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

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsIoTExpressLinkGroup
include('aws-q2-2022/Architecture/InternetOfThings/AwsIoTExpressLink')

' renders the element
AwsIoTExpressLinkGroup('AwsIoTExpressLinkGroup', 'Aws Io T Express Link Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```
