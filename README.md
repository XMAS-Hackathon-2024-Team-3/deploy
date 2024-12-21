Deploy

Step 0:
git clone https://github.com/XMAS-Hackathon-2024-Team-3/deploy

Step 1:  
git submodule foreach git pull origin main

Step 2:
move your payments.csv , providers.csv , ex_rates.csv files into volumes/data folder

Step 3:
docker compose up

Step 4:
check volumes/data/results folder
