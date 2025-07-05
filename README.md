OpenCore EFI for Fujitsu U938/S running MacOS Sonoma
My U938 specs:
CPU: Intel Core I5-7300U
RAM: 12GB DDR4
SSD: SATA 128GB
Wifi: AC8265

Everything works except for Airdrop.
The iGPU configs recommended by Dortania's guide does not seem to work on this specific laptop CPU variant, so I modified that to these specific values:
![image](https://github.com/user-attachments/assets/d33e2a87-6980-480d-bdc7-44ea3d64388e)
I am currently using the prebuilt ACPI patches because the SSDTs created by SSDTTime cannot enable me to change the display brightness. 
I also give credits to omjads on YouTube for providing the EFIs of Monterey and Ventura version, these are the groundworks for my version.
