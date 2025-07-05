<h2>OpenCore EFI for Fujitsu U938/S running MacOS Sonoma </h2> <br />
My U938 specs: <br />
CPU: Intel Core I5-7300U <br />
RAM: 12GB DDR4 <br />
SSD: M.2 SATA 128GB <br />
Wifi: AC8265 <br />

Everything works except for Airdrop.
The iGPU configs recommended by Dortania's guide does not seem to work on this specific laptop CPU variant, so I modified that to these specific values:
![image](https://github.com/user-attachments/assets/d33e2a87-6980-480d-bdc7-44ea3d64388e) <br />
I am currently using the prebuilt ACPI patches because the SSDTs created by SSDTTime cannot enable me to change the display brightness. <br /> 
I also give credits to omjads on YouTube for providing the EFIs of Monterey and Ventura version, these are the groundworks for my version.
