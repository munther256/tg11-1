# formeln in markdown

## formel im Text
Um eine formel in text darzustellen werden die `$$ ` verwendet.
 Die pq-formel lautet:
  $-\frac {p}{2} \pm \sqrt{\left(\frac{p}{2}\right)^2-q}$

sie wird mit folgendem code erstellt:

`$-\fraq{p}{2} \pm \sqrt{ \left(\fraq{p}{2}\right)^2-q}$

einfache formel: $3x^2+5x-7=0$

## Abgesetzte formel 
um eine eine Formel vom text abzusetzen werden je 2`$$` verwendet. 
beispiel: 
  $-\frac {p}{2} \pm \sqrt{\left(\frac{p}{2}\right)^2-q}$

diese formel wird dargestellt mit: 
  `$-\frac {p}{2} \pm \sqrt{\left(\frac{p}{2}\right)^2-q}$`

---
## Brüche 
brüche werden mit den befehl `$\fraq{<zähler>}{<nenner>}$`

Der bruch $\frac{3x}{x^2-1}$ wird erstellt mit `$\frac{3x}{x^2-1}$`
der befehl $\dfraq{}{}$
## wurzeln 
Die wurzel wird mit dem befehl `$\sqrt{<wert>}$` erstellt.
als optionaler parmeter kann die n-te wurzel mit angegeben werden mit
 `$sqrt[<n>]{<wert>}$` 

 ### Beispiele 
  - Die Wurzel $\sqrt{2}$ wird mit `$\sqrt{2}$` erstellt. 
  - Die 3-te Wurzel aus 2 $\sqrt[3]{2}$ wird mit befehl `2 $\sqrt[3]{2}$` erstellt.

  ## hoch- und tiefstellen 
  um einen wert hochgestellt darzustellen wird das `^{<wert>}` -Zeichen verwendet.

  ### Beispiel Hochgestellt 
  $e^{j\omega t}$ wird erstellt mit `$e^{j\omega t}$`

  um einen wert tiefgestellt darzustellen wird `_{<wert>} verwendet. 

  ### Beispiel Tiefgestellt
  die effektievspannung $U_{eff}$ wird dargestellt mit `$U_{eff}$`

## Sonderzeichen 
eine zusammenfassung vieler sonderzeichen finden wir [wikipedia](https://de.wikibooks.org/wiki/LaTeX-Kompendium:_Sonderzeichen).

### Beispiele: 
- $\alpha$ wird ertellt mit `$\alpha$`
- $\beta$ wird ertellt mit `$\beta$`
- $\gamma$ wird ertellt mit `$\gamma$`
- $\omega$ wird ertellt mit `$\omega$`
- $\Omega$ wird erstellt mit `$\Omega$`

## Integral 
ein Integral $\int_a^b \limits f(x) \cdot dx$
wird ertstellt mit `$\int_a^b \limits f(x) \cdot dx$`

Der Befehl `\limits` sorgt dafür dass die integrationsgrenzen a und b über und unter dem integralsymbol angezeigt werden. 