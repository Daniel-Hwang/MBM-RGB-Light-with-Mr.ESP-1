# MBM-RGB-Light-with-Mr.ESP-1
Mind control MBM RGB Light with Mr.ESP 1
Let’s do an interesting experiment, using EEG to control the RGB light.

First, the required materials and introduction:
To complete the tasks, you need to connect the circuits first, so let's take a look at the circuit blocks that are needed in the circuit and how they work. The required materials is shown in the file(The mindcontrol RGB light material required by MBM.jpg):
Note: You can also use the development board for this demo, and the way is as the same. 

You will need:
1*Control board	 
1*Lithium battery panel	 
1*Full color RGB module	
1*EEG Receive module	
3* 3-pin cable	
1* 4-pin cable	

Second, the circuit connection:
Prepare these circuit modules, and begin to connect the circuit!
The module diagram is shown in the file(The mindcontrol RGB light circuit connection by MBM.jpg)
1. Check the battery cable and the battery port has been connected;
2. Make sure any analog interface (such as A0) of the control board connect to full-color RGB module DI interface with 3-pin cable;
3. If you need more than one full-color RGB module, these RGB modules will be linked with DI to DO;
4. Anyone 5V power supply port of Lithium battery panel connect to the power port of Control board with 2-pin cable;
5. Serial COM port of the control board connects to the EEG Receive module 4-pin connector with a 4-pin cable.
Note: After the circuit is connected, and then double check to prevent misconnection.


Third, the programming code is in the file(code)

Finally, demo results as shown in the file (The mindcontrol RGB light demo result by MBM.jpg)

Best Wishes!
