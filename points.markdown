---
layout: page
title: "points"
permalink: /points/
---

Die points App, ist ein Beispiel für eine neumorphic crossplatform social media App, der Focus liegt hier auf dem Design. Die App wurde von mir in Android Studio geschrieben, mit der Flutter SDK sowie dem flutter_neumorphic package. Sie ist für die Platformen iOS und Android gedacht, sollte aber (theoretisch) problemlos für web kompilierbar sein [(Quellcode)](https://github.com/bit-burger/points/). 

### Server/Datenbank: 

Der Server ist in Javascript mit Node.js in Visual Studio Code geschrieben worden. Er versucht so wenig Daten wie möglich zu senden, doch alle durchgehend in Realtime zu updaten. Er ist sogar dazu in der Lage, mehrere Geräten, die im gleichen Account eingeloggt sind, in Realtime syncronisiert zu halten. Im Großen und Ganzen ist es jedoch ein Prototyp, besonders, wenn man auf die "Datenbank" schaut, welche eine einfache `.json` Datei darstellt. 

### Design:

Wie bereits erwähnt liegt der Fokus auf dem Design. Ich habe hierzu das flutter_neumorphic package genommen, da ich ein großer Fan von der Simplizität und Schönheit von Neumorphic Design bin. Die Farben sind fast identisch mit meiner ersten (halbwegs großen) Neumorphic App [SoundMeter](https://tonyborchert.xyz/soundmeter/). 

**Login:**

<img width="342" alt="login" src="/assets/points/png/login.png">

**Homepage:**

<img width="392" alt="homepage" src="/assets/points/png/homepage.png">

**Einstellungen:**

<img width="348" alt="einstellungen" src="/assets/points/png/einstellungen.png">


<img width="348" alt="einstellungen" src="/assets/points/png/profil.png">

### Demos:

**Realtime:**

![seite_an_seite](/assets/points/gif/seite_an_seite.gif)

**Swiping:**

![](/assets/points/gif/demo.gif)
