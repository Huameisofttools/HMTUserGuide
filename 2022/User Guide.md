# Huamei D365F&O Develops Tools User Guide

>  2024 Oct.9th
>
> Author: Willie Yao

## History

| date         | version | description | author     |
| ------------ | ------- | ----------- | ---------- |
| 2024 Oct.9th | 1.0     |             | Willie Yao |
|              |         |             |            |

## Overview

Huamei D365F&O Develops Tools can help Dynamics 365 developers increase their work efficiency. This extension is public in Visual Studio Marketplace, and it is free.

## Installation

### Installation Prerequisite

This extension can be installed for the following version of Visual Studio IDE:

- Visual Studio 2022 Enterprise

### Installation Step

1. Open the Visual Studio, find the Extension button.

![install1](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/globelmenu1.png)

2. Click the Manage Extensions button.

![install2](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/Installation2.png)

3. Input the key word "Huamei" or "Huamei 365® D365FO Tools", find it and install it.

![install2](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/Install3.png)

4. Close the Visual Studio, and Modify its extension.
5. Open the Visual Studio, if the HMT menu display, that means your installation successfully.

![install2](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/Install4.png)

## Develops Tools Menu

HMT has three menus on the Visual Studio IDE as shown below:

1. Menu in Extension tab `Globel Menu`
2. Menu in Project node `Project Menu`
3. Menu in Item node `Item Menu`

### Globel Menu

The global menu function list is as follows:

![install2](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/globelmenu1.png)


1. **Generate Label For All** the static text of the current Solution.
2. **Extension Class Name Setup** Sets the naming format of the coc.
3. **Generate AX Element By Templates**. Generate ax element by templates.

### Project Menu

The list of project menu functions is as follows:

![install2](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/globelmenu2.png)

1. **Generate Header Comment For Project** Generate header comment for project
2. **Generate Label For Project** Create labels for all static text for the project
3. **Generate Extension Class** Adds an Extension class for the project

### Item Menu

![install2](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/globelmenu3.png)

1. **Generate Form For Table** Create a form for the selected table
2. **Generate Header Comment For Item** Create comments for the code of the selected object
3. **Generate Label For Item** Creates a label for the text of the selected object
4. **Generate Privilege For Element**. Create privilege for the selected object
5. **Generate Find And Exist Method** Create a find exist method for the selected table
6. **Generate Extension Class** Creates an extension class for the selected object
7. The **Fields Builder** imports fields for the selected table
8. **Table Builder** selects EDT to create tables, forms, privileges, etc

## HMT Options

HMT supports the setting of some special parameters in Tools Option. The specific path is Tools > Option > HMT D365FFO tools > D365FFO Page:

![install2](https://github.com/HMWillieYao/HMTUserGuide/blob/main/2022/Images/option1.png)

Currently, HMT Option contains three parameters:
1. The **Extension Class Prefix** is the default prefix when the extension class is created.
2. **Set Label For Source Code** This function applies to all Label generators.
  (1) True, generates a Label for static text in the source code.
  (2) False, does not generate labels for static text in the source code.
3. **Parm methods** Setting whether the function is disabled
