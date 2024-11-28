# LaTeX-u-Markdown :star:

Konverzija iz LaTeX u Markdown i ispravljanje formatiranja.

## Konvertiranje .tex u .md format

Konvertirali smo [LaTeX file](102_radnje.tex) u [Markdown file](102_radnje.md) pomocu Pandoca.

## Ispravljanje blokova koda

Pretrazili smo sva spominjanja " ::: " i zamjenili ih sa " ``` " te urdili kod (npr. obrisali nepotrebne / i preuredili />/>/> u >>>).

## Ispravljaje tablica

Ispravili sintaksu za tablice da se tocno prikazuje u markdown formatu, pomocu ChatGPTa.

## Ispravljaje highlightanih blokova

Prepravili sintaksu blokova.

## Prije:

::: center
::: {#tab:operatori-aritmetika}
**operator** **operacija** **primjer** **rezultat**

---

$\boldsymbol{+}$ zbrajanje $7\:+\:2$ 9
$\boldsymbol{-}$ oduzimanje $7\:-\:2$ 5
$\boldsymbol{*}$ množenje $7\:*\:2$ 14
$\boldsymbol{**}$ potenciranje $7\:**\:2$ 49
$\boldsymbol{/}$ dijeljenje $7\:/\:2$ 3.5
$\boldsymbol{//}$ cjelobrojno dijeljenje $7\://\:2$ 2
$\boldsymbol{\%}$ ostatak cjelobrojnog dijeljenja $7\:\%\:2$ 1
: Aritmetički operatori
:::
:::

## Poslje:

| Operator | Operacija                       | Primjer  | Rezultat |
| -------- | ------------------------------- | -------- | -------- |
| `+`      | Zbrajanje                       | `7 + 2`  | `9`      |
| `−`      | Oduzimanje                      | `7 - 2`  | `5`      |
| `*`      | Množenje                        | `7 * 2`  | `14`     |
| `**`     | Potenciranje                    | `7 ** 2` | `49`     |
| `/`      | Dijeljenje                      | `7 / 2`  | `3.5`    |
| `//`     | Cjelobrojno dijeljenje          | `7 // 2` | `2`      |
| `%`      | Ostatak cjelobrojnog dijeljenja | `7 % 2`  | `1`      |
