# MaterialsBluetoothConnected
```text
elements/materials/Device/MaterialsBluetoothConnected
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsBluetoothConnected icon](../../../icons/materials/Device/MaterialsBluetoothConnected.png) | ![MaterialsBluetoothConnected element](MaterialsBluetoothConnected.element.png) | ![MaterialsBluetoothConnected card](MaterialsBluetoothConnected.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBluetoothConnected element
include('elements/materials/Device/MaterialsBluetoothConnected')
MaterialsBluetoothConnected('element', 'Bluetooth Connected', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBluetoothConnected element
include('elements/materials/Device/MaterialsBluetoothConnected')
MaterialsBluetoothConnected('element', 'Bluetooth Connected', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBluetoothConnected card
include('elements/materials/Device/MaterialsBluetoothConnected')
MaterialsBluetoothConnectedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the style
include('styles/materials')

' loads the MaterialsBluetoothConnected card
include('elements/materials/Device/MaterialsBluetoothConnected')
MaterialsBluetoothConnectedCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```