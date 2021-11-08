# Vi lager en skritt teller
## Trinn 1
Vi starter med denne
## Tinn 2
Velg variables og trykk Make a Variable.  I vinduet som kommer frem skriver du skritt og trykker på OK.  Plasser så set skritt to 0 inn i on start 
```blocks
let skritt = 0
```
## Trinn 3
Velg en showNumber blokk som du finner under Basic og sett den inn i on start
```blocks
basic.showNumber(0)
```
## trinn 4
Trykk på variables og velg variabelen skritt.  Set den inn i show number 
```blocks
basic.showNumber(skritt)
```
## trinn 5
Fra logic henter du blokken if og plassere den inn i forever blokken:
```blocks
basic.forever(function() {
    if (true) {

    }
    
})
```
## trinn 6
Sett inn en comparsion blokk av typen = og sett den inn i if setningen der det står true:
```blocks
if (0==0) {

}

```
## Trinn 7
Hent blokken acceleration som du finner under input og plasser den i if setningen.
```blocks
if (input.acceleration(Dimension.X) == 0) {
        
    }
})
```
##  Trinn 8
Endre x til strength ved å trykke på trekanten:
```blocks
if (input.acceleration(Dimension.Strength) == 0) {
        
    }
})
```
## Trinn 9
Endre verdien er lik til større enn i nedtrekksmenyen (trykk på trekanten):
```blocks
if (input.acceleration(Dimension.Strength) > 0) {
        
    }
})
```
## Trinn 10
Endre tallet 0 til 1500:
```blocks
if (input.acceleration(Dimension.Strength) > 1500) {
        
    }
})
```
## Trinn 11
Sett inn en change skritt by 1 blokk som du finner under variables:
```blocks
if (input.acceleration(Dimension.Strength) > 1500) {
       skritt+=1 
    }
})
```
## Trinn 12
Sett inn en on button A pressed blokk som du finner under Input:
```blocks
input.onButtonPressed(Button.A, function () {
    
})
```
## Trinn 13
Sett en show number blokk inn i on button A pressed. Du finner den under Basic:
```blocks
input.onButtonPressed(Button.A, function () {
    basic.showNumber(0)
})
```
## Trinn 14
Sett inn en skritt blokk som du plasserer inn i show number blokken som er plassert inne i on button A pressed.   Du finner den under Variables:
```blocks
input.onButtonPressed(Button.A, function () {
    basic.showNumber(skritt)
})
```


> Open this page at [https://svein-tore.github.io/test_tutorial/](https://svein-tore.github.io/test_tutorial/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/svein-tore/test_tutorial** and import

## Edit this project ![Build status badge](https://github.com/svein-tore/test_tutorial/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/svein-tore/test_tutorial** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/svein-tore/test_tutorial/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
