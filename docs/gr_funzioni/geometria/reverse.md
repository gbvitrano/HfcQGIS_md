# reverse

Inverte il verso di una linestring invertendo l'ordine dei sui vertici

## Sintassi

reverse(_<span style="color:red;">geometry</span>_)

## Argomenti

* _<span style="color:red;">geometry</span>_ una geometria

## Esempi

* `geom_to_wkt(reverse(geom_from_wkt('LINESTRING(0 0, 1 1, 2 2)'))) → 'LINESTRING(2 2, 1 1, 0 0)'`

![](../../img/geometria/reverse/reverse1.png)

## nota bene

--

## osservazioni

--

![](../../img/geometria/reverse/reverse2.png)
