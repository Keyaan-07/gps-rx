# GPS Receiver
GPS-RX is a custom-hardware, low-power GPS receiver that is just 16x16mm in size. This receiver does not have any COCOM limits and is fully customisable. It uses UART to communicate with other external controllers and takes a 3.3 volt input. Unlike other GPS receivers, there are no speed or height based limits and can go to any height or any speeds. It is built like a really small module and can be built and assembled by anyone and used basically everywhere. I built this project to learn verilog and also because this seems really cool! The ice40up5k from lattice semiconductor is the FPGA that processes the GPS signals. 


![schematic](/media/schematic.svg)
![pcb](/media/pcb.png)
![3d pcb](/media/pcb-3d.png)
![3d pcb back](/media/pcb-3d-back.png)



### Assembly instructions
1. Order the PCB from the gerber files in the [production](/hardware/production/) folder. Get two stencils(one for the top and one for the bottom).
2. Either get PCBA, or solder the components yourself. 
3. If soldering yourself, place the top side stencil over the top side and apply paste. Place all the components. 
4. Reflow the top side. 
5. Do the same process for the bottom side!
6. Program the firmware by connecting to the test points. 
7. Your receiver is ready!


### Note about firmware: GPS firmware development without the actual board will be really hard, thus i am not writing the firmware right now. 

## BOM
WIP 