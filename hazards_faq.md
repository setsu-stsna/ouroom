# Hazards rfaq

Here I describe how to update **/rfaq hazards**

Contents:
* The code
* Updating the faq

<hr>

## The code

What you first want to do is copy this entire thing into a notepad or any other text application. You can update the text from there and once you are done, you can use **/addhtmlfaq hazards,** followed by the new code. Please keep in mind that the comma is important, as it separates the name of the faq from the content.

```html
<table style="width: 100%">
<tr>
<td><b>Stealth Rock</b>
<td><b>Spikes</b>
<td><b>Removal and Hatt</b>
<tr>
<td><b>S</b> <psicon pokemon=landorustherian><psicon pokemon=garganacl><psicon pokemon=tinglu>
<td><b>S</b> <psicon pokemon=tinglu><psicon pokemon=samurotthisui>
<td><b>S</b> <psicon pokemon=greattusk><psicon pokemon=irontreads>
<tr>
<td><b>A</b><psicon pokemon=greattusk><psicon pokemon=irontreads><psicon pokemon=glimmora><psicon pokemon=deoxysspeed><psicon pokemon=heatran><psicon pokemon=tinkaton>
<td><b>A</b> <psicon pokemon=gliscor>
<td><b>A</b> <psicon pokemon=weezinggalar><psicon pokemon=hatterene><psicon pokemon=cinderace>
<tr>
<td><b>B</b> <psicon pokemon=garchomp><psicon pokemon=clefable><psicon pokemon=skarmory><psicon pokemon=gliscor>
<td><b>B</b> <psicon pokemon=skarmory><psicon pokemon=ogerponwellspring><psicon pokemon=deoxysspeed><psicon pokemon=garchomp>
<td><b>B</b> <psicon pokemon=corviknight><psicon pokemon=glimmora>
<tr>
<td><b>C</b> <psicon pokemon=torkoal><psicon pokemon=tyranitar><psicon pokemon=clodsire><psicon pokemon=blissey>
<td><b>C</b> <psicon pokemon=glimmora><psicon pokemon=clodsire><psicon pokemon=ogerpon-cornerstone><psicon pokemon=overqwil><psicon pokemon=meowscarada><psicon pokemon=ogerpon><psicon pokemon=chesnaught>
<td><b>C</b> <psicon pokemon=excadrill><psicon pokemon=scizor><psicon pokemon=torkoal><psicon pokemon=talonflame><psicon pokemon=mandibuzz><psicon pokemon=regieleki>
<tr>
<td><b>F</b> <psicon pokemon=necrozma><psicon pokemon=bronzong><psicon pokemon=arcaninehisui><psicon pokemon=smeargle><psicon pokemon=kingambit>
<td><b>F</b> <psicon pokemon=pincurchin><psicon pokemon=smeargle><psicon pokemon=klefki>
<td><b>F</b> <psicon pokemon=smeargle><psicon pokemon=hawlucha>
</table>
```
<hr>

## Updating the faq

The faq is structured in a table so it has rows and columns.

```html
<tr>
<td><b>Stealth Rock</b>
<td><b>Spikes</b>
<td><b>Removal and Hatt</b>
```

The above is the content in the first row. 

```html
<tr>
<td><b>S</b> <psicon pokemon=landorustherian><psicon pokemon=garganacl><psicon pokemon=tinglu>
<td><b>S</b> <psicon pokemon=tinglu><psicon pokemon=samurotthisui>
<td><b>S</b> <psicon pokemon=greattusk><psicon pokemon=irontreads>
```

The above is the content in the second row, the S tier. The first line lists the Pokemon that are S tier Stealth Rock users, the second line the ones that are S tier spikers, and the third one the S tier removal. Simply change the name of the Pokemon. Please be aware that names of Pokemon with two words or with a dash have to be written as a single word, so none of Landorus-Therian or Iron Treads, you have to write landorustherian and irontreads.

```html
<tr>
<td><b>A</b><psicon pokemon=greattusk><psicon pokemon=irontreads><psicon pokemon=glimmora><psicon pokemon=deoxysspeed><psicon pokemon=heatran><psicon pokemon=tinkaton>
<td><b>A</b> <psicon pokemon=gliscor>
<td><b>A</b> <psicon pokemon=weezinggalar><psicon pokemon=hatterene><psicon pokemon=cinderace>
```

The above is the content in the third row, the A tier. I think you understand the point by now. 

```html
<tr>
<td><b>F</b> <psicon pokemon=necrozma><psicon pokemon=bronzong><psicon pokemon=arcaninehisui><psicon pokemon=smeargle><psicon pokemon=kingambit>
<td><b>F</b> <psicon pokemon=pincurchin><psicon pokemon=smeargle><psicon pokemon=klefki>
<td><b>F</b> <psicon pokemon=smeargle><psicon pokemon=hawlucha>
```

The above is the content in the last row, the F tier. If you remove this code from the faq you will remove the entire F tier, try it out! This should tell you how to remove and add rows. Be careful to also remove the **tr** part if you are going to remove a row, and to add it if you are going to add a row. 
