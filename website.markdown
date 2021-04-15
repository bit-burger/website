---
layout: page
title:  "Website"
permalink: /website/
---
Die Website selbst ist mit Jekyll gebaut. Jekyll ist eine Software, mit der man aus Markdown und ein wenig Konfiguration (in YAML) eine Website bauen kann. Ich habe sie ausgewählt, weil sie einfach zu benutzen ist und gut mit GitHub integriert ist. GitHub hostet den [Quellcode](https://github.com/bit-burger/website/) und die Website selber. Ich benutze das [Minima Theme](https://github.com/jekyll/minima/), es ist das default von Jekyll. Anstatt der Posts/Blogeinträge auf der Homepage (also [index.markdown](https://github.com/bit-burger/website/blob/gh-pages/index.markdown)) habe ich eine normale Page genommen, da ich keine Posts/Blogeinträge habe.

Die Website hat zusätzlich eine CNAME Datei, welche nur `tonyborchert.xyz` enthält. Sie sorgt dafür, dass die Website unter der Domain [tonyborchert.xyz](https://tonyborchert.xyz/) gefunden werden kann, gleichzeitig muss jedoch Namecheap (in diesem Fall der Verwalter der Domain), auf die IP-Adressen von GitHub zeigen.
