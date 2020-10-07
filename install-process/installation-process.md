# Installation Process

### Setting up config.plist

I hope you have downloaded the repository I told you to.. If you haven't then [download it from here!](https://github.com/mvaisakh/Asus-X505ZA-Ryzen-Hackintosh/archive/master.zip)

P.S.: If you already have setup a config.plist from Dortania Guide, then you wouldn't need to do this.

Extract the downloaded archive to a folder. Head over to OpenCore folder in the archive and copy it to the newly created USB stick's EFI folder \(Should be named as BOOT\). 

**Copy over the** [**config.plist**](https://github.com/mvaisakh/Asus-X505ZA-Ryzen-Hackintosh/blob/master/OpenCore/config.plist) **to BOOT/EFI/OC/ folder**

**And that's it, you've setup the config.plist!**

**You can also follow the Dortania Clean config.plist import \(If you want to have that learning thrill, and it is highly recommended to do so too!\).**

### **Setting up Kexts**

Kexts are basically drivers, or otherwise known as Kernel Extensions.  
We need a few of them, you should always use the latest versions of each of the kexts.

#### What are the required kexts?

\* [Lilu Kext by acidanthera team](https://github.com/acidanthera/Lilu/releases) \(This is a basic kernel patcher, needed by it's plugins that we'll use\)  
\* [WhateverGreen by acidanthera team ](https://github.com/acidanthera/WhateverGreen/releases)\(Graphics patcher, WIP for us\)  
\* [VirtualSMC by acidanthera team](https://github.com/acidanthera/VirtualSMC/releases) \(SMC Emulation\)  
\* [itlwm by OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm/releases) \(Our WiFi magic\)  
\* [SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor/releases) by [HaoYan Qi](https://github.com/trulyspinach) \(Emulation of AMD Processor, plugin of VirtualSMC\)  
\* [VoodooI2C ](https://github.com/VoodooI2C/VoodooI2C/releases)\[Needed for Keyboard and Touchpad \(which is again WIP for us\)\]  


