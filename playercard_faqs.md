# Player Card rfaqs

Here we explain how to create a new player card. Here is a list of contents

* The code for the card
* Editing the code
  * Color of the card
  * Avatar
  * Username
  * Signature Team
  * Prizes
  * Favorite OU and Pokemon

<hr>

## The code for the card

First copy the following code in a notepad or any other similar application. You will be editing this code in order to create a new faq. Once it is done you can add it with **/addhtmlfaq player [name],** followed by the code. Please note that the comma is important as it separates the name of the faq from the content. In place of **[name]** you want to write the name of the user; the following code in particular is for d18l, so you can try **/addhtmlfaq player d18l,**

```html
<center>
<table style="border-collapse:collapse">
<tr style="border:1px solid #68a;text-align:center;padding:0px;height:1px;text-align:center;background-color:rgba(174, 111, 74, 0.45)">
<th style="border:1px solid #68a;text-align:center;padding:0px">
<i><b>Avatar</b></i>
<th style="border:1px solid #68a;text-align:center;padding:0px">
<i><b>User Info</b></i>    
<th style="border:1px solid #68a;text-align:center;padding:0px">
<i><b>Signature Team</b></i>
<th style="border:1px solid #68a;text-align:center;padding:0px">
<i><b>Prizes</b></i>
<tr style="border:1px solid #68a;text-align:center;padding:4px">
<td style="border:1px solid #68a;text-align:center;padding:0px;width:80px">
<img src="//play.pokemonshowdown.com/sprites/trainers/backpacker.png" width="80" height="80">
<td style="border:1px solid #68a;text-align:left;padding:7px 7px 8px 5px;width:150px;">
<span class="username" style="font-weight:bold;font-style:italic;padding:15px 2px 3px 2px;color:#ae6f4a">d18l</span> <br><u>Smogon</u>: <a href="//smogon.com/forums/members/d18l.547664/">d18l</a><br><u>Registered</u>: 03/20/21
<td style="border:1px solid #68a;text-align:center;padding:7px 6px 6px 6px;width:150px">
<a href="//pokepast.es/fb0e434de8244b90"><psicon pokemon=landorustherian><psicon pokemon=greattusk><psicon pokemon=ogerponwellspring><psicon pokemon=kingambit><psicon pokemon=slowkinggalar><psicon pokemon=ragingbolt></a>
<td style="border:1px solid #68a;text-align:center;padding:3px;width:85px">
<img src="//archives.bulbagarden.net/media/upload/4/4a/Bag_Dream_Ball_Sprite.png" width="24" height="24" title="Room Moderator"><img src="//archives.bulbagarden.net/media/upload/2/22/Dream_Moon_Ball_Sprite.png" width="24" height="24" title="Suspect Test Voter">
<tr style="border:1px solid #68a;text-align:center;padding:4px">
<td style="border:1px solid #68a;text-align:center;padding:4px;text-align:left;background-color:rgba(174, 111, 74, 0.2)" colspan="4">
<center><b>Favorite OU:</b> <i>Phineas</i> | <b>Favorite Pokemon:</b> <i>Scizor</i></center>
</table>
</center>
```

<hr>

## Editing the code

### Color of the card

```html
background-color:rgba(174, 111, 74, 0.45)
background-color:rgba(174, 111, 74, 0.2)
color:#ae6f4a"
```
The above determines the color. To get the color of a username you can pm scrappie with **.namecolor [username]** so for example, .namecolor d18l. Scrappie will give you an rgb and a hex, so just put those new values. The 0.45 and the 0.2 determine the intensity of the color, so you can ignore them, but you have to leave them in place.

<hr>

### Avatar

```html
<img src="//play.pokemonshowdown.com/sprites/trainers/backpacker.png" width="80" height="80">
```
This part lets you update the avatar. You can obtain the avatar's url by right clicking it on PS! then opening it in a new tab.

<hr>

### Username

```html
<span class="username" style="font-weight:bold;font-style:italic;padding:15px 2px 3px 2px;color:#ae6f4a">d18l</span> <br><u>Smogon</u>: <a href="//smogon.com/forums/members/d18l.547664/">d18l</a><br><u>Registered</u>: 03/20/21
```
Here you can add the username, their Smogon, and the date in which they registered. If they don't have a Smogon you can simply replace the following bit of code with N/A
```html
<a href="//smogon.com/forums/members/d18l.547664/">d18l</a>
```

<hr>

### Signature Team

```html
<a href="//pokepast.es/fb0e434de8244b90"><psicon pokemon=landorustherian><psicon pokemon=greattusk><psicon pokemon=ogerponwellspring><psicon pokemon=kingambit><psicon pokemon=slowkinggalar><psicon pokemon=ragingbolt></a>
```

Here you can add the users poekpaste and Pokemon. Pokemon names with multiple words have to be written as a single word. So none of Landorus-Therian or Great Tusk, you have to write landorustherian and greattusk.

If they do not have a paste you can edit it from the following instead:

```html
<psicon pokemon=landorustherian><psicon pokemon=greattusk><psicon pokemon=ogerponwellspring><psicon pokemon=kingambit><psicon pokemon=slowkinggalar><psicon pokemon=ragingbolt>
```

<hr>

### Prizes

