![](/tutorial/coverflow.png)
# Play Perfect
This is a website written in Vue.js for achievements or trophies hunter to track their games collection

https://playperfect.app/

## Feature:
* Support Steam, PSN, Xbox and RetroAchievements (other platform coming soon...)
* **Allow dual accounts on same platform** (PSN and Steam only)
* Multiple good looking interface, you can pick whatever you want 
* Single Sign On(SSO) with Google accounts
* Chart and Statistic for your records
  
## Limitation: 

* For better performance, only the latest 500 games per platform will be fetched
* For dual profile on same platform having the same game, only primary account will be counted. No merge for achievements/trophies.
* No leaderboard/comparison with other user 

## Tutorial:

### Step 1: Login and Register

* PlayPerfect is using Google Single Sign On(SSO) for user login. Therefore, you only need a Google account to use PlayPerfect. No credential will be store in our side. 

![](/tutorial/login1.png)
![](/tutorial/login2.png)

### Step 2: Enter your public game ID
* Your game account must be public (at least public for your games and achievements/trophies)
* **You may use comma(,) to seperate if you have two accounts**

![](/tutorial/editID.png)

### Step 3: Sync your collection after enter your ID
* You should see the progress bar running when it is syncing
![](/tutorial/syncing.png)

### Step 4: After Sync is completed, your collection will auto refresh and present to you

* Click the Refresh Collection button in menu to update your collection after sync is completed if it is not update automatically

## Collection:
### Collection View
You can choose different view for your collection (default is *Carousel*)

> Carousel / Table / Cover Flow

> #### Carousel
> ![](/tutorial/Carousel.png)

> #### Table
> ![](/tutorial/table.png)

> #### Cover Flow 
>![](/tutorial/coverflow.png)
*Cover Flow view does not support lazy load, so it will render all cover images of you collection immediately, it could cause performance issue and generate huge network traffic. A warning will be prompted before you enter that mode.*

### Achievement View

You can also choose different view for achievement (default is *Grid*)
> Grid / Table

> Grid
*For Grid View, You can hover to the achievement icon and it will show the detail and the date earned*
![](/tutorial/hoverAchievement.png)
> Table
![](/tutorial/AchievementTable.png)

#### *Chart*, *Stats*, *Achievements Rarity* and much more I let you to discover yourself...

## Welcome to support me on patreon

> Only one plan with one buck 🥂
> https://www.patreon.com/ckw1
