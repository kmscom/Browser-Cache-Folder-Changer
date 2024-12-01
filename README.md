# Web Browser Cache Folder Changer
This repository distributes a Windows application, using which we can change the cache folder path of popular web browsers.
- BrowserCacheFolderChanger.exe

This program redirects the browser's cache folder to a new folder, which is usually located at the RAM drive. For the technical details, refer following web link.
- [Moving Chrome cache folder?](https://superuser.com/questions/866016/moving-chrome-cache-folder)

By redirecting the cache folder to a RAM drive,
- You can run the web browser fast.
- You can reduce IO on your disk. If you are using an SSD, this can help increase the lifetime(V.V).

If your RAM drive supports data backup and restoration through the power cycle, the cache data will be persistent. Othersize, the cache data will be lost. Even when the RAM drive supports data backup and restore through the power cycle, the browser cache data can be lost if a sudden power off happens.

This application supports the following web browsers.
- [Brave](https://brave.com/)
- [Google Chrome](https://www.google.com/)
- [Microsoft Edge](https://www.microsoft.com/edge/)
- [Naver Whale](https://whale.naver.com/)
- [Opera](https://www.opera.com/)
- [Vivaldi](https://vivaldi.com/)

This program creates a symbolic link for the browser's cache folder to a new path, which is usually under a RAM drive. To create a symbolic link, an administrator privilege is required.

Use this application at your own risk. This application DOES NOT SUPPORT any issue caused by this program.
