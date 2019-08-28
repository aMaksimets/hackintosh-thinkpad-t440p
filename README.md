T440P Hackintosh guide (specifically for Windows users)
------
#### What doesnt work:
* Dock audio
* NVIDIA dGPU
* etc.

### What you need:
* T440p with Patches bios.
* 8GB USB.
* [TransMac](https://www.acutesystems.com/scrtm.htm).


### GET MACOS MOJAVE
First you need the .dmg of MacOS
To get MacOS just find a trusted torrent for the OS (google around or take to the seas).
#### Alternatively 
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
Windows has the best tool for getting and installing MacOS, to make a bootable drive. Its called [gibMacOS](https://github.com/corpnewt/gibMacOS). 
It requires [Python](https://www.python.org/downloads/) to run.

1. Extract folder and run the gibMacOS .bat file
2. Pick latest MacOS version.
3. Download (might take 5min).
4. After download, open MakeInstall.bat and choose your drive.
5. When prompted for the Recovery pkg file, just CTRL+C+V the directory to which MacOS downloaded to.
## Step 3
1. Open transmac and 
## Step 4
## Step 5
