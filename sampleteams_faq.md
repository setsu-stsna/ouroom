# Gen 9 Sample Teams rfaq

In the following document I describe how to update the rfaq **/rfaq gen9sampleteams**. Here is a table of contents

* A few notes
* The code
* Updating a slot
  * Updating the paste
  * Changing the Pokemon sprites
  * Changing the name of the team and its author
  * Adding a description / RMT link (Optional)
* Last thing if you know html

<hr>

## A few notes

The faq is structured in a way such that there can be at most 6 Offense teams, 6 BO teams, 6 Balance teams, and 3 stalls. Adding anything more than 21 teams is very likely not possible due to PS! having a character limit of 10000 in each htmlfaq; this limit was actually updated after **skymin / torino** recommended it [here](https://www.smogon.com/forums/threads/3761841/). If you wanted to add 4 or more stall teams, or less than 4 Offenses, the faq would have to change. This can be easily done if you know a little bit of html, but realistically and hopefully, this won't happen and so you won't be needing it.

If you just run the command **/rfaq gen9samples** and you are a room moderator or room owner, you will see a button saying **source**. If you click on this button you will see a similar code but all in one big paragraph. Do not worry much about it, it is basically the same thing but harder to read. Whenever you want to update the faq, please instead refer to the code I am showing below to do so.

<hr>

## The Code

Before anything else you want to copy this entire thing into a notepad or any other text application. You will be editing it in order to update the faq. Once it is finished you can add it by typing **/addfaq gen9sampleteams,** followed by the code below. Please beware that the comma is important, since it separates the name of the faq and its actual content.


```html
<center>
<b style="font-size:110%;color:#fff;background:#ff4a4d;padding:2px;display:block">GEN 9 SAMPLE TEAMS</b>
<p style="font-size:50%">
<div style="max-width:420px">
<details>
<summary>
<b style="font-size:130%">Offense</b>
</summary>
<table style="border-spacing:10px 5px; font-size:95%">
<tr>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/57780b9afe26d51b"><div style="background:#E2B7B8;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=dragonite><psicon pokemon=greattusk><psicon pokemon=deoxysspeed><psicon pokemon=gholdengo><psicon pokemon=zamazenta><psicon pokemon=ironvaliant></div>Life Orb Dragonite Hazards Deoxys-S HO</a> by <b>Vert</b>
<td style="width: 33.34%;vertical-align:top">
<a href="//pokepast.es/43eb8733a7cff75e"><div style="background:#E2B7B8;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=hawlucha><psicon pokemon=samurotthisui><psicon pokemon=rillaboom><psicon pokemon=gholdengo><psicon pokemon=kyurem><psicon pokemon=landorustherian></div>Hawlucha + Gholdengo<br>Grassy Terrain</a> by <b>Attribute</b>                      
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/f3c47120f38435fc"><div style="background:#E2B7B8;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=zamazenta><psicon pokemon=ironhands><psicon pokemon=ceruledge><psicon pokemon=ironvaliant><psicon pokemon=deoxysspeed><psicon pokemon=glimmora></div>Life Orb Ceruledge Screens</a> by <b>hellom</b>
<tr>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/a4c4b08f0dabaaa8"><div style="background:#E2B7B8;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=ragingbolt><psicon pokemon=ogerponwellspring><psicon pokemon=zamazenta><psicon pokemon=cresselia><psicon pokemon=glimmora><psicon pokemon=kingambit></div>Offensive Cresselia Screens</a> by <b>Storm</b> <b>Zone</b>
<td style="width: 33.4%;vertical-align:top">
<a href="//pokepast.es/b3ac0f8febd317c0"><div style="background:#E2B7B8;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=kingambit><psicon pokemon=kommoo><psicon pokemon=ironvaliant><psicon pokemon=kyurem><psicon pokemon=irontreads><psicon pokemon=ironcrown></div>Kommo-O Offense by</a><br><b>Mada</b>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/973922f6b4b266e5"><div style="background:#E2B7B8;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=walkingwake><psicon pokemon=greattusk><psicon pokemon=ninetales><psicon pokemon=cresselia><psicon pokemon=zarude><psicon pokemon=ceruledge></div>Zarude Sun</a> by <b>Ewin</b> 
</table>
</details>
<hr>
<details>
<summary>
<b style="font-size:130%">Bulky Offense</b>
</summary>
<table style="border-spacing:10px 5px; font-size:95%">
<tr>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/efd0a22207f6e5f9"><div style="background:#e2dbb7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=dragapult><psicon pokemon=gliscor><psicon pokemon=ogerponwellspring><psicon pokemon=ironcrown><psicon pokemon=tinglu><psicon pokemon=kingambit></div>Dragapult + Wellspring<br>BO</a> by <b>Vert</b>
<td style="width: 33.4%;vertical-align:top">
<a href="//pokepast.es/54d94a017c0f67ee"><div style="background:#e2dbb7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=hatterene><psicon pokemon=greattusk><psicon pokemon=tornadustherian><psicon pokemon=kyurem><psicon pokemon=slowkinggalar><psicon pokemon=kingambit></div>AV Tornadus-T + Specs Kyurem BO</a> by <b>heileone</b> 
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/f3a8f53d6e1fd2bb"><div style="background:#e2dbb7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=kyurem><psicon pokemon=hatterene><psicon pokemon=darkrai><br><psicon pokemon=greattusk><psicon pokemon=dragonite><psicon pokemon=gholdengo></div>3 Attacks Nasty Plot Gholdengo BO</a> by <b>kDCA</b>  
<tr>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/02b19c79ad13bbdd"><div style="background:#e2dbb7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=slowkinggalar><psicon pokemon=greattusk><psicon pokemon=kyurem><psicon pokemon=kingambit><psicon pokemon=cinderace><psicon pokemon=zapdos></div>Specs Kyurem + Cinderace BO</a> by <b>Ewin</b>
<td style="width: 33.4%;vertical-align:top">
<a href="//pokepast.es/d310ee8cb4666352"><div style="background:#e2dbb7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=dragonite><psicon pokemon=samurotthisui><psicon pokemon=gholdengo><psicon pokemon=pecharunt><psicon pokemon=walkingwake><psicon pokemon=tinglu></div>Walking Wake + Samurott-H BO</a> by <b>Attribute</b>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/4df83fed9c8bbc53"><div style="background:#e2dbb7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=gholdengo><psicon pokemon=irontreads><psicon pokemon=moltres><psicon pokemon=zamazenta><psicon pokemon=samurotthisui><psicon pokemon=garganacl></div>Garganacl + Iron Treads BO</a> by <b>LOOR</b>
</table>
</details>
<hr>
<details>
<summary>
<b style="font-size:130%">Balance</b>
</summary>
<table style="border-spacing:10px 5px; font-size:95%">
<tr>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/b1c94db7a26e6e90"><div style="background:#c4e2b7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=darkrai><psicon pokemon=garchomp><psicon pokemon=alomomola><psicon pokemon=corviknight><psicon pokemon=weezinggalar><psicon pokemon=ogerpon></div>Specs Darkrai + Ogerpon Balance</a> by <b>CTC</b>
<td style="width: 33.4%;vertical-align:top">
<a href="//pokepast.es/5e8f4b8ad86c3163"><div style="background:#c4e2b7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=gliscor><psicon pokemon=gholdengo><psicon pokemon=dragonite><psicon pokemon=tinglu><psicon pokemon=darkrai><psicon pokemon=zamazenta></div>Dragonite + Darkrai Hazard Stack</a> by <b>CTC</b>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/30429d73a070542b"><div style="background:#c4e2b7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=dragonite><psicon pokemon=tinglu><psicon pokemon=clefable><psicon pokemon=pecharunt><psicon pokemon=heatran><psicon pokemon=zamazenta></div>Dragonite + Heatran Anti-Offense Balance</a> by <b>ABR, Axzel</b>
<tr>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/dce51a40b1e57f2d"><div style="background:#c4e2b7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=ogerpon><psicon pokemon=samurotthisui><psicon pokemon=blissey><psicon pokemon=gliscor><psicon pokemon=skarmory><psicon pokemon=pecharunt></div>Samurott + Blissey + Ogerpon Fat Balance</a> by <b>ABR</b> - <a href="//pokepast.es/5c623ee360e9883e">Description</a>
<td style="width: 33.4%;vertical-align:top">
<a href="//pokepast.es/bae962323c67e031"><div style="background:#c4e2b7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=kyurem><psicon pokemon=corviknight><psicon pokemon=tinglu><psicon pokemon=dondozo><psicon pokemon=slowkinggalar><psicon pokemon=cinderace></div>Sub Kyurem + PhysDef Dondozo Balance</a> by <b>Blimax (CTC edit)</b>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/692d613a850bd291"><div style="background:#c4e2b7;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=weezinggalar><psicon pokemon=alomomola><psicon pokemon=irontreads><psicon pokemon=tornadustherian><psicon pokemon=zamazenta><psicon pokemon=lokix></div>Band Zama Balance</a> by <b>oldspicemike (Tyrants edit)</b> - <a href="//pokepast.es/b8f51b21803e391d">Description</a>
</table>
</details>
<hr>
<details>
<summary>
<b style="font-size:130%">Stall</b>
</summary>
<table style="border-spacing:10px 5px; font-size:95%">
<tr>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/6f16c982909428f7"><div style="background:#B7C9E2;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=weezinggalar><psicon pokemon=gliscor><psicon pokemon=blissey><psicon pokemon=corviknight><psicon pokemon=dondozo><psicon pokemon=toxapex></div>Swords Dance Gliscor Removal Stall</a> by <b>143 forever (Star edit)</b>
<td style="width: 33.4%;vertical-align:top">
<a href="//pokepast.es/056ce7c40fa545c6"><div style="background:#B7C9E2;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=dondozo><psicon pokemon=blissey><psicon pokemon=gliscor><psicon pokemon=toxapex><psicon pokemon=mandibuzz><psicon pokemon=talonflame></div>Mandibuzz Stall</a> by <b>jb291</b>
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/a7f2db28d77f7615"><div style="background:#B7C9E2;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=clodsire><psicon pokemon=toxapex><psicon pokemon=corviknight><psicon pokemon=dondozo><psicon pokemon=clefable><psicon pokemon=gliscor></div>Clodsire + Fast Gliscor Stall</a> by <b>WhiteQueen</b>
</table>
</details>
</div>
</center>
```

<hr>

## Updating a slot

Let us take the following two lines of code. Do not worry, you may not see all the content here but it will show up in a notepad if you copy it all.

```html
<td style="width: 33.3%;vertical-align:top">
<a href="//pokepast.es/f3c47120f38435fc"><div style="background:#E2B7B8;border:3px solid #000;border-radius:10px;width:120px;max-width:100%"><psicon pokemon=zamazenta><psicon pokemon=ironhands><psicon pokemon=ceruledge><psicon pokemon=ironvaliant><psicon pokemon=deoxysspeed><psicon pokemon=glimmora></div>Life Orb Ceruledge Screens</a> by <b>hellom</b>
```

The first important thing is that if you wanted to have less teams by for example removing this slot all together, that is the team *Life Orb Ceruledge Screens by hellom*, you would only need to delete those 2 lines. That is it. Let us know break down the rfaq.

<hr>

### Updating the paste

```html
<a href="//pokepast.es/f3c47120f38435fc">
```

The part above lets you update the pokepaste link. That's it! I highly recommend using this format, the one without the **www** and the **http:** as it decreases the characters while still working. I would keep the // for reasons, do not worry about them.

<hr>

### Changing the Pokemon sprites

```html
<psicon pokemon=zamazenta><psicon pokemon=ironhands><psicon pokemon=ceruledge><psicon pokemon=ironvaliant><psicon pokemon=deoxysspeed><psicon pokemon=glimmora>
```

This part has the Pokemon on the paste, just add the new names if you need to change the paste. Please be aware that names with two words or with a dash **must** be written in one word. So none of Landorus-Therian or Iron Valiant, you have to write landorustherian and ironvaliant.

<hr>

### Changing the name of the team and its author

```html
</div>Life Orb Ceruledge Screens</a> by <b>hellom</b>
```

This part lets you change the name of the team and its author, pretty easy. Be careful to **not** remove the **/div** part nor the **/a** one.

<hr>

### Adding a description / RMT link (Optional)

```html
- <a href="//pokepast.es/5c623ee360e9883e">Description</a>
```

Some teams have this line for a description, or an RMT link. If you want to include it you can simply update the link and add it after the author.

<hr>

## Last thing if you know html

If you 100% need to add a team, note that when you implement this rfaq in PS!, there are some extra characters where the linebreaks usually would be. You can take the time to delete them, that should give you a fair bit of room to add one more team but nothing more.


