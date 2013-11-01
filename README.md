Quiz-plugin for DasBot.
=======================
Version 0.5

For use with DasBot:
https://github.com/subfusc/DasBot/
and questions formatted like questions in:
http://moxquizz.de/

This distribution contains the following files:
 INSTALL
 LICENSE
 README
 Makefile
 plugin.cfg
 __init__.py
 Question.py
 Quiz.py

Please check out news and info about the newest code in http://trondth.at.ifi.uio.no/quizbot

Description of INF3331-project (Norwegian):
===========================================

Programutvalget for Informatikk: språk og kommunikasjon har en IRC-bot
kjørende på noen IRC-kanaler, blant andre #isk og #iskbot på IRCNet.
Kjernen i botten er i stor grad skrevet av sindrewe, og
forskjellige folk har
bidratt med plugins. Se https://github.com/subfusc/DasBot for
informasjon.

Jeg ønsker å skrive en quiz-plugin til denne botten. Her er foreløpige
punkter:
- Løsning for hvilke kanaler hvor quiz-pluginen skal være aktiv
- Datastruktur for å samle spørsmål og svar - antagelig sqlite-db.
- Spørsmål kan kunne legges til ved å sende melding til botten
- Ban nick som adder tullespm - og slette alle spm fra brukeren
- Spørsmål skal kunne importeres fra en tekstfil
- Spørsmål skal kunne fjernes
- Spørsmål og svar skal kunne endres
- Rating av spm
- Man har runder, enten tidsbestemt - eller bestemt ut i fra antall
  spørsmål
- Etter hver runde kåres en vinner.
- Vinnere legges til i all-star-tabellen.
- Lagring av all-star-tabellen i sqlite-db
- Presentasjon av spørsmål må velges
- Løsning for å gi hint hvis ingen svarer rett (antall bokstaver,
forbokstav, evt spesiallagde hint)
- Vurdering av likhet med svaret - skal fx både cairo og kairo
  godkjennes som svar på spm om hovedstad i egypt?
- Statistikk - hvem svarer på spørsmål når.
- Personlig statistikk
- Moro - !steal og andre ting man kan skrive for å lage en morsom
  reaksjon fra botten

Antagelig vil jeg ikke rekke alt dette i løpet av fire
arbeidsdager, men en
grunnstruktur bør jeg ha på plass, altså - en fungerende quizbot, som
blir utvidet etter hvert.
