## T440P Hackintosh Install ``` Unfinished ```
[Windows](#windows) | [Linux](#linux) |
--- | --- |

#### What doesnt work:
* Dell 1820A
* Nvidia dGPU
* Synaptics trackpad (gestures dont work out of the box)


<h2 name="windows">Windows 10 Install</h2>

### What you need:
* T440p with Patches bios.
* 8GB USB.
* [TransMac](https://www.acutesystems.com/scrtm.htm).


<h2 name="linux">Linux Install</h2>

### What you need:
* T440p w/Patches bios.
* 8GB USB.
* [TransMac](https://www.acutesystems.com/scrtm.htm).


### GET MACOS MOJAVE
You can use the [gibMacOS](https://github.com/corpnewt/gibMacOS) tool to get clover and your .dmg file.

### Step 1 - BIOS Setup
Provided you have already patched the bios.

1. Enter BIOS and set:
### Security menu:
Memory Protection > Execution Prevention: must be Enabled,
Virtualization > Intel Virtualization Technology: must be Disabled,
Internal Device Access > Bottom Cover Tamper Detection: must be Disabled,
Anti-Theft > Current Setting: must be Disabled,
Anti-Theft > Computrace > Current Setting: must be Disabled,
Secure Boot > Secure Boot: must be Disabled.
## Startup menu:
UEFI/Legacy Boot: Both,
UEFI/Legacy Priority: UEFI First,
CSM Support: Yes.

## Step 2 - Create a bootable usb
Create a Clover usb 

1. Extract folder and run the gibMacOS .bat file
2. Pick latest MacOS version.
3. Download (might take 5min).
4. After download, open MakeInstall.bat and choose your drive.
5. When prompted for the Recovery pkg file, just CTRL+C+V the directory to which MacOS downloaded to.

## Step 3 
1. TransMac - to 

## Step 4

## Step 5 - Booting into Clover
![clover](https://i.redd.it/np7ai9qbdld21.png)

### Sources & Links:
https://internet-install.gitbook.io/macos-internet-install/ - Full (but generic) hackintosh install guide
