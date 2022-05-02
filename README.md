## Problemraum

Ausgangspunkt dieser Arbeit ist der technische Fortschritt in der Webentwicklung und die dadurch stetig wachsende Auswahl an Möglichkeiten, diverse Problemstellungen zu lösen. Die voranschreitende Technologie, mit ihren neuen Arten informationstechnische Probleme zu lösen und darauf zu reagieren, teilt heutzutage gute von schlechten Webauftritten. In dieser Arbeit werden, aus Sicht eines Entwicklers, eine traditionelle Herangehensweise mit 2 neuen Technologien verglichen.

## Motivation/Fragestellung

Die Techniken und Frameworks der Webentwicklung lassen sich im Groben in 3 sogenannte Stacks unterteilen: **MEAN** (MongoDB, ExpressJS[Framework], AngularJS, NodeJS), **LAMP** (Linux, Apache, MySQL, PHP) und **JAM** (Javascript, API, Markup). Jeder dieser Stacks hat durch diverse Frameworks verschiedene Ausprägungen.

Diese Arbeit soll daher die Entscheidung eines Entwickler(-teams) für oder gegen einen bestimmten Stack, durch die Gegenüberstellung diverser Kriterien, unterstützen.

## Methodiken

Die Güte der verschiedenen Entwicklungsarten werden über diverse Kennzahlen der ISO 25010 und Eckpfeiler einer SEO-Analyse dargestellt. Als Grundlage dient hier eine Webseite, die mit der jeweiligen Technik erstellt und künstlich mit Daten befüllt wurde. Teile der ISO 25010, wie die Maintainability sowie Performance Efficiency werden als Gütemaß herangezogen. Als SEO-Daten werden die vom Google Crawler genutzten Metriken wie Time to First Byte (TTFB), Largest Contentful Paint (LCP), Time to Interactive (TTI) und Bundle Size verwendet. Des Weiteren werden Scorings von seobility[sic!] und Google (Lighthouse), sowie deren genutzte Metriken, genutzt, um weiterhin die Qualität zu bewerten.

## Ziel der Arbeit

Ziel der Arbeit soll ein intelligentes Entscheidungssystem, in Form eines Entscheidungsbaumes, sein, um Entwickler bei der Findung der passenden Technologie zu unterstützen. Ferner sollen die „Grenzen“ der Stacks klar definiert werden und Vor- sowie Nachteile deutlich gemacht werden. Es soll weitere Hinweise auf Charakteristiken geben, wie z.B. die Schnelligkeit eines Stacks oder die Aktualität.  

## Outline (9 Wochen)

 - Recherche (**1 Woche**)
	- Literatur
	- Vorgehen

 - LAMP (**2 Wochen**; 1 Woche Entwicklung + 1Woche schreiben)
	- Aufbau
	- Content
	- Kriterien dokumentieren

 - MEAN (**2 Wochen**; 1 Woche Entwicklung + 1Woche schreiben)
	- Aufbau
	- Content
	- Kriterien dokumentieren

 - JAM (**2 Wochen**; 1 Woche Entwicklung + 1Woche schreiben)
	- Aufbau
	- Content
	- Kriterien dokumentieren

 - Analyse (**2 Wochen**) 
	 - Auswertung Kriterien
	-  Abwägungen der Entscheidungen 
   - Erstellung des Entscheidungsbaumes

Das Schreiben erfolgt parallel zur Entwicklung

  

## Literatur

Software Architecture in Practice, Second Edition, [https://people.ece.ubc.ca/matei/EECE417/BASS/ch04lev1sec3.html](https://people.ece.ubc.ca/matei/EECE417/BASS/ch04lev1sec3.html)

Site Reliability Engineering, [https://sre.google/sre-book/table-of-contents/](https://sre.google/sre-book/table-of-contents/)

A primer on Design Patterns, [https://leanpub.com/aprimerondesignpatterns](https://leanpub.com/aprimerondesignpatterns)

<Evolution of Web Systems Architectures: A Roadmap, [https://link.springer.com/chapter/10.1007/978-3-030-35102-1_1](https://link.springer.com/chapter/10.1007/978-3-030-35102-1_1)

<Is Node.js a viable option for building modern web applications? A performance evaluation study, [https://link.springer.com/article/10.1007/s00607-014-0394-9](https://link.springer.com/article/10.1007/s00607-014-0394-9)

Analysing the Performance of Mobile Cross-platform Development Approaches Using UI Interaction Scenarios, [https://link.springer.com/chapter/10.1007/978-3-030-52991-8_3](https://link.springer.com/chapter/10.1007/978-3-030-52991-8_3)

A Code Quality Metrics Model for React-Based Web Applications, [https://link.springer.com/chapter/10.1007/978-3-319-63315-2_19](https://link.springer.com/chapter/10.1007/978-3-319-63315-2_19)

Elevating React Web Development with Gatsby, [https://www.packtpub.com/product/elevating-react-web-development-with-gatsby/9781800209091](https://www.packtpub.com/product/elevating-react-web-development-with-gatsby/9781800209091)

Hands-on Nuxt.js Web Development, [https://www.packtpub.com/product/hands-on-nuxt-js-web-development/9781789952698](https://www.packtpub.com/product/hands-on-nuxt-js-web-development/9781789952698)

Phuoc Nguyen  
How JavaScript ecosystem and open-  
source tooling enable a modern era of  
Single-Page Applications, [https://www.theseus.fi/bitstream/handle/10024/495352/Phuoc_Nguyen.pdf?sequence=2&isAllowed=y](https://www.theseus.fi/bitstream/handle/10024/495352/Phuoc_Nguyen.pdf?sequence=2&isAllowed=y)

Webanwendungen erstellen mit Vue.js, [https://link.springer.com/book/10.1007/978-3-658-27170-1](https://link.springer.com/book/10.1007/978-3-658-27170-1)

Mobile Web Performance Optimization, [https://link.springer.com/chapter/10.1007/978-1-4842-6528-4_4](https://link.springer.com/chapter/10.1007/978-1-4842-6528-4_4)

[https://jamstack.wtf/](https://jamstack.wtf/)

Practical JAMstack, [https://link.springer.com/book/10.1007/978-1-4842-6177-4](https://link.springer.com/book/10.1007/978-1-4842-6177-4)

Modern Web Development with JAMsatck, [https://www.theseus.fi/bitstream/handle/10024/341469/Modern%20Web%20Development%20with%20JAMstack_Edit%20Orosz_Thesis.pdf?sequence=2&isAllowed=y](https://www.theseus.fi/bitstream/handle/10024/341469/Modern%20Web%20Development%20with%20JAMstack_Edit%20Orosz_Thesis.pdf?sequence=2&isAllowed=y)

The Majesty of Vue.js2, [https://liteonqa.liteon.com/app/storage/document/document/vuejs2-sample.pdf](https://liteonqa.liteon.com/app/storage/document/document/vuejs2-sample.pdf)
