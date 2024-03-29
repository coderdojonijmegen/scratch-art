---
title: "Scratch - Art"
date: 2021-10-13T19:07:47+02:00
draft: false
toc: true
headercolor: "teal-background"
onderwerp: Scratch
---

We gaan kunst maken met Scratch.

<!--more-->

## Introductie
Naast een leuke achtergrond en het bewegen van de kat van Scratch kun je nog veel meer doen. Je kunt Scratch ook laten tekenen.

Hier zie je een paar voorbeelden van wat je met Scratch kunt:

|                                      |                                      |                                      |                                      |
| ------------------------------------ | ------------------------------------ | ------------------------------------ | ------------------------------------ |
| ![voorbeeld 1](images/example-1.png) | ![voorbeeld 2](images/example-2.png) | ![voorbeeld 3](images/example-3.png) | ![voorbeeld 4](images/example-4.png) |
   

Deze instructie leert je stap-voor-stap vergelijkbare tekeningen te maken.

<br>

## Benodigdheden

Om de instructie te volgen, heb je naast je computer niets nodig.

Ga naar <a href="https://scratch.mit.edu/projects/editor/" target="_blank">https://scratch.mit.edu/projects/editor/</a> om aan de stappen te beginnen.

Deze instructies gaan er vanuit dat je de pen uitbreiding gebruikt. Deze moet je eerst activeren:

 * Open het overzicht met uitbreidingen:
  ![knop om uitbreidingen te activeren](images/knop-om-uitbreidingen-te-activeren.png)
 * Kies uit het overzicht de pen uitbreiding
  ![keuzescherm uitbreidingen](images/keuze-scherm-uitbreidingen.png)
 * Er zijn nu groene pen blokken beschikbaar die verder in de instructies worden gebruikt
  ![blokken pen uitbreiding](images/blokken-pen-uitbreiding.png)

<br>

## Stappen

### Polygonen
Een polygoon is een ander woord voor een veelhoek. Een veelhoek is een vorm in een plat vlak met een aantal hoeken. Een veelhoek met 3 hoeken is een driehoek. Maar ook een achthoek is een veelhoek. In dit hoofdstuk gaan we veelhoeken tekenen.

<br>

#### Driehoek

![driehoek](images/driehoek.png)

Een driehoek is een eenvoudige veelhoek. Het bestaat uit 3 hoeken en 3 lijnen. Je kunt deze makkelijk teken met Scratch:

![code voor driehoek](images/driehoek-code.png)

Voor elke hoek doe je twee dingen:

1. neem 100 stappen om een lijn te tekenen
2. draai de pen 120°

En dat herhaal je dan 3 keer.

**Oefening 1**: Maak het voorbeeld eens na en experimenteer eens met het aantal stappen of de hoeken.

<br>

#### Vierhoek

![vierhoek](images/vierhoek.png)

De vierhoek is nog een eenvoudige veelhoek. Het bestaat uit 4 hoeken en 4 lijnen. Ook deze kun je makkelijk teken met Scratch:

![code voor vierhoek](images/vierhoek-code.png)

Voor elke hoek doe je twee dingen:

1. neem 100 stappen om een lijn te tekenen
2. draai de pen 90°

En dat herhaal je dan 4 keer.

**Oefening 2**: Neem je code van de driehoek en pas het aan zodat het een vierkant kan maken.  
**Oefening 3**: Neem je code van de vierhoek en probeer er eens een vijfhoek van te maken. Wat moet er veranderen?

Misschien valt het je op, dat de stappen voor de driehoek, vierhoek en vijfhoek erg vergelijkbaar zijn. Het aantal herhalingen is gelijk aan het aantal hoeken en de hoek van de te maken draai wordt wordt steeds groter.

<br>

### Polygoon functie

Bij de vierhoek en vijfhoek zagen we al dat het tekenen ervan vooral bestaat uit herhaling van stappen. Ook is er eigenlijk maar één getalletje dat veranderd; het aantal hoeken.

Om verschillende polygonen te tekenen, is het dus handig om één blokje te hebben waarbij je het aantal hoeken kunt opgeven. 

