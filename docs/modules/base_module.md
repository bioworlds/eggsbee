## Base Module

The key component of the Eggsbee Device is the Base Module, which comprises of a protective shell in which the Vessel is placed
![5Eggsbee_1](https://github.com/bioworlds/eggsbee/assets/140448792/4fbaecf6-1d22-4a67-bdd6-e8a08100dae0)
. The Base Module is fitted with a number of actuators and sensors for controlling and measuring bioprocesses occurring inside the Vessel. These include:

- A mechanism for operating a rotating magnetic stirrer at variable speeds. The stirring can also be pulsed by using the "Pulse" feature in Eggsbee Online. Currently, there are two versions of the Base Modules, each with different rotating speeds:
  - In the Cell Culture version, the rotating speed is between 10 to 300 rpm
  - In the Microbial Culture version, the rotating speed is between 300 to 3,000 rpm
- One row of white LED lights positioned along the inner wall of the Base Module.
- One row of 8 x optical density sensors positioned along the inner wall of the Base Module. They are positioned from the 100mL to 800mL markings of the Vessel. They can be used as level sensors as well as for measuring the turbidity of the contents of the Vessel.
- A thermal jacket surrounding the Vessel for heating and maintaining the temperature of the Vessel from room temperature to 50 degrees C.
- An infrared sensor to measure the temperature of the contents inside the Vessel.
- In some versions of the Base Module, an Emission Sensor may also be included. This sensor measures the levels of carbon dioxide emissions as well as 8 streams of different volatile organic compounds (VOC). The VOCs provide useful data that can be used for identifying and tracking the bioprocesses through machine learning.

On the outside of the Base Module, there are 3 light indicators:

- The top indicator, when green, indicates that the Eggsbee Device is powered on.
- The middle indicator, when green, indicates that the Eggsbee Device is online. If the indicator is orange, the device is offline.
- The bottom indicator, when green, indicates that bioprocessing data is being recorded.

**Important Notes:** The Base Module must be kept dry at all times. Do not remove the cap and pour liquids into the Vessel when inside the Base Module as accidental spillage may occur. To add liquids into the Vessel, first remove the Vessel, place the Vessel at a safe distance away from the Base Module, remove the cap, pour in the liquids, replace the cap securely, and return the Vessel into the Base Module. Alternatively, the Pump Module may be used to transfer liquids into or out of the Vessel.

## Vessel

The Vessel is provided when the advanced or standard package is purchased. The Vessel is a very important part of the Device as it contains the ingredients, and it is inside the Vessel that the bioprocesses take place. The features of the Vessel are as follow:

- There are 2 types of Vessels:
  - The 1-litre Vessel that can be used from a minimum volume of 100 mL to a maximum volume of 1,000 mL
  - The 500mL Vessel that can be used from a minimum volume of 100mL to a maximum volume of 500 mL.
- The Vessel is made of glass, round, and wide-mouth with GLS80 thread volume.
- The Vessel can be sealed with the orange polypropylene cap or the blue 4-port or 6-port caps. Both Vessel and caps can be safely autoclaved or sterilized by any other conventional means.
- The Vessel comes with permanent white enamel graduations and a marking spot.

**Important Notes:** If desired, the Vessel can be used as a single-use vessel.

## Connecting Your Eggsbee Base Module to Wi-Fi in Strict Security Environments

In numerous settings, particularly corporate and academic environments, strict security regulations govern the connection of network-enabled devices like the Eggsbee Base Module. Consequently, establishing an online connection for your Eggsbee may require some additional steps. This guide offers several viable strategies to assist you.

**Note:** The Eggsbee Base Module operates exclusively on a 2.4GHz Wi-Fi network and does not support 5GHz Wi-Fi.

### Option 1: Use WPA-2 Enterprise

If your network supports WPA-2 Enterprise, we recommend this method owing to its advanced security features. To connect:

1. Open the Eggsbee lid to locate the device ID number.
2. Connect your PC or mobile device to the Wi-Fi network that shares the same name (SSID) as the device ID number.
3. Open a web browser, enter `192.168.4.1` in the address bar. It will open the Eggsbee’s Wi-Fi setup page.
4. Select the “WPA2 Enterprise” tab, enter the SSID, EAP ID (same as SSID), EAP Username, and EAP Password for your WPA-2 Enterprise network.
5. Wait a few moments. A message will be displayed if the device is successfully updated. Restart your Eggsbee by unplugging and replugging it.
6. If the internet connection indicator light (second light from top) turns green, you're successfully connected.

### Option 2: Use a Mobile Router

A mobile router is another feasible option. It works similarly to a Wi-Fi bridge but functions as an independent device, creating its own network. Here's how to use it:

1. Follow the manufacturer's instructions to set up your mobile router.
2. Open the Eggsbee lid to locate the device ID number.
3. Connect your PC or mobile device to the Wi-Fi network that shares the same name (SSID) as the device ID number.
4. Open a web browser, enter `192.168.4.1` in the address bar. It will open the Eggsbee’s Wi-Fi setup page.
5. Select the “General Setup” tab, enter the SSID, and Password for the mobile router.
6. Follow steps 5 and 6 outlined in the WPA-2 Enterprise section to complete the setup.

### Option 3: Use a Wi-Fi Hotspot

Transforming your smartphone into a Wi-Fi hotspot provides another potential solution. This turns your phone into a Wi-Fi source for the Eggsbee. Here's how:

1. Enable the hotspot feature on your smartphone.
2. Connect the Eggsbee to your smartphone's Wi-Fi hotspot by following the steps outlined in the Mobile router section.

**Note:** The smartphone has to be within the Eggsbee connection range at all times; otherwise, data transmission by Eggsbee will be affected.

### Option 4: Use Connectify

Connectify is software that turns your Windows laptop into a Wi-Fi hotspot. In a high-security environment where the above options aren't practical, this could serve as an effective workaround. Here's how to use Connectify:

1. Download and install Connectify on your Windows laptop.
2. Create a Connectify hotspot with a distinct name and password.
3. Connect the Eggsbee to the Connectify hotspot by following the steps outlined in the Mobile router section.

**Note:**
- The laptop has to be within the Eggsbee connection range at all times; otherwise, data transmission by Eggsbee will be affected.
- The laptop Wi-Fi has to be set to 2.4GHz. In Windows, this can be done by Device Manager > Network Adapters > [Wi-Fi device].
- The laptop has to be powered on at all times, and power settings set on “Never” shutdown.

### Option 5: Use Internet Sharing on a Mac

Mac users can share their computer's internet connection with the Eggsbee. This workaround can be very effective in strict security environments:

1. Navigate to 'System Preferences' on your Mac.
2. Select 'Sharing'.
3. Choose 'Internet Sharing'.
4. From the 'Share your connection from' dropdown menu, select the internet connection you want to share.
5. In the 'To computers using' list, check the box next to 'Wi-Fi'.
6. Click 'Wi-Fi Options' and set a network name and password.
7. Tick the 'Internet Sharing' box on the left-hand side list.
8. Connect the Eggsbee to the Wi-Fi network created by your Mac by following the steps outlined in the Mobile router section.

### Option 6: Use a 4G Router with SIM Card

A 4G router can connect to a mobile phone network with a SIM card with a data plan subscription:

1. Subscribe to a SIM card with a data plan.
2. Follow the manufacturer's instructions to set up your 4G router.
3. Connect the Eggsbee to the 4G router by following the steps outlined in the Mobile router section.

Please note that these strategies aim to help you get your Eggsbee online. It is essential to adhere to your organization's IT policies and guidelines when connecting devices to the network. If you require further assistance, please contact us at support@dynacyte.com.
