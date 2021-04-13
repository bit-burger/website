---
layout: page
title: "points"
permalink: /points/
---

Die points App, ist eine neumorphic crossplatform beispiel social media App, der Focus liegt hier auf dem Design. Die App wurde von mir in Android Studio geschrieben, mit der Flutter SDK sowie dem flutter_neumorphic package. Sie ist für die Platformen iOS und Android gedacht sollte aber (theoretisch) problemlos für web compilebar sein [(Quellcode)](https://github.com/bit-burger/points/). 

### Server/Datenbank: 

Der Server ist in Javascript mit Node.js in Visual Studio Code geschrieben worden. Es versucht so wenig Daten wie möglich zu senden, doch alle durchgehend zu updaten in Realtime. Es ist dazu in der Lage mehreren Geräten eingeloggt im gleichen Account, in realtime syncronisiert zu halten. Im großen im ganzen ist es jedoch ein Prototyp, besonders, wenn man auf die "Datenbank" schaut, welche eine einfache `.json` Datei darstellt. 

### Design:

Wie bereits erwähnt liegt der Fokus auf dem Design. Ich habe hierbei das flutter_neumorphic package genommen, da ich ein großer Fan von der Simplicität und Schönheit von Neumorphic Design bin. Die Farben sind fast identisch meiner ersten (halbwegs großen) Neumorphic App [SoundMeter](https://tonyborchert.xyz/soundmeter/). 

**Login:**

<img width="342" alt="login" src="/assets/points/gif/login.png">

**Homepage:**

<img width="392" alt="homepage" src="/assets/points/gif/homepage.png">

**Einstellungen:**

<img width="348" alt="einstellungen" src="/assets/points/gif/einstellungen.png">


<img width="348" alt="einstellungen" src="/assets/points/gif/profil.png">

### Demos:

**Realtime:**

![seite_an_seite](/assets/points/gif/seite_an_seite.gif)

**Swiping:**

![](/assets/points/gif/demo.gif)
