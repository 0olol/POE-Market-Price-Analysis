# POE-Market-Price-Analysis
Analysing the Path Of Exile martket, with past data to predict what is the best invesment in at the point.

This Analysis has been done in Sanctum League, where the data is from previous league excluding Sanctum League.

Firstly I have removed the CSV file that contains the items section to be uploaded. 
- Because it is too big and i would have to pay for me to upload. For those that want to run this notebook please go ahead to download the files
- Download it from the following link, which is poe.ninja Api links for downloading the different leagues
    - https://poe.ninja/api/data/getdump?name=Kalandra
    - https://poe.ninja/api/data/getdump?name=Sentinel
    - https://poe.ninja/api/data/getdump?name=Archnemesis
    - https://poe.ninja/api/data/getdump?name=Scourge
    - https://poe.ninja/api/data/getdump?name=Expedition
    - https://poe.ninja/api/data/getdump?name=Ultimatum
    - https://poe.ninja/api/data/getdump?name=Ritual
- Extracting their specific league file type to their respective folder
    - e.g. Kalandra.currency.csv to Currency folder
    - e.g. Kalandra.items.csv to Items folder

Currency or Divination card that have been done.
  Currency:
    - Tailoring Orb
    - Tempering Orb 
    - Secondary Regrading Lens 
    - Mirror Shard 
    - Mirror 
  Divination Card:
    - Mirror Card:
        - House of Mirrors
        - The Immortal 
        - Seven Years Bad Luck
        - Unrequited Love 
    - MageBlood(MB) Card:
        - The Apothecary
        - The Insane Cat*
        - The Price of Devotion*
    - HeadHunter(HH) Card:*
        - The Doctor 
        - The Fiend 
        - The Demon

The ones with * has not been analyse. 

For HH after the rework it only has 2 leagues worth of data, and in Kalandra League because of the Loot Globin, everyone is equipping it to get higher Damage Per Second(DPS) in exchange dropping other slots for Quantity Gear.

For the 2 Mageblood Card, it is only released in Sanctum League which at the point of analysing, I do not have the dataSet.

But I would not advise to invest in The Apothecary card as two leagues worth of data is not sufficient to come up with decent information. 