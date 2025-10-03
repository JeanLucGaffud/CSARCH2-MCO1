# Custom Desktop PC Build – Group 3

**Course**: CSARCH2  
**Section**: S20  
**Group Members**:  
- LANZ WYNEL CHOI  
- JEAN LUC GAFFUD
- MARK GABRIEL PINEDA
---

## 1. Introduction
Briefly describe your project build (1–2 paragraphs).  
Mention: target use case (e.g., general-purpose desktop, gaming, programming, data science, etc.) and budget constraint.

As Group 3, we were tasked on building a Intel-based, entry-level gaming PC with good performance for its price and targeting the goal of being able to run 1080p AAA gaming at 60+ FPS with high graphics settings. 

Built within a strict budget of PHP 60,000, we prioritized current-generation components that are new and availble in Metro Manila retailers like PC Express, Villman, etc. With these restrictions, every parts must be carefull selected for compatibility and performance with every peso spent wisely.

---

## 2. Draft Build (PCPartPicker)
This build uses **PCPartPicker System Builder** for compatibility check. 
PCPartPicker Permalink: https://pcpartpicker.com/list/3Xvyh7 

### Summary Table 
| Component       | Model | Price (USD) | Notes |
|-----------------|-------|-----------------|-------|
| CPU             | Intel Core i5-14400 2.5 GHz 10-Core Processor  | 257.99          | ...   |
| CPU Cooler      | Cooler Master Hyper 212 Black Edition 42 CFM CPU Cooler   | 25.49            | may require a separately available mounting adapter to fit the Asus PRIME H610M-K Micro ATX LGA1700 Motherboard.  |
| Motherboard     | Asus Prime B760M-K Micro ATX LGA1700 Motherboard   | No Prices Available (but I found a listing for 149.73)            | may require a bios update before using with CPU, A USB 2.0 to USB 3.2 Gen 1 header adapter is required, A USB 3.2 Gen 1 to USB 3.2 Gen 2 header adapter is required. No Wifi or Bluetooth. |
| RAM             | Kingston FURY Beast 16 GB (1 x 16 GB) DDR5-5200 CL40 Memory  | 52.99             | ...   |
| Storage 1       |Samsung 990 EVO Plus 1 TB M.2-2280 PCIe 5.0 X2 NVME Solid State Drive | 69.98             | ...   |
| Storage 2       | Omitted  | ...             | ...   |
| Graphics Card   | MSI VENTUS 2X PLUS OC GeForce RTX 5060 Ti 8 GB Video Card  | 249.95             | ...   |
| Power Supply    | MSI MAG A650BN 650 W 80+ Bronze Certified ATX Power Supply  | 70.11           | ...   |
| Case            | NZXT H5 Flow (2024) ATX Mid Tower Case  | 89.99           | When the MSI VENTUS 2X PLUS OC GeForce RTX 5060 Ti 8 GB Video Card is used, the maximum depth for the NZXT H5 Flow (2024) ATX Mid Tower Case front radiator mount is reduced to 183 mm.   |
| Case Fans       | ...  | ...             | ...   |
| **Total**       |       | **966.23 USD**     |       |

---

## 3. Local Manila Build
This build uses **locally available parts** from Manila vendors.
Google spreadsheet link: https://docs.google.com/spreadsheets/d/1Z_oQBfhuihaOc44S0NKI8P9-z9PhoQGjrI0pvw9muhs/edit?usp=sharing


