# POE-Market-Price-Analysis
Analysing the Path Of Exile martket, with past data to predict what is the best invesment in at the point.

Firstly I have removed the CSV file that contains the items section to be uploaded. 
- Because it is too big and i would have to pay for me to upload. For those that want to run this notebook please go ahead to download the files
- Download it from the folling link, which is poe.ninja Api links for downloading the different leagues
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
