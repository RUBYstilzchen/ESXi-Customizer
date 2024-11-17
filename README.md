# Requirements
>The script runs on Windows XP or newer (both 32-bit and 64-bit) including the latest version Windows 8.1 and Server 2012 R2. It does not work with Windows 10!

>For customizing ESXi 4.1 Windows 7 (32-bit or 64-bit) or Windows Server 2008 R2 and administrative privileges are required.

>You need to have a copy of the original VMware install-ISO. It is available at VMware (free registration required to download). The script currently supports ESXi version 4.1, 5.0, 5.1 and 5.5.

>For ESXi 4.1 you need to have a OEM.tgz file with a custom driver.

>For ESXi 5.x you need to have a OEM.tgz, a VIB file or an Offline Bundle ZIP file.

>A good source for 5.x community drivers is the [V-Front Online Depot](https://vibsdepot.v-front.de/)


# Instructions
>Download the latest version of the ESXi-Customizer script (see Download section below). Since version 2.0 it is distributed as a signed self-extracting archive (created with 7-zip). Unpack the archive to a directory of your choice.

>Run ESXi-Customizer.cmd from the installation directory.

>A GUI will show up that lets you select the original VMware install-ISO, the customization file and a working directory for the script.

>For TGZ files you can choose a repacking option: The default is Force repacking, because this is how older versions behaved, other choices are Do not touch and Force repacking and pause for advanced editing. Hover your mouse over these options to get tooltips displayed with information on their purposes.

>Please use the update check feature if possible to be informed about updates of this script.

>Press the Run!-button to start the customization process.

>The script will auto-detect the ESXi version.

>If you try to customize an ESXi 4.1 media and you do not have administrative privileges or have UAC (User account control) enabled in Windows you will be prompted to allow the script to run with administrative access. Enter the credentials of an administrative user if needed and select Yes to continue.

>The customized ISO file that is produced by the script will be stored in the working directory, together with a detailed log file (that is necessary for troubleshooting in case something goes wrong).

# [Source - v-front](https://www.v-front.de/)
