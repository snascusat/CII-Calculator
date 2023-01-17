# CII Calculator
## CII Overview
This is the new approach by IMO to measure a vessel's operational efficiency. The main takeaway from the CII is its ranking scheme which is based on the operational efficiency of ships, which will be a measure of how efficient ships are when transporting cargo and passengers
## CII Rating Scheme
The rating scheme of CII ranges from A to E, where A is the most efficient ship. The rating parameters vary according to the type of ship. The rating is determined by comparing the required CII and attained CII. The figure below gives a clear idea about the rating and as well as the boundary names </br>
![1648557166261](https://user-images.githubusercontent.com/72561669/212858369-d6e43eba-0c5a-4964-b5da-8a18a3d40d83.jpg)</br>
If a vessel achieved E in a year or D in 3 years the vessel is expected to submit the correction plans and should obtain a ranking of C in the next year. More details on how to rank the vessel is given in the A/R Ratio section

## Attained CII
The attained CII of the individual ship is calculated as the ratio of the total mass of CO2 emitted by the ship to the total transport worm undertaken in a calendar year 

![image](https://user-images.githubusercontent.com/72561669/212859881-e54b8d3b-4bce-4dfb-a480-bbaa77e752cb.png)

Where is M is the mass of CO2 emitted and W is the transport work done 
### Mass Of CO2 emission(M)
Total mass of CO2 emitted is the sum of emission from all the fuel consumed on board ship in a given calendar year 
![image](https://user-images.githubusercontent.com/72561669/212860269-d341a490-75e5-46cc-af47-9c6cd601133c.png)


Where
 j is the fuel oil type
FCj is the total mass in grams of consumed fuel oil type  j in a calendar year as reported under IMO DCS
CFj represents the fuel oil mass to CO2 mass conversion factor for fuel  oil type 
#### Fuel mass to CO2 mass conversion factor
CF is a non-dimensional conversion factor between fuel consumption measured in g and
CO2 emission also measured in g based on the carbon content


![image](https://user-images.githubusercontent.com/72561669/212860507-083e5493-56a5-418d-a7de-f5128cd48897.png)



### Transport Work (W)
This is the distance travelled by the ship in nautical mile in one calender year 

![image](https://user-images.githubusercontent.com/72561669/212860686-f5e89bff-2ae9-4a98-898f-9a5e8e6a360c.png)


Where 
C represents Capacity of the ship
Dt represents total distance covered in one calender year under IMO DCS
## Required CII
This is defined as the curve representing the median attained by the operating CII performance as a function of capacity
![image](https://user-images.githubusercontent.com/72561669/212860835-58ba6156-dad9-4d1b-a1ee-d94e77de0eca.png)


Reference CII is the value of 2019, a and c are the parameters suggested in MEPC 337(76). The table containing suggested values of a and c is given below

![image](https://user-images.githubusercontent.com/72561669/212861096-d5e9bfa1-12d1-4a77-9ad1-3e24f6cf3fa8.png)

## How Capacity Is Determined?
In the above sections, we concluded that Attained CII and Required CII depend on the ship's capacity. The following criteria can determine the capacity of the ship

- For bulk carriers, container ships, tankers, gas carriers, LNG carriers, ro-ro cargo ships, general cargo ships, refrigerated cargo carriers, and combination carriers DWT should be used 
- For cruise ships, ro-ro cargo,ro-pax ships GT should be used
 


## A/R Ratio
This is the ratio between Attained CII and Reference CII. A higher value of the A/R ratio means more attained CII thus possibly more CO2 emitted by the ship. A higher value of A/R generally gives the worst-performing ships. Thus A/R ratio must be low in order to get a higher CII ranking.
If the A/R ratio equals one means attained and required CII are the same thus it lies in exactly the middle of the rating scheme which is C   
![image](https://user-images.githubusercontent.com/72561669/212861339-3dfbd29f-517f-4ce3-a4d9-ed5e3816f8e4.png)



We can rank the vessels by comparing their exp(d) values and obtained A/R ratios.Lets take the example of oil tanker
![image](https://user-images.githubusercontent.com/72561669/212861393-120df57f-0e76-4e37-a78d-f4e8ed733fc0.png)





As the A/R ratio is less than exp(d1) the rating will be A. Similarly, the CII ranking of every vessel can be obtained by comparing the A/R ratio and their respective exp(d) values  


