# Play Perfect
This is a web written in Vue.js for achievements/trophies Hunter to enjoy their collection

https://playperfect.app/

## Feature:
* Support Steam, PSN and RetroAchievements (other platform coming soon...)
* **Allow dual accounts on same platform** (PSN and Steam only)
* Multiple good looking interface, you can pick whatever you want 
* Single Sign On(SSO) with Google accounts
* Chart and Statistic for your records
  
## Limitation: 

* For better performance, only the latest 500 games per platform will be fetched
* For dual profile on same platform having the same game, only primary account will be counted. No merge for achievements/trophies.
* No leaderboard/comparison with other user 

## Tutorial:

### Step 1: Enter your public game ID
* Your game account must be public (at least public for your games and achievements/trophies)
* You may use comma(,) to seperate if you have two accounts

### Step 2: Sync your collection after enter your ID
* You should see the progress bar running when it is syncing

### Step 3: After Sync is completed, your collection will auto refresh and present to you

* Click the button to update your collection after sync is completed if not update automatically

## Collection:
### Collection View
You can choose different view for your collection (default is *Carousel*)
> Carousel / Table / Cover Flow 

*Cover Flow view does not support lazy load, so it will render all cover images of you collection immediately, it could cause performance issue and generate huge network traffic. A warning will be prompted before you enter that mode.*

### Achievement View

You can also choose different view for achievement (default is *Grid*)
> Grid / Table

*For Grid View, You can hover to the achievement icon and it will show the detail and the date earned*

## Chart, Stats and Achievements Rarity
### Chart

### Stats

### Achievements Rarity
