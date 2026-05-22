# DualDock Client

Client for the raspberry 4 working as a streamDeck, a KVM switch and a HDMI/USB hub.

## Modification from the fork

### Switch button

Added a side bar on the left that will trigger the hdmi switch and the usb switch.

Still have to :
- fill the hardware function : [Controller.java](https://github.com/Charly-sketch/DualDock-client/blob/29119dda22bbac8d25b78a67151ea31f6b71e62c/src/main/java/com/stream_pi/client/controller/Controller.java#L330-L331)

Added :
- side bar button : [DashboardBase.java](https://github.com/Charly-sketch/DualDock-client/blob/29119dda22bbac8d25b78a67151ea31f6b71e62c/src/main/java/com/stream_pi/client/window/dashboard/DashboardBase.java#L55-L56)
- side bar function : [Controller.java](https://github.com/Charly-sketch/DualDock-client/blob/29119dda22bbac8d25b78a67151ea31f6b71e62c/src/main/java/com/stream_pi/client/controller/Controller.java#L238-L239)