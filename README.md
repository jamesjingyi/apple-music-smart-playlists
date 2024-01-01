# Apple Music Smart Playlists

I use Apple Music but I miss Spotify's auto-generated playlists. I've taken to using one of the remanants of iTunes, Smart Playlists to sorta solve this. I am still trying to work out whether things like tracking skips works across iOS/iPadOS, but for now, these work well for just getting something to play in the car.

I have tried to document how I make these below, and you can also find the album covers I use.

## 250 Last Played - Auto Skipping [REDISCOVERY]

<img src="./Rules/Rules - 250 Last Played - Auto Skipping.png" alt="Screenshot of the rules for the 250 last played, instructions in text below" height=400>

### Rules
☑️ Match `all ↕` of the following rules:
* `Plays ↕` `is greater than ↕` <ins>**30**</ins>
* `Last Skipped ↕` `not in the last ↕` <ins>**2**</ins> `weeks ↕`

☑️ Limit to <ins>**250**</ins> `items ↕` selected by `least recently played ↕`

☑️ Live updating

### Album Cover

<img src="./Covers/REDISCOVERY - 250.jpg" alt="Album Cover for the 250 last played, with the text 'Rediscovery'" width=300 height=300>

## Top 250 of multiple genres

<img src="./Rules/Rules - Top 250 Hip-Hop Rap R%26B.png" alt="Example screenshot of the rules for the top 250 Hip-Hop/Rap/R&B, full instructions in text below" height=400>
<img src="./Rules/Rules - Top 250 Pop R%26B.png" alt="Example screenshot of the rules for the top 250 Pop/R&B, full instructions in text below" height=400>

### Rules
☑️ Match `any ↕` of the following rules:
* `Genre ↕` `contains ↕` <ins>**1st genre**</ins>
* `Genre ↕` `contains ↕` <ins>**2nd genre**</ins>
* etc...

☑️ Limit to <ins>**250**</ins> `items ↕` selected by `least recently played ↕`

☑️ Live updating

### Album Covers

<img src="./Covers/TOP 250 - Hip-Hop, Rap %26 R%26B.jpg" alt="Album Cover for the top 250 Hip-Hop, Rap and R%26B" width=300 height=300> <img src="./Covers/TOP 250 - Pop %26 R%26B.jpg" alt="Album Cover for the top 250 Pop and R%26B" width=300 height=300>

## Top 250 of a single genre 

<img src="./Rules/Rules - Тор 250 Рор.png" alt="Screenshot of the rules for the 250 last played, instructions in text below" height=400>

### Rules
☑️ Match for the following rule:
* `Genre ↕` `is ↕` <ins>**Genre**</ins>

☑️ Limit to <ins>**250**</ins> `items ↕` selected by `least recently played ↕`

☑️ Live updating

### Album Cover

<img src="./Covers/TOP 250 - Pop.jpg" alt="Album Cover for the top 250 Pop" width=300 height=300>
