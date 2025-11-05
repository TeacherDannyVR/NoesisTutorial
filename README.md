Youtube tutorial that goes with this code: [
<img width="3758" height="2131" alt="image" src="https://github.com/user-attachments/assets/63d7f5f5-9977-4c4d-9ee9-5f67a84db9b9" />](https://youtu.be/cu-u8cTYomg)


                         Code from the tutorial
*******************************************************************************
<Grid
  xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
  xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
  Width="500" Height="500">

    <Image Source="Images/DiamondFinder.png" />

</Grid>
*******************************************************************************

All the steps to the tutorial:


Download Neosis Studio Beta from this website. -> https://www.noesisengine.com/forums/viewtopic.php?t=3610
It’s a Zip File, so “Extract All” and open the NoesisGUI-Studio-win Folder
Put App.StudioTool somewhere on your computer. 
Make a ‘HorizonUI’ folder
Open Studio, create new, go to HorizonUI folder
At the bottom, name the project (i.e. ImageUI) and click ‘Create Project’.
The program opens, click on folder that has / at the top
Click the + sign, Make a new folder\
Name the folder “Images”,
Click on the Images folder, click + sign, click “Import Assets”
 Choose an image that you want to display
Click on / folder, it’s the top folder that has no name, just /
In the window below that there will be a file “MainPage.xaml”.
Right click the file, choose ‘Open in VS Code’
Erase the code and paste this:
<Grid xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation" xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml" Width="500" Height="500">   <Image Source="Images/DiamondFinder.png" /></Grid>\
****WARNING**** make sure you put the correct folder and image name. Mine was “Image/DiamondFinder.png” but yours might be different
Save file (CTRL + S)
Open Desktop Editor
Open a world, go to Assets, click the scroll down where it says ‘Add New’.
Choose ‘Noesis Project’
When it is fully imported, drag out the asset into the world.
Click on the ‘Noesis Project’ Gizmo
In the properties panel on the right, in the ‘Noesis Settings’ click the scroll down next to
Root Folder, choose ‘MainPage.xaml’
You are done, the Gizmo should now display the image you put in the studio.