**Let op**: bij deze stap ga je zelf het blok "polygoon" samenstellen; 
deze bestaat nog niet. 
Om dit te doen ga je naar *Mijn blokken > maak een blok*. 
Hierdoor beland je op het volgende scherm:

![maak een blok](images/maak-een-blok.png)

Verander hier de naam van het blok van *bloknaam* naar *polygoon*.  
Selecteer vervolgens *Voeg een invoer toe: getal of tekst*.  
Noem deze invoer vervolgens *aantal hoeken* en klik op *OK*.  
Vanaf nu staat "polygoon" onder *Mijn blokken* vermeld.  
Daarnaast kan je de variabele "aantal hoeken" verkrijgen 
door deze uit het *definieer polygoon* blok te slepen.

![code voor polygoon](images/polygoon-code.png)

Links staat het nieuwe blok dat polygonen tekent. Rechts staat hoe je het nieuwe blok kunt gebruiken.

**Oefening 4**: Maak het voorbeeld na. Wat wordt er getekend?  
**Oefening 5**: Experimenteer eens wat met het aantal hoeken, wat gebeurt er als je een groot aantal hoeken (20?) kiest?  
**Oefening 6**: Kun je het volgende figuur maken?

![polygoon](images/polygoon.png)

<br>

### Lissajous
Een lissajous is een vorm gemaakt met een wiskundige formule. Het is een combinatie van twee golven.

![sinus golven](images/golf.gif)

De combinatie van twee golven

### Sinusgolf

Voordat we de Lissajous maken, beginnen we met een enkele sinusgolf:

![sinus golf](images/golf.PNG)

Hieronder de code die hiervoor gebruikt is. Het belangrijkste blokje is het groene, met daarin variabelen amplitude, frequentie en x. Dit blokje zorgt voor de golfvorm.

![code voor golven](images/golf-code.png)

**Oefening 7**: Maak het voorbeeld na. Ziet het er hetzelfde uit als in het plaatje?  
**Oefening 8**: Probeer eens wat te varieren met de waarden van variabele amplitude en een frequentie. Wat gebeurd er?

### Lissajous functie
Hieronder staan een paar voorbeelden van een Lissajous. Met twee getallen (a en b) kan je aanpassen hoe een Lissajous eruit ziet.

![lissajous 1](images/lissajous1.png)  
a = 1, b = 2

![lissajous 2](images/lissajous2.png)  
a = 3, b = 4

![lissajous 3](images/lissajous3.png)  
a = 5, b = 4

De code om er een te maken ziet er als volgt uit: 

![code voor een lissajous](images/lissajous-code.png)

- Eerst wordt de pen gereset. Dan wordt de Lissajous functie aangeroepen met drie waardes: maat, a en b.
- Daarna wordt er elke keer de X- en Y-positie berekend. Hiermee wordt de vorm getekend.

Het groene blokje dat zorgt voor de golfvorm, wordt nu twee keer wordt gebruikt in het blauwe 'ga naar' blok.

**Oefening 9**: Maak het voorbeeld na. Kun je de waarden a en b van de drie voorbeelden gebruiken? Zijn de getekende plaatjes dan hetzelfde als de drie voorbeelden?  
**Oefening 10**: Probeer eens rare getallen uit voor maar, a en b en kijk wat er gebeurd.  
**Oefening 11**: Maak de lissajous kleurrijk, zoals als oefening 6.

<br>

## Conclusie
Je hebt nu een indruk gekregen van hoe je met Scratch kunt tekenen. Eerst door veelhoeken of polygonen te tekenen en te herhalen en vervolgens door een Lissajous te maken.

Heb je de smaak te pakken gekregen van het maken van kunst met Scratch? Kijk dan ook naar deze voorbeelden:

- Scratch 'art': <a href="https://scratch.mit.edu/search/projects?q=art" target="_blank">https://scratch.mit.edu/search/projects?q=art</a>
- Scratch 'kunst': <a href="https://scratch.mit.edu/search/projects?q=kunst" target="_blank">https://scratch.mit.edu/search/projects?q=kunst</a>

<br>
<br>
<br>

{{< licentie rel="http://creativecommons.org/licenses/by-nc-sa/4.0/">}}
