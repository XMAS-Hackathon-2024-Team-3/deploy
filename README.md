Deploy

Step 0:
git clone https://github.com/XMAS-Hackathon-2024-Team-3/deploy
cd deploy

Step 1:  
git submodule update --init --recursive

Step 2:
move your payments.csv , providers.csv , ex_rates.csv files (use same filenames) into volumes/data folder

Step 3:
docker compose up

Step 4:
check volumes/data/results folder
