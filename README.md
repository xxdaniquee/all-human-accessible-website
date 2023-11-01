
# Accessible Website

Een website van De Hallen waar een stichting of bewoner een initiatief kan aanmelden via een formulier.

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
De hallen heeft een nieuwe website waar buurtinitiatieven uit Amsterdam - west op staan voor hun buren. <br>
Op deze pagina kunnen de buren of organisaties, via een contactformulier, een organisatie aanmelden zodat die ook op de site komt te staan. <br> <br>

Link naar de pagina:       <br><br>


User story:
> Als stichting of bewoner kun je een initiatief aanmelden via een contactformulier op de website.
<img width="923" alt="Screenshot 2023-11-01 at 20 35 10" src="https://github.com/xxdaniquee/all-human-accessible-website/assets/128936068/e094993f-e549-41aa-ad31-1d1579b2bd19">

_De pagina_

## Kenmerken
De website is gebouwd met HTML en CSS. <br>

### HTML
De HTML is verdeeld met settings in de _head_ en de content in de _body_

#### Head
In de head staat een link naar de bijbehorende css file:
```
<link rel="stylesheet" href="./styles/style.css">
```

#### Body
De body van de HTML is verdeeld in 3 onderdelen: Header, Main en Footer:

##### Header
In de header staat het menu om verder te navigeren: 
```
<nav class="dropdown">
```
##### Main
In het main gedeelte staat alle content. Namelijk alle teksten en het formulier.
```
<div class="top">
<section class="formulier">
```
##### Footer
In de footer staan de links naar de andere pagina's.

### CSS

De css is een mobile first design en er zijn 2 media queries om het design aan te passen naar grotere schermen:
* @media (min-width:42rem) voor tablets.
* @media (min-width:63rem) voor laptops en desktop.

## Bronnen
* De Hallen: https://dehallen-amsterdam.nl/
* De Hallen huisstijl: https://github.com/fdnd-agency/de-hallen/blob/main/Huisstijl%20De%20Hallen.png
* Google Font Roboto: https://fonts.google.com/specimen/Roboto
* Foto Amsterdam: https://unsplash.com/photos/white-boat-on-river-between-buildings-during-daytime--e4vLFZV9QM
* HTML Forms: https://www.w3schools.com/html/html_forms.asp
## Licentie


This project is licensed under the terms of the [MIT license](./LICENSE).
