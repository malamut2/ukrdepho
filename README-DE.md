[![EN](readme-files/united_kingdom_home_icon_64.png)](README.md)
[![DE](readme-files/germany_home_icon_64.png)](README-DE.md)
[![UK](readme-files/ukraine_home_icon_64.png)](README-UK.md)

# ukrdepho
Ein Windows Tastatur-Layout für die ukrainische Sprache, 
auf phonetischer Grundlage des deutschen Standard-Tastatur-Layouts.

## ToDo

Sowohl dieses Readme als auch das Layout selbst sind 
Work in Progress. Dieser Abschnitt wird entfernt, sobald das
Layout fertig und von mindestens einem ukrainischen Natursprachler,
der auch gut deutsch spricht, abgenommen wurde.

## Motivation

Sowohl als Deutscher, der Ukrainisch lernen möchte, als auch als
Ukrainer in Deutschland hat man es nicht leicht, ukrainische Texte
zu tippen. Ukrainische Tastaturen sind schwer erhältlich, haben kein
einheitliches Layout und sind oft mit einem russischen Layout
kombiniert. Ein schnelles Umschalten zwischen deutschem und
ukrainischem Tippen ist nur schwer möglich, man muss dafür mindestens
eines der beiden Layouts Deutsch und Ukrainisch vollständig im Kopf
haben.

Für alle, die mit einer deutschen Tastatur arbeiten und kein
ukrainisches Layout fest im Gedächtnis haben, kann es von Vorteil
sein, sich an den auf der deutschen tastatur aufgedruckten Buchstaben
zu orientieren. Die meisten ukrainischen Buchstaben haben ja im
Deutschen eine 1:1 Entsprechung für denselben Laut.

Man benötigt also ein Layout, das den deutschen Tasten für die
ukrainische Sprache so weit wie möglich folgt. Windows 11 scheint
so etwas leider nicht anzubieten, daher gibt es nun hier eines als
Open Source. Das Layout wurde mit dem
[Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134)
erstellt, als Basis diente das deutsche Standard-Layout.

## Zuordnung der Tasten

Die [deutsche Wikipedia](https://de.wikipedia.org/wiki/Umschrift_des_ukrainischen_kyrillischen_Alphabets#Tabellen_zu_den_verschiedenen_Umschrift-_und_Romanisierungsvarianten)
nennt die folgende übliche 'scholary' Umschrift 
für das ukrainische Alphabet:

```
А а	->	a
Б б	->	b
В в	->	v
Г г	->	h
Ґ ґ	->	g
Д д	->	d
Е е	->	e
Є є	->	je
Ж ж	->	ž
З з	->	z
И и	->	y
І і	->	i
Ї ї	->	ji
Й й	->	j
К к	->	k
Л л	->	l
М м	->	m
Н н	->	n
О о	->	o
П п	->	p
Р р	->	r
С с	->	s
Т т	->	t
У у	->	u
Ф ф	->	f
Х х	->	ch
Ц ц	->	c
Ч ч	->	č
Ш ш	->	š
Щ щ	->	šč
Ь ь	->	′
Ю ю	->	ju
Я я	->	ja
’	->	-
```

An dieser orientiere ich mich. Es gibt zwar auch eine 'deutsche'
Umschrift dort, die z.B. в als w statt v schreibt. Ich glaube aber,
dass die scholary-Variante für jeden, der sich auch mit slawischen
Sprachen mit lateinischer Schrift beschäftigt, eingänglicher ist.

In allen Fällen, in denen diese Umschrift einen Buchstaben nennt,
der auf der deutschen Tastatur verfügbar ist, ordne ich die
entsprechende Taste zu. In den anderen Fällen habe ich folgende
Zuordnung verwendet:

```
Є є	->	AltGr + e (AltGr + r rechts daneben für Großbuchstaben)
Ж ж	->	AltGr + g (AltGr + h rechts daneben für Großbuchstaben)
Ї ї	->	AltGr + i (AltGr + o rechts daneben für Großbuchstaben)
Х х	->	x ( klingt anders, sieht aber genauso aus)
Ч ч	->	AltGr + c (AltGr + v rechts daneben für Großbuchstaben)
Ш ш	->	w ( klingt anders, sieht aber ähnlich aus)
Щ щ	->	q ( liegt direkt neben w, dem ähnlichen ш) 
Ь ь	->	AltGr + b (AltGr + n rechts daneben für Großbuchstaben)
Ю ю	->	ü ( klingt anders, aber beides sind Varianten von u )
Я я	->	AltGr + a (AltGr + s rechts daneben für Großbuchstaben)
’	->	' ( wie schon auf der deutschen Tastatur vorhanden, Shift + #)
```
Den Buchstaben ж legen wir zusätzlich auf ö, was sonst keine Verwendung
hätte und der Belegung auf physikalischen ukrainischen Tastaturen
entspricht.

## Juristisches

Das Keyboard Layout is Open Source, entsprechend der sehr permissiven
[MIT License](LICENSE). Jeder ist eingeladen, es entsprechend zu
verwenden und weiterzugeben.

Die Symbolbilder aus diesem Readme stammen von
https://www.freeflagicons.com/ .

















