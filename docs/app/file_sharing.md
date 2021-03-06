# File Sharing on GL.iNet Routers

You can use GL.iNet routers with external storage device such as USB stick, MicroSD card, etc,  thus the contents can be shared among all your connected clients. You can easily read or modify its contents. 

---



##Router settings

The contents of the external storage device are shared to LAN but not WAN and they are unwritable by default. Please click on your router model below to check how to change the file sharing settings of the router. 

**Supported external storage devices**


| Router Model | USB Stick | USB Hard Drive | MicroSD Card |
| :----------- | :-------: | :---: | :---: |
| GL-MT300N*   |  √  | √ | - |
| GL-MT300N-V2* |     √     |    √ | - |
| [GL-AR150 Series](https://docs.gl-inet.com/en/3/setup/mini_router/applications/#file-sharing) | √ | √ | - |
| [GL-AR300M Series](https://docs.gl-inet.com/en/3/setup/mini_router/applications/#file-sharing) | √ | √ | - |
| GL-USB150 | - | - | - |
| [GL-MiFi](https://docs.gl-inet.com/en/3/setup/4g_smart_router/applications/#file-sharing) | √ | √ | √ |
| [GL-AR750](https://docs.gl-inet.com/en/3/setup/travel_ac_router/applications/#file-sharing) | √ | √ | √ |
| [GL-AR750S-Ext (Slate)](https://docs.gl-inet.com/en/3/setup/slate/applications/#file-sharing) | √ | √ | √ |
| GL-B1300* | √ | √ | - |

*Firmware 3.0 for this model has not released yet.

*Note: The power consumption of USB hard drive is quite high. You should use it with an external power supply. Otherwise, it may cause malfunction.*

---



##Access the storage device

You can access the contents of the external storage device from your computer or smart phone. Please check the following guidance for the using of file sharing among different operating systems.



### Windows

**1)** Your network must be Home/Private. Otherwise you may not be able to see your router in **Network**. if you are using Win10, you also need to enable SMB 1.0.

- Win7

  Go to Control panel -> Network and Internet -> Network and Sharing Center. Find if your active network is **Home network**. If not, click it and change it to **Home network**.

- Win10

  Go to Control panel -> Network and Internet -> HomeGroup. Click **Change network location**.

  Go to Control Panel -> Programs and Features -> Turn Windows features on or off -> Find SMB 1.0/CIFS file sharing support, check all SMB1 related items, click apply and restart your computer.



**2)** Open a Windows explorer, you can find **Network** in the folder directory. Double click your router to access its contents.

![Network](https://static.gl-inet.com/docs/en/3/app/file_sharing/network.jpg)



### Mac

**1)** Go to System Preferences -> Sharing -> File sharing. Click `Options` and then enable SMB.



**2)** Open Finder. You should be able to find your router under Shared.



###IOS

You have to use file manage app to access the contents of your external storage device.

You may use **FE File Explorer**:

**1)** Click `+` to create a `Windows` connection.

![IOS1](https://static.gl-inet.com/docs/en/3/app/file_sharing/ios11.jpg)



![IOS1](https://static.gl-inet.com/docs/en/3/app/file_sharing/ios12.jpg)

**2)** Enter the **IP address** of your router (192.168.8.1). The **User Name** is root and the **Password** is the one that you use to login the web Admin Panel. Finally, click `Save`.

![IOS1](https://static.gl-inet.com/docs/en/3/app/file_sharing/ios13.jpg)

**3)** Click your newly created connection to access the contents.

![IOS1](https://static.gl-inet.com/docs/en/3/app/file_sharing/ios14.jpg)



### Android

Most Android devices have file manager which you can use to access the contents of your external storage device. Or you can use **ES file explorer**:

**1)** Open the app and then click `Network`.

![android1](https://static.gl-inet.com/docs/en/3/app/file_sharing/android1.jpg)

**2)** Click `Scan` to find your network storage device.

![android2](https://static.gl-inet.com/docs/en/3/app/file_sharing/android2.jpg)

![android3](https://static.gl-inet.com/docs/en/3/app/file_sharing/android3.jpg)