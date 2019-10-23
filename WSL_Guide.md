# Windows Subsystem for Linux (WSL) 



### Install WSL

Before installing any Linux distros for WSL, you must ensure that the "Windows Subsystem for Linux" optional feature is enabled:



1. Open PowerShell as Administrator and run: 

   ```powershell
   Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-	Subsystem-Linux
   ```

2. Restart your computer when prompted

   ### or

1.  open your Settings menu.

2. In the search bar, type “turn windows features on or off,” click the item from the drop-down box, and a new window will pop up.

   ![image-20191023212401266](image-20191023212401266.png)

5. It may take a few moments to load, but once it’s done there will be a list of features with checkboxes next to them. Scroll down to **Windows Subsystem for Linux** and check the box. This will begin downloading and installing the necessary files. Your computer will then restart, after which the installation is complete.

   

### Install your Linux Distribution of Choice

**Download and install from the Microsoft Store**

1. Open the Microsoft Store and choose your favourite Linux distribution. Ubuntu is beginner friendly.

   The following links will open the Microsoft store page for each distribution:

   - [Ubuntu 16.04 LTS](https://www.microsoft.com/store/apps/9pjn388hp8c9)
   - [Ubuntu 18.04 LTS](https://www.microsoft.com/store/apps/9N9TNGVNDL3Q)
   - [OpenSUSE Leap 15](https://www.microsoft.com/store/apps/9n1tb6fpvj8c)
   - [OpenSUSE Leap 42](https://www.microsoft.com/store/apps/9njvjts82tjx)
   - [SUSE Linux Enterprise Server 12](https://www.microsoft.com/store/apps/9p32mwbh6cns)
   - [SUSE Linux Enterprise Server 15](https://www.microsoft.com/store/apps/9pmw35d7fnlx)
   - [Kali Linux](https://www.microsoft.com/store/apps/9PKR34TNCV07)
   - [Debian GNU/Linux](https://www.microsoft.com/store/apps/9MSVKQC78PK6)
   - [Fedora Remix for WSL](https://www.microsoft.com/store/apps/9n6gdm4k2hnc)
   - [Pengwin](https://www.microsoft.com/store/apps/9NV1GV1PXZ6P)
   - [Pengwin Enterprise](https://www.microsoft.com/store/apps/9N8LP0X93VCP)
   - [Alpine WSL](https://www.microsoft.com/store/apps/9p804crf0395)

    

2.  From the distro's page, select "Get" 

### Setting up your WSL to run ASM code

   **Run the following commands(ubuntu users)**

```bash
sudo apt update
sudo apt upgrade
sudo apt install binutils
sudo apt install gdb
```

