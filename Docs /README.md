# <p align="center"> File Sorter & Renamer: A Unity Asset </p>

**Description**:
An essential package for anyone looking to streamline their Unity project file management. With just a click of a button, you can easily sort your files into customizable folders based on your desired format. 

This asset allows you to easily customize the names of your files and folders based on a set format, making it easier to find the files you need. 

Not only can you sort and rename files in your Unity project, but you can also add your own directories with custom extensions, allowing you to sort and manage files of your Unity project with ease.

**Version**: 1.0.0

**Asset Store**: [Link](https://u3d.as/34DZ)

## <p align="center"> How to customize the Package's settings </p>

### 1. Go to Edit/Preferences to access the Preferences Window
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/519c06b5-1697-43c8-a439-ccbd73a48182" width="200">

 ### 2. Click on the File Sorter and Renamer tab
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/65388d93-77a9-4057-8121-692bc37ea599" width="600">


`Replace identical files` = A directory file is replaced if a file with the same name exists in both the sorted folder and the directory.

`Backup Folder` = A file is transferred to this folder when it is replaced.

`File Name Format` = The format of the file name after the sorting is completed.

<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/c8c6fcd7-0241-45b2-acf6-a0daf4bc59d7" width="600">

`Folder Name Format` = The format of the folder name after the sorting is completed.

<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/67f65d83-f71f-47dd-8393-60d806972acb" width="600">

 ### 2. Click on the File Sorter and Renamer/Directories tab
 
- By pressing the Select Button, you can choose the folder in which the files should be placed based on their type.
 
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/c0e2a2c7-cae8-4abf-95f1-12e33a2da3b8" width="600">
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/33edf8c8-1917-4d59-a70d-8c620d32bc89" width="600">

<br></br>

- By right-clicking on a folder in the Project Window, you can access the File Sorter and Renamer/Set Directory menu item, which allows you to set the selected folder to the specified file type.
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/0b776bc3-70f0-45c3-9063-c55a31494f15" width="600">

<br></br>

- Note that you can only set directories to folders, not files.
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/6b24a709-7d6a-4649-b1c0-7c1e20514503" width="600">


## <p align="center"> How to sort a Folder </p>
 
- By right-clicking on a folder in the Project Window, you can access the File Sorter and Renamer/Sort All menu item, which enables you to initiate the sorting process.
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/cd6a6e01-6682-4533-be18-07edf132df21" width="600">

<br></br>

- By right-clicking on a folder in the Project Window, you can access the File Sorter and Renamer/Sort Selective menu item, which enables you to initiate the sorting process selectively.
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/5c591775-5bc4-4c0e-be69-16210736d8e2" width="200">

## <p align="center"> How to create new directories with custom extensions </p>

 ### 1. Open BackendInstance.cs script
<img src="https://github.com/blindeyethe/File-Sorter-And-Renamer/assets/62220844/78ea3f0a-6231-43ea-a7d4-d6be4dbb1360" width="600">

 ### 2. Include a `new FileType()` with a specified name and extension or a list of extensions.
