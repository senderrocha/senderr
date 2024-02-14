# Lessons Learned in Soft Sensory Motor System based on Ionic Solution

# 1 Abbreviation
SSMS-IS: Soft Sensory-Motor System based on Ionic Solution

# 2 Introduction

## 2.1 Abstract 
This project presents a soft sensory-motor system based on an ionic solution (SSMS-IS). The proposed soft transducer-actuator can measure the pressure compression for external forces and simultaneously measure the inner pressure during self-expansion. Also, it can actuate in the environment when inflated. 

This project can contribute to the sensory-motor coordination studies for soft robots since it is able to sense and actuate simultaneously in the environment bringing rapid response performance.

## 2.2 Background knowledge 
There are 3 states of the sensor: relaxed, inflated, and compressed. In the relaxed state, there is no air inlet in the sensor and the variation of the internal and external pressure is null. In the inflated state, there is an air inlet in the sensor and the internal pressure increases making the sensor inflated, once the body is deformable. For the compressed state, the air inlet is null as well, but an external pressure is applied to the sensor, making the sensor compressed. For each state, the electrolyte in the sensor varies its volume consequently variating its internal electric resistance.  

![image](https://github.com/senderrocha/senderr/assets/32946334/1d6d6c57-45ab-4aa3-87fc-9bcf8e318874)

Figure 01: Diagram of the principle of functionality regarding Soft Sensory-Motor System based on Ionic Solution. Three states of the sensor operation: relaxed, compressed and inflated. 

![image](https://github.com/senderrocha/senderr/assets/32946334/a3edaf06-ede1-49b7-a97a-2e8581e025cb)

Figure 02: Soft Sensor Pressure. 

# 3 Design
## 3.1 Component Overview 
The sensor prototypes were manufactured with two main components: the elastomer material that deforms the sensor body in response to internal and external pressure and the ionic sensing gel. The elastomer used was RPRO-30 (Reschimica) mixed in a 1:1 ratio by weight. 

The conductive fluid was fabricated by mixing aloe vera gel (99%) and domestic sodium chloride in a 10:1 ratio by weight. In addition, the ionic fluid was filled with 40% glycerin concentration. The mold forms an elliptical flat-head container with a major radius of 10mm and a minor radius of 7.5mm. The elastomer component was cured in a 3D-printed mold and copper wires were installed inside the body to form an electrical connection. A thin flexible tube of 2mm in diameter was inserted in each prototype to allow the air inlet in the sensor. After, the ionic conductive gel is filled in each prototype. At this point, the rectangular container was sealed with a thin cover layer (1 mm approx.) of RPRO-30 to form the soft sensor. The fabrication procedure of the proposed ionic gel sensors is shown in figure 03. 

![image](https://github.com/senderrocha/senderr/assets/32946334/b1256cdd-0251-4bab-8699-0dd7476ce582)

Figure 03: Fabrication procedure of the SSMS-IS for rectangular geometry.

### 3.1.1	Diagram of the full sensor 
The Soft Sensory-Motor System based on Ionic Solution is composed of two copper electrodes immersed in the ionic solution; one air tube to allow the air inlet in the sensor and the body´s sensor has one thin diaphragm to let the sensor detect the external pressure and expand during the air inlet. 

![image](https://github.com/senderrocha/senderr/assets/32946334/828a5f34-60bb-4aa8-9426-5ef2da54c5e6)

Figure 04: Soft Sensory-Motor System based on Ionic Solution internal components.

## 3.2 Bill of Materials

This section will give a list of items that are used in this project with selected links to suppliers. 

Note: Many of the items listed are just examples and the designer can use your own discretion to substitute parts that are easier or cheaper to obtain. 

### 3.2.1	Molds

This work has four molds to manufacture the SSMS-IS, as shown in the figure below. The fourth mold is composed of three molds: cover layer, middle layer, and bottom layer. Depending on the application proposed the middle layer can be designed with different thicknesses. For example, for projects that demand more robustness is recommended a middle layer with a thicker thickness, but on the other hand, if the application requires more expansion of the diaphragm then the middle layer should have a thinner thickness. 

![image](https://github.com/senderrocha/senderr/assets/32946334/fca4faef-66cf-475f-a768-fdfffc7dc7fe)

Figure 05: Molds to manufacture the SSMS-IS.

![image](https://github.com/senderrocha/senderr/assets/32946334/b41a4fbf-582d-4418-90af-5ce2a7bdc9dc)

![image](https://github.com/senderrocha/senderr/assets/32946334/11a59463-49bf-4a98-9afe-7f899b2a91eb)

![image](https://github.com/senderrocha/senderr/assets/32946334/798362a1-1b2b-418f-80e8-7c77be608c33)

![image](https://github.com/senderrocha/senderr/assets/32946334/cddfa71b-56fa-4c2d-b008-b98efdf0d291)

![image](https://github.com/senderrocha/senderr/assets/32946334/c74114c8-c29f-4762-912a-e48ff0e0fe3a)

![image](https://github.com/senderrocha/senderr/assets/32946334/8de823e6-6a82-4e33-a136-3f4bf985e18b)

#### 3.2.2	Materials

![image](https://github.com/senderrocha/senderr/assets/32946334/36cde441-83b0-4bfa-b549-17d9a7229951)

#### 3.2.3	Tools

![image](https://github.com/senderrocha/senderr/assets/32946334/9bd77525-f5e5-44bf-a2dd-b3a6ad6a55c5)

#### 3.2.4	Equipment

![image](https://github.com/senderrocha/senderr/assets/32946334/a588faca-6201-4495-be56-7fe5a7ad2305)

## 3.3 Material Selection 

### Material
#### Silicon 
RPRO 30 Reschimica

https://www.reschimica.com/gb/silicone-rubbers/123-r-pro-30-liquid-silicone-rubber-for-high-hardness-molds.html

#### Aloe Vera
Vegan 

https://www.apotekhjartat.se/produkt/hjartats-aloe-vera-gel-oparfymerad-60ml/?code=1024054&ab_version=B&gclid=CjwKCAjw3oqoBhAjEiwA_UaLtjmMye_NkfwHSszE5flTnj1QEuAMsa58Gt244jkpA3mifujs0GJ-fxoCbJQQAvD_BwE

#### Glycerol
Unimedic Pharma

https://www.apotekhjartat.se/produkt/glycerol/?ab_version=A&gclid=CjwKCAjw3oqoBhAjEiwA_UaLtmT0mbM6GBN66Z3V1cBiaY-jNZmatHt9bGK687kEaR1a-ld6dFEkvxoCudgQAvD_BwE

#### Salt
Falksalt
https://www.coop.se/handla/varor/kryddor-smaksattare/kryddor-orter/salt/salt-finkornigt-7311631525125

#### Copper wires 
2 x 1mm2 (twist cable) 
https://www.alibaba.com/product-detail/twisted-pair-cable-1mm_60782387943.html

#### Plastic Air tube 
https://www.amazon.com/Hooshing-Silicone-Flexible-Winemaking-Transfer/dp/B08PTVL8L3/ref=sr_1_3?keywords=2mm%2Bdiameter%2Bplastic%2Btubing&qid=1698091404&s=industrial&sr=1-3&th=1

#### 2.54mm pitch female connector pin crimp
https://www.amazon.se/Aussel-kabelkabel-tonh%C3%B6jd-kontakt-krimpanslutning/dp/B01NGU13WC/ref=sr_1_13?crid=1FP68BLQ68WN9&keywords=pussel+200+pcs+2.54mm+pitch+female+connector+pin+crimp&qid=1694722780&sprefix=aussel+200+pcs+2.54mm+pitch+female+connector+pin+crimp%2Caps%2C109&sr=8-13

### Alternate Material description 
#### Silicon
RPRO 20 Reschimica 

https://www.reschimica.com/gb/silicone-rubbers/122-230-r-pro-20-liquid-silicone-rubber-for-medium-hardness-molds.html#/108-packaging-500_gr_250_gr_a_250_gr_b

RPRO 10 Reschimica

https://www.reschimica.com/gb/silicone-rubbers/121-r-pro-10-liquid-silicone-rubber-for-soft-molds.html

Dragon SkinTM10 Fast Smooth-On Inc

https://www.smooth-on.com/products/dragon-skin-10-fast/


## 3.4 Design Optimization
### 3.4.1	Variation: Quantity of the Ionic Solution 
The variation of the ionic solution quantity affects the resistance value of the sensor and the sensibility of the sensor. High quantity of electrolyte reduce the internal resistance (Figure 06). Also, more quantity of electrolyte can limit the space for the sensor inflate reducing its performance for the actuation function. 
To investigate the effects of the quantity of the ionic solution in the sensor, it was designed a dummy sensor with the same internal volume of the real sensor, around 1.27ml. It was added ionic solution in the dummy sensor for increments of 100mg of electrolyte and monitored the variation of the internal resistance using a multimeter. 
Depending on the application it is possible to adjust the quantity of electrolyte in the sensor to attend to the project requirements.   

![image](https://github.com/senderrocha/senderr/assets/32946334/04cb12a6-0468-4030-9171-46086514f147)

Figure 06: Setup tests. Addition of electrolyte in the sensor on the mass scale and simultaneously monitoring of the internal resistance variation using digital multimeter.  

![image](https://github.com/senderrocha/senderr/assets/32946334/cf144571-e7b8-4b6e-afdf-68259313d9e5)

Figure 07: Correlation between internal resistance of the sensor and eletrolyte weight. As much electrolyte is added in the sensor is notice the reduction of the sensor internal resistance. 

![image](https://github.com/senderrocha/senderr/assets/32946334/b4b238dc-ffe6-4a3c-beaa-b69525e10206)

Figure 08. Detailed upper 30mg of electrolyte. It is observed a certain linearity upper this quantity of electrolyte. 

### 3.4.2	Variation: Electrode Distance between 
The variation of the distance between the electrodes affects the internal resistance value of the sensor and consequently its sensibility. For long distances between the electrodes the internal resistance of the SSMS-IS increases as showed in the figure 09. 
To check the influence of the distance variation of electrodes in the sensor resistance it was designed a test setup where it was possible to increment the distances between the electrodes in each 4mm. One of the electrodes remained fixed while the other moved in relation to it. The quantity of electrolyte was defined as 300mg. 
Depending on the project the distance between the sensor’s electrodes can be modified to attend to its requirement. 

![image](https://github.com/senderrocha/senderr/assets/32946334/62cbecf2-eb2b-4fd9-a4de-f4fc34c04597)

Figure 09: Setup test to verify the variation of the internal resistance regarding the variation of the distance between the electrodes. Between the electrodes, it has the same quantity of the electrolyte, varying only the distance between the electrodes. 

![image](https://github.com/senderrocha/senderr/assets/32946334/aff20f31-2caf-472b-ab8d-02db53f04937)

Figure 10: Correlation curve between the distance between electrodes and the internal resistance.  

### 3.4.3	Variation: Electrode Material
The variation of the electrode material can influence in the electrode mechanical endurance for external forces. 
To check this parameter, it was manufactured sensors with electrodes with and without a connector in the wire copper. The connector used for the electrodes with connector was considered the pitch female connector pin crimp composed by copper material. 
Below, it showed sensors with electrodes without connectors had a poor mechanical performances for external forces, showing ruptures in the wire copper. The sensors using a connector showed more mechanical endurance for external pressure in long-term.  

![image](https://github.com/senderrocha/senderr/assets/32946334/f786719f-dc6b-437b-800c-505ab51a8b2b)

Figure 11: Different electrode material: (a) electrode without connector. (b) copper broken in the electrode. (c), (d) electrode with connector. 

### 3.4.4	Variation: Mold Material 
To reduce the cost of the sensor manufacturing, different materials of mold, cheaper in comparison of printer 3D materials, such as cardbox, foam and playdough can be used.
The same performance can be reached but the same precision as the one obtained with the print 3D materials is not guaranteed.

![image](https://github.com/senderrocha/senderr/assets/32946334/ed5fe52e-40f7-45aa-a682-320f4d288abb)

Figure 12: Example of SSMS-IS fabrication using cardbox as the mold.

### 3.4.5	Variation: Elastomer
The variation of the elastomer material results in different sensor characteristics especially regarding hardness. Elastomer with low level of shore hardness scale presents best stretchability range performance during the inflation mode. For the compressibility, it also can be observed a greater range of deformability. Consequently, less external and internal pressure need to be applied for the sensor´s performance. To test the variation of the material, some sensors have been fabricated using three different models of elastomers (two brands), as shown in the table below.  

![image](https://github.com/senderrocha/senderr/assets/32946334/e019baa6-62d4-4c17-859b-85ce592575d5)
Figure 13: Elastomer variation.

![image](https://github.com/senderrocha/senderr/assets/32946334/b9c55d84-c07c-4d20-8101-c91cf1d51f07)

Figure 14: Variation of the elastomer material. The yellow silicon has shore hardness of 30A and on the blue silicon has shore hardness of 20A. 

# 4 Fabrication
This section contains detailed step-by-step instructions for casting a Soft Sensory-Motor System based on Ionic Solution (SSMS-IS). The figures in this section describe the fabrication process regarding the silicon rubber RPRO30 but the same process can be done with other options of elastomers, as mentioned in the section 3.2. 

## 5.1 Process Overview 
As explained in the previous sections, the SSMS-IS consists of two main parts: the main body and the cover layer. 
The main body contains the ionic solution, air tube and copper wires. And the cover layer builds the sensor´s diaphragm that allows to inflate or to compress. 
The two parts are molded separately and then glued together. Without the use of an oven to accelerate the curing process, the sensor parts can be cast and assembled in less than 24 hours. An overview of the process is provided below.

![image](https://github.com/senderrocha/senderr/assets/32946334/d0ec33ff-3bb0-4226-923a-0593e57837c3)

![image](https://github.com/senderrocha/senderr/assets/32946334/b3d4390c-de49-4ad8-bc05-75e96f7badbc)

## 5.2 Step1: Mold body layer
### 5.2.1	Measure 
Elastomer needs to be mixed in a 1:1 ratio (by weight) of PartA: PartB. In this example we will prepare a total of 3g of elastomer. This step needs to use the mold#1. 
(Note: if you are using a different material, see the manufacturer instructions regarding the mixing ratio and adjust the following instructions accordingly). 

Take a bottle of elastomer RPRO30 Part A. Measure out 1.5g in the cup, pouring slowing so you do not overshoot. 
After, add 1.5g of Part B. This should give you 3g total material in the cup. 
Then start to mix the material with a spatula. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/704b10f9-0dda-4c43-8e7f-db1a74652f38)](https://youtu.be/hFzYer2Egt0)

### 5.2.2	Pouring 
Slowly pour mixture into the mold #1. 
Wait 3 hours for cure the material in the environment temperature.

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/4a1f068b-565c-4ea5-b0e3-dcf94ad4d1ad)](https://youtu.be/9Wmfy8GAlZQ)

### 5.2.3	Demold
After 3 hours, demold carefully the elastomer from the mold#1. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/c189fb24-c1ee-46f1-a4cb-bec98a8e70ef)](https://youtu.be/It-05RlSMfs)

## 5.3 Step2: Mold bottom layer
Elastomer needs to be mixed in a 1:1 ratio (by weight) of PartA: PartB. In this example we will prepare a total of 1g of elastomer. In this step needs to use the mold#2. 

### 5.3.1	Measure 
Take a bottle of elastomer RPRO30 Part A. Measure out 0.5g in the cup, pouring slowing so you do not overshoot. 
After, add 0.5g of Part B. This should give you 1g total material in the cup. 
Then start to mix the material with a spatula.  

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/36ec190a-e55e-4771-8301-ad6dd7f9ae60)](https://youtu.be/JuzkM146Jqo)

### 5.3.2	Pouring 
Slowly pour mixture into the mold #2. 
Wait 3 hours for cure the material in the environment temperature.

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/441a8a88-e045-478a-96ff-fc4058fca807)](https://youtu.be/Wjk1bTlrO14)

### 5.3.3	Demold 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/95503d6d-486c-4d2e-8db5-82fc09cfc386)](https://youtu.be/EUK70fzJB7I)

## 5.4 Step3: Assemble body and bottom layers
### 5.4.1	Join body and bottom layers
Prepare a total of 0,6g elastomer. 
Using mold#3 join the body layer done in step 1 together bottom layer done in step 2 and use the not cured silicon rubber as glue.  
Wait 3 hours for cure the material in the environment temperature. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/a2f8d951-a552-4f18-8200-bcc99a8690e9)](https://youtu.be/z4cKzqhqpSE)

![image](https://github.com/senderrocha/senderr/assets/32946334/7b9770e4-17aa-43eb-941e-38db5144893e)

### 5.4.2	Demold
After 3 hours, demold carefully the elastomer from the mold#3. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/3e036e47-fda8-4ec7-8409-9384884e018f)](https://youtu.be/WI6rk0a_xxI)

![image](https://github.com/senderrocha/senderr/assets/32946334/12521fd7-e4b7-4740-8167-c3cb0abf0b68)

## 5.5 Step4: Inserting the wires 
### 5.5.1	Preparing the wires
Cut two pieces of 15 cm each one of wire cables and remove 10 mm of the isolated part in the end of each wire. Crimp each wire end with the male connector pin (2.54mm pitch male connector pin crimp)

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/a6ad6e5c-9b88-4b71-865d-9d2ba22ed543)](https://youtu.be/o_MT8tJoXt4)

![image](https://github.com/senderrocha/senderr/assets/32946334/3fadd16b-9f82-439b-b252-505dc211576a)

### 5.5.2	Inserting the wires
Observing the wire cables guides position in the silicon insert the crimped wires in each one. 
It is recommended to observe the limit to insert the crimped wires without drilling the silicon body. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/2888cd05-38af-451b-a46d-a4f05bd96d93)](https://youtu.be/TsGQQ4W9ZQk)

## 5.6 Step5: Inserting the air tube
Insert the air tube wit 2mm of diameter in the middle layer silicon in the position showed in the silicon air tube guide as showed in the figure. It is recommended to use a thin tool (as wooden toothpick) to crate the hole in the silicon. 

![image](https://github.com/senderrocha/senderr/assets/32946334/7dedfce5-0ca8-4d1f-b2c8-d5ec02bb0d96)

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/8eb14e3e-03d4-4784-9293-d32a496d1959)](https://youtu.be/-pITGnmzHIE)

### 5.7.1	Pouring ionic solution 
Pour the ionic solution in the silicone body measuring the quantity of the ionic solution using the mass scale. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/969def76-315d-46e8-b039-5c9596b81b22)](https://youtu.be/YpGLJXMaMfk)

## 5.7 Step6: Prepare Ionic Solution 
The ionic solution should be composed by mixing 40% of glycerin, 54.64% of aloe vera (99% solution), 5.46% domestic salt and liquid dye, as showed in the table 4 for different options of total weight as example. The liquid dye color is used to make the manipulation easy during the sensor fabrication since the ionic solution is transparent. After measuring the weight for each component for the ionic solution, combine each component and mix them. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/43f399fb-0173-426e-8fca-dba8e57eeaf7)](https://youtu.be/pp0Di67Tm_s)

The total quantity of the ionic solution to be prepared depends on the resistance required for each project. 

![image](https://github.com/senderrocha/senderr/assets/32946334/006574db-c632-4f8c-b57f-87e634176359)

Figure 17: Preparation of the ionic solution using the balance to measure the proportion of each component: Aloe vera, glycerol, salt and dye. Mixing the ionic solution.

### 5.7.1	Pouring ionic solution 
Pour the ionic solution in the silicone body measuring the quantity of the ionic solution using the mass scale. 

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/50a06e60-f3c2-461d-9d09-9cba0907e4c7)](https://youtu.be/YpGLJXMaMfk)

## 5.8 Step7: Mold Cover layer 
### 5.8.1	Measure
Take a bottle of Elastomer RPRO30 Part A. Measure out 0.75g in the cup, pouring slowly so you do not overshoot. 
After, add 0.75g of Part B. This should give you 1.5g total material in the cup. 
Then start to mix the material with a spatula.

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/05449563-b640-4c36-bcc1-e239313e8612)](https://youtu.be/GKo7tF3HNiQ)

### 5.8.2	Pouring
Fit the middle layer mold#4 into the bottom layer mold#4.  
Slowly pour mixture into the mold #4. 
Insert the top layer mold#4 into the middle and bottom layer.
Wait 3 hours for cure the material in the environment temperature.

![image](https://github.com/senderrocha/senderr/assets/32946334/70038884-c3d5-4d1b-9307-d9e62deaa4c6)

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/e89f8bc9-b045-4d79-8dbc-8f681a12327d)](https://youtu.be/OZ44-jkReN4)

### 5.8.3	Demold
After 3 hours, demold carefully the elastomer from the mold#4.

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/7e4f2abf-efbe-4ef5-a973-e04b361cfb63)](https://youtu.be/lHXfsVV7-YM)

![image](https://github.com/senderrocha/senderr/assets/32946334/a4bcf3d3-6e16-444d-8405-34f5c7efa1b6)

## 5.9 Step8: Bond body and cover layers 
### 5.9.1	Join body and bottom layers 
Prepare a total of 0,6g elastomer. 
Using mold#3 join the body done in step 3 together with the cover layer done in step 7 and use the silicon rubber not cured as glue.  
Wait 3 hours for cure the material in the environment temperature.
Note: in this step it is recommended to remove the air tube to guarantee a better glue between the elastomer layers. 

![image](https://github.com/senderrocha/senderr/assets/32946334/86d188c8-6b64-449e-951d-c2ad8b3a129b)

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/79558198-a5ab-478d-a8cb-638bd5ea4edc)](https://youtu.be/W4_wWvGZiAM )

### 5.9.2	Demold
After 3 hours, demold carefully the elastomer from the mold#3. 
Now the sensor is ready to be tested. 
Note: if the air tube was removed during cure then it needs to be inserted again in the sensor.

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/18cedf49-59a9-4575-8015-ee8b54cad83a)](https://youtu.be/YJIRM7S5cdc)

![image](https://github.com/senderrocha/senderr/assets/32946334/5320e07d-86a4-4da6-9445-09abffa03fed)

Step8 Assembly

[![Watch the video](https://github.com/senderrocha/senderr/assets/32946334/e4e2b2b2-26c4-4a7a-ac8f-f4fce396943f)](https://youtu.be/W4_wWvGZiAM)

## 5.10 Test:
This session describes some examples of tests that have been carried out to characterize the SSMS-IS. To measure the sensor’s resistance, it was connected to a resistive divisor, and the voltage was monitored by a microcontroller, such as Arduino. The acquisition data of the resistance variation by the time was acquired by the software MATLAB Support Package for Arduino Hardware. The test results is showed in the video:

[![Watch the video]](https://youtu.be/RWEe7iyYSOg)

This session describes some examples of tests that have been carried out to characterize the SSMS-IS. To measure the sensor’s resistance, it was connected to a resistive divisor, and the voltage was monitored by a microcontroller, such as Arduino. The acquisition data of the resistance variation by the time was acquired by the software MATLAB Support Package for Arduino Hardware

![image](https://github.com/senderrocha/senderr/assets/32946334/ae0536bb-5a22-4ba5-8041-01d998367d6e)

Figure: Circuit diagram regarding acquisition data for the resistance variation of the SSMS-IS. 

### 5.10.1	Internal pressure tests
The internal pressure in the SSMS-IS has been applied using an air pump of 10ml of total volume. The pump was controlled by a servo.  The pressure frequency applied from the pump was programmed by an Arduino microcontroller allowing it to emulate different profiles of internal pressures over the sensor. The response of the sensor was recorded using MATLAB Software.    

![image](https://github.com/senderrocha/senderr/assets/32946334/30cc674e-2a81-4eae-b845-419a289a4d7c)

Figure: Setup of internal pressure tests

### 5.10.1.1	Internal pressure time interval variation
Different time intervals using the pump have been applied to analyze the resistance variation of the sensor for a constant pressure. Three-time intervals of internal pressure have been tested: 2s, 7s, and 15s. The results are shown in figure below. 

![image](https://github.com/senderrocha/senderr/assets/32946334/6f9113bc-31d0-4606-9e02-827f37a06171)

### 5.10.1.2	Sensitivity
To measure the SSMS-IS sensitivity for internal pressures, it was conducted an experiment increasing the value of the internal pressure in the sensor in incremental steps of volume air inlet of 0.5ml. It is noted a sensor sensitivity variation of approximately 35% for a sensing range between 0-0.0892MPa, as shown in the figure below. This result was carried out by (Rocha, S. et al forthcoming 2024).

![image](https://github.com/senderrocha/senderr/assets/32946334/6db87548-253e-4377-8c40-07880bda67fb)

Figure: Sensor sensitivity within the sensing range of external pressure of 0-0.0892MPa.


### 5.10.1.3	Cyclic loading
To verify the level of durability for the SSMS-IS, the sensor has been subjected to repeated cycles of internal pressure of 2.21MPa. The result is noted in the figure below where the SSMS-IS was able to withstand a cyclic pressure of 2.21MPa for 2000 cycles, indicating that it is physically durable. This result was obtained by (Rocha, S. et al forthcoming 2024) 

![image](https://github.com/senderrocha/senderr/assets/32946334/31bdea1d-9213-42de-b59c-ec10e3467366)

Figure 23: Results of cyclic loading of the sensor for 2000 cycles of internal pressure at 2.21MPa.

### 5.10.2	External pressure
The external pressure input for the sensors has been applied using a setup with a servo applying a specific compression pressure when its arm goes to up and down for a specific time interval. The time of the arm movement was programmed by the microcontroller Arduino allowing it to emulate different profiles of external pressures over the sensor. The response of the sensor was recorded using MATLAB Software.

![image](https://github.com/senderrocha/senderr/assets/32946334/64c3593c-c095-43e3-99f1-cfb714ceb751)

Figure: Setup for external pressure tests over the SSMS-IS.

### 5.10.2.1	External pressure time interval variation

Different time intervals of servo’s arm actioning over the sensor have been applied to analyze the resistance variation of the sensor. Three-time intervals of external pressure have been tested: 2s, 7s, and 15s. The results are shown in figure below. 

![image](https://github.com/senderrocha/senderr/assets/32946334/e667c834-d7c0-49a8-bb19-d480611f1ce9)

Figure: External pressure test for different intervals of time of servo arm actioning. 

### 5.10.2.2	Sensitivity 

To measure the SSMS-IS sensitivity for external pressures, it was conducted an experiment to increase the value of the external pressure in the sensor in incremental steps of 1.68MPa. It was a variation of 10% regarding the sensor sensitivity for a sensing range between 0-38.64MPa, as shown in the figure below. This result was obtained by (Rocha, S. et al forthcoming 2024) 

![image](https://github.com/senderrocha/senderr/assets/32946334/0a19aed6-ca10-4518-86a8-f56b006da7f9)

Figure: Sensor sensitivity within the sensing range of external pressure of 0-38.64MPa.

### 5.10.2.3	Drift
To test the sensor drift for external pressures, the sensor has subjected to a constant load of 3.29x10-4MPa for a prolonged duration of 15min to observe some resistance drift in the output parameter for external pressure. As shown in figure below, a sensor drift was observed for the specific time tested. The drift results not adversely affect the sensor's capacity to measure pressure but might require algorithms for its calibration and corrections. This result was obtained by (Rocha, S. et al forthcoming 2024) 

![image](https://github.com/senderrocha/senderr/assets/32946334/8bdc5ca0-f469-4177-a087-d553487cea2e)

Figure: Drift of sensor for approximately 15min.

## Referencias
https://softroboticstoolkit.com/book/fiber-reinforced-bending-actuators
1.	Atalay, A.; Sanchez, V.; Atalay, O.; Vogt, D.; Haufe, F.; Wood, R.; Walsh, C. Batch Fabrication of Customizable Silicone-Textile Composite Capacitive Strain Sensors for Human Motion Tracking. Advanced Materials Technologies 2017, 2.
2.	Almassri, A. M.; Hasan, W. Z.; Ahmad, S. A.; Ishak, A. J.; Ghazali, A. M.; Talib, D. N.; Wada, C. Pressure sensor: state of the art, design, and application for robotic hand. Journal of Sensors 2015. 
3.	Cheung, Y.-N.; Zhu, Y.; Cheng, C.-H.; Chao, C.; Leung, W.W.-F. A Novel Fluidic Strain Sensor for Large Strain Measurement. Sens. Actuators A Phys. 2008, 147, 401–408. 
4.	Cheung, Y.-N.; Zhu, Y.; Cheng, C.-H.; Chao, C.; Leung, W.W.-F. A Novel Fluidic Strain Sensor for Large Strain Measurement. Sens. Actuators A Phys. 2008, 147, 401–408. 
5.	Felt, W.; Chin, K. Contraction Sensing with Smart Braid McKibben Muscles. IEEE/ASME Transactions Mechatronics 2015, 21(3), 1-1. 
6.	Ferman, Victor; Mota, F.; Silva, C.; Rohmer, E. Development and Design of an Innovative Smart Exoskeleton-Crutch System. In: XII Congreso Iberoamericano de Tecnologías De Apoyo A La Discapacidad (IBERDISCAP 2023), São Carlos, SP, Brazil 2023
7.	Hauser, H.; Füchslin, R. M.; Nakajima, K. E-book on Opinions and Outlooks on Morphological Computation, 1rd ed.; Publisher: Self-Published, England, 2014; pp. 226-244. 
8.	Kim, S.; Laschi, C.; Trimmer, B. Soft robotics: a bioinspired evolution in robotics. Trends in Biotechnology 2013. 

9.	Laschi, C.; Cianchetti, M. Soft robotics: new perspectives for robot bodyware and control. Frontiers in Bioengineering and Biotechnology 2014. 
10.	Muth, J.; Vogt, D.; Truby, R.; Mengüç, Y.; Kolesky, D.; Wood, R.; Lewis, J. Embedded 3D Printing of Strain Sensors within Highly Stretchable Elastomers. Advanced Material 2014, 26, 6307-6312. 
11.	Nakajima, K. , Hauser, H., Li, T., & Pfeifer, R. Exploiting the Dynamics of Soft Materials for Machine Learning. Soft Robotics 2018, 5(3), 339-347.
12.	Pfeifer, R..; Lungarella, M; Lida, F. Self-Organization, Embodiment, and Biologically Inspired Robotics. Science 2007, 318, 1088-1093. 
13.	Russo, S.; Ranzani, T.; Liu, H.; Nefti-Meziani, S.; Althoefer, K.; Menciassi, A. Soft and Stretchable Sensor Using Biocompatible Electrodes and Liquid for Medical Applications. Soft Robot. 2015, 2, 146–154. 
14.	Sujeesh, V; Ponraj, G; Ren, H. Soft Ionic Pressure Sensor with Aloe Vera Gel for Low-Pressure Applications.  Micromachines 2022, 13, 146-159. 
15.	Tenzer, Y.; Jentoft, L.; Howe, R. Inexpensive and Easily Customized Tactile Array Sensors using MEMS Barometers Chips. IEEE Robotics&Automation 2014, 21(3), 89-95.
16.	Wolpert, D. M.; Diedrichsen, J.; Flanagan, R. Principles of sensorimotor learning. Neuroscience 2011, 12, 739-751.
17.	Ward-Cherrier, B.; Cramphorn, L.; Lepora, N. Exploiting sensor symmetry for generalized tactile perception in biomimetic touch. IEEE Robotics Automation Letters 2017, 2, 1218-1225.
18.	Zhang, C.; Zhou J.; Jin G. Pillbot: a soft origami robot inspired by pill bugs. In Proceedings of the RICAI 20, Shanghai, China, September 20-22, 2019. 


___________________________________________________________________________________________________________________________________________________________________________________________________________________________

61![](https://github.com/senderrocha/senderr/blob/master/file/bom.png)

62![](https://github.com/senderrocha/senderr/blob/master/file/tabela%20bom.png)
24 <img src="https://github.com/senderrocha/senderr/blob/master/file/75934960-1377-4D7A-9C03-C22A81A1F4D3.jpeg"  width="100" height="100"> 
28 <img src="https://github.com/senderrocha/senderr/blob/master/file/878ABAEF-43DB-400B-9092-7434FB68E739.jpeg"  width="100" height="100">

26 <img src="https://github.com/senderrocha/senderr/blob/master/file/7A6F7356-33D5-41EC-ADEC-9EC35EB261A3.jpeg"  width="100" height="100">
12 <img src="https://github.com/senderrocha/senderr/blob/master/file/3B1C5B81-E6BA-4596-96B6-8540CE3FD657.jpeg"  width="100" height="100"> 
41 <img src="https://github.com/senderrocha/senderr/blob/master/file/B3B49790-0214-4A49-A90B-66A1E8400A86.jpeg"  width="100" height="100"> 
51 <img src="https://github.com/senderrocha/senderr/blob/master/file/D546C6D0-DB5F-4AD9-9889-3F3394FB44F9.jpeg"  width="100" height="100"> 
18 <img src="https://github.com/senderrocha/senderr/blob/master/file/5C644AFE-E273-4EF5-9A27-67C8FBB402FC.jpeg"  width="100" height="100"> 

## Partes difíceis de nacionalizar – vent screw
Vent Screw <img src="https://github.com/senderrocha/senderr/blob/master/file/vent%20screw.jpeg"  width="100" height="100"> 
12 <img src="https://github.com/senderrocha/senderr/blob/master/file/3B1C5B81-E6BA-4596-96B6-8540CE3FD657.jpeg"  width="100" height="100"> 
15 <img src="https://github.com/senderrocha/senderr/blob/master/file/4D181714-7A12-4358-A132-8C771D7D8A4F.jpeg"  width="100" height="100"> 
18 <img src="https://github.com/senderrocha/senderr/blob/master/file/5C644AFE-E273-4EF5-9A27-67C8FBB402FC.jpeg"  width="100" height="100">
31 <img src="https://github.com/senderrocha/senderr/blob/master/file/9201322A-7FFC-47D0-B0E8-DFCDBB51DCF2.jpeg"  width="100" height="100"> 
um pouco cara, mas eficiente:

###Tentativa de fabricacao do vent screw por impresssora 3D. Sem sucessso. Material muito frágil:

<img src="https://github.com/senderrocha/senderr/blob/master/file/D466B104-A9EB-4B74-B51A-C900EBC9B8F2.jpeg"  width="100" height="100">


Fibra de vidro:

<img src="https://github.com/senderrocha/senderr/blob/master/file/5C644AFE-E273-4EF5-9A27-67C8FBB402FC.jpeg"  width="100" height="100">

Barra de metal no meio do material

## Papel serve para fazer sulcos 
precisa inserir figura no servidor 

## Partes importantes do material: balanca (balanca de cozinha serve mas não tanto) 	
5 <img src="https://github.com/senderrocha/senderr/blob/master/file/147A2E91-A048-46A8-A7CD-3EBD4F6244C0.jpeg"  width="100" height="100"> 
53 <img src="https://github.com/senderrocha/senderr/blob/master/file/DACE03BB-D375-4A46-AF29-FA60DB6E4C5A.jpeg"  width="100" height="100">

## Bolhas no material: mexer bastante, de preferencia com furadeira, mas não muito pois pode esquentar o material e solidifica-lo
4 <img src="https://github.com/senderrocha/senderr/blob/master/file/0B979163-9075-4A15-9EF6-4F64B96A15BC.jpeg"  width="100" height="100">
9 <img src="https://github.com/senderrocha/senderr/blob/master/file/30E23079-B2AE-4C01-8C7E-2E2D0865BB60.jpeg"  width="100" height="100">
14 <img src="https://github.com/senderrocha/senderr/blob/master/file/42EF7571-0911-43F4-83B5-96111DBE9243.jpeg"  width="100" height="100"> 
21 <img src="https://github.com/senderrocha/senderr/blob/master/file/680D0695-34CD-4B20-BD8C-CE40DD6CEC29.jpeg"  width="100" height="100">

## Como virar o tubo de silicone: usar pipeta 
24 <img src="https://github.com/senderrocha/senderr/blob/master/file/75934960-1377-4D7A-9C03-C22A81A1F4D3.jpeg"  width="100" height="100"> 

## Como fabricar moldes com baixo custo
* 	- materiais que não grudam 
* 	- plásticos em geral, metal, madeira, cartolina, 
42 <img src="https://github.com/senderrocha/senderr/blob/master/file/B47090A3-F4A2-443F-BA42-2A721FEE0909.jpeg"  width="100" height="100"> 
30 <img src="https://github.com/senderrocha/senderr/blob/master/file/91846026-69BF-4FD3-84E3-E0F3F62FE27B.jpeg"  width="100" height="100"> 

## Como guardar sobra de material já preparado: dentro de balão (sem contato com ar)
57 <img src="https://github.com/senderrocha/senderr/blob/master/file/F88359E5-A0B2-43A0-AB60-E7A8E24CA17E.jpeg"  width="100" height="100"> 

## Cola de silicone para montagem de partes do molde ou do produto a ser fabricado
Importante nao so para colar o tecido de fibra de vidro no silicone como tambem para colar partes de silicone de um projeto. 

44 <img src="https://github.com/senderrocha/senderr/blob/master/file/BD23E245-254C-4406-B2D3-B898A2168108.jpeg"  width="100" height="100"> 
16 <img src="https://github.com/senderrocha/senderr/blob/master/file/4D98DB0B-EE08-4794-A08F-3C8CC3D38F67.jpeg"  width="100" height="100"> 

## Vedação de material – cola, borracha, plástico
* 	- fabricar o atuador sempre com um formato de cone no final para poder passar abraçadeira para fixar 
20 <img src="https://github.com/senderrocha/senderr/blob/master/file/64E3AFFA-86FD-46D9-8966-7F2A08034559.jpeg"  width="100" height="100">
27 <img src="https://github.com/senderrocha/senderr/blob/master/file/872D45CA-F047-4070-ADE8-49A1F85F4804.jpeg"  width="100" height="100"> 
35 <img src="https://github.com/senderrocha/senderr/blob/master/file/9E416364-D00A-4200-9C1E-95C7B05F89DD.jpeg"  width="100" height="100">
36 <img src="https://github.com/senderrocha/senderr/blob/master/file/A2FE61E9-156F-400B-B74D-9E6F107A4827.jpeg"  width="100" height="100"> 
39 <img src="https://github.com/senderrocha/senderr/blob/master/file/AC375DBF-01F1-41B9-82B8-77A43FA6867B.jpeg"  width="100" height="100"> 
43 <img src="https://github.com/senderrocha/senderr/blob/master/file/BB81586E-8BD6-49B6-978A-ED132987A527.jpeg"  width="100" height="100"> 
46 <img src="https://github.com/senderrocha/senderr/blob/master/file/C13E8CE9-75A1-4C26-91F5-07479C6CE7F9.jpeg"  width="100" height="100"> 
48 <img src="https://github.com/senderrocha/senderr/blob/master/file/CA25FF9D-ABBA-49A9-B813-D796A1AC387C.jpeg"  width="100" height="100"> 
50 <img src="https://github.com/senderrocha/senderr/blob/master/file/D466B104-A9EB-4B74-B51A-C900EBC9B8F2.jpeg"  width="100" height="100">


## Como testar o material: recipiente com agua para verificar bolhas 
falta imagens

## Rigidez do material: paredes espessas exigem grandes pressões 
15 <img src="https://github.com/senderrocha/senderr/blob/master/file/4D181714-7A12-4358-A132-8C771D7D8A4F.jpeg"  width="100" height="100">

## Manutenção de pneu de bicicleta para reparos 


## Quanto menos espesso melhor para expansão do material 


## Silicone não seca muito bem em moldes plásticos 


## É possível fazer um molde de silicone mas tem que colocar um filme platico ou outro material para evitar que o material grude no molde 





