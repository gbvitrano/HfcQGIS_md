# soundex

Restituisce la rappresentazione Soundex di una stringa. Soundex รจ un algoritmo di abbinamento fonetico, per cui le stringhe con suoni simili dovrebbero essere rappresentate dallo stesso codice Soundex.

## Sintassi

* soundex(*<span style="color:red;">string</span>*)

## Argomenti

* _<span style="color:red;">string</span>_ una stringa

## Esempi
```
* soundex('robert') โ 'R163'
* soundex('rupert') โ 'R163'
* soundex('rubin') โ 'R150'
```

![](../../img/corrispondenza_fuzzy/soundex1.png)

secondo questo algoritmo *Sicilia bedda* e *Sicilia bella* hanno stesso suono :+1:

![](../../img/corrispondenza_fuzzy/soundex2.png)
