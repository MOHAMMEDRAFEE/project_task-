# project_task-
Hello,Welcome to my repository.My self Mohammed Rafeeq khan.pursuing my BE final year.
For being tenacious towards my final year project .I started working out to know the tools,by a few basic programs.which are below following.

**1.HALF ADDER (combinational circuit)**

Steps to be followed to execute the above program.
=
 ![image](https://user-images.githubusercontent.com/93427617/140308328-bb34eda3-899b-4f86-8674-454ff5a54d1e.png)
**STEP1**:Click on the mark icon,Then make a new folder by naming it.

Again beside the mark icon click on it,
follow the same procedure to make new subfolders.

![image](https://user-images.githubusercontent.com/93427617/140309432-34269ade-2cb6-492b-bc46-bc6a6f3e80a8.png)

**STEP2**:Write the verilog program in the blank feild and Save it by pressing ctrl+s.
![image](https://user-images.githubusercontent.com/93427617/140310138-5425983c-7e51-4512-bef3-3e902208d5bf.png)

**STEP3**:Go to another sub-folder,write testbench for the above verilog program written.

![image](https://user-images.githubusercontent.com/93427617/140311791-fa2263c8-bcac-436a-88ec-931893d07749.png)

**STEP4**:Write the shown command,to be in working file.
Command syntax={cd  tabfoldername.v}

![image](https://user-images.githubusercontent.com/93427617/140312317-b491f1a1-be15-4d25-bad9-d19c16d3c32b.png)

**STEP5**:command written is for to check sub-folders

![image](https://user-images.githubusercontent.com/93427617/140312651-72ae04e6-e77f-44aa-b492-d731a33262aa.png)

**STEP6**:Further,to check for the codes to be errorfree.use the shown command.
By successful errorfree codes,a file gets generated as (a.out).

command syntax={iverilog tabverilogcodesubfoldername.v tabtestbenchsubfolder.v}

![image](https://user-images.githubusercontent.com/93427617/140315939-dc2712ff-6d61-46a8-9063-90d137ea40ac.png)

**STEP7**:To run the simulation,have the following command

command syntax={vvp taba}

A new file will genterated with the processingfoldername.vcd.

![image](https://user-images.githubusercontent.com/93427617/140318217-32c116f2-6bdb-4666-83ad-08909bf428ed.png)

**STEP8**: Now,to generate the waveform Enter the command (gtkwave tabprocessingfoldername.vcd).


![image](https://user-images.githubusercontent.com/93427617/140317143-b1d5e471-a02f-4765-8192-5c75d662bc4f.png)

**STEP9**:Attach the cmos (program) lib file or liberty file in the proccessing folder.

![image](https://user-images.githubusercontent.com/93427617/140318600-a296ef7f-61c1-427f-96af-a00ba94b7caf.png)

**STEP10**:Now,go to yosys.by giving the command {yosys}

![image](https://user-images.githubusercontent.com/93427617/140319345-036836c3-6ed0-44cd-8198-052c1b26fa50.png)

**STEP11**:To read the liberty file,Enter the command shown in demonstration image.

![image](https://user-images.githubusercontent.com/93427617/140320195-0685c449-3bfd-47e1-a505-00522e0aa587.png)

**STEP12**:For executing verilog frontend.
Enter read_verilog (processingfilename.v).

![image](https://user-images.githubusercontent.com/93427617/140320757-e8142913-c9c1-463a-8526-62b3c0695db0.png)

**STEP13**:To synthesize ,Enter synth -top modulename

![image](https://user-images.githubusercontent.com/93427617/140321225-bb62b1d7-53fc-4ef4-8147-c8664f03b4c0.png)

=>To execute ,Enter the shown command in demonstration image.

![image](https://user-images.githubusercontent.com/93427617/140321759-82259eaa-aa06-435c-a778-fb0f5aa3e1e0.png)

=>To genrate the show.dot file.Enter the command (show modulename).

![image](https://user-images.githubusercontent.com/93427617/140322599-fce3cf23-a6ed-43b5-bf7b-4c7ca7350dca.png)

After,successful generation of show.dot file 

Then click on show.dot file 

Go,to view  from the following list in view select (command palette) or PRESS ctrl+Shift+P.Furthere enter or select Graphviz:open preview to the slide.

![image](https://user-images.githubusercontent.com/93427617/140324132-a0393f06-57db-4f96-b131-ee09eb2a7f38.png)

Finally,Successful generation of output or preview to the slide.

**Lets,do the other program using skylibertyfile**
=

**2.D FLIP FLOP (SEQUENTIAL CIRCUIT)**

**steps to be followed same as previous a few steps differ.which we will see sequentially.**

**STEP1**:Download the files using https://drive.google.com/drive/folders/1CQvbm9vSEIKuPZCqJT04rVpkR61yKr-a

**STEP2**:![image](https://user-images.githubusercontent.com/93427617/140597247-36840016-3f75-4cae-aece-f947cab25e50.png)

From the downloaded files copy this files into a seprate file,by doing so our process gets hands down..!!

**STEP3**:
 ![image](https://user-images.githubusercontent.com/93427617/140308328-bb34eda3-899b-4f86-8674-454ff5a54d1e.png)

Click on the mark icon,Then make a new folder by naming it.Again beside the mark icon click on it, follow the same procedure to make new subfolders.

**STEP4**:![image](https://user-images.githubusercontent.com/93427617/140597403-df40bc86-a66a-47fa-a2d9-029a62d47e4b.png)

Write the verilog program in the blank feild.and save it by PRESSING CTRL+S

**STEP5**![image](https://user-images.githubusercontent.com/93427617/140597452-d2853e0a-a427-4f13-af02-e670fa1cfc85.png)

write test bench for verilog program and save it 









