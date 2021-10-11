(./README_zh-tw.md) | [English](./README_en-us.md)**<br>
[![Badge](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg?style=flat-square)](https://996.icu/#/en_US)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/ blob/master/LICENSE)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/zhongyang219/TrafficMonitor/Release%20CI?label=Release%20CI&logo=github&style=flat-square)](https:// github.com/zhongyang219/TrafficMonitor/actions?query=workflow:"Release+CI")
[![GitHub release](https://img.shields.io/github/release/zhongyang219/TrafficMonitor.svg?style=flat-square)](https://github.com/zhongyang219/TrafficMonitor/releases/latest )

#TrafficMonitor Introduction
Traffic Monitor is a network speed monitoring floating window software for the Windows platform, which can display the current network speed, CPU and memory utilization, supports embedded in the taskbar display, supports skin replacement, historical traffic statistics and other functions.

# Related Links:

Please [click here](https://github.com/zhongyang219/TrafficMonitor/releases/latest) to download the latest version of TrafficMonitor. <br>
Alternate link: [Baidu network disk download](https://pan.baidu.com/s/15PMt7s-ASpyDwtS__4cUhg) Extraction code: `ou0m`<br>

If domestic users encounter slow downloads on Github, they can [click here](https://gitee.com/zhongyang219/TrafficMonitor) to go to the page of this project on Gitee.

If you encounter problems, please [click here](./Help.md). <br>

You can also [click here](https://github.com/zhongyang219/TrafficMonitor/actions?query=workflow:"Release+CI") to download the pre-release build version of TrafficMonitor.

Starting from version 1.80, TrafficMonitor has added a temperature monitoring function. If you do not need the temperature monitoring function and you encounter problems with the version 1.80 or higher, it is recommended to download the version without temperature monitoring. (Find the version with `without_temperature` in the file name on the Release page.)

# Main features
* Display the current network transmission rate, CPU and memory usage<br>
* If the computer has multiple network cards, it supports automatic and manual network connection selection<br>
* View network details<br>
* Support embedded in the taskbar display<br>
* Support skin replacement and custom skin<br>
* Historical traffic statistics<br>
# Instructions for use

**[Click here](https://github.com/zhongyang219/TrafficMonitor/wiki) Go to the Wiki page to view the detailed documentation on TrafficMonitor. **

# screenshot

Main floating window:<br>
![](./Screenshots/main1.png)<br>
Right-click menu: <br>
![](./Screenshots/main.png)<br>
Taskbar window:<br>
![](./Screenshots/taskbar.PNG)<br>
Colorful skins:<br>
<img src="./Screenshots/skins.PNG" style="zoom:80%;" /><br>

# how to use
After the program is started, a floating window showing the internet speed will be displayed on the screen. Click the right mouse button on the floating window to pop up the right-click menu.

TrafficMonitor supports displaying information to the taskbar. But TrafficMonitor only displays the main window (floating window) by default. If you need to embed it in the taskbar display, please select the "Show taskbar window" command in the right-click menu.

The taskbar window supports custom display items. By default, only the network speed is displayed. If you need to display the CPU and memory utilization, please check the items that need to be displayed under the "Display Settings" submenu in the taskbar right-click menu, as shown in the figure below Shown:

<img src="./Screenshots/taskbar_item_settings.png" style="zoom:80%;" />

# Custom skin
<img src="./Screenshots/selecte_skin.png" style="zoom:80%;" /><br>
Select "Other Functions"-"Change Skin" on the right-click menu of the icon in the main window or notification area to open the skin change interface. [Click here](https://github.com/zhongyang219/TrafficMonitorSkin/blob/master/skin download.md) can download more skins. Users can also edit their own skins according to their needs. <br>
The skin files are placed in the `skins` directory of the directory where the program is located. Each skin is placed in a separate folder. The name of the folder is the name of the skin. <br>
Among them, `background.bmp` and `background_l.bmp` are background images, and `skin.ini` is the skin configuration file. You can specify text color, font, skin author, size and position of each item through `skin.ini` And other information. <br>

The skin configuration file `skin.xml` in xml format has been added since version 1.80. Only the skin configuration file in xml format supports the display of temperature and graphics card usage.

For detailed skin making tutorial, please [click here](./skin making tutorial.md). <br>
It is recommended to use [Skin Editor](https://github.com/zhongyang219/TrafficMonitorSkinEditor/releases) to create or edit skins. <br>

# Option settings
<img src="./Screenshots/option.jpg" style="zoom:80%;" /><br>
In the right-click menu, select "Options..." to enter the option settings. In the option setting dialog box, you can individually set the text color, font, background color, network speed unit, displayed text, etc. of the main window and taskbar window. <br>
In the "General Settings" tab, you can set whether to automatically check for updates during the program, and whether to automatically run when the program is turned on. You can set when you need to send a message notification. <br>
Starting from version 1.72, the text color of each item can be set individually. After checking "Specify the color of each item", click the color box to the right of "Text color", a dialog box for detailed color settings will pop up, where you can specify the color of each item individually. <br>

# About the hardware monitoring function

Starting from version 1.80, TrafficMonitor has added hardware monitoring functions (including temperature monitoring and graphics card usage monitoring), and it uses a third-party open source library [LibreHardwareMonitor] (https://github.com/LibreHardwareMonitor/LibreHardwareMonitor). If you encounter problems when using the temperature monitoring function, please [click here](./Help.md#13-About the trafficmonitor temperature monitoring problem).

It should be noted that the temperature monitoring function is turned off by default. If you want to use the temperature monitoring function of TrafficMonitor, please go to ["Option Settings"-"General Settings"-"Hardware Monitoring"](https://github.com/ zhongyang219/TrafficMonitor/wiki/options#hardware monitoring).

**Note: The hardware monitoring function (including temperature monitoring and graphics card usage monitoring) may have some problems, it may take up more CPU and memory. According to feedback from some users, turning on the temperature function will cause problems such as program crashes and system crashes. Please decide to turn on the hardware monitoring function after you are aware of the above risks. Otherwise, please do not use the hardware monitoring function. **

# Update log

**[Click here to view the update log](./UpdateLog/update_log.md)**

# About this project's warehouse on Gitee

The repository on Gitee is only used as a backup of the GitHub repository. All my code submissions are made on GitHub. The Gitee repository will synchronize the updates of the GitHub repository from time to time. Therefore, the repository on Gitee does not accept any pull requests. If you want to contribute your code to TrafficMonitor, please submit your pull request on GitHub.
