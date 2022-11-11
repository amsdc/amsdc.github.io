---
permalink: /products/zoom-autojoiner-gui
layout: redirect
redirect_url: https://advaith.pythonanywhere.com/amsdc/software/getDetails?productID=autojoiner
---

# Zoom Autojoiner GUI

Details | Value
--|--
Name | Zoom Autojoiner GUI
Release Date | July 31st, 2021
Last Updated | October 20th, 2022
Latest Version | 0.5.5
License | GNU GPL v3
Programming Language | Python 3
Language | English
Type | GUI (Automation)
Copyright | (c) 2021-22 Advaith Menon/AMSDC
Repository | Coming Soon
Installer | [Zoho WorkDrive](https://workdrive.zohopublic.in/folder/gc2944a6c06e96e4543f3b55066196a4bd566?layout=list)

## Installation
1. Go to the Installer link mentioned above.
2. Select the latest version. Usually, this is the one which was modified more recently. (You can click on the Last Modified column to sort in descending order.)
3. Run the downloaded EXE.<br>![image](https://user-images.githubusercontent.com/83835839/184684310-d21c8038-d923-49d9-b5e5-7a7fc8ed3844.png)

4. Accept the License Agreement and press Next.<br>![image](https://user-images.githubusercontent.com/83835839/184688992-c7507165-6e20-44db-ad91-a8debfca33b4.png)

4. Select all the components in the Components page and press Next.<br>![image](https://user-images.githubusercontent.com/83835839/184689116-1dca3c23-5512-47a8-ab99-4e063359b01a.png)

5. Leave install location as is and press Next.<br>![image](https://user-images.githubusercontent.com/83835839/184689208-39596d13-8b78-42ff-beb9-2dfe2818f419.png)

6. Leave the folder name as it is and press Install.<br>![image](https://user-images.githubusercontent.com/83835839/184689303-ac5840ea-263d-474c-923d-e431a98a5133.png)

7. When prompted, fill out the configuration options as desired. You can also enable extensions in the `Extensions Configuration` tab.<br>![image](https://user-images.githubusercontent.com/83835839/184689607-7a88bea3-e34d-4b64-96fb-972473489c59.png)

8. Finish the installation.

## What's new
### v0.5.5
* Reorganized config tool, with help strings. <br> ![image](https://user-images.githubusercontent.com/83835839/197012169-6a2c3ec8-343b-4c73-a187-0ca1846186e0.png)
* Reorganized menu structure - The meetings menu has moved under the Application main menu, thus removing unnecessary clutter. For developers: The menu bar helper function is no longer used. Rather, the menu is now a plain Tkinter menu. This means the menu objects are programmatically exposed and can be accessed in the API. The docs will be updated in accordance with the same.
* About dialog box - Not sure which version you're on? No worries, the new About box (Application &rarr; About) will help you in identifying the same with ease. <br> ![image](https://user-images.githubusercontent.com/83835839/197012969-847400fb-6c43-4b2f-a4db-356a23df7b06.png)
* New system tray - **in beta**. Use this if you often press the &times; button and close the autojoiner. To close the application when the system tray icon is on, first quit the app (Application &rarr; quit), and then only exit the system tray. DO NOT DO THE REVERSE, or else the app will run in background with no way to exit (other than the Task Manager). Recommended to keep this off. 
