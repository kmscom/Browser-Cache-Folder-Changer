## Web Browser Cache Folder Changer User Guide

### Download install package

Download the install file at the following link.

*   [web\_browser\_cache\_folder\_changer\_setup.exe](https://github.com/kmscom/Browser-Cache-Folder-Changer/blob/main/Release/web_browser_cache_folder_changer_setup.exe)

### Install
Run web\_browser\_cache\_folder\_changer\_setup.exe.
Following window will appear.

![Select Setup Install Mode](image/1.%20install_1.png)

Choose one depending on your favor.

Then, following window will appear. As this program needs "privilege permission" to create a symbolic link file, you should choose "Yes".
![User Account Control](image/1.%20install_2.png)

Following sequence of windows will appear.

![Select Setup Language](image/1.%20install_3.png)

![License Agreement](image/1.%20install_4.png)

![Select Destination Location](image/1.%20install_5.png)

![Select Additional Tasks](image/1.%20install_6.png)

![Ready to Install](image/1.%20install_7.png)

At the following step, DON'T CHECK the 'Launch Web Browser Cache Folder Changer' checkbox.

![Completing the Web Browser Cache Folder Changer Setup Wizard](image/1.%20install_8.png)

If you check and run the program at this step, following error will happen. This is because Browser Cache Folder Changer needs "privilege permission".

![Unable to execute file.](image/1.%20install_9.png)

### Run the program
Find the icon at the desktop and execute the program!

![Web Browser Cache Folder Changer](image/2.%20execute.png)

When you run the program, following window will appear.

![User Account Control](image/1.%20install_2.png)

As mentioned earlyer, this is because this program needs "privilege permission" to creat a symbolic link file. Choose "Yes" to continue.

Following window will appear.

![Browser Cache Folder Changer](image/3.%20main_1.png)

### Main functions
Browser Cache Folder Changer creates a symbolic link for a browser cache folder.

![Browser Cache Folder Changer with Number](image/3.%20main_2.png)

Here is a typical use-case scenario.

#### 1️⃣ Select a web browser. Here, we choose "Microsoft Edge". Following dialog will appear.

![Select User Profile](image/3.%20main_3.png)

Web browser's cache folder can be different based on the profile name.
If you don't know the profile name, then choose "Default".
If you know the profile name, then choose
- Profile 1
- Profile 2
- or, input custom name.

#### 2️⃣ Select the browser's current cache folder
The default cache foldr path will be available at the edit control. If it does not match, click the "Select the Browser's Default Cache Folder" button and select one.

![Select the Default Cache Folder](image/3.%20main_4.png)

The current cache folder of "Microsoft Edge" may not exist if you had never executed the Edge browser. In that case, run the browser and quit. Then, retry.

#### 3️⃣ Select the RAM Drive web cache top folder
Prepare a web cache top folder. You need to install the RAM drive application and configure in advance.

Here, we assume that "R:\webCacehTop\" is the web cache top folder.
Click the "Select a RAM Drive Folder (ex: R:\webCacheTop)" button and choose one.

![Select the Web Cache Top Folder](image/3.%20main_5.png)

Now, the Browser's New Cache Folder will be specified as followings.

![New Cache Folder](image/3.%20main_6.png)

You can see that "R:\webCacheTopFolder\edgeCache" is specified.

#### 4️⃣ Redirect cache folder
Now, by clicking "Redirect Cache Folder" button, you can create symbolic link for the "Browser's New Cache Folder".

C:\Users\CacheFolderChanger\AppData\Local\Microsoft\Edge\User Data\Default\Cache\Cache_Data
-->
R:\webCacheTop\edgeCache

If you click the "Redirect Cache Folder" button, you may meet the following error window.

![Process Check Error](image/3.%20main_7.png)

It means that the Microsoft Edge browser is running. If the browser process is running, we cannot change the browser's cache folder path. You should quit the browser and tr-try.

If you succeed in redirecting the browser's cache folder to a new cache folder path, then following window will appear.

![Redirect Cache Folder Success](image/3.%20main_8.png)

Also, the new cache folder will be appeared in the explorer.

#### Check if the browser cache folder is redirected successfully
We can check if the browser's cache folder is redirected successfully.
- Run the Microsoft Edge browser and check if the cache files are created successfully at the new cache folder.
    - ![Cache files](image/3.%20main_9.png)

#### 5️⃣ Restore cache folder
If you want to undo the browser's cache folder change, then click the "Restore Cache Folder" button. Note that you should select the browser 1st before clicking the "Restore Cache Folder" button.


### 6️⃣ RAM Drive Applications
There are several RAM Drive applications.
- [ImDisk](https://sourceforge.net/projects/imdisk-toolkit/)
- [AMD Radeon(TM) RAMDisk](https://www.radeonramdisk.com/software_downloads.php)

### 7️⃣ There are several ways to help this program.
- [Go for DRAM shopping!!!](https://semiconductor.samsung.com/dram/ddr/ddr5/?cid=us_pd_ppc_google_b2b_none_sem-b2b_text_b2b_samsung%20ddr5&utm_source=google&utm_medium=pd_ppc&utm_campaign=us_b2b_none_sem-b2b&utm_content=text_b2b&utm_term=samsung%20ddr5&gad_source=1)
- [GitHub (Browser Cache Folder Changer)](https://github.com/kmscom/Browser-Cache-Folder-Changer)
- [Support Developer if you like this application ($1)](https://www.paypal.com/paypalme/CacheFolderChanger?country.x=US&locale.x=en_US)

### 8️⃣ Quit the program
You can quit the program by clicking "Quit" button.

### 9️⃣ Open Log
You can open the log file, in which the execution log is available.

### 🔟 Open Folders
You can open each folder at the explorer by clicking "Open" button.
