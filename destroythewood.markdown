---
layout: page
title:  "DestroyTheWood"
permalink: /destroythewood/
---
### Generelle Informationen

Die App ist eine native iOS App und ist mit Swift, UIKit und 2d SpriteKit in Xcode gebaut, die Graphiken habe ich nicht selber erstellt (bis auf die Graphik beim App start wo "Tony Borchert" steht, diese ist eine bearbeite Version von den Knöpfen). Bisauf die Graphiken (und Töne) habe ich alles selber gemacht [(Quellcode)](https://github.com/bit-burger/destroythewood/.


### Login

Der Login ist extrem einfach, es wird auf der Datenbank (FireBase) gesucht, ob es diesen Namen gibt, wenn nicht wird ein neuer Account erstellt und du wirst damit eingelogged. Die Datenbank, ist natürlich, überhaupt nicht sicher und sollte eigentlich nur dem Testen dienen.

![](/assets/destroythewood/gif/login.gif)


### Spielen

Hier haben wir eine Mischung von einem (2d) SpriteKit View und einem normalen ViewController die durch delegation komunizieren. Hier wird, wie in der restlichen App viel mit Haptic Feedback gearbeitet. 

![](/assets/destroythewood/gif/spielen.gif)


### Einstellungen

Man kann auch z.B.: das Haptic Feedback ausschalten, dies geht über die Einstellungen, die man nur aus dem Hauptmenü betreten kann. In den Einstellungen kann man auch die Touch distance finden, also wie weit die Holzklötzchen von den Fingern sind. Wenn man die Einstellung auf 0 stellt, liegt der Finger genau auf den Holzklötzchen.

![](/assets/destroythewood/gif/einstellungen.gif)


### Statistiken/Leaderboards

Hier kann man seine eigenen Statistiken sehen, und die der anderen, man kann alle Statistiken verschieden sortieren (nach Datum, nach besten Ergebnis...) und an und ausschalten, ob Scores mit dem Wert 0 angezeigt werden sollen.

![](/assets/destroythewood/gif/statistiken.gif)

In den Leaderboards, also unter Global, finden sich die besten Scores jeder Person, wenn diese Person auch bisher gespielt hat. Während man spielt updaten diese in Echtzeit.

![](/assets/destroythewood/gif/seite_an_seite.gif)


### Account Löschen

In den Einstellungen gibt es die Möglichkeit, entweder alles zu löschen oder alles bisauf seinen Rekord zu löschen.

![](assets/destroythewood/gif/alles_loeschen.gif)
