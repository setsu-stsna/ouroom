# Pokemon faqs

Here I describe how to create or edit one of the Pokemon rfaqs, taking as example the code for **/rfaq great tusk**. Here is a table of contents

* The code
* Creating a Pokemon faq
  * Pokemon sprite
  * Items
  * Checks
  * Tera types
  * Moves
 
<hr>

## The code

First copy the following code in a notepad or any other similar application. You will be editing this code in order to create a new faq. Once it is done you can add it with /addhtmlfaq [pokemon], followed by the code. Please note that the comma is important as it separates the name of the faq from the content. In place of [pokemon] you want to write the name of the pokemon; the following code in particular is for great tusk, so you can try /addhtmlfaq greattusk,

```html
<center>
<img src="//play.pokemonshowdown.com/sprites/ani/greattusk.gif" width="104" height="68">
<table style="text-align:center;margin:auto">
<tbody>
<tr>
<td style="padding-right: 25px">
</td>
<td style="padding-right: 25px">
<b>Items:</b> <br><psicon item=heavydutyboots> <psicon item=rockyhelmet> <psicon item=boosterenergy> <psicon item=leftovers> <br><br><b>Checks:</b><br><psicon pokemon=walkingwake><psicon pokemon=ironvaliant><psicon pokemon=sinistcha><psicon pokemon=skarmory><psicon pokemon=kyurem><psicon pokemon=ogerponwellspring><br><psicon pokemon=corviknight><psicon pokemon=moltres><psicon pokemon=zapdos><psicon pokemon=enamorus><psicon pokemon=dondozo><psicon pokemon=latios>
</td>
<td>
<b>Tera types:<br> <span style="color: #B7B7CE">Steel</span>, <span style="color: #1dece5"> Ice</span>, <span style="color: #735797">Ghost</span>, <span style="color: #E2BF65">Ground</span>, <span style="color: #EE8130">Fire</span>,<br><span style="color: #6390F0">Water</span>, <span style="color: #A33EA1">Poison</span>, <span style="color: #C22E28">Fighting</span></b><br><br><b>Moves:</b><br>Rapid Spin, Headlong Rush, Ice Spinner,<br>Stealth Rock, Knock Off, Bulk Up,<br>Close Combat, Earthquake, Head Smash,<br>Temper Flare, Taunt, Stone Edge, Supercell Slam
</td>
</tr>
</tbody>
</table>
</center>
```

<hr>

## Creating a Pokemon faq

### Pokemon Sprite

```html
<img src="//play.pokemonshowdown.com/sprites/ani/greattusk.gif" width="104" height="68">
```
The above code includes an url to the Pokemon's sprite on PS! If the Pokemon has a gif, you can simply change the part where it says greattusk for the name of the new Pokemon. You may have to struggle a bit to find the sprite, png, or gif, but they are all in the [sprite directory](https://play.pokemonshowdown.com/sprites/). To obtain the width and height you can open the url; once there, the name of the page will be the dimensions of the sprite.

<hr>

### Items

```html
<psicon item=heavydutyboots> <psicon item=rockyhelmet> <psicon item=boosterenergy> <psicon item=leftovers>
```
This part is the items. Feel free to change the names; be careful, as items with multiple words on their names must be written as a single word, so no Booster Energy, its boosterenergy. It should be self explanatory how to add ot remove items. I also recommend leaving a space between each item, as the code shows.

<hr>

### Checks

```html
<br><br><b>Checks:</b><br><psicon pokemon=walkingwake><psicon pokemon=ironvaliant><psicon pokemon=sinistcha><psicon pokemon=skarmory><psicon pokemon=kyurem><psicon pokemon=ogerponwellspring><br><psicon pokemon=corviknight><psicon pokemon=moltres><psicon pokemon=zapdos><psicon pokemon=enamorus><psicon pokemon=dondozo><psicon pokemon=latios>
```
This part is the pokemon checks. Just as with items, Pokemon with multiple words in their names must be written as a single word, so no Ogerpon-Wellspring or Walking Wake, its ogerponwellspring and walkingwake. Note that there is a part with a **br**, that is a linebreak, you can add them or not depending how you want the faq to look. In particular, there are two linebreaks at the start, this happens in this rfaq cause you want the word **Checks** to be aligned with the word **Moves**; try to add or remove more **br** to see how the faq changes.

<hr>

### Tera types

```html
<span style="color: #B7B7CE">Steel</span>, <span style="color: #1dece5"> Ice</span>, <span style="color: #735797">Ghost</span>, <span style="color: #E2BF65">Ground</span>, <span style="color: #EE8130">Fire</span>,<br><span style="color: #6390F0">Water</span>, <span style="color: #A33EA1">Poison</span>, <span style="color: #C22E28">Fighting</span>
```
Here are the Tera-types. You can just change the word for a different type and add the proper color; the hex for the colors can be found in another file in thie repository, that is [here](https://github.com/setsu-stsna/ouroom/blob/main/pokemontypes_colors.txt). Note that there is a **br** here, this is a linebreak and can be used depending on how you want the faq to look.

<hr>

### Moves

```html
Rapid Spin, Headlong Rush, Ice Spinner,<br>Stealth Rock, Knock Off, Bulk Up,<br>Close Combat, Earthquake, Head Smash,<br>Temper Flare, Taunt, Stone Edge, Supercell Slam
```
Here you can add and remove moves. The **br** represent linebreaks, so you can add or remove them depending on how you want the rfaq to look.


