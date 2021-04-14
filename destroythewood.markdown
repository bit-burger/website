---
layout: page
title:  "DestroyTheWood"
permalink: /destroythewood/
---

Die App ist eine native iOS App und ist in Swift, mit UIKit und 2d SpriteKit in Xcode programmiert. Die Graphiken habe ich nicht selber erstellt (bis auf die Graphik beim App start wo "Tony Borchert" steht, diese ist eine bearbeite Version von den Knöpfen). Bis auf die Graphiken (und Töne) habe ich alles selber gemacht [(Quellcode)](https://github.com/bit-burger/destroythewood/). Das Spielkonzept stammt aus der App Woody Block Puzzle (bzw. daher kenne ich es).


### Login

Der Login ist extrem einfach, es wird auf der Datenbank (Firebase) gesucht, ob es diesen Namen gibt, wenn nicht wird ein neuer Account erstellt und du wirst damit eingelogged. Die Datenbank ist natürlich überhaupt nicht sicher und sollte eigentlich nur dem Testen dienen.

![](/assets/destroythewood/gif/login.gif)


### Spielen

Hier haben wir eine Mischung von einem (2d) SpriteKit View und einem normalen ViewController, die durch Delegation kommunizieren. Hier wird wie in der restlichen App viel mit Haptic Feedback gearbeitet. 

![](/assets/destroythewood/gif/spielen.gif)


### Einstellungen

Man kann auch z.B. das Haptic Feedback ausschalten, dies geht über die Einstellungen, die man nur aus dem Hauptmenü betreten kann. In den Einstellungen kann man auch die "Touch distance" finden, also wie weit die Holzklötzchen von den Fingern entfernt sind. Wenn man die Einstellung auf 0 stellt, liegt der Finger genau auf den Holzklötzchen.

![](/assets/destroythewood/gif/einstellungen.gif)


### Statistiken/Leaderboards

Hier kann man seine eigenen Statistiken sehen, und die der anderen, man kann alle Statistiken verschieden sortieren (nach Datum, nach bestem Ergebnis...) und an und ausschalten, ob Scores mit dem Wert 0 angezeigt werden sollen oder nicht.

![](/assets/destroythewood/gif/statistiken.gif)

In den Leaderboards, also unter "global", finden sich die besten Scores jeder Person, wenn diese Person bereits gespielt hat. Während man spielt, updaten diese in Echtzeit.

![](/assets/destroythewood/gif/seite_an_seite.gif)


### Account Löschen

In den Einstellungen gibt es die Möglichkeit, entweder alles zu löschen oder alles bis auf seinen Rekord zu löschen.

![](assets/destroythewood/gif/alles_loeschen.gif)
