## AIM: 
   To Schematic and Simulate Inverter using CADENCE virtuoso. 
## APPARATUS REQUIRED: 
   CADENCE VIRTUOSO 
## PROCEDURE: 
### Procedure for Commands to get into Cadence<br>
1.	Right Click and open the terminal window<br>
2.	Type the following commands as follows and press enter.<br>
    i)	tcsh<br>
    ii)	source /home/install/cshrc<br>
    iii)	virtuoso <br>
### Procedure for Schematic simulation using Cadence<br>
1.	Now two windows must open i)virtuoso/command interpreter window ii)”Whats New…"<br>
2.	Close the 2nd window<br>
3.	Use 1st window i.e virtuoso window(CIW) for further processing.<br>
    i)	Create a New Library<br>
    ii)	Create Schematic Cell view.<br>
    iii)	Create the Symbol for schematic Cell view.<br>
    iv)	Create the test Cell view.<br>
    v)	Analog simulation by spectre<br>
### Procedure for Creating New Library.<br>
a)	File –New – Library<br>
b)	Name : Give name for ur library Ex: VLSILAB , Enable Attach to an existing technology library, Click OK<br>
c)	Attach the library to the technology library gpdk045.Click OK<br>
### Create Schematic Cell view.
a)	Go to 1st window i.e virtuoso(CIW)<br>
b)	File-New-Cell view<br>
c)	Setup the new file form, Library: Select the one you a created. Cell : Give the experiment name Ex: Inverter View: Schematic<br>
d)	Type: Schematic press OK<br>
e)	Add the required components from the libraries and make the connections.<br>
f)	Go to instance fixed menu or use shortcut key “I” from keypad to go instances Click on browse. This opens the library browser ow select the appropriate library for components like Gpdk045,nmos, pmos<br>
g)	Analog library	Vdd, Gnd, Vcc, Vpulse, Vsin<br>
h)	Make the connections by using fixed narrow wire key<br>
i)	Click Check and Save button<br>
### Creating the Symbol for schematic Cell view
a.	In the schematic window, execute
Crate – Cell view – From Cell view
The cell view from cell view window appears
Check Lib Name, Cell Name, From View name must be schematic Press ok<br>
b.	Now Symbol generation form appears. Click Ok If No changes required<br>
c.	A new window with with default symbol is created.<br>
d.	Edit the symbol if you want to give actual symbol shape else continue.<br>
    i.	Execute Create-Cell view-from cell view<br>
    ii.	Library Name and Cell Name must be same which you have used for schematic. Press OK<br>
    iii.	Check for the position of pin side.Prss OK<br>
    iv.	Edit for the shape by Create-Shape-Choose required options to edit.<br>
## Creating the new test cell view<br>
a)	Go to CIW window, Execute File-New-Cell view<br>
b)	Setup the new file form<br>
Library: Select the one you a created.<br>
Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test<br>
View: Schematic<br>
Type: Schematic  press OK<br>
Analog simulation by SPECTRE.<br>
a.	In test cell view window<br>
b.	Launch – ADE L(Analog Design Environment)<br>
c.	Execute Setup—Simulation/directory/Host A new window opens<br>
d.	Set the simulation window to spectre and click ok<br>
e.	Execute Setup-Model Library. Anew window opens, Check of gpdk.scs as lib and section type as stat then press OK.<br>
f.	Execute Analysis – Choose. A window opens.<br>
g.	Select the type and set the specifications and press OK<br>
h.	Execute Output s—to be plotted – Select on Schematic<br>
i.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse<br>
j.	Execute Simulation -- Net list and Run<br>
## Simulation Settings

Setup for transient analysis:<br>
1. Stop time = 400n<br>
Setup for D.C analysis<br>
1. Component to be selected in schematic is	for d.c analysis<br>
2. Start = -1 Stop = 1 resp.<br>

## CMOS INVERTER
![WhatsApp Image 2024-05-15 at 12 32 02 PM](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/3e336a66-13c5-4da6-956f-b8195b3a4a21)
![WhatsApp Image 2024-05-15 at 12 31 53 PM](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/406f55bd-11f9-41e5-9592-c52a4d219b9a)

## OUTPUT
![Screenshot 2024-04-27 114912](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/c3546127-c5f4-4802-b709-898757e349c9)

## NANDGATE
![WhatsApp Image 2024-05-15 at 3 10 41 PM](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/f54e8aa1-f7c1-498b-9c36-d532819ca0e8)
![WhatsApp Image 2024-05-15 at 3 10 42 PM](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/c909717f-baca-4f7a-9358-009b6c950e77)

## OUTPUT
![Screenshot 2024-05-07 134745](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/9ae8390a-57cf-454a-a78d-cbfd868c8176)

## NORGATE
![WhatsApp Image 2024-05-15 at 3 10 40 PM](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/71f05040-35df-405f-bb47-3630a781cedc)
![WhatsApp Image 2024-05-15 at 3 10 49 PM](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/840cf0b0-3d45-465a-af8c-a56f13c09a25)

## OUTPUT

![Screenshot 2024-05-07 142449](https://github.com/Udayabharathim/VLSI-LAB-EXP-6/assets/160568654/94d85148-2ba5-4722-99bc-af66a2319183)

## RESULT
The schematic and simulate inverter using CADENCE is done and  verified successfully.
