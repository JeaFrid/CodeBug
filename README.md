version: 1.0 Beta
# What is CodeBug?

**Lightweight, fast and easy software development tool.**

## How to Install?

To install, make sure your device is Windows and make sure you have [Visual Studio Code](https://code.visualstudio.com/) installed. Then follow the installation list.

1. Go to [CodeBug/Setup/Visual Studio Code/](https://github.com/JeaFrid/CodeBug/tree/main/Setup/Visual%20Studio%20Code) folder.
2. In File Explorer, navigate to the following folder: **_C:\Users\<UserName>\AppData\Roaming\Code\User\snippets_**
3. Drag and drop the two snippets files located in the **CodeBug/Setup/Visual Studio Code/** folder into the folder named 'Snippet' that we found in File Explorer.

It's that simple!

## Start a new project

If you are embarking on a new project then you will need four folders; CodeBug-Schema, CodeBug-Blocks, assets, src.

### Why?

These folders can serve as an introduction in any compiler or factory.

### What, Why, Where

`CodeBug-Schema`: Folder with all schema types and codes. You can view and download it on github by clicking [here](https://github.com/JeaFrid/CodeBug/tree/main/CodeBug). Don't forget to put it in your project folder after downloading.

`CodeBug-Blocks`: Folder with all bloks types and codes. You can view and download it on github by clicking [here](https://github.com/JeaFrid/CodeBug/tree/main/CodeBug). Don't forget to put it in your project folder after downloading.

`Assets`: You can add images, files or extensions you need to this folder. This folder is required for the compiler to understand the path of the assets. You can create it manually inside the project folder. But make sure its name is "assets".

`Factories`: Factories are code snippets that can be called externally. Even if you didn't call a factory from this folder, you still have to add the folder to your project. Otherwise, the compiler will cause problems. You can get this folder on Github from https://github.com/JeaFrid/CodeBug path.

`Src`:The "src" folder is the most important folder. Here you have your source codes and here you write code. Create this folder manually and put the code files in it.

## What is a code file?

The code file is the file where the codes will be written. Finds two types of code files; bcode and bschema.

### What is (project name).bcode?

The .bcode extension is the file containing the backend codes. Here background operations are performed. Operations such as math, writing, functions, controls, lists are done here. Create this file in the folder named "src". Do not use spaces, special characters and make sure the extension is ".bcode" when naming.

### What is (project name).bschema?

The .bschema extension is a design extension used to develop appearances. Create this file in the folder named "src". Do not use spaces, special characters in the naming, and make sure that the extension is ".bschema".
