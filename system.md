# System
For the ones curious about the system that I use. 

I like to keep myself updated on the new hardware available in the consumer computing space. I started my journey on a laptop with an Nvidia 940M GPU. I quickly realized that the models created and the data that needed to be processed quickly consumed all the VRAM causing OOM (out-of-memory) issues. In 2020, I invested in a system capable of running my tests locally. My primary focus was not to incur any costs for processing and testing models using the cloud. 

## System configuration (November 2020)
 - CPU: AMD 3700X - (8-cores)
 - Motherboard: MSI MAG X570 Wi-Fi
 - RAM: G.Skill RipJaws V 32 GB @ 3200 MHz (2 x 16 GB kit running in dual channel configuration)
 - GPU: Nvidia GTX 1650 (4 GB of VRAM) - There was a GPU shortage at this time 
 - Power Supply: Corsair RM 650
 - Primary Drive: Western Digital Blue SATA drive (500 GB)
 - Secondary Drive: Seagate Barracuda Hard drive (2 TB)

## Upgrades
### 2023
GPU: (Out) Nvidia GTX 1650  ---> (IN) Nvidia RTX 3060 (12 GB of VRAM)

## Wish-list
Primary Drive: M.2 Gen 4 SSD with a minimum 1 TB

## Parts selection logic
1. 8-core CPU for any multi-threading, multi-processing loads
2. 32 GB is not required for a normal system but is required for "containers". This has also proved useful for testing LLMs locally using "LMStudio"
3. RTX 3060 - effective price per GB of VRAM. AMD does have a good value but CUDA libraries are (currently) the industry standard and run only on Nvidia.
4. X570 - Future-proofing by adding M.2 Gen 4 and I needed all the IO ports.
