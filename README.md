My project is a USB HUb that has one male USB A connector to plg into a laptop or PC, which then splits off into 2 USB A female and 2 USB C femlae ports can you can plu things into. I made it because I'm tired of my chromebook not having enough ports to plug in accessories and such. Also, it doesn't have any USB C ports. 
The overall design of this is pretty simple, there is 1 male usb a connector and 2 usb a female connectors, 2 usb c femlae connectors. These all sit on a pcb that I designed, all connected to a usb controller that basically takes the incoming data and power and diverts it to the 4 output ports. 
The 12MHz keeps the necessary timing consistent in order for the data to be synchronized.
The decoupling capacitators filter out electrical noise, smooth out voltage spikes, and ensure the SL2.1A chip gets stable power during data spikes.
The pull up/down resistors configure specific control pins on the hub controller to fixed logic states. This allows the chips to handle port power control correctly.
<img width="696" height="738" alt="FullSchematic" src="https://github.com/user-attachments/assets/eb175b5c-a5d0-4c3c-bc0e-453fca70ff0f" />
This is the schematic of the hub.
<img width="837" height="738" alt="FinalPCB" src="https://github.com/user-attachments/assets/2434df76-4bc1-48d9-880a-49ccbdaa2037" />
This is the finsihed PCB design.
<img width="1117" height="870" alt="image" src="https://github.com/user-attachments/assets/fa633209-de33-48e0-a780-e5419d0123aa" />
[SL2.1A_USB_Hub_BOM.csv](https://github.com/user-attachments/files/33315746/SL2.1A_USB_Hub_BOM.csv)
This is the 3d model of the PCB.
<img width="888" height="455" alt="costofbill" src="https://github.com/user-attachments/assets/611be7e7-6843-481a-840c-b5250dbd6cfa" />
BOM with link to suppliers
