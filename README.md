# Daz_Material_Preset_System
System that uses Data Assets (No C++ needed) to set up and apply material changes in game via blueprints

Setup:

Click on Code then Download Zip

<img width="1319" alt="Download_Zip" src="https://user-images.githubusercontent.com/38672299/128644838-2da77272-95bb-4be8-b9a1-dfd84a9326b6.png">

Once Downloaded right click on the zip folder and click "Extract All.."

<img width="565" alt="Extract_All" src="https://user-images.githubusercontent.com/38672299/128644870-ee151b09-2b35-4695-8612-e71439b88761.png">

Click Extract

<img width="441" alt="Extract" src="https://user-images.githubusercontent.com/38672299/128644887-ab5f2e25-8015-48e6-993c-a239506c3740.png">

Once extracted open up the folders until you find the UpL8 folder

Right click and copy the folder

<img width="565" alt="Copy_UpL8_Folder" src="https://user-images.githubusercontent.com/38672299/128644931-1ad2ea48-b3df-40e4-8bf5-5bb5d26fec9c.png">

Open your projects "Content" folder

Usually located at C:\Users\"username"\Documents\Unreal Projects\"projectname"\Content

Paste the UpL8 folder into the Content Folder

<img width="550" alt="Paste_Into_Project_Content_Folder" src="https://user-images.githubusercontent.com/38672299/128645031-e5afb413-7d7d-45ef-b4f4-8dfdceb1124b.png">

In Unreal Engine open the UpL8 folder and the UpL8_Material_Preset_System folder

<img width="971" alt="Open_the_UpL8_Material_System" src="https://user-images.githubusercontent.com/38672299/128645205-db89c54b-25c1-4cf6-9396-86d461c7c7da.png">

The Data Assets will look gray at first. Right clicking on them will change their appearance.

<img width="960" alt="Right_click" src="https://user-images.githubusercontent.com/38672299/128645302-3a17e6c7-0479-4336-be5a-e72f79e2886a.png">

Next drag the Test_BP into the level The notice to "Please add an MI Preset Data Asset" is normal

Next add a skeletal mesh to the Test_BP in your level

![Add_Skeletal_Mesh_Edit](https://user-images.githubusercontent.com/38672299/128645693-e3178a90-2908-45f4-a2b8-d438e12ffa3c.png)

In the default section click on "None" to add an MI Preset Data Asset

<img width="960" alt="Add_An_MI_Preset_Data_Asset" src="https://user-images.githubusercontent.com/38672299/128645719-975ea001-0d05-43cb-8504-b73b38aec78e.png">

Click on Daz_Figure_Demo_DA

<img width="960" alt="Choose_Demo" src="https://user-images.githubusercontent.com/38672299/128645779-7ba4a5db-7aef-477f-ada0-b77ff1c2826e.png">

The different sections of the character will change color

<img width="960" alt="Different_Colors" src="https://user-images.githubusercontent.com/38672299/128645813-c1f9bc47-9efa-4883-8cba-0787015459e5.png">

Open the the Daz_Figure_Demo_DA Data Asset from the content browser

<img width="960" alt="Open_The_Daz_Figure_Demo_DA" src="https://user-images.githubusercontent.com/38672299/128645862-1cbf0d89-b7d1-4186-ae3e-7206beea8971.png">

Expanding Daz Body Material Presets and Material Slot Setup you can see that the Face, Lips, Ears and Head (G8.1) Diffuse Color Vector Parameters are being overiden with a purple color.

<img width="960" alt="Check_Out_Setup" src="https://user-images.githubusercontent.com/38672299/128646012-725dec8d-db08-492f-9405-3fa653742f7f.png">

Expanding the other Material Slot Setups you can see how the other section's Diffuse Color Vector Parameters are being overiden.

<img width="960" alt="Check_Out_More" src="https://user-images.githubusercontent.com/38672299/128646124-fdc697ff-d95f-492b-b266-d4ff84ff8ec4.png">












