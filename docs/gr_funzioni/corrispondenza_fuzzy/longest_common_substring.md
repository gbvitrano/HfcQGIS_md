# longest_common_substring

Restituisce la sottostringa in comune più lunga tra due stringhe. Questa sottostringa è la stringa più lunga che è una sottostringa delle due stringhe in ingresso. Es: la sottostringa in comune più lunga di "ABABC" e "BABCA" è "ABC". La sottostringa è sensibile alle lettere maiuscole

## Sintassi

* longest_common_substring(*<span style="color:red;">string1</span>, <span style="color:red;">string2</span>*)

## Argomenti

* _<span style="color:red;">string1</span>_ una stringa
* _<span style="color:red;">string2</span>_ una stringa


## Esempi
```
* longest_common_substring('ABABC','BABCA') → 'ABC'
* longest_common_substring('abcDeF','abcdef') → 'abc'
* longest_common_substring(upper('abcDeF'),upper('abcdex')) → 'ABCDE'
```

![](../../img/corrispondenza_fuzzy/longest_common_substring1.png)
