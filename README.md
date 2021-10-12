# QiU

QiU is a free Open Source solution to automate and grow whatever you want, wherever you are. 

This project is based on numerous Open Source ideas and tutorials of amazing people contributing to a better world, the objective of QiU is to develop a complete professional solution as cheap as possible to accelerate de adoption of smart agriculture.


### Learning Sources and Thanks!
<details>
 <summary>Expand to learn!</summary>

```
```
  
### Led Gardener OpenGarden
[Github](https://github.com/ledgardener/gardenAutomation)

### Hydroponics / Gardening
[Hoocho](https://www.youtube.com/channel/UC2DFOHCzzuSlS8vyrvMq7Ng)

[Simple Greens Hydroponics](https://www.youtube.com/channel/UCaS_KzwSmTVuWvR1xTsllwA)

[Epic Gardening](https://www.youtube.com/channel/UCSbyncU597LMwb3HhnAI_4w)

[Kyle Gabriel](https://www.youtube.com/channel/UCA4gOP4kv3uYbPybAraDuUw)


### Home Assistant / Node-red / Hardware
[Andreas Spiess](https://www.youtube.com/c/AndreasSpiess)

[The Hook Up](https://www.youtube.com/channel/UC2gyzKcHbYfqoXA5xbyGXtQ)

[Steve Cope](https://www.youtube.com/user/stevecope)

[Electronic Clinic](https://www.youtube.com/channel/UCo1jouP-SEy7Pjrk1p-lDaQ)

```
```
</details>

#### The Idea :
* Create a PCB that can sense and control everything you need to grow whatever you want
* Cheap, Easy to find and repair components
* Simple to implement
* Future Proof
* Open source


## Why QiU Exists?

#### TL;DR

There isn't enough food, and climate change + soil erosion will make farming production a nightmare for most of the population.
[National Geographic: The Future of Food](https://www.nationalgeographic.com/foodfeatures/feeding-9-billion/)


#### TS;WM
* The earth eventually will have to support around 12Bn people. [Wikipedia](https://en.wikipedia.org/wiki/Projections_of_population_growth) 
* we have to grow in the next 30 years the same amount of food that in the past 10.000 years combined.
* Fertile land is reducing really fast. 60% less land by 2070 [EU Science Hub](https://ec.europa.eu/jrc/en/news/global-soil-erosion-projected-be-worse-previously-expected)

## Uff. Let's solve it

QiU Specs:
- Input: 100-240VAC and 12VDC
- Processor: [ESP32-WROOM-32 WiFi+BLE](https://lcsc.com/product-detail/WiFi-Modules_Espressif-Systems-ESP32-WROOM-32_C82899.html)
- High Voltage Control: 7 x [ 100-220VAC 10A Relays](https://lcsc.com/product-detail/Power-Relays_Ningbo-Songle-Relay-SRD-05VDC-SL-C_C35449.html)
- Dosis Pumps: 6 x [0-12VDC Motor Driver](https://www.lcsc.com/product-detail/Motor-Driver-ICs_HGSEMI-L293DN_C434590.html)
- Low Voltage control: 3 x [0-12VDC 200mA 2N3904S-RTK](https://www.lcsc.com/product-detail/Transistors-NPN-PNP_KEC_2n3904S-RTK-P_2n3904S-RTK-P_C18536.html) 
- Light Control: 2 x [0-10VDC PWM](https://www.lcsc.com/product-detail/Optocouplers-Phototransistor-Output_Sharp-Microelectronics-PC817X2CSP9F_C66405.html) for compatible Led Drivers
- Temperature & Humidity: 1 x [BME280](https://lcsc.com/product-detail/Humidity-Sensors-Temperature-and-Humidity-Sensors_Bosch-Sensortec-BME280_C92489.html)
- Flood Sensors: 4 x [Sensors](https://www.aliexpress.com/item/32562744759.html?spm=a2g0s.9042311.0.0.70ef4c4dyahqkG)
- Weight Scale: 4 x 50kg Scale [HX711](https://www.aliexpress.com/item/32786655201.html?spm=a2g0s.9042311.0.0.70ef4c4dyahqkG)
- Ph Sensor: 1 x [PH 0-14 Sensor](https://www.aliexpress.com/item/1005002973899737.html?spm=a2g0s.9042311.0.0.70ef4c4dyahqkG)
- EC Sensor: 1 x [TDS Analog Sensor](https://www.aliexpress.com/item/1005003343459012.html?spm=a2g0s.9042311.0.0.70ef4c4dyahqkG)
- OLED Display: 1 x [128x64 OLED Display](https://www.aliexpress.com/item/32957392300.html?spm=a2g0o.productlist.0.0.7f3a5dd8rtcThQ&algo_pvid=81bb12a4-6b82-4953-ae34-5724fe5d0fa6&aem_p4p_detail=2021101209184112938460683862600027638738&algo_exp_id=81bb12a4-6b82-4953-ae34-5724fe5d0fa6-1&pdp_ext_f=%7B%22sku_id%22%3A%2210000002569065727%22%7D) 
- Laser Water Sensor: Up to 3 [TOF10120 Sensors](https://www.aliexpress.com/item/1005003301622057.html?spm=a2g0s.9042311.0.0.70ef4c4dyahqkG)


### Where to get the schematics and board:
[Link to EasyEDA](https://oshwlab.com/project/join/1434277bf96d4e55b25e27bfc97eff9a)

### How to buy one:
You can manufacture the board directly to the factory in EasyEDA (click Fabrication in the menu) and get it shipped to your house with components soldered. You can order from 1 unit. 

I don't take any commision for the sales, if you would like to help you can 
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/jnrivera)


### How expensive is QiU?
Price depends on amount of units and where is shipped but in general each board costs around:
- PCB: 
- Assembly service:
- Shipping:
- Components: 38.2USD


![alt text](https://github.com/jnrivra/QiU/blob/main/Images/PCB_sections.png)

<img src="https://github.com/jnrivra/QiU/blob/main/Images/PCB_3D.png" width="30%"></img> <img src="https://github.com/jnrivra/QiU/blob/main/Images/PCB_Board.png" width="30%"></img> <img src="https://github.com/jnrivra/QiU/blob/main/Images/PCB_Silk.png" width="30%"></img> 



![alt text](https://github.com/jnrivra/QiU/blob/main/Images/3D_Apartment_MicroFarm.png)










# Hydroponics system

I'm creating a hydroponics system for my own apartment

* cheap
* 


To-Do:
* Upload Raspberry Image "plug and play" with Home Assistant and everything ready to go.

# A collapsible section containing markdown
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>

# A collapsible section containing code
<details>
  <summary>Click to expand!</summary>
  
  ```javascript
    function logSometing(something) {
      console.log(`Logging: ${something}`);
    }
  ```
</details>

# How to structure
```
# A collapsible section with markdown
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>
```
**Two important rules:**
1. Make sure you have an **empty line** after the closing `</summary>` tag, otherwise the markdown/code blocks won't show correctly.
2. Make sure you have an **empty line** after the closing `</details>` tag if you have multiple collapsible sections.








# Foobar

Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
