Business Data Analytics - Exposé

Team:
    Simon Engelhardt, siengelh@stud.hs-heilbronn.de
    Nils Gammel, ngammel@stud.hs-heilbronn.de
    Hannes Gruber, hgruber@stud.hs-heilbronn.de
    Mikael Topsakal, mtopsakal@stud.hs-heilbronn.de 


Fragestellung:
NBA-Teams mit einem höheren Anteil an internationalen Spielern erzielen bessere Ergebnisse
in der Liga.

Erläuterung:
Das Ziel dieser Analyse ist es, zu messen, wie stark der Erfolg von NBA-Teams durch den Anteil und die Qualität importierter Spieler beeinflusst wird. 
Insbesondere soll untersucht werden:
    > Ob Teams mit einem höheren Anteil internationaler Spieler erfolgreicher sind (z. B. in Bezug auf Siegquote, Playoff-Erfolg)
    > Ob bestimmte Leistungskennzahlen internationaler Spieler (z.B. Punkte, Effizienz, Win Shares) in stärkerem Maße zum Teamerfolg beitragen.
    > Wie sich die Rolle internationaler Spieler im Laufe der Zeit entwickelt hat.


Ansatz:
In diesem Projekt soll der Zusammenhang zwischen der Anzahl und der Leistung von internationalen Spielern (Imports) und der Teamperformance in der NBA untersucht werden.

Vorgehensweise:
1. Datenbeschaffung und -vorbereitung:
    > Verwendung der Datensätze von Kaggle.
    > Analyse der Daten ab dem Jahr 1980 bis zum Jahr 2022.

2. Datenaufbereitung und -klassifikation: 
    > Spieler werden auf Basis ihrer Nationalität in zwei Kategorien unterteilt: International (Rest der Welt) und National (USA).
    > Berechnung des Anteils internationaler Spieler pro Team pro Saison. 

3. Leistungskennzahlen:
    > Leistungkennzahlen Spieler: Punkte pro Spiel, Effizienz, Win-Shares und Spielerbeiträge zur Gesamtleistung.
    > Leistungkennzahlen: Teams: Sieg-Quote, Playoff-Erfolg, Punkte pro Spiel, Anteil internationaler Spieler

4. Datenanalyse:
    > Vergleich der Teamleistung: Einteilung der Teams in Gruppen mit hohem vs. niedrigem Anteil internationaler Spieler. Anschließender Vergleich ihrer Leistungskennzahlen
    > Korrelationsanalyse: Analyse, wie stark die Anzahl internationaler Spieler mit der Teamperformance korreliert und ob bestimmte Leistungskennzahlen internationaler Spieler (Punkte pro Spiel, Effizienz) besonders stark mit dem Teamerfolg zusammenhängen.

5. Zeitanalyse: 
    > Zeitreihenanalyse, inwiefern sich der Einfluss internationaler Spieler auf den Erfolg von Teams über die Jahre verändert hat.
    > Spielerpositionsanalyse: Performanceuntersuchung nationaler und internationaler Spieler auf ihrer jeweiligen Position (Center, Guard, …).

6. Ergebnisse und Schlussfolgerungen:
    > Auf Basis der Analyse wird untersucht, ob ein signifikanter Zusammenhang zwischen dem Anteil internationaler Spieler und der Teamleistung besteht.



Datenquellen:
> NBA Games
https://www.kaggle.com/datasets/nathanlauga/nba-games?select=games_details.csv 
zuletzt abgerufen am: 15.11.2024

> NBA Player Data
https://www.kaggle.com/datasets/justinas/nba-players-data zuletzt abgerufen am: 
15.11.2024