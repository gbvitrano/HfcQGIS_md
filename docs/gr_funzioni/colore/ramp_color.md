# ramp_color

Restituisce una stringa rappresentante un colore ottenuto da una scala colore.

## Variante di scala salvata

Restituisce una stringa che rappresenta un colore da una scala salvata

## Sintassi

ramp_color(_<span style="color:red;">ramp_name</span>, <span style="color:red;">value</span>_)

## Argomenti

* _<span style="color:red;">ramp_name</span>_ il nome della scala colore come stringa, per esempio 'Spectral'
* _<span style="color:red;">value</span>_ la posizione nella scala colore da cui selezionare il colore come numero reale fra 0 e 1

## Esempi

* `ramp_color('Spectral',0.3) → '253,190,115,255'`

![](../../img/colore/ramp_color/ramp_color1.png)

## nota

Le scale di colore disponibili differiscono fra le varie installazioni di QGIS. Questa funzione potrebbe non restituire il risultato atteso se sposti i tuoi progetti QGIS fra le diverse installazioni.

## Variante di scala creata con un'espressione

Restituisce una stringa che rappresenta un colore da una scala creata con un'espressione

## Sintassi

ramp_color(_<span style="color:red;">ramp</span>, <span style="color:red;">value</span>_)

## Argomenti

* _<span style="color:red;">ramp</span>_ la scala di colori
* _<span style="color:red;">value</span>_ la posizione nella scala colore da cui selezionare il colore come numero reale fra 0 e 1

## Esempi

* `ramp_color(create_ramp(map(0,'0,0,0',1,'255,0,0')),1) →255,0,0,255`

## osservazioni

--
