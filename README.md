<h1>QiU<br>
Grow Anything.</h1>

<a title="License MIT" href="https://github.com/xnbox/DeepfakeHTTP/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square"></a>
<a title="Release 0.8" href="https://github.com/xnbox/DeepfakeHTTP/releases"><img src="https://img.shields.io/badge/release-5.1.1-4DC71F?style=flat-square"></a>
<a title="Powered by jnrivera" href="https://github.com/jnrivra"><img src="https://img.shields.io/badge/powered_by-Tommy-blueviolet?style=flat-square"></a>

<p align="center">
<a href="#learning-sources-and-thanks">Learn</a> | <a href="#uff-lets-solve-it">Specs</a> | <a href="#where-to-get-the-schematics-and-board">Download</a> | <a href="#how-to-buy-one">Make one</a> |<a href="https://www.buymeacoffee.com/jnrivera">Donate</a> | <a href="https://linkedin.com/in/jnrivra">Contact Me</a> | <a href="https://opensource.org/licenses/MIT">License</a>
</p>

<p align="center">
<table>
<tr>
<td>
<img align="left" src="https://github.com/jnrivra/QiU/blob/main/Images/Icon.png" width="190">
<h3>QiU is an Open Source solution to automate and grow whatever you want, wherever you are. </h3>
<ul>
    <li>Create a PCB that can sense and control everything you need</li>
    <li>Cheap, Easy to find and repair components</li>
    <li>Future Proof</li>
    <li>Open Source</li>
</ul>
<img width="1000" height="0">
</td>
</tr>
</table>
</p>


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

![alt text](https://github.com/jnrivra/QiU/blob/main/Images/PCB_sections.png)

### Where to get the schematics and board:
[Link to EasyEDA](https://oshwlab.com/project/join/1434277bf96d4e55b25e27bfc97eff9a)

### How to buy one:
You can manufacture the board directly to the factory in EasyEDA (click Fabrication in the menu) and get it shipped to your house with components soldered. You can order from 1 unit. 

I don't take any commission for the sales but if you want, you can  
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/jnrivera)


### How expensive is QiU?
Price depends on the number of units and where is shipped but in general, each board costs around:
- PCB: 10USD
- Components: 38.2USD
- Shipping: 30USD
Total: 80USD

![alt text](https://github.com/jnrivra/QiU/blob/main/Images/PCB_gif.gif)

<img src="https://github.com/jnrivra/QiU/blob/main/Images/PCB_3D.png" width="30%"></img> <img src="https://github.com/jnrivra/QiU/blob/main/Images/PCB_Board.png" width="30%"></img> <img src="https://github.com/jnrivra/QiU/blob/main/Images/PCB_Silk.png" width="30%"></img> 

# UI

![alt text](https://github.com/jnrivra/QiU/blob/main/Images/UI_Home.png)



# MVP 

In order to test the board, I'm designing a hydroponics system for my apartment. The idea is to have a good looking product made with cheap and easy materials.

The 3D Design is still a work in progress but the general idea:

![alt text](https://github.com/jnrivra/QiU/blob/main/Images/3d_gif.gif)
![alt text](https://github.com/jnrivra/QiU/blob/main/Images/UI_Gif.gif)





# Status of the Project

-   [x] Kick Off, Design, Requirements (1 Oct)
-   [x] PCB Design (7 Oct)
-   [x] Sent to Manufacture (9 Oct)
-   [x] Components Purcharsed (10 Oct)


## Short Term To-do List
-   [x] Manufacture Structure
-   [ ] Install Hydroponics System
-   [ ] Install Electronics and Equipment
-   [ ] Testing 

## What is the future of QiU?

-   [ ] After testing, I will redesign the PCB and upload a single SD image with Home Assistant and everything installed for a RPI (December 2021)
-   [ ] The second part of this project will be the creation of an End Computing node so you can build a complete vertical farm with AI and Machine Learning using 4USD cameras. Biofeedback systems are the future.
       
       If you want to go ahead and start playing, Here is what I would do: (there are no Rpi 4 anywhere so the links are for a CM4 + Expansion
       
       
       | Component | Link |
       | --- | --- |
       | Raspberry Pi Compute Module 4 | [Link Aliexpress](https://www.aliexpress.com/item/1005001848142895.html?src=google&src=google&albch=shopping&acnt=494-037-6276&slnk=&plac=&mtctp=&albbt=Google_7_shopping&albagn=888888&isSmbAutoCall=false&needSmbHouyi=false&albcp=14918626770&albag=131075370209&trgt=489474619664&crea=es1005001848142895&netw=u&device=c&albpg=489474619664&albpd=es1005001848142895&gclid=Cj0KCQjw5JSLBhCxARIsAHgO2SfgPqK6wu8Esv-qE-KF0beukylT3p4Y-LQtYN0YuhFwPtYGu93W8NQaAr2iEALw_wcB&gclsrc=aw.ds&aff_fcid=1d12d46de696499b8ad48e36d574783e-1634073380501-01282-UneMJZVf&aff_fsk=UneMJZVf&aff_platform=aaf&sk=UneMJZVf&aff_trace_key=1d12d46de696499b8ad48e36d574783e-1634073380501-01282-UneMJZVf&terminal_id=baaa587099104045ac6761d6ae30d994) |
       | RPi CM4 Expansion | [Link](https://www.aliexpress.com/item/1005003086145065.html?spm=a2g0o.productlist.0.0.553e599a7rlbLZ&algo_pvid=a9022b7e-bb04-4fef-adf2-4a5fdcbae8fa&algo_exp_id=a9022b7e-bb04-4fef-adf2-4a5fdcbae8fa-49&pdp_ext_f=%7B%22sku_id%22%3A%2212000023993743935%22%7D) |
       | RPi UPS | [Link](https://www.aliexpress.com/item/33008497003.html?spm=a2g0o.cart.0.0.295c3c00lpCyOn&mp=1) |
       | RPi SSD | [Link](https://www.aliexpress.com/item/1005001505371944.html?spm=a2g0o.cart.0.0.7e023c00vcdi9t&mp=1) |
       | ESP32-CAM | [Link](https://www.aliexpress.com/item/1005001322358029.html?spm=a2g0o.productlist.0.0.10bb6d3ewPaSHo&algo_pvid=e44bdea8-616d-40f4-93fe-3bb0a1f4502a&algo_exp_id=e44bdea8-616d-40f4-93fe-3bb0a1f4502a-0&pdp_ext_f=%7B%22sku_id%22%3A%2212000018185630628%22%7D) |

## License
[MIT](https://choosealicense.com/licenses/mit/)