```html
<img src="//archives.bulbagarden.net/media/upload/4/4a/Bag_Dream_Ball_Sprite.png" width="24" height="24" title="Room Moderator"><img src="//archives.bulbagarden.net/media/upload/2/22/Dream_Moon_Ball_Sprite.png" width="24" height="24" title="Suspect Test Voter">
```
in the code above d18l has the Poke Ball for Room Moderator and Suspect Test Voter. Simply put the code for the Poke Ball that is needed. Here is the html for each of them.

```html
1 Win: <img src="//archives.bulbagarden.net/media/upload/9/93/Bag_Pok%C3%A9_Ball_Sprite.png" width="24" height="24" title="1 Weekly Win!">
2 Wins: <img src="//archives.bulbagarden.net/media/upload/3/3e/Bag_Sport_Ball_Sprite.png" width="24" height="24" title="2 Weekly Wins!"> 
3 Wins: <img src="//archives.bulbagarden.net/media/upload/7/70/Bag_Fast_Ball_Sprite.png" width="24" height="24" title="3 Weekly Wins!">
4 Wins: <img src="//archives.bulbagarden.net/media/upload/8/89/Bag_Repeat_Ball_Sprite.png" width="24" height="24" title="4 Weekly Wins!"> 
5 Wins: <img src="//archives.bulbagarden.net/media/upload/d/df/Bag_Level_Ball_Sprite.png" width="24" height="24" title="5 Weekly Wins!">
6 Wins: <img src="//archives.bulbagarden.net/media/upload/c/ca/Bag_Great_Ball_Sprite.png" width="24" height="24" title="6 Weekly Wins!">
7 Wins: <img src="//archives.bulbagarden.net/media/upload/2/25/Bag_Lure_Ball_Sprite.png" width="24" height="24" title="7 Weekly Wins!">
8 Wins: <img src="//archives.bulbagarden.net/media/upload/4/4b/Bag_Net_Ball_Sprite.png" width="24" height="24" title="8 Weekly Wins!">
9 Wins: <img src="//archives.bulbagarden.net/media/upload/f/f2/Bag_Dive_Ball_Sprite.png" width="24" height="24" title="9 Weekly Wins!">
10+ Wins: <img src="//archives.bulbagarden.net/media/upload/f/f2/Bag_Beast_Ball_Sprite.png" width="24" height="24" title="10+ Weekly Wins!">
Room Voice: <img src="//archives.bulbagarden.net/media/upload/1/17/Bag_Heal_Ball_Sprite.png" width="24" height="24" title="Room Voice">
Room Driver: <img src="//archives.bulbagarden.net/media/upload/4/42/Bag_Love_Ball_Sprite.png" width="24" height="24" title="Room Driver">
Room Mod: <img src="//archives.bulbagarden.net/media/upload/4/4a/Bag_Dream_Ball_Sprite.png" width="24" height="24" title="Room Moderator">
Room Owner: <img src="//archives.bulbagarden.net/media/upload/f/ff/Bag_Cherish_Ball_Sprite.png" width="24" height="24" title="Room Owner">
Trophy Holder: <img src="//archives.bulbagarden.net/media/upload/6/6d/Bag_Master_Ball_Sprite.png" width="24" height="24" title="Trophy Holder">
Leaderboard Winner: <img src="//archives.bulbagarden.net/media/upload/8/87/Bag_Luxury_Ball_Sprite.png" width="24" height="24" title="Leaderboard Winner">
OU PSPL: <img src="//archives.bulbagarden.net/media/upload/e/eb/Bag_Safari_Ball_Sprite.png" width="24" height="24" title="OU PSPL">
#1 OU Ladder: <img src="//archives.bulbagarden.net/media/upload/0/03/Bag_Ultra_Ball_Sprite.png" width="24" height="24" title="#1 OU Ladder">
Minigame Winner:<img src="//archives.bulbagarden.net/media/upload/5/55/Bag_Premier_Ball_Sprite.png" width="24" height="24" title="Minigame Winner">
Global Staff: <img src="//archives.bulbagarden.net/media/upload/3/3d/Bag_Timer_Ball_Sprite.png" width="24" height="24" title="Global Staff">
OURLT Winner: <img src="//archives.bulbagarden.net/media/upload/7/74/Bag_Heavy_Ball_Sprite.png" width="24" height="24" title="OURLT Winner">
Suspect Test Voter: <img src="//archives.bulbagarden.net/media/upload/2/22/Dream_Moon_Ball_Sprite.png" width="24" height="24" title="Suspect Test Voter">
#1 ROA OU Ladder: <img src="//archives.bulbagarden.net/media/upload/9/9c/Bag_Strange_Ball_HOME_Sprite.png" width="24" height="24" title="#1 ROA OU Ladder">
OUFL Tryouts Winner: <img src="//archives.bulbagarden.net/media/upload/b/b1/Bag_Dusk_Ball_SV_Sprite.png" width="24" height="24" title="OUFL Tryouts Winner">
Prize Shop Reward: <img src="//archives.bulbagarden.net/media/upload/6/63/Bag_Park_Ball_SV_Sprite.png" width="24" height="24" title="Prize Shop Reward">
```

<hr>

### Favorite OU and Pokemon

```html
<center><b>Favorite OU:</b> <i>Phineas</i> | <b>Favorite Pokemon:</b> <i>Scizor</i></center>
```

The code above includes the user's Favorite OU and Favorite Pokemon.

