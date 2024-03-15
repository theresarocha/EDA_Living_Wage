# Exploratory Data Analysis

- Author: Theresa Rocha
- Programming language: Python

# Objective

Exploratory data analysis with some information about the population of the 100 largest cities in the United States according to the Census 2020.
This analysis has the intention to answer the following questions:

- Which city has the largest population?
- Which city has the smallest number of residents?
- Which city has the highest population density?
- Which city has the lowest population density?
- What is the average hourly minimum wage per one adult?
- What is the average hourly minimum wage per two adults wich just one is currently working?
- What is the average hourly minimum wage per two adults wich both are currently working?


# Data Source

- Dataset extracted from Kaggle: <https://www.kaggle.com/datasets/brandonconrady/living-wage-top-100-cities>
- US States Json from PublicaMundi: <https://github.com/PublicaMundi/MappingAPI/tree/master/data/geojson>

# Census 2020: Living Wage of the Largest Cities in the United States

![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/4d693be5-3eb0-4e89-9ba4-78d316ff65c4)
- Photo by Absalom Robinson in Pexels

![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/5fe26fb7-4a54-41cc-ad17-8ee0c2191a50)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/3b5c787e-0a26-4207-bc78-8b2d59a29289)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/fa8e39ac-1d7b-43de-83e5-3c59e72cee02)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/af160d66-ddcb-45e8-a6b3-c6512879b1c4)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/29cb1232-b56e-4ab3-9d33-676fcddf95c6)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/643458cf-165b-4277-a810-61708ffbbea3)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/746b4dfe-6bf1-468c-b4c2-96961949edcc)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/54e51ff0-9763-4ac4-a898-991c2004a655)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/e1a132c1-82df-42dd-ac36-5a669095321f)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/146361bc-848a-4cf4-89ba-544e4585edfa)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/96cb91cb-3fb7-4387-a1dd-becfabccdd2f)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/cb6fddf0-ccd6-4489-82ca-f994ecd5b72a)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/c9195b26-7624-4871-9405-d6bfd201bc0b)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/5ae01d5c-5ba3-4d40-87b6-ec11d7919fa9)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/073fa8c7-c732-44a0-ad79-258fc25fe21d)

- Curiosities Sources:
- CuddlyNest: <https://www.cuddlynest.com/blog/facts-about-new-york/>
- City Sightseeing: <https://city-sightseeing.com/blog/en/facts-about-los-angeles>
- Choose Chicago: <https://www.choosechicago.com/press-media/toolkit/chicago-facts/>

![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/a8b2bb18-107a-4c30-9314-e55d019b2b19)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/ffbc49d2-4d9e-4a75-be9a-d170ac0e9082)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/d4b40170-2d96-4ab0-b1f3-84188cc369f3)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/9e24fbab-a65e-4ff1-8baa-ef12cd57f463)

- Curiosities Sources:
- Facts.Net: <https://facts.net/world/cities/41-facts-about-richmond-va/>
- BR Proud: <https://www.brproud.com/news/louisiana-news/what-is-baton-rouge-known-for-history-art-music-and-more/>
- Facts.Net: <https://facts.net/world/cities/33-facts-about-santa-clarita-ca/>

![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/d55bf64b-e1cb-4656-96b9-7a7948c295b6)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/adb0f11c-18e2-4721-9f9c-c61d575db50d)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/1996c45c-1bf1-4124-b41d-4fca4bf7b805)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/9d7f5fb8-7ad7-4d77-bcba-023ac4d552a6)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/a10b1331-5664-481a-a366-fe9413b8e440)

- Curiosities Sources:
- CuddlyNest: <https://www.cuddlynest.com/blog/facts-about-new-york/>
- Facts.Net: <https://facts.net/world/cities/50-facts-about-jersey-city-nj/>
- California.com: <https://www.california.com/san-francisco-fun-facts-youll-wish-you-knew/>

![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/00216c63-5da1-4c1a-9427-809337937845)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/f5d29a39-d341-4019-a59b-f873b4ec4440)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/90c9026f-2918-4b2b-81ed-f23c3e400753)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/810499cf-03aa-46f6-9d6a-e02f8452e06f)

- Curiosities Sources:
- Anchorage.Net: <https://www.anchorage.net/blog/post/9-surprising-things-about-anchorage-alaska/>
- Facts.Net: <https://facts.net/world/cities/33-facts-about-chesapeake-va/>
- Fun World Facts: <https://funworldfacts.com/oklahoma-america/>

![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/41182c6d-8dc9-4e76-8371-19afd04ab83e)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/26887e18-04fa-48e1-a192-7e1bbe537bef)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/2c011e71-2e64-4cf2-8955-81c170b2736a)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/788c773b-0715-42af-bbef-67201add1391)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/5de4778f-c2a2-4067-b04d-3488776c2a4f)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/00e13b21-6fbe-4b7e-b552-b32af6c1a86e)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/6a87f84d-07a4-44a7-a505-593cb4190a32)
![image](https://github.com/theresarocha/EDA_Living_Wage/assets/84404461/060923b2-5a44-4445-90f5-03fd07c5c434)







































