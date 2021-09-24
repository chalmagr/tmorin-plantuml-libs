# AwsIoTGreengrassRecipe


```text
aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe
```

```text
include('aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe')
```



| Illustration | AwsIoTGreengrassRecipe | AwsIoTGreengrassRecipeCard | AwsIoTGreengrassRecipeGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe.png) | ![illustration for AwsIoTGreengrassRecipe](../../../aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe.Local.png) | ![illustration for AwsIoTGreengrassRecipeCard](../../../aws-20210730/Resource/LoT/AwsIoTGreengrassRecipeCard.Local.png) | ![illustration for AwsIoTGreengrassRecipeGroup](../../../aws-20210730/Resource/LoT/AwsIoTGreengrassRecipeGroup.Local.png) |




## AwsIoTGreengrassRecipe

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-20210730/bootstrap')

' loads the Item which embeds the element AwsIoTGreengrassRecipe
include('aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe')

' renders the element
AwsIoTGreengrassRecipe('AwsIoTGreengrassRecipe', 'Aws Io T Greengrass Recipe', 'an optional tech label')
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
include('aws-20210730/bootstrap')

' loads the Item which embeds the element AwsIoTGreengrassRecipe
include('aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe')

' renders the element
AwsIoTGreengrassRecipe('AwsIoTGreengrassRecipe', 'Aws Io T Greengrass Recipe', 'an optional tech label')
@enduml
```

## AwsIoTGreengrassRecipeCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-20210730/bootstrap')

' loads the Item which embeds the element AwsIoTGreengrassRecipeCard
include('aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe')

' renders the element
AwsIoTGreengrassRecipeCard('AwsIoTGreengrassRecipeCard', 'Aws Io T Greengrass Recipe Card', 'an optional description')
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
include('aws-20210730/bootstrap')

' loads the Item which embeds the element AwsIoTGreengrassRecipeCard
include('aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe')

' renders the element
AwsIoTGreengrassRecipeCard('AwsIoTGreengrassRecipeCard', 'Aws Io T Greengrass Recipe Card', 'an optional description')
@enduml
```

## AwsIoTGreengrassRecipeGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-20210730/bootstrap')

' loads the Item which embeds the element AwsIoTGreengrassRecipeGroup
include('aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe')

' renders the element
AwsIoTGreengrassRecipeGroup('AwsIoTGreengrassRecipeGroup', 'Aws Io T Greengrass Recipe Group', 'an optional tech label') {
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
include('aws-20210730/bootstrap')

' loads the Item which embeds the element AwsIoTGreengrassRecipeGroup
include('aws-20210730/Resource/LoT/AwsIoTGreengrassRecipe')

' renders the element
AwsIoTGreengrassRecipeGroup('AwsIoTGreengrassRecipeGroup', 'Aws Io T Greengrass Recipe Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```
