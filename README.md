# VLSI-LAB-EXP-6
## AIM
To create,simulate the design of CMOS inverter,NAND,NOR from schematic using cadence.

## APPARATUS REQUIRED:
cadence

## PROCEDURE:

## Commands to get into Cadence
Right Click and open the terminal window
Type the following commands as follows and press enter. i) tcsh ii) source /home/install/cshrc iii) virtuoso
## Procedure for Schematic simulation using Cadence
Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…”
Close the 2nd window
Use 1st window i.e virtuoso window(CIW) for further processing. i) Create a New Library ii) Create Schematic Cell view. iii) Create the Symbol for schematic Cell view. iv) Create the test Cell view. v) Analog simulation by spectre
## Procedure for Creating New Library.
a) File –New – Library b) Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK c) Attach the library to the technology library gpdk045.Click OK

## Create Schematic Cell view.
a) Go to 1st window i.e virtuoso(CIW) b) File-New-Cell view c) Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic d) Type: Schematic press OK e) Add the required components from the libraries and make the connections. f) Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos g) Analog library Vdd, Gnd, Vcc, Vpulse, Vsin h) Make the connections by using fixed narrow wire key i) Click Check and Save button

## Creating the Symbol for schematic Cell view
a. In the schematic window, execute Crate – Cell view – From Cell view The cell view from cell view window appears Check Lib Name, Cell Name, From View name must be schematic Press ok b. Now Symbol generation form appears. Click Ok If No changes required c. A new window with with default symbol is created. d. Edit the symbol if you want to give actual symbol shape else continue. i. Execute Create-Cell view-from cell view ii. Library Name and Cell Name must be same which you have used for schematic. Press OK iii. Check for the position of pin side.Prss OK iv. Edit for the shape by Create-Shape-Choose required options to edit.

## Creating the new test cell view
a) Go to CIW window, Execute File-New-Cell view b) Setup the new file form Library: Select the one you a created. Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test View: Schematic Type: Schematic press OK

## Analog simulation by SPECTRE.
a. In test cell view window i. Launch – ADE L(Analog Design Environment) b. Execute Setup—Simulation/directory/Host A new window opens c. Set the simulation window to spectre and click ok d. Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK. e. Execute Analysis – Choose. A window opens. f. Select the type and set the specifications and press OK g. Execute Output s—to be plotted – Select on Schematic h. Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse i. Execute Simulation -- Net list and Run

## INVERTER SCHEMATIC:
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/0448fb32-ced0-46aa-a24c-4dc8c9b869d1)
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/8ec22ffd-457d-4fa1-b67f-fa5ac46f2833)

## Specifications:
Vpulse

V1 = 0	       

V2 = 1

td = 0,tr=tf=1 n, ton= 100n ,T=200n

Vdc = 1
Simulation Settings

Setup for transient analysis:

Stop time =400n

Setup for D.C analysis

Component to be selected in schematic is for d.c analysis

Start = -1 Stop = 1 resp.
Expected Waveform:

## Transient Analysis
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/823bcc77-ec15-41c9-b8e0-101354b4b991)
## DC ANALYSIS
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/e30b81dd-5f44-4dab-8f39-3e07f04e1670)
## NAND 
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/ef848445-7950-4b2c-81d7-4d099ba37bf4)
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/e67f6742-0e85-46a7-b40f-d1b24a9b02c7)

## Specifications:

Vpulse

Va1 = 0 Va2 = 1 tr=tf=50ps, period=20ns pulse width = 10ns

Vb1 = 0 Vb2 = 1 tr=tf=50ps, period=40ns pulse width = 20ns

Vdc = 1

Expected Waveform:

## Transient Analysis:
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/2afd1d54-d444-4b8c-b17d-839058079085)
## NOR
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/9ad451ac-7359-4a3e-b734-453a91e03142)
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/d3cd3887-e9c7-46fc-9f71-5baaeb4c9bff)

## Specifications:

Vpulse

Va1 = 0 Va2 = 1 tr=tf=50ps, period=20ns pulse width = 10ns

Vb1 = 0 Vb2 = 1 tr=tf=50ps, period=40ns pulse width = 20ns

Vdc = 1

Expected Waveform:

## Transient Analysis:
![image](https://github.com/abinayaela/VLSI-LAB-EXP-6/assets/164911294/9bad2a17-e47d-4774-9330-2cee722900eb)

## RESULT:

Thus, the design,simulation and verification of the CMOS inverter,NAND,NOR from schematic using cadence was successfully completed.