### Local Build Table
| Component       | Model       | Vendor & Link      | Price (Php) | Compatibility Notes                  |
|-----------------|-------------|--------------------|-------------|--------------------------------------|
| CPU             | Intel Core i5-14400        | DynaQuest (https://dynaquestpc.com/products/intel-core-i5-14400-20m-cache-up-to-4-70ghz-lga-1700-processor-tray?variant=50528540262693) | 10,135.00         | Socket LGA1700 compatible with B760M |
| CPU Cooler      | COOLER MASTER HYPER 212 SPECTRUM V3 RGB CPU Cooler Fan         | PCExpress (https://pcx.com.ph/products/cooler-master-hyper-212-spectrum-v3-rgb-cpu-cooler-fan?_pos=2&_sid=9b04ad997&_ss=r)    | 1,300.00         | may require a separately available mounting adapter to fit the Asus PRIME H610M-K Micro ATX LGA1700 Motherboard. |
| Motherboard     | Asus Prime B760M-K D5 mATX (LGA 1700) Motherboard         | DynaQuest (https://dynaquestpc.com/products/asus-prime-b760m-k-d5-matx-lga-1700-motherboard?_pos=1&_psq=b760m&_ss=e&_v=1.0) | 6,645.00       | may require a bios update before using with CPU, A USB 2.0 to USB 3.2 Gen 1 header adapter is required, A USB 3.2 Gen 1 to USB 3.2 Gen 2 header adapter is required. No Wifi or Bluetooth.                   |
| RAM             |  KINGSTON 16GB DDR5 5200MHZ FURY BEAST BLK RAM       | PCExpress (https://pcx.com.ph/products/kingston-16gb-ddr5-5200mhz-fury-beast-blk-ram?_pos=6&_sid=9b46094e6&_ss=r) | 2,700.00      | DDR5-5200 CL40; matches motherboard spec               |
| Storage 1 (SSD) |   SAMSUNG 1TB 990 EVO PCIe NVMe M.2 Solid State Drive    | PCExpress (https://pcx.com.ph/products/samsung-1tb-990-evo-pcie-nvme-m-2-solid-state-drive?_pos=1&_sid=549f94013&_ss=r) | 4,800.00        | PCIe 4.0 NVMe M.2, supported by motherboard              |
| Storage 2 (HDD) | Omitted        |  | 0       | Justification: 1TB sufficient for OS and games              |
| GPU             |  MSI GeForce RTX™ 5060 Ti VENTUS 2X PLUS 8GB GDDR7 128-bit Graphics Card      | PCExpress (https://pcx.com.ph/products/msi-geforce-rtx-5060-ti-ventus-2x-plus-8gb-gddr7-128-bit-graphics-card?_pos=6&_sid=e57fb8157&_ss=r)   | 26,100.00    | PCIe 4.0 x16; requires 1×8-pin PCIe which PSU supports it|
| PSU             | MSI 650W MAG A650BN 80+ Bronze True Rated Power Supply         | PCExpress (https://pcx.com.ph/products/msi-650w-mag-a650bn-80-bronze-true-rated-power-supply?_pos=10&_sid=80047324f&_ss=r) | 3,150.00        | 80 Plus Bronze certified for high efficiency|
| Case            | NZXT H5 Flow TG (2024) ATX Mid-Tower       | DynaQuest (https://dynaquestpc.com/products/nzxt-h5-flow-tg-2024-atx-black-case-cc-h52fb-01?_pos=6&_psq=nzxt+flow&_ss=e&_v=1.0)   | 4,850.00         | When the MSI VENTUS 2X PLUS OC GeForce RTX 5060 Ti 8 GB Video Card is used, the maximum depth for the NZXT H5 Flow (2024) ATX Mid Tower Case front radiator mount is reduced to 183 mm.|
| Case Fans       | two 120mm Quiet Airflow fans       | included with the case    | 0         | Case includes 2×120mm front and 1×120mm rear fans pre-installed in the case                     |
| **Total**       |             |                    | ***PHP 59,680.00*** | Within budget ✅ ***YES***                       |

---

## 4. Compatibility Justification
For each part, explain compatibility and choices.  
Example:  
- **CPU + Motherboard**: The Intel Core i5-14400 uses the LGA1700 socket and is fully supported by the ASUS Prime B760M-K D5 motherboard, which features an LGA1700 socket and B760 chipset with out-of-the-box compatibility for 14th Gen Intel CPUs. The motherboard is capable for provided a stable power supply for the CPU.
- **CPU Cooler**: COOLER MASTER HYPER 212 SPECTRUM V3 RGB CPU Cooler Fan supports LGA1700 mounting, dimensions fits comfortably within the NZXT H5 Flow case
- **RAM**: The Kingston FURY Beast 16GB (2×8GB) DDR5-5200MHz matches the motherboard’s DDR5 memory and operates within its supported speed range 
- ***Storage 1**: The Samsung 990 EVO 1TB NVMe M.2 SSD utilizes a PCIe 4.0 x4 interface, which is fully supported by the motherboard’s primary M.2 slot (PCIe 4.0 x4).
- ***Storage 2***: We chose not to include this since 1TB NVMe SSD provides ample space for the operating system and multiple AAA games, but motherboard includes SATA ports should future expansion be needed.
- ***GPU***: The motherboard has a PCIe 4.0 x16 slot, which is fully compatible with the RTX 5060 Ti’s PCIe interface.
- ***PSU***: MSI 650W MAG A650BN 80+ Bronze True Rated Power Supply has 80+ Bronze rating to ensure a reliable and efficient power supply and it includes the required 1×8-pin for the RTX 5060
- ***Case+Case Fans***: The NZXT H5 Flow TG that supports micro-ATX motherboards like our B760M board and offers pre-installed fans, and provides ample space for both the GPU and CPU cooler. Equipped with 2 120mm fans (front and rear), it provides balanced airflow and this 2-for-1 deal.

---

## 5. Budget Analysis
- **Budget Limit**: ₱60,000  
- **Final Total**: ₱59,680  
- ✅ Within budget
- Notes on trade-offs (e.g., cheaper RAM, higher PSU wattage, no aftermarket cooler, etc.).
- ***Prioritized GPU over secondary storage***: We allocated a significant portion of the budget (₱26,100) to the RTX 5060 Ti, which is essential to achieving our target of 60+ FPS in AAA games at 1080p high settings. As a result, we could not put more resource in other parts like skipping out on a 2nd storage unit.
- ***Striking the balance between costs instead of more expensive options***: For instance, we chose a low price cooler instead of a high-end on to save on cost for the GPU. We opted for reliable but budget-friendly options, balancing the cuts in cost to affording more suitable components to fit the requirements.
- ***Lack of Bluetooth and Wi-Fi connectivity of the motherboard***: We prioritized performance-to-cost ratio over quality of life features of the motherboard's bluetooth and wifi.
---

## 6. Conclusion & Learnings
Reflections on:  
- Price differences (international vs. Manila vendors)  
We observed that local prices in Metro Manila are significantly higher compared to USD. For example, the MSI GeForce RTX™ 5060 Ti VENTUS 2X PLUS 8GB GDDR7 128-bit Graphics Card costs 249.95 USD (14,512.85 PHP) compared to the 26,100 PHP one sold by Manila vendors. This shows the impact of import taxes, shipping, and local distribution costs on pricing. As a result, we have to take local prices more into consideration if we actually want to build this PC.

- Challenges in finding stock or cheaper equivalents  
While we were able to find cheaper components to fit our budget, it was very close to hitting the PHP 60,000 budget limit. This also taught us the value of checking multiple vendors because we were able to find some amazing deals like the case that came with fans limited, but sometimes compremises have to trade off more expensive high-end options for poor but still reliable ones.

- What the group learned about PC components and system design  
We learned that PC building is not just about find the most expensive and powerful parts, but about planning ahead to figure out if certain components match the specifications of others, for instance, selecting an LGA1700 CPU for cooler compatibility. The project allowed us to evaluate our skills of cost-trade off and compatibility to build a PC whose performance can meet our specifications.

---
## 7. Video pitch
- Your video link here  

## 8. References
- PCExpress Link: https://pcx.com.ph/pages/download-pc-express-pricelist 
- DynaQuest Link: https://dynaquestpc.com/ 
- PCPartPicker Link: https://pcpartpicker.com/list/3Xvyh7 
- Google spreadsheet link: https://docs.google.com/spreadsheets/d/1Z_oQBfhuihaOc44S0NKI8P9-z9PhoQGjrI0pvw9muhs/edit?usp=sharing 
- https://www.newegg.com/asus-motherboards-intel/p/1JW-000C-01705#:~:text=ASUS%20Prime%20B760%2DPLUS%20Intel,%24195 (site where I found the USD price listing for Asus Prime B760M-K Micro ATX LGA1700 Motherboard since PCPartPicker does not have it)

