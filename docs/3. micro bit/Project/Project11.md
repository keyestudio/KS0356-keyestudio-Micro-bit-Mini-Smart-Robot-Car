### Project 11 Bluetooth Test

**1.Description**

The micro:bit robot car shield comes with a Bluetooth module. We can use the built-in Bluetooth module to communicate with your phone’s APP, thus control the external devices connected to micro:bit control board using APP.

In the experiment, we only use the phone’s APP to control the LED matrix on the micro:bit main board, showing the different characters.

<font color="red">**(note that when controlled by Bluetooth, use leds show matrix drawing module, easy to crash.)**</font>

**2.Library link settings**

The micro:bit robot car shield comes with a Bluetooth module.

Before sending the test code, we should add the library to micro:bit on the browser. The method is as below.

Connect the micro:bit main board to your computer using a USB cable.

![](media/wps75.png)

Open micro:bit MakeCode Block editor: https://makecode.microbit.org/#editor. Firstly click the Extensions.
![](media/wps76.jpg)

Then click the **Bluetooth**.

![](media/wps77.jpg)

TAP Remove extensions and add Bluetooth.

![](media/wps78.jpg)

Finally, you should see the Bluetooth is added well.

![](media/wps79.jpg)

Then click the **Extensions** again, enter the library link below and search:
https://github.com/LaboratoryForPlayfulComputation/pxt-BlockyTalkyBLE-UART

![](media/wps80.jpg)

Finally, you should see the library **blocky Talky BLE** is added successfully.

![](media/wps81.jpg)

**3.Test Code**

![](media/wps82.jpg)

**4.Bluetooth APP Use**

After add the library and send the test code to micro:bit main board, power on the micro:bit main board.

![](media/wps1.png)

Click the link to download the Bluetooth APP:
https://drive.google.com/open?id=17jJB--GKxPytDyPuqqhs6B2NUCCu7kST

Installed the APP, click the APP icon to open it.![](media/wps2.jpg)

When your phone detects the Bluetooth module on the micro:bit main board, the APP will prompt to open the Bluetooth. Choose to open the Bluetooth. Pop up the interface below.

![](media/wps3.jpg)

Then click the Bluetooth icon ![](media/wps4.jpg), it will pop up the micro:bit information.

![](media/wps5.jpg)

Then click![](media/wps1.jpg)to connect the micro:bit Bluetooth. 

![](media/wps6.jpg)

After that, click![](media/wps2-1765847705274-2.jpg)for connection, pop up the interface shown below.

![](media/wps3-1765847724128-4.jpg)

Here the Bluetooth is connected successfully, you can use the APP to control your micro:bit car. The options are shown on the right side.

You can click the![](media/wps4-1765847762129-6.jpg)to disconnect the Bluetooth. Shown below.

![](media/wps5-1765847780328-8.jpg)

**5.Test Result**

Send well the test code to micro:bit main board, and power on the micro:bit main board. Follow the method mentioned above, connect the Bluetooth on the micro:bit main board using your phone’s APP.

Connected, click the right icons on the APP, the LED matrix on the micro:bit main board should show different letters.

![](media/wps6.png)

![](media/wps7.png)