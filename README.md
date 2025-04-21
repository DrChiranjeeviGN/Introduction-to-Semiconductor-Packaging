# Ansys_Labs
This repository consists of Lab-1 and Lab-2 projects of the VSD Semiconductor Packaging course.
# Lab 1: Thermal Simulation of Semiconductor Packages with ANSYS
Open Ansys Electronics Desktop. Go to Project -> Insert Icepack Design
![image](https://github.com/user-attachments/assets/04f163ef-c947-4d89-8b6e-88dbeb89b6b4)

 
An Icepack Project will appear.
![image](https://github.com/user-attachments/assets/a91ca7e7-2808-4b8e-9551-27f65ccdc265)

 




Go to Icepack -> Toolkit -> Geometry -> Packages -> FilpChip_BGA
![image](https://github.com/user-attachments/assets/625ec2a4-e2d4-4b4c-bc2c-f3a17ec004df)

 
A tiny window will appear where you can customize the dimensions of the package.
![image](https://github.com/user-attachments/assets/3eaf2833-eb9b-429f-8b24-414fe0060798)






The model of the package is loaded.
![image](https://github.com/user-attachments/assets/a194e51d-e0ee-4d6a-8f4d-3e0f5ee6c05c)

 
Go to Model to see the package.
 ![image](https://github.com/user-attachments/assets/46c9d768-2fbd-44e6-a29e-a9d462ac9b88)





Go to Project Manager -> Thermal -> Select the Power -> OK
![image](https://github.com/user-attachments/assets/3a8c138b-4587-42e2-be2f-0c092a2a272f)

 
Go to solids -> Flipchip-BGA2_substrate -> Assign Thermal -> Source
![image](https://github.com/user-attachments/assets/50373443-826e-4aa2-b897-6812d03de19a)






A window will pop up. Here, select Ambient Temp and Finish.
![image](https://github.com/user-attachments/assets/b7e3aa8e-7ce8-4dab-b52d-d6de9ad05a90)

 
Go to solids -> Flipchip-BGA2_substrate -> Assign Monitor -> Point
 ![image](https://github.com/user-attachments/assets/a436ccea-db24-471b-b84c-251b52af95e8)






A window will pop up. Here, under Thermal select Temperature. Repeat this process for Die and Underfill also.
![image](https://github.com/user-attachments/assets/c6a9da22-da1c-4daf-8ce1-f4b352c921c3)

 
Go to Mesh ->  Simulation -> Generate Mesh -> save the file -> OK. Go to Quality and click on Face alignment.
![image](https://github.com/user-attachments/assets/96171bca-b58a-4389-b9be-15c36278cfa6)

 





Similarly, click on Skewness.
![image](https://github.com/user-attachments/assets/bcd266f0-d293-4463-adcd-7d00b66044c5)

 
Go to Project Manager -> Analysis -> Add Solution Setup. A window will pop up. Click OK.
![image](https://github.com/user-attachments/assets/a676d4ba-c943-4f4b-a48f-f4f42e91b097)


	
Click on Validate. If all the parameters have green ticks then there are no errors and you can proceed. 
![image](https://github.com/user-attachments/assets/2698a51d-c752-48e5-bb84-17ebf7e3f032)

Click on Analyze All.
![image](https://github.com/user-attachments/assets/9839924a-577f-4787-a5e6-cca7d05c44da)





	

Go to Solids -> Flipchip_BGA2_die_underfill -> Assign Mesh Region -> select die -> OK -> again click OK on popped up window. 
![image](https://github.com/user-attachments/assets/9187878f-ce56-483e-ae1e-bee7182f7d0f)

 
Select the package -> Plot Fields -> Temperature -> Temperature
![image](https://github.com/user-attachments/assets/0b736959-cbba-4a65-81f8-37fdc806375c)


	



Click on Specify Name and Specify Folder. Select Plot on surface only and in Surface Smoothing, enable Guassian Smoothing and click Done.
![image](https://github.com/user-attachments/assets/7ecc32b3-2059-4934-b1a2-d1a34e9edac0)

 
Thermal Analysis of the package will appear.
 ![image](https://github.com/user-attachments/assets/e682a12a-9d51-4dc2-83f2-648dc8893101)
![image](https://github.com/user-attachments/assets/f417e48a-4282-4048-9c72-4afcad2c13e8)

# Lab 2: Package Design and Modelling
Open The AEDT application. Go to Project -> Q3D extractor Design
 ![image](https://github.com/user-attachments/assets/091dead3-7303-4ffc-ac4a-57ab9523898d)

Click Rectangle and draw from the origin in XY Plane.
![image](https://github.com/user-attachments/assets/57176888-1826-490f-bbfe-36a327364bdd)






Set the required values of the rectangle.
![image](https://github.com/user-attachments/assets/25e4e2dc-3d44-4f60-8394-d1f93fbf432b)

Click on the rectangle -> Modeler -> Surface -> Thicken Sheet
 ![image](https://github.com/user-attachments/assets/833a154a-118f-4008-907a-1d2d47f92377)





Set the thickness to 0.2mm
![image](https://github.com/user-attachments/assets/72dea6eb-7e06-4fdd-a2e4-04d2c5ac0b6c)

Change the name of the rectangle to Die.
![image](https://github.com/user-attachments/assets/1f769346-7564-45a7-977d-9927c656c114)

 





Select the material as silicon.
![image](https://github.com/user-attachments/assets/3d1da441-fe4a-4a47-9f3f-264e845660c4)
![image](https://github.com/user-attachments/assets/8d446e3e-783d-418d-ba81-e6dea5197aef)








Draw another rectangle which is bigger than the previous one.
![image](https://github.com/user-attachments/assets/4ecd9f07-a4ff-4178-ba24-14726b4619f2)

 
Set the required dimensions.
![image](https://github.com/user-attachments/assets/e825d074-d458-49c6-a9b3-e7b9aedb0dc8)





Set the thickness to -0.5mm
![image](https://github.com/user-attachments/assets/dba2461b-061e-48cb-bfd3-efd87cf05be9)

 
Change the name as Substrate and assign FR4_epoxy material.
 ![image](https://github.com/user-attachments/assets/c1d84213-490f-4cb1-8aae-06333df76d89)






Change the position of substrate accordingly.
![image](https://github.com/user-attachments/assets/9b9b1950-53d5-478b-ae77-f01cb9c9a45c)

 
Draw another rectangle over the die with the same dimensions.
![image](https://github.com/user-attachments/assets/5898daa1-c83b-4470-8051-2a827b6d0977)






Set the required dimensions and position.
![image](https://github.com/user-attachments/assets/d1bce635-2a82-494c-aad6-145e314bbfe3)

 
Set thickness to -0.1mm
![image](https://github.com/user-attachments/assets/57cb56d9-d6bd-4307-bb7e-b43fdd5dc6b1)






Change the name to DieAttach and assign modified_epoxy material.
![image](https://github.com/user-attachments/assets/ad3d3757-c51e-4b84-9edb-43c051673ee8)

 
Draw a small rectangle on the Die.
![image](https://github.com/user-attachments/assets/d02e50ec-9f95-4dbb-b303-3ff72d5bbd23)
 





Set the required position and dimensions.
![image](https://github.com/user-attachments/assets/14a9f850-1d52-4fbe-bb1a-3a3ef9230b66)

Set thickness as 0.005mm
![image](https://github.com/user-attachments/assets/f71ac108-8354-47c1-8663-f141d728bf38)

 





Similarly, draw a small rectangle on the substrate.
![image](https://github.com/user-attachments/assets/ce8d670a-b977-4cbe-89b3-aa68b6b7a68a)

 
Set the required position and dimensions.
![image](https://github.com/user-attachments/assets/d18218a4-bbc4-4f64-af82-967d89d9549b)

 





Change the name of rectangle on die as Diebondpad.
![image](https://github.com/user-attachments/assets/980f2a72-938d-4024-ab3f-23f92ab38e30)

Change the name of rectangle on substrate as Substratebondpad.
![image](https://github.com/user-attachments/assets/bb2a4970-ac42-425f-84f8-2c30220f4f33)






Click on Bondwire and draw from center of Diebondpad to center of Substratebondpad.
![image](https://github.com/user-attachments/assets/e0f19cd9-c85a-4954-a16a-8e102dd61845)

 
Assign material of bondwire as gold and change the color.
![image](https://github.com/user-attachments/assets/24dc9eb3-f24d-4442-906b-77da8b3c45c9)
![image](https://github.com/user-attachments/assets/eaf5a8b1-a65c-46a7-beeb-5803e054d9af)





 
Click on Diebondpad -> Edit -> Duplicate -> Along Line
![image](https://github.com/user-attachments/assets/5ed37c08-22b0-4ec6-b3e7-6e7624e5d00f)






Set the number as 7.
![image](https://github.com/user-attachments/assets/22cc2834-3465-4348-90c5-64251bed8cc3)

Similarly, duplicate the Substratebondpad and bondwires.
![image](https://github.com/user-attachments/assets/0ecdb612-4e7d-4056-a80d-34eb263064d2)






Repeat the process on the remaining 3 sides.
![image](https://github.com/user-attachments/assets/2e78e19c-985a-4c42-88d4-58641bde8669)

 
Draw a rectangle on the substrate with the same dimensions.
 ![image](https://github.com/user-attachments/assets/5a91474e-bea9-40c4-9c81-340cc117c4b9)





Set the thickness as 1.2mm
![image](https://github.com/user-attachments/assets/8c6baeb0-ade3-47ed-9e1f-c0256d388ba8)

 
Change the name as MoldCompound and assign epoxy_Kevlar_xy material.
 ![image](https://github.com/user-attachments/assets/ce615271-3598-4903-a2c7-3a9bfccdb164)





The final package looks like this.
![image](https://github.com/user-attachments/assets/838d990e-82d6-44ee-bfb0-c42a5aa9d8a1)
![image](https://github.com/user-attachments/assets/ddeb5038-7671-4af4-8330-f73275445411)


 















