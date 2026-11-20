# Jagged Amber Tactics · Komplettlösung Akt I

> **Westmark: vom Konvoi bis zur Herzkammer.** Ein Leitfaden für einen gründlichen Durchlauf, in dem man alles einmal gesehen hat: jede Quest, jeden Gefährten, jeden Nebenschauplatz und die versteckten Funde.
>
> **Stand:** 20.11.2026, gilt für v0.7.0-alpha (ausgebaute Herzsenke, Zauber ohne Wirkzeit, stärkere Höhepunkte). Wie es nach der Krankenstation weitergeht, steht in der [Komplettlösung Akt II](Komplettloesung-Akt2.md).
> **⚠️ Vollständige Spoiler.** Wer Akt I unbelastet erleben will, liest nur die Übersicht und die Routentabelle.

---

## Inhalt

1. [So liest du diesen Leitfaden](#so-liest-du-diesen-leitfaden)
2. [Grundlagen: Stufen, EP, Unruhe, Gespräche](#grundlagen)
3. [Die Hauptgeschichte in einem Absatz](#die-hauptgeschichte-in-einem-absatz)
4. [Empfohlene Route mit Zielstufen](#empfohlene-route-mit-zielstufen)
5. [Alle Gefährten auf einen Blick](#alle-gefährten-auf-einen-blick), dazu [Freunde und Rivalen](#freunde-und-rivalen)
6. Kapitel 1 · [Westmark-Start und Mühlbrück](#kapitel-1--westmark-start-und-mühlbrück)
7. Kapitel 2 · [Dreifurt und Umgebung](#kapitel-2--dreifurt-und-umgebung)
8. Kapitel 3 · [Tannried, Werkhof und Tannwald](#kapitel-3--tannried-werkhof-und-tannwald)
9. Kapitel 4 · [Karrfels und Graufelspfad](#kapitel-4--karrfels-und-graufelspfad)
10. Kapitel 5 · [Brackhafen und Glockenwacht](#kapitel-5--brackhafen-und-glockenwacht)
11. Kapitel 6 · [Lichtenruh und Glasgrund](#kapitel-6--lichtenruh-und-glasgrund)
12. Kapitel 7 · [Die Wege zwischen den Orten](#kapitel-7--die-wege-zwischen-den-orten)
13. Kapitel 8 · [Das Finale](#kapitel-8--das-finale)
14. [Abhakliste](#abhakliste)

---

## So liest du diesen Leitfaden

Jeder Eintrag trägt ein Kennzeichen:

| Kennzeichen | Bedeutung |
| --- | --- |
| 🔴 **PFLICHT** | Gehört zum kürzesten Weg der Hauptgeschichte. Ohne sie endet Akt I nicht. |
| 🟣 **HAUPTGESCHICHTE** | Erzählt die Hauptgeschichte weiter oder weist den Weg, ist aber nicht zwingend nötig (z. B. Orwin und die Hüter, die Sabotage in Lichtenruh). |
| 🟢 **OPTIONAL** | Nebenquest oder Nebenschauplatz mit eigener Geschichte, eigenen Kämpfen und Belohnung. |
| 🔵 **GEFÄHRTE** | Ein Gefährte, den man anwerben kann. |
| 🟡 **ENTDECKUNG** | Kleine Szene, Fund oder Ortsgeschehen ohne Auftraggeber. Leicht zu übersehen. |
| 🧭 **WEGWEISER** | Wer einen wohin schickt. |
| 🛠️ **NUR TESTER-BUILDS** | Hilfe aus dem Entwicklermenü, im fertigen Spiel nicht vorhanden. |

Jeder Eintrag folgt dem gleichen Schema:

- **Auslöser:** wie es anfängt.
- **Stufe:** empfohlene Gruppenstufe und die Gegner.
- **Lösungsweg:** die Schritte der Reihe nach.
- **Wahlen und Enden:** die Abzweigungen.
- **Belohnung:** was man dafür bekommt.
- **Zum Testen:** was man sich bewusst ansehen sollte.

**Koordinaten:** „Weltkarte (x, y)“ meint die große Karte der Westmark, „(x, y)“ allein die Ortskarte, in der man gerade steht. Die Automap zeigt beide.

**Gesprächswörter** stehen **fett**: Man fragt eine Figur im Gespräch nach diesem Wort. Wörter lernt man im Spiel, von anderen Figuren oder an Fundstellen. Fehlt ein Wort, nennt der Eintrag, wer es beibringt.

**Gruppenstufe** heißt im Leitfaden die Stufe der Gefährten, die man gerade dabeihat. Die Angaben „gemessen zu viert auf Stufe 8“ stammen aus den automatischen Balance-Tests des Spiels: Mit dieser Gruppe auf dieser Stufe ist der Kampf gut zu gewinnen. Mit dem Spiel selbst geprüft sind sie noch nicht. Rückmeldungen dazu sind ausdrücklich erwünscht.

---

## Grundlagen

### Stufen und Erfahrung

| Stufe | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 20 |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| EP ab | 100 | 300 | 600 | 1000 | 1500 | 2100 | 2800 | 3600 | 4500 | 5500 | 6600 | 7800 | 9100 | 10 500 | 12 000 | 13 600 | 19 000 |

- Die Tabelle gilt für Figuren mit Klasse. Brydan beginnt **klassenlos** und braucht bis dahin 20 % mehr EP je Stufe. Die erste Klasse lernt er in einer Gilde in Dreifurt, zum halben Preis.
- **Quest-EP** bekommt **jedes** Gruppenmitglied voll. **Kampf-EP** werden auf die stehende Gruppe **geteilt**: Zu sechst steigt jeder langsamer.
- Die Höchststufe ist 30 (seit M71). In Akt I spielt das keine Rolle: Eine Gruppe endet den Akt mit Stufe 15 bis 17, nur ein Held, der alles allein erledigt, kommt über 20 hinaus.
- Gefährten treten mit einer festen Stufe bei, spätere Gefährten mit der Stufe ihres Ortes (siehe Gefährtentabelle).
- **Lebenspunkte der Gegner:** Die LP-Angaben im Leitfaden sind Grundwerte. Im Spiel steigen LP, Waffen- und Zauberkraft mit dem Ausrüstungsrang des Gebiets (Rang 1 etwa +15 % LP, Rang 5 etwa +65 %). Einige Höhepunkte halten seit v0.7.0 deutlich mehr aus, etwa das Doppelte ihres Grundwerts: Nachhall in der Gruft, Dornwuchs, Archivwächter, Flimmervögel, Höhlenkrabben, Läufer der Furche, Wächter des Herzrings und der Fremde in der Herzkammer.

### Unruhe: die Welt reagiert auf die Relikte

Die Westmark wird mit jedem gewonnenen **Relikt** (Fassung, Abschrift, Antwort) unruhiger.

| Unruhe | wann | was sich ändert |
| --- | --- | --- |
| 0 | kein Relikt | Grundzustand |
| 1 | ein Relikt | Wirte reden auf **Reisewege** von der Schranke am Moosfels, erste Gruppen auf den Wegen |
| 2 | zwei Relikte | Orks auf der Nordroute, Brand am **Brandhof**. In Lichtenruh ist die **Schutzleitung zerschnitten**: Ein Flimmerband sperrt den Weg zur Quelle, Durchgehen kostet Lebenspunkte. |
| 3 | drei Relikte | **Riss am Südweg** (Lichtenruh–Glasgrund), Meret schlägt den **Versuch im Kleinen** vor |

Keine Folge der Unruhe nimmt einen Ort, einen Händler, eine Aufgabe oder einen Gefährten weg. Gefahren werden immer angekündigt (Spuren, Gerüchte, sichtbare Gegner). Wer die Wege-Quests (Kapitel 7) in ihrer vollen Form erleben will, geht sie **nach dem zweiten Relikt**.

### Tag und Nacht

Viele Figuren haben Tageszeiten. In Brackhafen gilt das besonders: Bei Tag stehen Menschen draußen, nachts das Katzenvolk, in der Dämmerung beide. Wer nachts jemanden nicht findet, rastet bis zum Morgen. Einige Kämpfe sind nachts deutlich leichter oder schwerer (Leitfeuerbank, Handelsstein); der Leitfaden sagt es jeweils.

### Sprachen

Manche Gefährten sprechen keine Gemeinsprache. Ohne Übersetzer in der Gruppe kommt nur ein fremder Satz:

- **Jaro** (Elfisch, Gnomisch): Tavion, Venya oder Sylis mitnehmen.
- **Haldaar** (Zwergisch, Hünisch): Beric oder Odrik mitnehmen.
- **Z'zarek** (Drakonisch, Orkisch): Korgar, Varka oder Odrik mitnehmen.

---

## Die Hauptgeschichte in einem Absatz

Nach dem Überfall auf Rabans Konvoi landet Brydan in Mühlbrück. Die Goblins haben nichts geraubt, und an Orten, an denen es nie jemand gesehen hat, zittert die Luft: das **Flimmern**. Taro schickt nach dem Wasserstollen mit dem Bericht zu **Meister Orwin** in die Magiergilde von Dreifurt. Orwin kennt das Flimmern nicht und bittet um eine zweite Sichtung (etwa am alten Harzweg bei Tannried). Danach findet er in einer alten Abschrift die **Hüter**, einen Orden, der an drei Orten wachte. Jeder dieser Orte hält ein Stück einer uralten Anlage:

- die **Fassung** in der kalten Schmelzhalle von **Karrfels** (Q08, der Hammer im Berg),
- die **Abschrift** vom schwarzen Altar im **Moorarchiv** bei Brackhafen (Q06, das Haus mit Fächern),
- die **Antwort** an der Quelle von **Lichtenruh** (Q10, die Quelle, die antwortet).

Die Reihenfolge ist frei, und jeder Ort verweist auf die beiden anderen. An **jedem** der drei Relikte ertappt Brydan einen **Fremden**, der es zerstören will (Q15a, Q15b, Q15c, seit Ä45). Beim ersten Mal ist er ein Unbekannter, beim zweiten erkennt Brydan ihn wieder, beim dritten weiß er, dass es seine letzte Gelegenheit vor der Herzsenke ist. Das Wort **Herz** fällt ab dem ersten Relikt, erklärt wird es erst später. Nach dem zweiten Relikt zerschneidet der Fremde die Schutzleitung von Lichtenruh (F01). Mit allen drei Relikten führt Priorin Meret den **Versuch im Kleinen** durch (Q16): Am Knoten erlischt das Flimmern für einen Atemzug, Meret erklärt, dass alle Leitungen der Hüter im Herz in der Senke im Osten zusammenlaufen, und ihre Karte legt den verschütteten Abstieg dorthin frei. Meret lädt alle Gefährten an die Rast der drei Steine (O12). Dann folgt der Abstieg in die **Herzsenke**: äußerer Ring, die Herzanlage mit drei Flügeln und dem Torwächter, gebrochene Galerie, inneres Tor, Herzkammer, Kampf gegen den Fremden. Danach geht es in die Übergangsprobe (Abschnitt C).

Die Aufgabe **„Das Flimmern“** im Journal führt durch den ganzen Hauptstrang und nennt immer das nächste Ziel, mit Notizen zu jeder Sichtung und zu jedem offenen und geborgenen Relikt.

**Kürzester Pflichtweg:** Konvoi → die drei Relikte in beliebiger Reihenfolge → Versuch im Kleinen bei Meret (Q16) → Herzsenke. Orwin ist kein Muss: Wer ohne ihn an einen Reliktort kommt, spielt die Quest dort trotzdem, und „Das Flimmern“ beginnt mit dem ersten Relikt. Allein gespielt kommt der Held damit auf Stufe 9 vor der Herzsenke, das ist knapp. Alles andere ist freiwillig, lohnt sich aber.

> 💡 **Tipp für Tester:** Q15 (der Fremde) kommt an allen drei Relikten, jede Ortsfassung immer. Die Reden hängen aber an der Reihenfolge: Die erste Begegnung spricht die Fassung ihres Ortes (Risszeichnungen), die zweite und dritte die gesteigerten Texte. Wer die erste Fassung eines anderen Ortes sehen will, **speichert vor dem ersten Relikt** und nimmt von dort ein anderes zuerst.

---

## Empfohlene Route mit Zielstufen

Gründlicher Weg zu viert (Held und drei Gefährten), alles mitgenommen außer den freien Gruppen auf der Weltkarte. Die Spalte „Stufe“ nennt die Stufe beim **Betreten** des Abschnitts, links ohne, rechts mit den freien Gruppen der Weltkarte (Wolfsrudel, Streifen, Lager). Die Werte sind gerechnet, nicht gespielt (Werkzeug `tools/ep_survey.py`).

| # | Abschnitt | Stufe beim Betreten | Hauptinhalt | Pflicht darin |
| ---: | --- | --- | --- | --- |
| 1 | Mühlbrück und Startdreieck | 1 | Konvoi, Korgar und Tavion, Wasserstollen, Bienenhaus, Nacht im Korn, Seewachturm, Weiße Flecken | Konvoi |
| 2 | Dreifurt | 2 bis 3 | Gilde und Klasse, Orwin und die Hüter, Namar, Werkzeuglieferung, Zollhaus, Berthold (Wachhof, Weidenkehre, Karrweg), Nordzeile, vierte Furt, Orkhöhle mit Odrik | – |
| 3 | Tannried und Tannwald | 3 bis 5 | Sägewerk, Grenze der Axt, Holzbruch, Waldlager, Kohlenfuhre, Fallenstellerin, das leere Nest | – |
| 4 | Karrfels und Graufelspfad | 7 bis 8 | Varka, Beric, die kalte Esse, Seilklamm, Handelsstein mit Haldaar, die letzte Schicht, Schlackenring | **Fassung (Q08)** |
| 5 | Brackhafen und Glockenwacht | 10 bis 11 | Salzwaage, Leitfeuerbank, Moorarchiv, Jaro, Glockenwacht mit Rhiann, Flut und Strandrecht | **Abschrift (Q06)** |
| 6a | Lichtenruh | 12 bis 13 | Quelle, Gruft mit Venya, Pilgerweg, Garten, Briefe (zweite Hälfte) | **Antwort (Q10)** |
| 6b | Glasgrund | 13 bis 14 | leuchtende Furche, Dornwacht, Steinbruch mit Z'zarek, Tibbes Gänge mit Sylis | – |
| 7 | Wege zwischen den Orten | 14 bis 15 | Moosfels, Deich und Glockengarten, Hünenlager, Lehmhang, Brandhof, freie Begegnungen | – |
| 8 | Finale | 15 bis 17 | zerschnittene Leitung, Versuch im Kleinen, Rast der drei Steine, Riss am Südweg, Herzsenke | **Versuch (Q16), Ring, Herzanlage, Galerie, Herzkammer** |
| | nach dem Fremden | 16 bis 17 | Übergangsprobe C | |

**Faustregeln:**

- **Ziel für Akt I** bei vollständiger Erledigung: Stufe 14 bis 15. Der gründliche Weg landet eher bei 15 bis 17.
- **Zu sechst** liegt man etwa eine Stufe tiefer, weil sich die Kampf-EP auf mehr Köpfe verteilen. Späte Kämpfe bringen zu fünft und zu sechst je einen Gegner mehr.
- **Zu früh dran?** Liegst du mehr als zwei Stufen unter der Spalte, hol zuerst Nebenquests in der Nähe nach. Die Wolfsrudel und Goblintrupps auf der Weltkarte sind schnelle EP.
- **Reihenfolge:** Die Relikte sind frei wählbar. Diese Route nimmt die Reihenfolge Karrfels → Brackhafen → Lichtenruh, weil die Gegner in dieser Folge stärker werden. In Lichtenruh steht man damit schon mit Unruhe 2 vor dem Flimmerband (Kapitel 8, F01).

---

## Alle Gefährten auf einen Blick

Höchstens sechs in der aktiven Gruppe. Überzählige warten in jedem Gasthaus („Gefährten verwalten“). Anheuern im Gespräch über **Anheuern**. **Jemand in der Gruppe muss eine Sprache der Figur sprechen** (Brydan spricht nur Gemeinsprache). Die Stufen in **fett** sind Ortsstufen: Diese Gefährten werden beim Beitritt auf die Stufe ihres Ortes angehoben.

| Figur | Volk, Klasse | Ort, Zelle | Bedingung | Beitrittsstufe | Sprachen | EP beim Beitritt |
| --- | --- | --- | --- | --- | --- | --- |
| Korgar | Ork, Kämpfer | Mühlbrück, Gasthaus Zur Bachbrücke (4, 6) | nach der Auszahlung des Konvois | 3 | Orkisch, Gemeinsprache | – |
| Tavion | Elf, Schütze (Begabung Schütze, Grau) | Mühlbrück (30, 4) | nach der Auszahlung des Konvois | 3 | Elfisch, Gemeinsprache | – |
| Namar | Katzenvolk, Dieb (Begabung Schütze, Dieb) | Dreifurt, an der Hofmauer (30, 35) | keine | 3 | Katzenzunge, Gemeinsprache | – |
| Odrik | Zwerg, Weißmagier | Orkhöhle im Granitmassiv nördlich von Dreifurt (Höhlenmaul Weltkarte 225, 98), im Käfig | Käfig öffnen (Schlüssel oder Knacken 50); bei voller Gruppe wartet er im Gasthaus; zieht sich im ersten Gasthaus um (Schuppengewand, Heilerkolben) | 5 | Zwergisch, Gemeinsprache, Orkisch | – |
| Varka | Orkin, Graumagierin | Karrfels, Lager im Vorland vor dem Südtor (23, 47) | keine | 6 | Orkisch, Gemeinsprache | 30 |
| Beric | Zwerg, Kämpfer | Karrfels, Werkterrasse vor dem Hallentor der Schmelzhalle (13, 14), Tag und Nacht | keine (auch vor Q08) | **7** | Zwergisch, Gemeinsprache | 30 |
| Haldaar | Hüne, Weißmagier (Begabung Kämpfer, Weiß, Grau) | Weltkarte (352, 144), Felsblock am Handelsstein (Graufelspfad), ansprechbar von (353, 144) oder (352, 145) | keine; spricht nur Hünisch und Zwergisch, also Beric oder Odrik mitnehmen | **7** | Hünisch, Zwergisch | 30 |
| Jaro | Gnom, Graumagier (Begabung Dieb, Grau) | Brackhafen, am Ufer vor dem östlichen Pegelpfahl (31, 29), Tag und Nacht | erst nach der Frage **Pegel** (Wort von **Name**); spricht nur Elfisch und Gnomisch, also Tavion, Venya oder Sylis mitnehmen | **8** | Gnomisch, Elfisch | 30 |
| Rhiann | Mensch, Schützin | Brackhafen, Glockenwacht (9, 11) | Q13 abgeschlossen | 8 | Gemeinsprache | 30 |
| Venya | Elfin, Schwarzmagierin (Begabung Grau, Schwarz) | Lichtenruh, Hospiz (3, 6) | Q28 abgeschlossen | 9 | Elfisch, Gemeinsprache | 30 |
| Sylis | Gnomin, Diebin (Begabung Dieb, Schütze) | Glasgrund, Weiler am Schlüsselbrett (30, 13), außer nachts | Q29 abgeschlossen | 10 | Gnomisch, Gemeinsprache | 30 |
| Z'zarek | Drachenblütiger, Schwarzmagier (Begabung Kämpfer, Schwarz) | Steinbruch östlich von Glasgrund, vor der Messhütte (388, 290) | keine; spricht nur Drakonisch und Orkisch, also Korgar, Varka oder Odrik mitnehmen | **10** | Drakonisch, Orkisch | 30 |

Nicht anwerbbar (nur Verbündete im Kampf): Ulf (Q19 Dreifurt, steht danach im Wachhof), Ruumar (W03, Sommerlager der Hünen).

Die Gefährten kommentieren Orte, Funde und Entscheidungen unterwegs. An der Rast der drei Steine (Kapitel 8) hat jeder angeworbene Gefährte eigene Zeilen. Es lohnt sich, die Gruppe öfter zu wechseln.

### Freunde und Rivalen

Die Gefährten mögen einander oder eben nicht. Das hat Folgen im Kampf und am Lagerfeuer, und wer nicht aufpasst, verliert zwei Gefährten für immer füreinander.

**Woran man es sieht:**

- **Charakterbogen** (Rechtsklick aufs Portrait): Die anderen Portraits der Gruppenleiste zeigen oben links, wie sie zur gezeigten Figur stehen. Verschränkte Hände heißt Freund, gekreuzte Klingen Rivale, eine Gewitterwolke „Streit droht“, ein zerbrochener Ring Erzfeind. Mit der Maus über einem Portrait nennt der Hinweis alle Beziehungen in der Gruppe, im Bogen selbst stehen sie mit Zahl.
- **Beim Anheuern** (Gespräch mit jemandem, der mitkommen würde) tragen die Portraits ihr Symbol zur neuen Figur, und die Fußzeile nennt, wen sie mag oder nicht leiden kann.
- **Im Gasthausmenü** zeigen die Portraits die Symbole zur Figur unter der Maus, praktisch beim Verabschieden und Abholen.
- **Gewitterwolke unten links** am Portrait, auch im Hauptbildschirm und im Kampf: Diese Figur steht mit jemandem in der Gruppe kurz vor dem Bruch (die letzten Warnungen). Der Hinweis darauf nennt, mit wem. Sonst bleiben die Portraits im Hauptbildschirm, im Kampf, beim Händler und im Inventar frei von Beziehungssymbolen.

**Was sie bewirken:**

| | Wirkung |
| --- | --- |
| Freund daneben | Steht ein Freund im Kampf auf einem der acht Nachbarfelder, trifft man um 10 Punkte besser. |
| Freund fällt | Fällt ein Freund (bewusstlos oder tot), packt die Figur zu Beginn ihres nächsten Zugs der **Zorn**: +1 AP und +10 Treffer bis Kampfende. |
| Rivale | Im Kampf kein Nachteil. Aber Rivalen **streiten beim Rasten** (auch im Gasthaus), wenn sie seit der letzten Rast nichts Gutes zusammen erlebt haben. Jeder Streit verschlechtert die Beziehung um 5. |
| Streit droht | Zwei Warnungen: Unter −60 „Die Stimmung kippt“, unter −70 „Letzte Warnung“. Nach dem Streit fragt das Spiel, ob man **schlichten** will (Charisma-Probe gegen 50, der Charismastärkste versucht es, der Zweitbeste hilft). Gelingt sie, steigt die Beziehung um 15. |
| Erzfeind | Fällt die Beziehung unter −80, ist es aus, **endgültig**. Der zuletzt Beigetretene geht ins Gasthaus, und die beiden reisen nie wieder zusammen. Jeder für sich bleibt voll spielbar. |

**Was hilft (ein „Lichtblick“ bis zur nächsten Rast):**

- **Gemeinsam siegen.** Jeder gewonnene Kampf, in dem beide dabei waren, verhindert den nächsten Streit und hebt Rivalen um 3, höchstens bis 0 (Respekt, keine Freundschaft).
- **Retten.** Wer einen Blutenden versorgt oder einen Gefallenen mit Zauber oder Trank zurückholt, gewinnt bei ihm 8 Punkte. Das kann aus Rivalen Freunde machen.
- **Entscheidungen** in manchen Quests, die beide gutheißen (siehe unten).
- **Schlichten** in einer Warnstufe.
- **Trennen.** Wartet einer der beiden im Gasthaus, streiten sie nicht. Das ist der sichere Weg, wenn man die beiden gerade nicht braucht.

**Faustregel:** Rivalen, die zusammen kämpfen, streiten nicht. Gefährlich wird es nur, wenn man mit beiden lange herumreist und rastet, ohne zu kämpfen, etwa auf Gesprächsrunden durch die Städte. Ein Rivalenpaar mit −40 braucht neun Rasten ohne Lichtblick bis zum Bruch, die erste Warnung kommt nach vier.

**Das Netz zu Beginn.** Niemand beginnt als Erzfeind. Jede Grundklasse bleibt für jeden Gefährten erreichbar, auch wenn alle Rivalitäten brechen. Rivalitäten sperren nie ein Anheuern.

| Paar | Start | Kennen sich | Warum |
| --- | --- | --- | --- |
| Beric und Z'zarek | −45 Rivalen | nein | Alte Fehde zwischen Zwergen und Drachenblut. Sie haben keine gemeinsame Sprache, ihr Streit läuft ohne Worte. |
| Odrik und Korgar | −40 Rivalen | nein | Odrik saß Monate im Käfig der Hauer und traut keinem Ork. |
| Odrik und Varka | −35 Rivalen | nein | Für Odrik ist ein Ork ein Ork, und das nimmt Varka ihm übel. |
| Rhiann und Namar | −40 Rivalen | ja | Rhiann gibt Namar die Schuld, dass Kesh und Jirr mit dem alten Boot hinausfuhren. |
| Sylis und Jaro | −40 Rivalen | ja | Jaro stammt aus dem Gnomenweiler und hat einen Schlüssel vom Brett genommen, ohne zu fragen. |
| Beric und Haldaar | +60 Freunde | ja | Vom Handelsstein. |
| Korgar und Tavion | +45 | ja | Zusammen Konvoischutz. Fast Freunde: Eine Rettung oder Entscheidung macht sie dazu. |
| Beric und Odrik | +35 | nein | Zwei Zwerge in der Fremde. |
| Rhiann und Odrik | +40 | nein | Retter erkennen einander. |
| Z'zarek und Korgar | +40 | nein | Z'zarek wuchs bei Orks auf. |
| Z'zarek und Varka | +35 | nein | Beide lesen das Feuer. |
| Venya und Jaro | +40 | nein | Venya zählt, Jaro schreibt ab. |
| Namar und Tavion | +30 | nein | Zwei Nachtaugen. |
| Sylis und Venya | +30 | nein | Beide arbeiten mit Sorgfalt. |
| Beric und Jaro | −15 | nein | Sticheleien ums Gold, ohne Wirkung. |
| Korgar und Haldaar | −10 | nein | Korgar mag keinen, der größer ist, ohne Wirkung. |
| Beric und Venya | −20 | nein | Schwarzmagie ist Beric nicht geheuer, ohne Wirkung. |

Wenn sich zwei zum ersten Mal in der Gruppe treffen, erzählt eine kurze Szene, was zwischen ihnen steht. Bei Paaren, die sich kennen, kommt die Vorgeschichte heraus.

**Entscheidungen, die Rivalen versöhnen:**

- **Orkhöhle:** Lässt man Murrk gehen und hat Korgar dabei, merkt Odrik sich das beim Beitritt (+5 zu Korgar).
- **V05 Bootsschuld:** Bezahlt man Ashka das Boot mit Rhiann in der Gruppe, +15 zwischen Rhiann und Namar.
- **E09 Kesh retten:** Mit Rhiann und Namar in der Gruppe +15 zwischen den beiden.
- **Q29 Das letzte Schloss:** Mit Jaro und Sylis in der Gruppe +10, das reicht für die Versöhnung.

**Tipps:**

- Korgar und Tavion früh zusammen kämpfen lassen: Die erste Rettung im Kampf macht sie zu Freunden, und der Trefferbonus hilft im ganzen Startdreieck.
- Beric und Haldaar sind von Anfang an Freunde. Nebeneinander als Frontlinie aufgestellt, treffen beide besser.
- Odrik ist der einzige mit zwei Rivalen (Korgar und Varka). Wer mit zwei Orks reist, lässt Odrik lieber im Gasthaus oder kämpft viel.
- Brackhafen ist der Ort, an dem Rhiann und Namar sich aussöhnen können: erst V05, dann E09.


---

## Kapitel 1 · Westmark-Start und Mühlbrück

**Anreise:** Das Spiel beginnt hier. „Neues Spiel“ im Titelmenü fragt den Namen des Helden (tippen, Rücktaste, Enter beginnt, Esc zurück; leer bleibt er **Brydan**). Start um 09:00 auf der Landstraße vor Mühlbrück (eigene Karte), allein mit 5 Gold, 2 Rationen, Kurzschwert rechts, Fackel links, im Rucksack Schleuder, 2 Heiltränke, 1 Fackel, keine Zauber, Gesprächswörter **Name** und **Arbeit**. Nach dem Konvoi steht man auf dem Mühlenhof von Mühlbrück. Von der Weltkarte aus führen vier Zugänge ins Dorf: West Weltkarte (146, 200), Ost (158, 200), Nord (150, 195), Süd (149, 205); dazu die beiden Bachzellen am Nord- und Südrand (152, 195) und (152, 205) ins Bachbett. Aus den Dorfausgängen kommt man eine Zelle vor dem Zugang heraus.
**Wann:** Spielbeginn, Stufe 1. Mühlbrück bleibt das ganze Spiel über Heimat und Rastort. Q23 und Q24 öffnen sich erst nach der Wasserfrage (Q01).
**Dienste:** Gasthaus (Tür im Westteil des Dorfs, Ortskarte (8, 15)), Wirtin **Hanne** hinter dem Schanktisch (5, 2). Ihr Menü: „Gefährten verwalten“ (Gefährten verabschieden und abholen), „Reden“, „Zimmer und Proviant“ (Bett 5 Gold, Ration 1 Gold), „Fackeln und Tränke“ (Fackel 2 Gold, Heiltrank 25 Gold, Ankauf zu 50 %), „Gepäck verwahren“ (Lager). Keine Gilde, kein Training, kein Tempel im Dorf. Ausbildung und Klassenwahl gibt es erst in Dreifurt (Hanne auf **Ausbildung**: Kämpfer- und Magiergilde sitzen in Dreifurt). Gerüchte/Reiseauskunft: Hanne auf **Reisewege** (ändert sich mit der Unruhe-Stufe, siehe „Offene Enden“).
**Gefährten:** **Korgar** (Ork, Kämpfer, Stufe 3, Handaxt) im Gasthaus am linken Tisch (4, 6) und **Tavion** (Elf, Schütze, Stufe 3, Kurzbogen, Lederrüstung) am Bach im Norden des Dorfs (30, 4). Beide erst nach der Auszahlung des Konvois, getrennt anwerbbar, ohne Antrittsgeld, Bedingung nur „Gruppe kleiner als 6“.

---

### Q00 Rabans Konvoi (Überfall auf der Landstraße) · 🔴 PFLICHT
- **Auslöser:** Automatisch nach der Namenswahl. Einblendung: Ihr begleitet seit Tagen Rabans Händlerwagen. Raban, Tavion und Raban rufen (lehrt **Goblins**), dann beginnt sofort der Kampf.
- **Stufe:** Held Stufe 1 (einzige steuerbare Figur). Gegner: 4 Goblin (Stufe 1, 8 LP, Keule, je 20 EP), ohne Anführer, furchtlos. Verbündete: Korgar (Nahkampf, KI) und Tavion (Bogen aus Deckung, KI), beide Stufe 3.
- **Lösungsweg:**
  1. Kampf auf der Landstraße (Ausschnitt 18 × 14). Held steht bei (12, 12) mit Blick Ost, Korgar (12, 8), Tavion (10, 11). Goblin A in der rechten Heckenlücke (14, 13), B dahinter (16, 14), C vor Korgar (11, 6), D bei Tavion (7, 12). Der Held hat den ersten Zug.
  2. Drei Hinweise begleiten den ersten Zug: Bewegen (endet nach einer Bewegung), Angreifen (endet nach dem Angriffsversuch), Aktionspunkte und „Zug beenden“. „Hinweise ausblenden“ blendet sie aus.
  3. Der Kampf endet in jedem Fall erfolgreich (geschützter Ausgang, kein dauerhafter Tod): Sieg; Held geht zu Boden (die Angreifer weichen, Raban steht mit Fackel daneben, Korgar sagt „Langsam. Ihr habt einen Schlag abbekommen.“); Rückzug („Ihr weicht hinter den Wagen zurück …“); oder alle Wachen unten (Raban vertreibt die Goblins mit einer brennenden Fackel).
  4. S03: Raban wundert sich über die verschnürten Säcke, Korgar („Einer hat nach mir gebissen, als seine Keule weg war.“), Tavion („Er hätte fortlaufen können.“). Ihr räumt den Stamm beiseite, Teleport nach Mühlbrück (alle geheilt), einmalige Draufsicht auf das Dorf.
  5. S04 Auszahlung am Mühlenhof: Raban zahlt, dann der Streit zwischen Taro und Lene ums Wasser (lehrt **Wasser**), Raban sucht Platz für die Säcke. Ab hier freie Steuerung.
- **Wahlen und Enden:** Alle Ausgänge führen gleich weiter. Nur der Ausgang „Held zu Boden“ ändert später Korgars Antwort auf **Goblins** („Den Schlag habt Ihr abgekriegt … Das nächste Mal bleibe ich näher.“).
- **Belohnung:** 20 Gold, 2 Rationen; Kampf-EP der Goblins (4 × 20 = 80, geteilt auf die drei Kämpfer, also rund 26 je Kopf). Wörter **Goblins**, **Lohn**, **Wasser**.
- **Zum Testen:** Ochse am Wagenende (14, 8) benutzen und umschauen, umgestürzter Baum (15–17, 7) umschauen. Verbündete erscheinen nicht in der Portraitleiste, ihre LP nur in der Zeitleiste. Prüfen, dass der Held mindestens eine sinnvolle eigene Handlung bekommt. Rückzug-Ausgang und Bewusstlos-Ausgang je einmal durchspielen.

### Mühlbrück kennenlernen (Gesprächsnetz) · 🟡 ENTDECKUNG
- **Auslöser:** Nach der Auszahlung, frei.
- **Lösungsweg (Figuren und Lagen auf der Ortskarte, 44 × 36):**
  - **Raban** am Wagen auf dem Mühlenhof (21, 11): **Arbeit** (Dreifurt: „mehr Wagen als hier Häuser“), **Goblins**, **Dreifurt** (über die Brücke, breite Straße), **Lohn**, **Taro**.
  - **Taro**, der Müller, am Mühlenhof (23, 12): **Arbeit** und **Wasser** (startet Q01), **Fen**, **Dreifurt** (Bera hat die Beschläge fürs Rad gemacht, Schmiede an der Marktgasse).
  - **Lene**, die Bäuerin: zuerst am Mühlenhof (23, 11), nach dem ersten Gespräch am Feldtor im Süden (26, 28). **Name** (lehrt **Taro**), **Arbeit** (lehrt **Wasser**, **Jette**), **Wasser** (der Schieber am Feldtor steht offen), **Tannried** (Feldweg im Süden, bei den Köhlern), **Jette**.
  - **Hanne** im Gasthaus: Begrüßung lehrt **Versorgung**; **Arbeit** lehrt **Wasser**, **Almut**, **Zeichen**, **Ausbildung**, **Dreifurt**, **Tannried**, **Reisewege**.
  - **Wegweiser** (24, 20): Dreifurt nach Osten über die Brücke, Tannried nach Süden, Oberlauf am Bach nach Norden (lehrt **Dreifurt**, **Tannried**, **Oberlauf**).
  - Gebäude: Mühle (Ladetür 24, 13; drinnen Mahlstein, Säcke, Werkbank, nach Q01 Fen), Gasthaus (8, 15), Lenes Hof (Tür 28, 27 auf der Südseite), Wohnhaus (privat), Scheune (verschlossen), Mühlrad (32, 15–16) umschauen.
- **Belohnung:** nur Wörter.
- **Zum Testen:** Jedes bekannte Thema bei einer unkundigen Figur ergibt deren Rücksatz. Figuren drehen sich beim Ansprechen zur Gruppe.

### Korgar und Tavion anwerben · 🔵 GEFÄHRTE
- **Auslöser:** Nach der Auszahlung. Korgar im Gasthaus (4, 6), Tavion am Bach im Norden (30, 4).
- **Stufe:** Beide treten mit Stufe 3 bei (Korgar Kämpfer, Tavion Schütze).
- **Lösungsweg:**
  1. Korgar nach **Arbeit** fragen („Mit Euch würde ich weiterziehen.“, lehrt **Gemeinsam reisen**), dann im Gespräch den Knopf **Anheuern**.
  2. Tavion: seine Begrüßung bietet die Begleitung an (lehrt **Gemeinsam reisen**), dann **Anheuern**.
- **Wahlen und Enden:** Wer das Gespräch nach dem Angebot ohne Anheuern verlässt, hört einmal den Abschiedssatz („Dann tut das. Ich laufe Euch nicht davon.“ bzw. „Wie Ihr wollt. Ich bleibe noch am Bach.“). Beim Wiedersehen fragen sie erneut, die Aufnahme bleibt jederzeit möglich. Bei voller Gruppe Systemmeldung „Die aktive Gruppe ist voll.“ und ein eigener Satz, niemand wird entfernt.
- **Belohnung:** zwei Stufe-3-Gefährten. Dringend empfohlen vor dem Wasserstollen (solo gelingt der ganze Stollen laut Messung nur etwa jedes zweite Mal).
- **Zum Testen:** Ablehnen, wiederkommen, dann anwerben. Kommentare beider in Q01 (Flimmern, Mühle), Q23 (Tavion an der Suhle, Korgar zum Braten), Q24 (Korgar zu den Booten, Tavion zum Spalt). Journal „Gefährten“ verweist auf weitere Gefährten in Dreifurt.

### Q01 Das versiegende Wasser (Wasserstollen) · 🟢 OPTIONAL
- **Auslöser:** Taro nach **Wasser** (oder **Arbeit**, lehrt Wasser) fragen: „Erst wurde das Rad langsamer, dann stand es … Ich habe Fen zum Oberlauf geschickt.“ (lehrt **Fen**, **Oberlauf**), dann Wahl „Ich sehe nach dem Zulauf.“ (Zusage, Journal sichtbar) oder „Ich muss weiter.“ (ohne Folgen). Die Aufgabe wird auch ohne Taro sichtbar durch die Hinweise am Bach, am Feldschieber oder die geöffnete Wartungstür.
- **Stufe:** Stufe 1–2, mit Korgar und Tavion. Gegner: Ratte (Stufe 1, 7 LP, Dunkelsicht, 10 EP). Kampf 1: 2 Ratten (mit 2 Kämpfern 3, ab 3 Kämpfern 5); Kampf 2: 3 Ratten (mit 2 Kämpfern 4, ab 3 Kämpfern 6). Balance-Test: Storyheld Stufe 1 solo: zwei Ratten 30/30 Siege, drei Ratten nur 11/30 Siege (der ganze Stollen gelingt solo etwa jedes zweite Mal); mit Korgar und Tavion je 30/30 Siege, rund 87 % bzw. 77 % LP übrig.
- **Lösungsweg:**
  1. Hinweise (optional, in beliebiger Reihenfolge): Feldschieber auf der Weltkarte (153, 192) oder im Dorf am Feldtor (31, 30): der offene Schieber (lehrt **Wasser**). Nördlich des Dorfs quer über den Bachweg die Zeile y 182 (x 144–160, mit dem flachen Stein über dem Bach (152, 182)): Beleg „schon vor den Abzweigungen“ fehlt Wasser (lehrt **Bach**, Taro antwortet darauf).
  2. Aus dem Nordausgang auf den Bachweg (Weg von (150, 194) nach Norden) bis zur Stollenmauer im Hügel. Wartungstür Weltkarte (150, 172), daneben der Durchlass, aus dem das Rinnsal kommt. Erstes Benutzen zeigt Spuren und Kratzen: „Tür aufdrücken“.
  3. Stollen (dunkel, Licht nötig; Fackel in die Hand). Vorraum A mit Öllampe (1, 10) und Eimern. Am Ostrand des Vorraums (7, 11–13) oder auf dem Steg (8, 12) ruft Fen (Zuruf, lehrt **Fen**, Name bekannt). Steg über der Lücke (9, 12) ist gebrochen, Fens Werkzeugbeutel liegt jenseits (10, 11).
  4. Nach Süden in den Wartungsbogen C (Zugang 3–4, 15). Warnzeile (Kratzen), beim Betreten des Raums Kampf 1 (Ratten bei der Werkbank (3, 20) und hinter dem Pfeiler (7, 19)). Flucht führt in den Vorraum (3, 12).
  5. Werkbank (2, 21): „Eine brauchbare Fackel mitnehmen“ (einmal).
  6. Durch den Gang (10–13, 19, dann 13, 15–18) nach Norden in den Abzweig D. Fen in seiner Nische (17, 12): erste Begegnung als Popup, dann Dialog (Themen **Wasser**, **Umleitung**, **Flimmern**, **Taro**, **Oberlauf**). Beim Verlassen verabschiedet er sich und geht zur Mühle (Rettung). Ohne geräumten Wartungsbogen bleibt er in der Nische.
  7. Nach Norden in den Schieberraum E (erste Zelle in Zeile 9): Warnzeile (Krallen), Kampf 2 (zwei Ratten an der Winde (18, 4), (20, 4), eine hinter der Säule (15, 4)). Flucht zum Abzweig (13, 12).
  8. Winde (19, 3) benutzen: zuerst das Relief an der Wand (lehrt **Umleitung**, erklärt den Seitenkanal auch ohne Fen), dann „Schieber öffnen“. Wasser rauscht, das Wasser fließt wieder (kein Schließen möglich).
  9. Entdeckung: Einbruch F im Nordwesten (Schutt in der Rinne, Wände 8–9, 1; Flimmereffekt bei (9, 2)). Die Sichtung kommt beim ersten Schritt im Schieberraum E nach dem Rattenkampf oder in der Nische davor (10–15, 1–2) als Protokollzeile, spätestens beim Öffnen des Schiebers als Popup. Kommentare von Tavion und Korgar, Wort **Flimmern**, Notiz im Journal. Wer Q01 abschließt, hat das Flimmern damit immer gesehen.
  10. Zurück zu Taro, **Arbeit** oder **Wasser**: wenn Fen gerettet und Wasser offen, zahlt er; danach holt er Lene herüber (Versöhnung).
- **Wahlen und Enden:** Reihenfolge frei: Fen zuerst oder Wasser zuerst, Taro antwortet passend (nur Wasser offen: „Fen ist immer noch fort …“; nur Fen gerettet: „Er redet dauernd von einer Winde …“). Folgen der Wasseröffnung auf der Karte: Mühlbach auf der Weltkarte wird Bach (vorher begehbares Rinnsal, danach nur Furt/Brücke), Gräben füllen sich, im Dorf dreht sich das Rad, das Bachbett wird Wasser (Dorf nur noch über die Brücke zu queren), Seitenkanal im Stollen führt Wasser. Mühle innen mit Mahlgeräusch.
- **Belohnung:** 30 Gold, 4 Rationen, 90 EP je lebendem Mitglied (einmal). Kampf-EP Ratten (10 je Ratte). Fackel. Wörter **Fen**, **Oberlauf**, **Umleitung**, **Flimmern**, **Bach**. Schaltet Q23 und Q24 frei. Taro gibt beim Lohn den Hinweis auf Meister Orwin (Start von „Das Flimmern“, siehe unten), denn das Flimmern ist bis dahin immer gesehen.
- **Zum Testen:** Beide Reihenfolgen. Auslösebereich der Kämpfe (ganzer Raum, auch diagonal kein Vorbeischleichen). „Nicht über die Bretter!“ auf dem Steg bis zur Rettung. Rast im Stollen ohne Überfall. Bachzellen-Eingänge ins Dorf trocken und mit Wasser. Mühlrad-Umschauen vor und nach.

### Das Flimmern (Hauptstrang, Orwin und die Hüter) · 🟣 HAUPTGESCHICHTE
- **Auslöser:** Wer das Flimmern gesehen hat, wird zu **Meister Orwin** in der Magiergilde von Dreifurt geschickt: Taro beim Lohn für Q01 (Popup, das Flimmern ist bis dahin immer gesehen) oder auf **Flimmern**, Hanne, Ragna (Kämpfergilde), Hauptmann Berthold und Ilve auf **Flimmern**, Berthold auch bei der Meldung zum Goblinbau (Q26). Damit erscheint die Aufgabe „Das Flimmern“. Ohne Orwin beginnt sie spätestens mit dem ersten Relikt.
- **Stufe:** kein Kampf.
- **Sichtungen** (je eine Notiz im Journal, bis zum Wendepunkt): Einbruch im Wasserstollen (Q01), alter Harzweg westlich von Tannried (Kapitel 3), Eingang des Wolfsbaus über dem Karrweg (Q20), Trommelhalle im Goblinbau (Q26), Plattform der Glockenwacht (Q13).
- **Lösungsweg:**
  1. Orwin (Magiergilde, Tür (44, 24) am Brückenkopf in Dreifurt, „Reden“) nach **Flimmern** fragen. Erster Bericht: Orwin kennt so etwas nicht, ein Satz in einer alten Abschrift erinnert daran, eine Stelle allein reicht nicht. Orwin bittet um eine zweite und nennt die Holzfäller von Tannried (Harzweg) und Hauptmann Berthold. 20 EP.
  2. Eine zweite Stelle sehen, dann Orwin wieder nach **Flimmern** fragen. Wendepunkt (Popup): die Abschrift der Hüter mit drei Zeichen um eine abgeriebene Mitte und dem Satz »Wo die Luft kalt zittert, hört der Ort keine Antwort mehr«. Orwin ordnet die Zeichen zu: Hammer im Berg = **Karrfels**, Haus mit Fächern im Moor = **Brackhafen**, Quelle, die antwortet = **Lichtenruh**. Lehrt **Hüter**, **Karrfels**, **Brackhafen**, **Lichtenruh**. 50 EP. Wer schon zwei Stellen gesehen hat, bekommt den Wendepunkt gleich beim ersten Besuch.
  3. Mit **Hüter** an den drei Orten fragen: Hedda in Karrfels (lehrt **Alte Esse**), Neve in Brackhafen (gibt die Messleine sofort), Meret oder Aelis in Lichtenruh (lehren **Quellbezirk** und **Antwort**). Die Reliktquests beginnen auch ohne dieses Wort wie gewohnt.
  4. Nach jedem Relikt Orwin auf **Hüter** fragen (freiwillig): Er wertet aus, mit drei Stücken schickt er zu Meret.
- **Journal:** Die Aufgabe zeigt immer den nächsten Schritt: Orwin, zweite Sichtung, die drei Orte, je Relikt „noch offen“ mit einem Hinweis (Schmelzhalle, Pegelschreiberin, Meret) oder „geborgen“, mit drei Relikten Meret, nach Q16 die Herzsenke, am Ende das Herz.
- **Belohnung:** 20 + 50 EP, Wörter **Hüter** und die drei Orte. Orwin antwortet nach dem ersten Bericht auch auf **Goblins** (Tiere, die fliehen, rauben nicht).
- **Zum Testen:** Taros Popup beim Lohn, einmal mit Sichtung im Schieberraum, einmal erst an der Winde. Orwin mit einer und mit zwei Sichtungen beim ersten Besuch. Die Notizen im Journal. Ohne Orwin direkt zu einem Reliktort: Die Aufgabe erscheint mit dem Relikt und nennt Orwin.

### E01 Die fremden Zeichen am Bienenhaus (Apfelhang) · 🟢 OPTIONAL
- **Auslöser:** Hanne nach **Arbeit** (lehrt **Almut**, **Zeichen**) oder direkt zum Apfelhang: aus dem Nordausgang den Bachweg hinauf, dann östlich auf den Apfelhang (Höhe 2). **Almut**, die Imkerin, steht vor dem Vordach (160, 178), ihre Begrüßung lehrt **Zeichen**. Bienenhaus-Tür (166, 178).
- **Stufe:** beliebig, kein Kampf, keine Frist.
- **Lösungsweg (Reihenfolge frei):**
  1. Almut nach **Zeichen**: Verdacht gegen Lene (lehrt **Lene**), einmalige Wahl „Ich sehe mich um.“ oder „Das beweist nichts gegen Lene.“.
  2. Krug am Vordach (163, 177) untersuchen: Kreidestriche, heruntergefallener Korb (lehrt **Zeichen**).
  3. Beschädigter Bienenstand am Westgiebel (162, 176) untersuchen: Astbeleg, ein abgebrochener Ast hat den Korb umgeworfen (lehrt **Ast**). Das ist der wichtige Beleg.
  4. Futterschale am trockenen Graben (164, 182): hinkender Fuchs (lehrt **Fuchs**). Fuchs im Gebüsch (164, 184) nur umschauen.
  5. **Jette** (Lenes Tochter, etwa zwölf) am Graben (163, 182): Begrüßung lehrt **Fuchs**. Nach **Zeichen** fragen: ihre Erklärung, die Kreide markiert ihre Futterplätze (lehrt **Almut**).
  6. Almut mit beiden Belegen nach **Zeichen**: sie bittet, mit Jette zu reden (lehrt **Aussprache**).
  7. Jette nach **Almut** oder **Aussprache**: Entscheidung. Mit Astbeleg „Der Ast war es. Das erklären wir ihr.“ oder „Du erklärst es ihr. Ich komme mit.“; ohne Astbeleg nur die zweite Wahl, aber Jette weiß nicht, was sie zum Korb sagen soll (bleibt offen). „Später“ ändert nichts.
  8. Jette steht nun neben Almut (161, 178). Almut oder Jette ansprechen: Aussprache (Popup mit beiden), Almuts Dank.
- **Wahlen und Enden:** Nur ein Ende. Früher Fund: wer Krug, Schale, Jette und Ast vor Almut erledigt, hört bei Almut gleich die Antwort mit beiden Belegen. Danach: Krug ohne Kreide, Korb aufgerichtet, Ast als Holzstapel (170, 177), Futterschale unter dem Unterstand (169, 185), Jette am Unterstand (168, 186). Lene und Hanne haben Abschlusssätze (Lene: Jette darf den Fuchs weiter versorgen).
- **Belohnung:** 2 Rationen (Honig und Brot), 30 EP je lebendem Mitglied, einmal.
- **Zum Testen:** Fall „früher Fund“ und Fall „ohne Ast“. Belohnung genau einmal (auch nach Speichern und Laden). Bienenhaus innen: Wachskessel, Honigregal, Werkzeugleiste, Schleierhut (nur Umschau-Texte). Der Graben am Apfelhang bleibt auch nach Q01 trocken.

### Q23 Die Nacht im Korn · 🟢 OPTIONAL
- **Auslöser:** Erst nach Taros Lohn aus Q01 und einem Verlassen des Dorfs durch einen der vier Ausgänge (still freigeschaltet). Erst dann zeigen die Felder Schäden. Lene (am Feldtor, 26, 28) ansprechen: Szene mit der geknickten Ähre, sie bittet um eine Nachtwache (lehrt **Korn**).
- **Stufe:** Stufe 3 mit Korgar und Tavion (Bezugsgruppe der Balance-Test: Held, Korgar, Tavion auf Stufe 3). Gegner: Rotte Wildschweine, Keiler (Anführer, Stufe 5, 44 LP, 90 EP, Beute Keilerzahn) und Bachen (Stufe 3, 24 LP, 40 EP): 2 Bachen, ab 4 Kämpfern 3, ab 6 Kämpfern 4; mit vernagelten Löchern eine Bache weniger. Messung (16 Läufe, Sieg/Frist/Niederlage): ohne Vorbereitung 4/3/9, Bretter 12/4/0, Köder 3/12/1, beides 15/1/0, Soloheld 0/0/16. Also: beide Vorbereitungen machen.
- **Lösungsweg:**
  1. Feld südöstlich des Dorfs (Südausgang, dann östlich; Weltkarte 160–173, 206–210, links Acker, rechts Korn, Hecke am Südrand y 211 mit Durchfahrt 166–167). Zertrampeltes Korn umschauen.
  2. Hecke: zwei Schlupflöcher (162, 211) und (171, 211) untersuchen: schwarze Borsten (lehrt **Wildschweine**, nach dem Auftakt auch **Bretter**).
  3. Futterstelle im Acker (162, 208) untersuchen (nach dem Auftakt lehrt **Köder**).
  4. Jette am Apfelhang nach **Korn** oder **Wildschweine**: „Die Schwarzen?“ ein sehr großer mit langen Zähnen und mehrere kleinere (Journal-Notiz).
  5. Taro nach **Bretter**: „Bretter und Pflöcke“ vom alten Mehlkasten. Beide Löcher benutzen, „Vernageln“ (nach dem zweiten ist das Bündel verbraucht).
  6. Hanne nach **Köder**: „Eimer Küchenabfälle“. An der Futterstelle benutzen, „Auskippen“. (Lene nennt Taro und Hanne auf **Bretter** bzw. **Köder**.)
  7. Hochstand am Ostrand (175, 208) benutzen: bei Tag „Wachen“ lässt die Zeit bis zur Dämmerung vergehen, dann ein Blick auf die Rotte (vier Fassungen je Vorbereitung).
  8. Ins Feld treten (jede Feldzelle, von der Dämmerung bis zum Morgen): Kampf. Ausschnitt ab (157, 204), 20 × 11, Hecke halbe Deckung, aufgewühlter Acker doppelte Bewegungskosten. Frist: nach 21 Ticks „Die Rotte ist satt“ (Marke in der Zeitleiste). Mit Köder hat die Gruppe den ersten Zug, die Bachen kommen verzögert. Fällt der Keiler, bricht die Moral der Bachen. Nachts ohne Licht ist das Feld dunkel (Lene: Licht mitnehmen).
  9. Zurück zu Lene: Lohn.
- **Wahlen und Enden:** Sieg vor der Frist: Ernte gerettet. Frist abgelaufen: halbes Feld verloren, die Rotte kommt nicht wieder, EP nur für gefallene Tiere. Flucht: an den Feldrand (177, 208), alles bleibt offen, neue Wache in der nächsten Nacht. Niederlage: Spielende. Kampf ohne Auftakt (Wanderer in der Dämmerung) möglich, Lene zahlt dann nachträglich („Ihr wart das heute Nacht?“). Nachhall: Hanne kauft nach einem Sieg einmal das Fleisch (beim nächsten Gespräch: 15 Gold, zwei Stunden Wildbraten, volle Heilung, Korgar: „Kruste. Endlich kocht hier jemand richtig.“). Fährte nach Süden über die Straße zur **Suhle** am Waldrand (165–167, 221–222): Popup, Wort **Suhle**, Tavions Kommentar. **Verzahnung:** Runa in Tannried erklärt auf **Suhle**, dass Goblins seit dem Frühjahr in der Mulde am Holzfällerhang sitzen (eigene Fassung, wenn der Holzbruch schon geräumt ist).
- **Belohnung:** gerettet 40 Gold, 4 Rationen, 100 EP je Kopf; halbes Feld 15 Gold, 2 Rationen, 60 EP. Kampf-EP (Keiler 90, Bache 40), Keilerzahn. Wildbraten (15 Gold, Heilung). Wörter **Korn**, **Wildschweine**, **Bretter**, **Köder**, **Suhle**.
- **Zum Testen:** Alle vier Vorbereitungen, Lesbarkeit in der Dämmerung, Fristmarke „in N“, abgelenkte Bachen, Speichern/Laden im Kampf mit laufender Frist, Kartenzustände (Löcher vernagelt/offen, Schäden bleiben bis zur Zahlung, halbes Feld). Volles Gepäck bei Brettern/Eimer (sie bleiben stehen, nochmal fragen).

### Alter Seewachturm · 🟢 OPTIONAL
- **Auslöser:** Kein Auftraggeber, keine Aufgabe im Journal. Aus dem Westausgang den Westweg (von (141, 200) nach Südwesten bis zur Küstenstraße bei (57, 216)), dann über die Wiese zum Turm am Strand (Weltkarte 41–47, 211–217). Tür nach Osten (47, 214), Zugang von der Wiese (48, 214). Kein Pfad zur Straße.
- **Stufe:** Stufe 2–4 mit Trio. Jede Ebene ein Kampf, friedliche sichtbare Gruppe, startet beim Betreten einer Raumzelle (außer dem sicheren Feld vor Tür bzw. Luke) oder beim Benutzen. Gegner (furchtlos, mit Gefährten mehr):
  - Ebene 0 Vorräte: Ratten 2 bis 4 (Stufe 1, 10 EP).
  - Ebene 1 Wachstube: Ratten 3 bis 6.
  - Ebene 2 Lager: Kellerspinnen 2 bis 4 (Stufe 1, 12 EP).
  - Ebene 3 Kisten und Stroh: Ratten und Spinnen, 4 bis 6.
  - Ebene 4 Turmstube: Große Kellerspinne (Stufe 3, 35 EP, Anführerin) mit 1 bis 3 Kellerspinnen.
  - Keine Balance-Test (Balance offen).
- **Lösungsweg:** Je Ebene den Raum räumen, dann die Leiter in der Nordnische hinauf (Ebene 0 bei (10, 6), 1 bei (4, 6), 2 bei (10, 6), 3 bei (4, 6)); Luke hinab jeweils in der anderen Nische. Ab Ebene 2 liegt draußen das Wolkenmeer. Oben in der Nordostnische (10, 6) die Truhe.
- **Wahlen und Enden:** Flucht führt eine Ebene tiefer vor die Leiter bzw. auf die Wiese vor der Tür, die Gruppe bleibt.
- **Belohnung:** Truhe: 60 Gold, **Schwert des Turmwächters** (1W8+1, Wert 90), 2 Heiltränke, 1 Brandflasche. Kampf-EP. In der Turmstube der Sehschlitz für Q24.
- **Zum Testen:** Fluchtzellen je Ebene, Aufstellung in Ecken und Mitte, Truhe nur einmal, schräge Leitern. Entwicklermenü-Teleport „Alter Seewachturm“.

### Q24 Weiße Flecken · 🟢 OPTIONAL
- **Auslöser:** Nach Taros Lohn (Q01) steht die Landvermesserin **Frauke** im Gasthaus am zweiten Tisch (10, 6), mit verbundenem Knöchel. **Arbeit** lehrt **Kartenblatt** und **Knöchel**. Nach **Kartenblatt** fragen: sie drückt Euch das **Winkelbrett** (Questgegenstand) in die Hand (lehrt **Peilung**) und zählt vier Punkte auf. Bei vollem Gepäck bleibt alles offen.
- **Stufe:** kein eigener Kampf, aber der Weg führt durch den Seewachturm (Ebene 4 muss geräumt sein) und in den Tannwald (Holzfällerhang). Für alle vier Punkte etwa Stufe 3–4 und Besuch von Dreifurts Umland und Tannried.
- **Lösungsweg (Reihenfolge frei, nur bei Tag oder Dämmerung; nachts nur „Zum Peilen ist es zu dunkel.“):**
  1. **Kuppe** über dem Wasserstollen: Messstange Weltkarte (152, 161) auf dem Hügel nördlich der Stollenmauer (Höhe 3). Aufstieg vermutlich vom Apfelhang aus über die Grasstufen (unklar, kein Weg). Benutzen: Blick nach Nordosten, Flusstal, über dem Berg von Karrfels nur eine dünne Rauchfahne. Ohne Auftrag nur die Buchstaben H und L (lehrt **Messstange**; Frauke: Harm und Lisbet haben sie gesetzt, lehrt **Vermesser**).
  2. **Zollhausdach:** Altes Zollhaus östlich von Mühlbrück an der Straße nach Dreifurt (Hoftor Weltkarte (210, 197), Abzweig von der Straße in Zeile 199; Turmtür (211, 187)). Innen Holzleiter in der Mauernische (12, 1) zur Dachkammer, dort die Tür zur Dachplattform (7, 3). Blick nach Norden auf die Palisade der Weidenkehre: ohne Q19 (Hauptmann Berthold, Dreifurt) kein Rauch, nach Q19 der Rauch des Signalfeuers.
  3. **Turmstube** des Seewachturms (Ebene 4): Sehschlitz in der Nordwand (7, 6), erst nach dem Kampf der Ebene. Blick nach Norden: die Insel Glockenwacht, kein Rauch auf dem Leuchtturm. Probe Wahrnehmung (Schwelle 30, Figur wählen): zwei Boote liegen still weit vor der Insel (Korgar kommentiert).
  4. **Hochsitz** am Holzfällerhang im Tannwald (Weltkarte 108, 302): von Tannrieds Südwesttor (142, 278) den Waldpfad zur Gabel (124, 281), dann die Fahrspur nach Süden. Der Hochsitz blickt auch in die Mulde des Holzbruchs (Goblinlager). Peilung: Blick nach Süden auf die Südklippen, nirgends Rauch. Probe Wahrnehmung (Schwelle 35): ein heller Steig zu einem dunklen Spalt im Fels (Tavion kommentiert).
  5. Zu Frauke, **Peilung**: Bericht je genommener Peilung (einzeln oder mehrere auf einmal). Ohne Neues zählt sie die Punkte auf.
- **Wahlen und Enden:** Zollhaus in drei Berichtsfassungen: Rauch gesehen; kein Rauch („gehört dem Hauptmann gemeldet“); kein Rauch, aber Q19 inzwischen erledigt (sie trägt Posten und Feuer ein). Boote und Spalt sind Zusätze. Ein Abbruch der Figurenwahl bei der Probe kostet nur den zweiten Blick, nicht die Peilung. **Verzahnung:** der Spalt an den Südklippen ist die Spur zu Q26 „Das leere Nest“; Karrfels (Rauch), Glockenwacht (Leuchtfeuer, Boote) und Weidenkehre (Q19) sind Fährten in andere Regionen. Das Wort **Vermesser** bleibt (Harm und Lisbet am Graufelspfad, Folge E06 Seilklamm in Karrfels: Marken oder Messkasten zu Frauke bringen).
- **Belohnung:** je Peilung 30 EP je Kopf und ein aufgedecktes Stück Automap (Kuppe: Umland und Karrfels; Zollhaus: Umland; Turm: Küste und Glockenwacht; Hochsitz: Tannwald und Südklippen). Je Bericht 10 Gold. Nach dem vierten Bericht 40 Gold, 80 EP, Winkelbrett zurück und Fraukes Abschrift: Automap Weltkarte (28, 140) bis (257, 325), gesehen, nicht besucht. Zusammen 200 EP und 80 Gold.
- **Zum Testen:** Frauke erst nach Q01. Messstange vor dem Auftrag. Peilen bei Nacht, ein zweites Mal. Zollhausdach vor und nach Q19, Bericht wenn Q19 zwischen Peilung und Bericht erledigt wird. Sehschlitz vor dem Kampf (nur Umschauen). Berichte gesammelt, Abschrift auf der Automap (Ortsnamen, Umfang). Ton: deutet Frauke zu viel oder zu wenig?

### Wolfsrudel der Westmark · 🟢 OPTIONAL
- **Auslöser:** 13 wandernde Rudel ohne Geschichte. Auf der Karte steht ein einzelner Wolf (Umschauen: „ein Wolf“), erst der Kampf zeigt das ganze Rudel. Wahrnehmung 7 Felder rundum, auch nachts, 120 % Tempo, sie verfolgen bis 6 Schritte ohne Sicht.
- **Stufe:** Wolf Stufe 2 (12 LP, 25 EP), Leitwolf als Anführer (fällt er, kann das Rudel einbrechen). Rudelgröße mit Gefährten: klein 2 (mit 2 Kämpfern 3, ab 3 Kämpfern 4), mittel 3 (ab 3 Kämpfern 4, ab 4 Kämpfern 5), groß 4 (ab 3 Kämpfern 5, ab 4 Kämpfern 6, ab 5 Kämpfern 7). Keine Balance-Simulation. Empfehlung: klein ab Stufe 2–3 im Trio, groß ab Stufe 4–5.
- **Lage (Weltkarte):**

| Rudel | Zelle | Größe | Lage |
| --- | --- | --- | --- |
| Westhain Nord | (96, 158) | klein | Hain westlich von Mühlbrück, Nordteil |
| Westhain Süd | (90, 186) | klein | Hain westlich von Mühlbrück, Südwestrand |
| Tannwald Nordwest | (116, 238) | klein | Nordwestzipfel zwischen Westweg und Tannriedstraße |
| Tannwald Nordost | (172, 240) | klein | Nordostrand östlich der Tannriedstraße |
| Tannwald Südwest | (138, 332) | mittel | tief im Süden westlich der Mitte |
| Tannwald Süd | (170, 324) | mittel | tief im Süden |
| Tannwald Südost | (200, 326) | mittel | Süden östlich der Mitte |
| Tannwald Ostrand | (241, 270) | mittel | südlich der Straße nach Karrfels |
| Tannwald Ost | (238, 298) | mittel | Ostteil |
| Tannwald Fernost | (266, 302) | groß | äußerster Osten |
| Tannwald Südrand | (228, 328) | groß | Südostrand |
| Nordwald West | (220, 70) | groß | am Granitmassiv, Westteil |
| Nordwald Ost | (252, 74) | groß | Ostteil |

- **Belohnung:** 25 EP je Wolf, keine Beute. **Verzahnung:** die Fallenstellerin im Ostteil des Tannwalds (V01a, Abschnitt Tannried) gibt den Rudeln einen Zweck.
- **Zum Testen:** Kartenname „ein Wolf“ vs. Kampfmeldung „Wolfsrudel“. Mindestabstand zu Wegen (15 Felder), Verfolgung.

### Weltkarte des Startdreiecks · 🟡 ENTDECKUNG
- **Straßen ab Mühlbrück:** Bachweg nach Norden (150, 194) bis zur Wartungstür (150, 173). Oststraße vom Ostzugang (155, 200) über (200, 203) zum Westtor von Dreifurt (230, 196), unterwegs der Abzweig zum Alten Zollhaus (Hoftor 210, 197). Südstraße vom Südzugang (148, 206) durch den Wald zum Nordtor von Tannried (148, 270); von Tannrieds Osttor (154, 272) Straße nach Dreifurt (Südtor) mit Abzweig nach Karrfels. Westweg vom Westzugang (141, 200) nach Südwesten zur Küstenstraße (57, 216) beim Seewachturm; die Küstenstraße läuft an der Küste nach Norden Richtung Brackhafen und nach Süden zum Deichweg (Einzelheiten in den Abschnitten Brackhafen und Wege).
- **Felder:** südöstlich von Mühlbrück (Q23) und südwestlich.
- **Hohe Punkte** (B-W1, mit Q24 gebaut): Kuppe über dem Stollen, Zollhausdach, Turmstube, Hochsitz (siehe Q24). Ohne Auftrag bieten sie nur Umschau.
- **Freie Begegnungen im Startdreieck** (ohne Quest, wandernd, mit größerer Gruppe stärker): Ratten (Stufe 1) nördlich von Mühlbrück bei (167, 146) und (125, 146), bei Tannried (156, 291), bei Dreifurt (232, 211); Goblin-Trupps (Stufe 1–3, stehen 2–7 Felder neben Wegen) an der Tannriedstraße (151, 231), am Küstenweg (69, 225), an der Dreifurtstraße (198, 209), an der Karrfelsstraße (206, 250), an den Südklippen (98, 356, wandernd); Spinnen (Kellerspinne/Große Kellerspinne, Stufe 1–3) im Tannwald West (92, 319), Tannwald Mitte (201, 287), Westhain (90, 252); Wildschweine (Bache/Keiler, Stufe 3–5) im Feld westlich (120, 212), am Waldrand (259, 214), im Südwesten (65, 352); Strandkrabben (Stufe 3, 35 EP) am Strand (40, 179), (50, 265), (36, 346).
- **Rast:** Draußen kann man überall rasten, im Startdreieck gibt es keine Überfälle beim Rasten. Bett bei Hanne 5 Gold. Im Wasserstollen rastet man ohne Überfall. Eigene Rastplätze gibt es im Startdreieck nicht (unklar, ob B-W1 noch welche plant).

### Wie es nach Mühlbrück weitergeht · 🧭 WEGWEISER
- Kürzester Pflichtweg: nach der Auszahlung zum **Osttor** hinaus auf die Weltkarte, Q01, E01, Q23, Q24 und die Gefährten sind nicht nötig. Danach die drei Relikte (Karrfels, Brackhafen, Lichtenruh), siehe deren Abschnitte.
- **Hauptstrang:** Taro (nach Q01) und Hanne auf **Flimmern** schicken zu Meister Orwin in die Magiergilde von Dreifurt (siehe „Das Flimmern“).
- Wer schickt wohin:
  - **Raban** (**Arbeit**, **Dreifurt**): Dreifurt, Markt, dort suchen Leute Fuhrleute und Wachen.
  - **Hanne** (**Ausbildung**): Kämpfer- und Magiergilde in Dreifurt (dort wählt der klassenlose Held seine Klasse). (**Reisewege**): Stadt über die Brücke, Oberlauf am Bach, Tannried über den südlichen Feldweg.
  - **Taro** (**Dreifurt**): Beras Schmiede an der Marktgasse in Dreifurt.
  - **Lene** (**Tannried**): Feldweg im Süden zu den Köhlern. Hanne erwähnt auf **Arbeit**, dass Bewaffnete dort das Sägewerk besetzt halten.
  - **Wegweiser** (24, 20): Dreifurt Ost, Tannried Süd, Oberlauf Nord.
  - **Journal „Gefährten“**: in Dreifurt im Gasthaus hinter dem Westtor suchen weitere Leute Anschluss.
  - **Frauke** (Q24): Karrfels (Rauch), Glockenwacht vor Brackhafen (Leuchtfeuer), Weidenkehre (Hauptmann Berthold in Dreifurt), Südklippen (Q26), Harm und Lisbet am Graufelspfad hinter Karrfels (E06).
  - **Suhle** (Q23): Runa in Tannried.
- Empfehlung für den gründlichen Weg: Konvoi → Korgar und Tavion → Q01 → E01 → Seewachturm Ebene 0–2 → Q23 (Stufe 3) → Kuppe peilen → Dreifurt (Zollhausdach unterwegs) → Tannried (Hochsitz) → Seewachturm Ebene 3–4 und Turmstube → Bericht bei Frauke. Ankunft in Dreifurt laut EP-Vermessung mit Stufe 2–3.

---

### ↩️ Offene Enden und Rückkehr später
- **Q24 Bericht:** Zollhaus- und Hochsitz-Peilung erst nach Abstechern nach Dreifurt bzw. Tannried; Frauke wartet im Gasthaus. Zollhausdach nach Q19 (Weidenkehre, Dreifurt) zeigt Rauch statt kaltem Posten.
- **Frauke und die Vermesser:** nach E06 (Seilklamm, Karrfels) Marken oder Messkasten zu Frauke bringen, Wort **Vermesser** (Abschnitt Karrfels).
- **Q23 Suhle → Runa (Tannried)**, Hochsitz-Spalt → **Q26 Das leere Nest** an den Südklippen (Abschnitt Tannried/Südklippen).
- **Wildbraten** bei Hanne einmal nach dem Sieg in Q23.
- **Unruhe:** Hanne antwortet auf **Reisewege** je Stufe anders (1: Schranke am Moosfels auf dem Weg nach Lichtenruh; 2: Orks auf der Nordroute; 3: Gäste fragen nach dem Weg und nach Platz in der Scheune). Sonst ändern sich in Mühlbrück laut Daten keine Gespräche mit der Unruhe.
- **Gefährten verwalten** bei Hanne (Gefährten abgeben und abholen).
- **Flimmern im Stollen** bleibt sichtbar (Taro: an den verschütteten Zulauf erst mit Abstützung). Es ist die erste Sichtung des Hauptstrangs, Orwin in Dreifurt will davon hören.
- **Wolfsrudel und große freie Gruppen** im Tannwald-Osten und Nordwald lohnen sich erst später (Stufe 4+).

---

## Kapitel 2 · Dreifurt und Umgebung

**Anreise:** Dreifurt ist eine ummauerte Marktstadt am Fluss mit vier Toren, die auf der Weltkarte direkt in die Ortskarte führen (Ankunft eine Zelle innerhalb, beim ersten Betreten je Tor ein Blick auf die Stadt):
- **Westtor** Weltkarte (230, 196): Straße von Mühlbrück (der übliche Weg nach dem Konvoi). Ortskarte (0, 32–33), führt in die Marktgasse.
- **Südtor** Weltkarte (240, 201): Weg nach Tannried. Ortskarte (27–28, 43).
- **Nordtor** Weltkarte (245, 177): Küstenstraße nach Nordwesten (Brackhafen, Weidenkehre). Ortskarte (40–41, 0).
- **Osttor** Weltkarte (250, 181): Straße nach Karrfels (Karrweg). Ortskarte (55, 6–7).

Der Fluss läuft quer durch die Stadt (Ortskarte Zeilen 15–18), die Bohlenbrücke liegt bei x 40–41. Südufer: Marktgasse, Schmiede, Fuhrplatz, Markt, Gilden am Brückenkopf. Nordufer: Wohnhäuser, Kai, die Nordzeile.

**Wann:** Direkt nach Mühlbrück (Konvoi, Wasserstollen, Bienenhaus). Ankunft mit Gruppenstufe 2–3. Der gründliche Weg (4 Köpfe) verlässt die Region mit etwa Stufe 7 Richtung Karrfels. Empfohlene Reihenfolge: Stadt und Dienste, Namar, Q02 (ohne Kampf), E03 Zollhaus (Stufe 2–3), Nordzeile Q21 (Stufe 4 für den Kampf, mit Ration jederzeit), Wachhof Q18 (Stufe 4), Weidenkehre Q19 und Karrweg Q20 (Stufe 4–5), Vierte Furt (Stufe 4–6), Q22, zuletzt die Orkhöhle (Stufe 5–7, Gruppe von 4–6). Die Startdreieck-Quests (eigener Abschnitt) liegen zeitlich dazwischen.

**Dienste:**
- **Gasthaus Zum Brückenbogen**, Tür (6, 31) an der Marktgasse kurz hinter dem Westtor (Schild mit Ausleger bei 7, 32). Wirtin **Hella** am Schanktisch (Innenraum 5, 2): Wahl „Gefährten“ (Wartebank, Gefährten abholen/abgeben), „Reden“, „Zimmer und Proviant“ (5 Gold je Nacht, Ration 1 Gold), „Waren ansehen“ (Fackel, Heiltrank), „Gepäck verwahren“. Gerüchte: **Arbeit** lehrt **Zollhaus** (Hinweis auf E03). Ab Unruhestufe 1 antwortet sie auf **Reisewege** je Stufe anders (Stufe 1 und 2 lehren **Moosfels**). Ein stummer Gast sitzt bei (11, 5).
- **Schmiedin Bera**, offene Schmiede am Südufer (18, 35): Reden und Waffen (Handaxt, Knüppel, Kurzschwert, Kriegshammer, Holzschild).
- **Vessa**, Marktstand an der Nordwestecke des Markts (33, 29): Reden und einfache Reiseausrüstung (Kurzschwert, Fackel, Schleuder, Lederkappe).
- **Krämer Joris**, Tür (31, 40) nach Westen, Schild (30, 39): Magierstab, Fackel, Heiltrank, Gegengift, Brandflasche (Türdienst, keine Figur auf der Karte).
- **Kämpfergilde (Ragna)**, Tür (38, 24) am Brückenkopf: Ausbildung Kämpfer, Schütze, Dieb.
- **Magiergilde (Orwin)**, Tür (44, 24) gegenüber: Ausbildung Weißmagier, Graumagier, Schwarzmagier. Orwin ist der Wegweiser des Hauptstrangs: **Flimmern** (erster Bericht, Wendepunkt ab der zweiten Sichtung), **Hüter** (Auswertung je Relikt), **Goblins** (siehe „Das Flimmern“ in Kapitel 1). Ragna gegenüber schickt auf **Flimmern** zu ihm.
- **Tempel (Schwester Sunna)**, Tür (48, 31) an der Ostseite des Markts, Schild (47, 30): Wiederbelebung, Fluch heilen. **Arbeit** lehrt **Hospiz** und **Lichtenruh**.
- **Heilhaus (Tamo)**, Tür (48, 40) am Seitenweg: LP heilen (1 Gold je LP), Gift, Verletzung, Verlangsamung, Lähmung, Verwirrung.
- **Hauptmann Berthold**, Pult unter dem Vordach am Brückenkopf (43, 22): Auftraggeber für Q18–Q20, Richter in Q02, nimmt Meldungen von den Wegen an. **Arbeit** lehrt **Reisewege**, **Orks** und **Wachhof**.
- Erstausbildung: Die erste Klasse einer klassenlosen Figur kostet die Hälfte. Brydan zahlt bei direkter Anreise 25 Gold.

**Gefährten:**
- **Namar** (Katzenvolk, Dieb, Stufe 3) an der niedrigen Hofmauer am Markt (30, 35). Jederzeit anheuerbar über den Beitritts-Button, Bedingung nur: Gruppe kleiner als 6.
- **Odrik** (Zwerg, Weißmagier, Stufe 5) in der Orkhöhle, siehe dort.
- Die lange Tafel im Gasthaus ist leer: Jaro, Beric, Haldaar und Z'zarek warten an ihren eigenen Orten (Brackhafen, Karrfels, Handelsstein, Steinbruch bei Glasgrund).

---

### Ankunft in Dreifurt · 🟡 ENTDECKUNG
- **Auslöser:** Erstes Betreten über ein Tor zeigt einen Blick auf die Stadt (je Tor eigener Text, einmal je Spiel).
- **Stufe:** keine Kämpfe in der Stadt.
- **Lösungsweg:**
  1. Durch das Westtor die Marktgasse nach Osten gehen. Zwischen x 12 und 26 auf der Gasse (Zeilen 32–33) startet die Szene D02 (siehe Q02).
  2. Umschauen lohnt: Ausleger-Schilder (Gasthaus, Gilden, Heilhaus, Tempel, Krämer, Schmiede), Brunnen (38, 32), Wendels leerer Wagen (23–24, 39), Handwagen (21, 28), Pult (43, 21). Speicher (24, 28) und Werkstatt (16, 37) sind verschlossen, private Wohnhaustüren geben nur eine Zeile.
  3. Bei Berthold **Arbeit**, dann **Reisewege** (lehrt **Brackhafen**, **Karrfels**, **Tannried**), **Orks** (Hinweis auf die Orkhöhle), **Wachhof** (Q18), **Flimmern** (schickt zu Orwin). Bera erwähnt auf **Tannried** den besetzten Werkhof.
- **Belohnung:** Wörter, Orte.
- **Zum Testen:** Jedes Tor hinein und hinaus inkl. Speichern/Laden. Wer per Klick zum Markt läuft, nimmt evtl. den Umweg über den Kai und sieht D02 erst an der Schmiede (bekannte Grenze).

### Namar · 🔵 GEFÄHRTE
- **Auslöser:** Namar an der Hofmauer (30, 35) ansprechen.
- **Stufe:** Namar tritt mit Stufe 3 bei (Dieb, Nachtauge, kann Schlösser öffnen).
- **Lösungsweg:**
  1. **Name**, **Arbeit** (lehrt **Reise** und **Ladung**), **Reise** = sein Angebot.
  2. Beitritts-Button im Dialog (jederzeit verfügbar). Verlässt man ihn ohne Beitritt, sagt er einmal „Dann bleibe ich noch hier.“, danach begrüßt er mit „Das Angebot gilt.“
  3. Bei voller Gruppe zuerst Systemhinweis, dann sein Satz.
- **Wahlen und Enden:** Wichtig für Q02: Namar ist Zeuge (Beleg A) **nur solange er NICHT in der Gruppe ist**. Wer Q02 über Namar lösen will, fragt ihn zuerst nach **Ladung**, **Werkzeuge**, **Handwagen** oder **Pell** (nach D02) und heuert ihn danach an. Orik ersetzt ihn als Zeugen jederzeit.
- **Belohnung:** Gefährte. Mit Tavion in der Gruppe begrüßt Tavion ihn beim Beitritt.
- **Zum Testen:** Ablehnen, volle Gruppe, späteres Anheuern, Tavions Kommentar. Mit Namar in der Gruppe gibt es in Q21 die Wahl „Namar fauchen lassen“ (Loyalität +2).

### Q02 Die vermisste Werkzeuglieferung · 🟢 OPTIONAL
- **Auslöser:** Szene D02 beim Betreten der Marktgasse vor Schmiede und Fuhrplatz (x 12–26, Zeilen 32–33): Bera und der Fuhrmann Wendel streiten neben dem leeren Wagen. Lehrt **Werkzeuge** und **Lagerbuch**. Alternativ startet der Streit über Beras oder Wendels **Arbeit**. Ohne Streitkenntnis bleiben Funde still und Orik, Vessa, Pell, Namar und Berthold antworten neutral.
- **Stufe:** kein Kampf, beliebige Stufe.
- **Lösungsweg:** Vier Belegarten sammeln, Reihenfolge egal, Funde sind wiederholbar:
  1. **W (Ware = Musterblatt):** Arbeitstisch mit Musterblatt in der Schmiede (18, 34) benutzen/umschauen (sechs Äxte, vier Sägen, Werkzeichen: offener Kreis mit zwei Zacken) und die Ware an Vessas Stand (30–31, 28) ansehen. Erst beide zusammen ergeben W, der zweite Fund nennt den Vergleich.
  2. **L (Lagerbuch):** Lagerbüro, Tür (19, 24) im Lagerhof. Pult mit dem Lagerbuch (Innenraum 4, 3): Wendel als Abholer eingetragen, Randnotiz von Pell. Lehrt **Wendel** und **Pell**.
  3. **K (Kaufbeleg):** Vessa nach **Arbeit** oder **Werkzeuge** fragen (lehrt **Pell**, **Kaufbeleg**), dann **Kaufbeleg**: Vessa zahlte Pell 60 Gold.
  4. **A (Aussage):** Orik am Lagertor (19, 30) nach **Wendel**, **Werkzeuge**, **Handwagen** oder **Pell** fragen (lehrt **Handwagen**): Pell fuhr die Werkzeuge mit dem Handwagen zum Markt. Oder Namar (nur vor dem Beitritt) nach **Ladung**, **Werkzeuge**, **Handwagen** oder **Pell**: Er sah Pell bei Vessa abladen.
  5. Sobald W, L, K und A vorliegen, ist der Fall vollständig (Stufe P). Optional: Pell im Büro (4, 4) nach **Werkzeuge** oder **Pell** fragen, er gesteht und lehrt **Rückzahlung**.
  6. Zu **Berthold** (43, 22), nach **Werkzeuge** oder **Pell** fragen. Ohne alle Belege nennt er nur die fehlenden Belegarten (bestätigt vorhandene). Mit allen Belegen stellt er die Wahl.
- **Wahlen und Enden:**
  - »Entzieht Pell das Lager.« (OFF): Zusammenkunft am Brückenkopf, Pell muss gehen (verschwindet aus dem Lagerbüro), Bera zahlt 45 Gold.
  - »Ich vermittle Rückzahlung und Aufsicht.« (EIN): Pell zahlt Vessa zurück, bleibt unter Aufsicht im Büro, Bera zahlt 40 Gold und 2 Rationen.
  - »Ich spreche erst mit den Beteiligten.«: bindet nichts, die Wahl kommt beim nächsten Gespräch wieder.
  - Beide Enden: Werkzeuge gehen wieder nach Tannried, an Vessas Stand entsteht eine Lücke, Lagerbuch zeigt Bertholds Berichtigung, Begrüßungen und Abschlusssätze von Bera, Wendel, Vessa, Orik, Berthold, Namar ändern sich.
  - **Verzahnung Tannried:** Nach dem Abschluss setzt jedes Verlassen von Dreifurt die Lieferung in Gang. Die nächste Ankunft in Tannried zeigt einmal die Ankunft der Werkzeuge (je nach Stand von Q04 Abladen am Holzplatz oder Kisten ins Versammlungshaus).
- **Belohnung:** 100 EP je lebendes Mitglied (einmal), 45 Gold (OFF) bzw. 40 Gold + 2 Rationen (EIN).
- **Zum Testen:** Belege in beiden Reihenfolgen, drei von vier Belegen ohne Wahl, das Wort **Pell** allein bei Berthold gibt nur eine Ortsauskunft, Namar vor/nach Aufnahme, Orik als Ersatz, Lohn genau einmal, Vessas Lücke und Pells Abwesenheit nach Speichern/Laden. Wendel nennt bei **Karrweg** die Ziegen im Fels (Hinweis für Q20).

### E03 Die letzte Nacht im Zollhaus · 🟢 OPTIONAL
- **Auslöser:** Hella nach **Arbeit**, dann **Zollhaus** (»im alten Zollhaus … an der aufgegebenen Brücke westlich der Stadt«) oder einfach den Ort finden: Hoftor Weltkarte (210, 197), Abzweig von der Straße Mühlbrück–Dreifurt (Zeile 199), also kurz vor dem Westtor. Beim ersten Betreten des Tors: Blick auf Turm, Brückenrest, Waage, Herdfeuer (lehrt **Zollhaus**). Das Journal beginnt mit Hellas Hinweis oder bei Edda.
- **Stufe:** Stufe 2–3. Z1: 2 Kellerspinnen (Stufe 1). Z2: Große Kellerspinne (Stufe 3) als Anführer + 1 Kellerspinne. Keine Anpassung an die Gruppengröße, furchtlos, keine Beute. Balance-Test: Brydan Stufe 2 mit Korgar und Tavion gewinnt beide fast immer (Z2 mit ~81 % LP übrig), ein vorbereiteter Soloheld (Stufe 2, Kämpfer, Lederkappe) gewinnt Z1 sicher, Z2 nur etwa jedes zweite Mal.
- **Lösungsweg:**
  1. Turmtür Weltkarte (211, 187) im Hof. In der Halle stehen **Edda** (3, 3), **Marten** (10, 5) und **Selke** (6, 8). Edda: **Name**, **Arbeit** (lehrt **Werkzeuge**, **Lohn**), **Keller** oder **Spinne**: einmaliges Angebot »Ich sehe nach einem sicheren Zugang.« / »Ich muss weiter.« (keine Bedingung, nur Ton).
  2. Barrikade vor der Kellertreppe (1, 2) benutzen: »Einen Durchgang freiräumen« (kein Schlüssel, keine Probe).
  3. Kellertreppe (1, 1) hinab. Treppenabsatz, dann Vorkeller: Betreten löst Z1 aus (Flucht auf den Absatz oben). Danach Rückkehr zu Edda möglich (eigene Begrüßung, Teilstand).
  4. An den Zugängen (11–12, 5 und 11–12, 10) Hinweiszeile, Betreten des Lagerraums löst Z2 aus (Flucht in den Vorkeller 5, 5).
  5. Zughebel an der Säule (20, 5) ziehen: Gitter fällt vor den Bruch in der Ostwand (23, 7).
  6. Arbeitskisten (19–21, 12): »Für die Arbeiter sichern« (optional, sonst holt Edda sie).
  7. Kiste mit Gebührenstempel (14, 3): »Mitnehmen« / »Liegen lassen« (bei vollem Gepäck bleibt er liegen). Keine Wirkung auf andere Quests.
  8. Zurück zu Edda: Sind beide Gruppen besiegt und das Gitter verriegelt, löst das Ansprechen den Abschluss aus (ohne gesicherte Kisten zuerst »Ich komme mit bis zu den Kisten.«).
  9. Optional: Holzleiter in der Mauernische (12, 1) zur Dachkammer, Tür zur Dachplattform (Wand 7, 3): Umschau über Fluss und Dreifurt.
- **Wahlen und Enden:** Nur ein Ende. Flucht aus Z1 oder Z2 lässt besiegte Gruppen besiegt, offene bleiben offen. Gitter kann auch vor dem Gespräch mit Edda verriegelt werden.
- **Belohnung:** 70 EP je Mitglied und 20 Gold (einmal). Kampf-EP gering (bei 4 Köpfen etwa 6 + 11 je Kopf). Gebührenstempel (Wert 2).
- **Zum Testen:** Nach dem Abschluss stehen die drei mit gepackten Kisten im Hof; wer den Hof durch das Tor verlässt, sieht sie aufbrechen (Protokollzeile), danach liegt ein Packtuch am Feuer. Speichern/Laden zwischen Z1 und Z2. Verzahnung Startdreieck: Die Dachplattform ist eine Peilstelle für Q24 (Winkelbrett, 30 EP, deckt die Weidenkehre auf der Karte auf, Rauch je nach Q19).

### Q21 Die Wette der Kinder · 🟢 OPTIONAL
- **Auslöser:** Nordufer, Nordzeile: Ida (47, 6) und Mats (49, 6) vor dem leeren Bäckerhaus östlich des Nordtors ansprechen oder die Bäckerhaustür (48, 4, Zugang von 48, 5) benutzen. Die Szene nennt Wette und Einsatz: Ida wettet auf einen Geist, Mats auf nichts. Gewinner bekommt beide Einsätze (Idas Drachenzahn, Mats' Holzschwert Donnerklinge), Verlierer muss Hauptmann Berthold fragen, ob er im Bett den Helm trägt. Lehrt **Wette**, **Geist**, **Helm**, **Bäckerhaus**. Ohne die Szene kommt niemand ins Haus.
- **Stufe:** Kampf (optional) gegen Mardermutter (Stufe 3) und 3 Jungmarder (Stufe 2), ab 5 Kämpfern ein vierter. Ohne Tote, Ziel: die Mutter zu Boden. Balance-Test: Gruppe Stufe 4 (Held + Korgar, Tavion, Namar) 16/16 Siege, Soloheld Stufe 3 verliert immer (folgenlos).
- **Lösungsweg:**
  1. Ins Bäckerhaus. Spuren umschauen: Tresen (Kinderhandabdruck), Ofen (Eierschalen), Mehlspur (fünf Zehen, Schleifspur), Säcke.
  2. Erster Schritt durch den Durchgang (7, 5) in die Backstube: Ofenklappe scheppert, etwas Weißes flitzt die Leiter hinauf.
  3. Leiter (5, 1) zum Dachboden, Ankunft (5, 2). Zum Laken (9, 4) gehen (acht Felder drumherum lösen aus) oder es benutzen: Das Laken rutscht, darunter Marder voller Mehl. Lehrt **Marder**.
  4. Wahl: **Zuschlagen** (Kampf), **Eine Ration in die Giebellücke legen** (kostet 1 Ration; ohne Ration fragt das Spiel sofort neu), **Namar fauchen lassen** (nur mit Namar in der Gruppe), **Erst einmal nicht** (Wahl bleibt, Haufen oder Nest erneut benutzen).
  5. Nest (11, 1) durchsuchen: Gesas Socken, Silberlöffel, lehrt **Socken**.
  6. Zurück zu den Kindern und das Urteil sprechen.
- **Wahlen und Enden:**
  - »Marder. Eine ganze Familie.« (Wahrheit): beide verlieren, beide müssen zu Berthold, Gruppe bekommt Drachenzahn und Donnerklinge.
  - »Ein Geist, weiß und ohne Gesicht.« (Lüge): Ida gewinnt, nur der Drachenzahn geht an die Gruppe.
  - »Nichts. Das Haus ist leer.« (Lüge): Mats gewinnt, nur Donnerklinge geht an die Gruppe.
  - »Später«: nichts.
  - Kampf verloren: Gruppe erwacht geheilt auf der Gasse (48, 5), beliebig wiederholbar. Flucht: die Leiter hinab.
- **Belohnung:** 40 EP je Mitglied (einmal, jedes Urteil). Kampf-EP (bei 4 Köpfen ~18 je Kopf). Drachenzahn (Hals, Glück +2) und/oder Donnerklinge (Holzschwert 1W3), Silberlöffel (Wert 12), Gesas Socken (für Q22). Mit Namar: Loyalität +2.
- **Zum Testen:** Nachhall: Berthold auf **Helm** je nach Urteil, Tilda (Wachhof) auf **Marder** (die Wurst aus der Wachstube), die Kinder wetten danach um Neues. Kommentare von Namar, Korgar, Tavion. Bei voller Gruppe geht ein Einsatz mit Meldung verloren. Ergebnisse auf Gasse und Dachboden in Ego und Iso ansehen (Kindergröße, Mehlboden).

### Q18 Die Probe auf dem Wachhof · 🟢 OPTIONAL
- **Auslöser:** Berthold **Arbeit**, dann **Wachhof** (lehrt **Probe**), oder einfach die Tür des Wachhauses ganz im Osten am Brückenkopf (52, 23, von Westen 51, 23) benutzen. Im Hof steht **Tilda** (2, 7) bei der Tür.
- **Stufe:** Stufe 4 empfohlen. Gegner: Tilda (Stufe 5, 52 LP), 3 Wachleute mit Übungsspeer (Stufe 3, Reichweite 2), 1 Schleuderer (Stufe 2). Keine Kampf-EP. Balance-Test (Held + 3 Gefährten): Stufe 3 6/16, Stufe 4 13/16 Siege.
- **Lösungsweg:**
  1. Tilda ansprechen: „Reden“ (**Arbeit**, **Probe**, **Wachhof**), „Zur Probe antreten.“, „Gehen“.
  2. Kampf ohne Tote: Die Gruppe beginnt im Westen, Holzwand mit zwei Lücken (Zeilen 4–5 und 10–11), Tilda auf dem Podest im Osten. Ziel: Tilda zu Boden, die übrigen müssen nicht fallen.
  3. Nach dem Sieg zu Berthold, **Arbeit**: Er gibt beide Aufträge (lehrt **Weidenkehre** und **Karrweg**).
- **Wahlen und Enden:** Niederlage oder Flucht: Heilung, freundlicher Spott, beliebig wiederholbar, keine EP. Wer Q19 oder Q20 schon vorher erledigt und gemeldet hat, bekommt die Aufträge ohne Probe; Tilda bietet die Probe trotzdem an, Lohn dann genauso (einmal).
- **Belohnung:** 80 EP je Mitglied, 30 Gold, Heilung. Wachleute grüßen danach.
- **Zum Testen:** Korgar kommentiert die stumpfen Speere. Figuren des Hofs verschwinden während des Kampfs und kehren danach zurück. Speichern/Laden im Kampf.

### Q19 Der stumme Posten · 🟢 OPTIONAL
- **Auslöser:** Berthold **Weidenkehre** (nach der Probe oder ohne Auftrag): Der Posten schickt seit sechs Tagen keinen Boten. Ohne Auftrag findet man ihn auch selbst: zerschlagener Botenkarren an der Küstenstraße bei Weltkarte (232, 175), knapp nordwestlich des Nordtors (lehrt **Weidenkehre**, Pfeile alle von Norden).
- **Ort:** Palisade nördlich der Küstenstraße, Weltkarte 199–213, 153–164. Tor im Süden (206, 164), Bresche im Norden (209, 153), Plattform (Höhe 3) im Nordwesten mit Ulf. Goblinlager nördlich im Gebüsch (Gruppe bei 208, 140, Unterstand 207, 138).
- **Stufe:** Stufe 4–5. Hofkampf: Goblin-Kriegsführer (Stufe 5), 3 Goblin-Räuber, 1 Goblin-Bogner (Stufe 3), ab 5 Kämpfern ein Räuber mehr. Zweiter Haufen (Lager): Goblin-Schamane, 2 Goblin-Bogner, 1 Goblin-Räuber (Stufe 3), ab 5 Kämpfern ein Räuber mehr. Balance-Test (Held + 3, Stufe 4): Hof gestürmt 16/16, mit Horn 15/16, zweiter Haufen danach 12/16 (Ulf fällt in den übrigen). Der Doppelkampf ohne Rast ist schwerer als die Zahlen.
- **Lösungsweg (gründlich):**
  1. Botenkarren (232, 175) ansehen.
  2. Zuerst das Goblinlager nördlich ausheben (normale Kartengruppe, Kontaktkampf, Anschleichen möglich).
  3. Unterstand (207, 138) benutzen: Goblinhorn und 25 Gold (lehrt **Horn**).
  4. Zum Tor (206, 164): Ulf ruft von der Plattform. Wahl: „Hineinstürmen.“, „Das Goblinhorn blasen.“ (nur mit Horn und geräumtem Lager), „Noch nicht.“
  5. Mit Horn: Die Goblins rennen zur Bresche und drehen dem Tor den Rücken zu (Überraschung für die Gruppe). Ziel: Ulf (Verbündeter, Schütze auf der Plattform, 22 LP) muss überleben.
  6. Zurück zu Berthold, **Weidenkehre** melden.
- **Wahlen und Enden:**
  - Ohne Lager-Vorbereitung: Hofkampf, danach sofort der zweite Haufen als Folgekampf durch die Bresche (ohne Rast). Flucht aus dem Folgekampf: beim nächsten Mal am Tor beginnt gleich der Folgekampf.
  - Lager ausgehoben, gestürmt: nur der Hofkampf.
  - Ulf überlebt: er erzählt (Tiere zogen vom Nordhang zum Fluss, lehrt **Tiere**), geht nach Dreifurt und steht danach im Wachhof (2, 12).
  - Ulf fällt (auch im Folgekampf): Goblins ziehen ab, die Gruppe begräbt ihn. Geringerer Lohn.
  - „Noch nicht.“: zurück auf die Straße (Ulf wartet). Auch die Bresche (209, 153) löst dieselbe Wahl aus.
- **Belohnung:** Mit Ulf 120 EP und 60 Gold, ohne Ulf 60 EP und 30 Gold. Kampf-EP (4 Köpfe) etwa 68 je Kopf im Hof, 47 je Kopf für den zweiten Haufen. 25 Gold im Unterstand. Danach ist der Posten besetzt (Feuer brennt, Bresche geschlossen, zwei Wachen).
- **Zum Testen:** Kommentare von Tavion und Korgar nach dem Sieg. Meldung ohne Probe gibt beide Aufträge (»Tilda muss Euch nicht mehr prüfen«). Plattform in Iso. Die KI-Gruppe nutzt den Horn-Vorteil kaum, beim Spielen sollte er spürbar sein.

### Q20 Die Meute am Karrweg · 🟢 OPTIONAL
- **Auslöser:** Berthold **Karrweg** (»nehmt Euch das Leittier vor«), Wendel **Karrweg** (Ziegen im Fels). Ohne Auftrag: Überfallstelle an der Straße nach Karrfels, Weltkarte (285, 157), durch das Osttor und der Straße nach Nordosten folgen.
- **Stufe:** Stufe 4–5. Leitwolf (Stufe 6, 46 LP) und 4 Wölfe der Meute (Stufe 3), ab 5 und ab 6 Kämpfern je einer mehr, furchtlos. Balance-Test (Held + 3, Stufe 4): Rinne 13/16, Kamm 13/16 (mehr LP übrig).
- **Lösungsweg:**
  1. Wagen (285, 157) und Planenfetzen nach Norden (286, 155 bis 286, 148) verfolgen.
  2. Weg wählen:
     - **Schlucht** (kurz): ab dem Eingang (285–287, 148) startet die Aufgabe automatisch, Auslöser in der Rinne (283–285, 141): Hinterhalt, Wölfe auf beiden Seiten über der Gruppe.
     - **Kamm** (Umweg, besser): Ziegenpfad von der Straße (295, 133) hinauf, über den Kamm (293, 129–130): Die Gruppe steht oben am Kesselrand, das Rudel schaut zur Schlucht (Überraschung für die Gruppe), der Leitwolf liegt abseits im Norden.
  3. Kampf: Fällt der Leitwolf, zerstreut sich das Rudel (Kampf endet). Wer zuerst alle Wölfe schlägt, verdient mehr EP und riskiert mehr.
  4. Bau (285, 124) untersuchen: kein Wurf, frisch aufgewühlte Erde, Flimmern über dem Eingang (verschwindet nach dem Popup).
  5. Bei Berthold **Karrweg** melden.
- **Wahlen und Enden:** Leitwolf zuerst oder alle zuerst; Flucht setzt auf (285, 149) zurück. Nach dem Bericht sind Wrack und Fetzen fort, Wendel fährt wieder.
- **Belohnung:** 110 EP, 50 Gold. Kampf-EP bei vollem Sieg (4 Köpfe) ~60 je Kopf. Beute: Wams aus Wolfsfell (Körper) vom Leitwolf, Wolfsfelle (Chance).
- **Zum Testen:** Tavion kommentiert den Bau. Flimmern ist eine Beobachtung ohne Erklärung (Faden der Hauptgeschichte). In der Nähe an der Karrfels-Straße (Kampfausschnitt um 279–297, 158–174) lauern die „Orks an der Brücke“ (freie Begegnung, Hinterhalt, siehe Freie Begegnungen).

### Die vierte Furt · 🟡 ENTDECKUNG
- **Auslöser:** Kein Auftraggeber, kein Journal. Wohnhaus mit offener Tür am Nordufer, Ortskarte (7, 11), ganz im Westen der Nordzeile. Drinnen **Gesa** (4, 2) am Feuer: **Arbeit** lehrt **Keller**, **Klappern**, **Socken**. **Klappern** lehrt **Großvater** (»Unter der Stadt liegt noch die alte Stadt«).
- **Stufe:** Stufe 4–6, Gruppe von 4–6. K1 Straßengewölbe: 3 Blinde Höhlenlurche (Stufe 4), ab 5 Kämpfern 4, ab 6 Kämpfern 5. K2 Insel (umgehbar): 3 Lurche, ab 5 Kämpfern 4. K3 Wächterhalle (Pflicht): 2 Steinwächter (Stufe 6, 55 LP, furchtlos), ab 6 Kämpfern 3. Balance-Test (Held + Korgar, Tavion, Namar, Stufe 4): Gewölbe 16/16, Insel 16/16, Wächter mit Wasser im Streifen 13/16, auf trockenem Boden 9/16. Soloheld Stufe 5 verliert gegen die Wächter.
- **Lösungsweg:**
  1. Holztreppe (6, 4) in den Keller. Regal (4, 2) benutzen: »Das Regal beiseiteschieben?«. Vermauerung (4, 1): »Die losen Steine herauslösen?«. Bogen benutzen: hinab in den Dungeon.
  2. Abstieg zum Absatz mit Blick ins Straßengewölbe. Betreten des Westufers löst K1 aus (Flucht 9, 9).
  3. Zollhäuschen am Westufer: Hochwassermarken (15, 15), Schalter mit dem Ruf an die Flüchtenden (14, 16), Tafel mit dem Plan der Wehre (13, 18), Kasten des Zöllners (18, 19): Schlüsselbund des Zöllners und 6 Gold.
  4. Über die Stufe (18, 6) in die Wehrkammer. Hebel **Teilwehr** (19, 1) umlegen: Der Altarm fällt, die Furtplatten (22–24, 12–14) liegen frei. Pflicht, sonst kommt man nicht hinüber.
  5. Über die Furt aufs Ostufer, Umgang nach Süden. Optional Hebel **Ablass** (35, 27): Becken läuft leer (knöcheltief oder trocken), Insel erreichbar (K2, Flucht 34, 22), dahinter die Schatznische im Westen (9, 28): 80 Gold, 2 Heiltränke.
  6. Gittertor (34, 32): mit dem Schlüsselbund oder Schloss knacken (Schwierigkeit 60). Befehl an die Wächter am Pfeiler (33, 32) lesen.
  7. Wächterhalle: K3 gegen die Steinwächter (Flucht hinter das Gittertor, 34, 31). Taktik: Ablass zu lassen = knöcheltiefer Streifen vor dem Fluttor verlangsamt die Wächter (Fernkämpfer gewinnen Zeit). Ablass offen = Inselkampf und Schatz, aber Wächter auf trockenem Boden. Den Ablass kann man auch nach den Wächtern öffnen, nichts geht verloren.
  8. Tür der Wachstube (41, 37). Überreste (43, 35), Josts letzte Nachricht auf dem Tisch (45, 35): Abschluss. Truhe (44, 39): Amulett des Fährmanns und 40 Gold.
  9. Treppe (46, 36): »Gemeinsam dagegenstemmen« öffnet die Uferklappe. Ankunft am Nordufer von Dreifurt (12, 13). Die Klappe (12, 14) ist danach ein dauerhafter Zugang in beide Richtungen.
- **Wahlen und Enden:** Beide Hebel umkehrbar. Wer auf dem Ostufer das Teilwehr zurückstellt, flutet die Furt hinter sich, der Ausgang liegt aber ohnehin im Osten. Tiefes Wasser hier ist nicht schwimmbar.
- **Belohnung:** 100 EP je Mitglied (Nachricht, einmal). Kampf-EP (4 Köpfe) ~33 + 33 + 55 je Kopf. Amulett des Fährmanns (Hals, Ausdauer +5, Geschick +2), 40 + 80 + 6 Gold, 2 Heiltränke, Uferklappe.
- **Zum Testen:** Nach dem Sieg über die Wächter Popup „Kette verstummt“, Gesas Begrüßung und **Klappern** ändern sich. Licht: Tageslicht durch zwei Deckengitter im Gewölbe, fahles Licht durch das Fluttor in der Halle. Speichern/Laden mitten im Wehrrätsel. Keine Rastüberfälle.

### Q22 Die letzte Kerbe · 🟢 OPTIONAL
- **Auslöser:** Gesa im Haus der vierten Furt (Tür 7, 11, Stube 4, 2). Zwei Wege hinein: Socken aus Q21 zurückbringen oder direkt nach **Floß** fragen (lehrt man über ihre Antwort auf **Name** oder beim Sockentausch). Das alte Floß liegt auf dem Kai am Nordufer (24–25, 14) und lässt sich jederzeit ansehen (viele Kerben im Steuerpfosten).
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Mit Gesas Socken im Gepäck Gesa nach **Socken** fragen (oder die Socken zeigen/geben): Sie nimmt sie zurück, gibt Hinnerks Schal, lehrt **Floß** (20 EP).
  2. Gesa **Floß**: Hinnerk schnitt für jede Heimkehr eine Kerbe, die letzte fehlt. Sie bittet darum (Journal beginnt).
  3. Floß auf dem Kai (24, 14) benutzen, Rückfrage bestätigen: Die Gruppe schneidet die Kerbe und entdeckt auf der Rückseite des Pfostens ein jedes Jahr nachgeschnittenes G.
  4. Gesa erneut **Floß**: Bericht.
- **Wahlen und Enden:** Ein Ende. Q22 funktioniert auch ohne Socken und ohne die vierte Furt.
- **Belohnung:** 20 EP (Socken) + 30 EP (Bericht) je Mitglied, Hinnerks Schal (Hals, Ausdauer +3).
- **Zum Testen:** Kein Text kündigt das G an. Gesas Begrüßung nach dem Abschluss anders. Bei vollem Gepäck: Schal erneut über **Socken** holen.

### Orkhöhle mit Odrik · 🟡 ENTDECKUNG · 🔵 GEFÄHRTE
- **Auslöser:** Kein Auftrag und kein Journal. Hinweis von Berthold auf **Orks**: Rauch aus einer Felsnische im Granit, ein gutes Stück nördlich. Ort: Nische im Granitmassiv (Weltkarte 227–235, 88–103), die sich nach Norden öffnet. Höhlenmaul in einer kleinen Tasche am Westrand der Nische, an deren Nordseite bei Weltkarte (225, 98), Benutzen von (225, 99). Erkennbar am Orkzeichen (229, 97, gehörnter Schädel, rote Lumpen) und einem Lagerfeuer (230, 100). Man muss das Massiv (etwa x 176–253, y 70–120) umgehen und von Norden in die Nische gehen (welcher Umweg am kürzesten ist: unklar).
- **Stufe:** Stufe 5–7, 4–6 Figuren. Balance-Test: 5 Figuren auf Stufe 6 (Brydan als Kämpfer, Korgar, Tavion, Beric, Haldaar): Wachhöhle, Teich, Spinnen, Murrk, Schlafhöhle meist sicher; Grashaks Halle 6/12 Siege, alter Troll 5/12. Gegner: Ork-Krieger (Stufe 4), Ork-Schütze (Stufe 4), Ork-Schamane (Stufe 5), Grashak (Stufe 7, 75 LP), Murrk (Stufe 3) mit Wolf (Stufe 2), Große Kellerspinnen (Stufe 3) und Kellerspinnen, Alter Höhlentroll (Stufe 9, 300 LP, Rüstung 5, Knochenkeule 3W6). Rasten in der Höhle weckt mit 30 % die Patrouille. In der Nähe auf dem Massiv stehen außerdem freie Höhlentrolle (Weltkarte 191, 110 und 178, 68).
- **Lösungsweg:** Eingang im Osten (82, 27). Kreuzhöhle (40–51, 21–30) ist der einzige Knoten.
  1. **Wachhöhle** (61–81, 21–29): 2 Ork-Krieger am Feuer und ein Ork-Schütze auf dem Absatz (Höhe 5), ab 5 Kämpfern ein Krieger mehr.
  2. **Nordast:** Tropfsteingang mit Speerfalle an der Engstelle (46, 12, Werte 40/45, 2W6). **Teichhöhle** (24–43, 1–11): 2 Ork-Krieger am Ostufer, 2 Ork-Schützen am Westufer (ab 5 Kämpfern ein dritter), erreichbar über die Furt im Norden, durch den Teich oder um den Pfeiler. Sickergang als Schleife zurück. **Barrikade** (22, 11): Geröllfalle (1W6 auf alle), dann Stärkeprobe 40 mit Helfer (Fehlschlag kostet 20 Minuten). **Abstieg**: 2 Große Kellerspinnen + 2 Kellerspinnen (ab 5 eine mehr). **Trollkaverne** (dunkel): Alter Höhlentroll als Kartengruppe (Kontakt). **Trollnische**: Branns Truhe (27, 29), 60 Gold, 2 Heiltränke, Skizzen des toten Erzsuchers Brann.
  3. **Südast:** Lagergang mit Patrouille (Ork-Krieger mit Vorratsschlüssel + 2 Krieger, wandert zwischen Kreuzhöhle und Lagergang) und **Stolperdraht** (47, 35; Werte 35/30, 1 LP; löst er aus, sind die Schläfer wach). **Schlafhöhle** (33–48, 37–45): 2 Ork-Krieger, Ork-Schamane, Ork-Schütze (ab 5 Kämpfern ein Krieger mehr); ohne Alarm Überraschung für die Gruppe. **Vorratskammer** (58–68, 38–46): Verschlag (59, 38) mit dem Schlüssel der Patrouille, Schlossknacken 45 oder von innen über den Kriechgang ohne Schlüssel. Kisten: Odriks Habe (Keule, Lederrüstung, 40 Gold, Gegengift, Heiltrank), 3 Fackeln und einmal 6 Rationen, eine Kiste mit Giftnadel (45/45, 1W4 und vergiftet), eine verschlossene (Knacken 40).
  4. **Grubenhöhle** (23–35, 42–48): Murrk mit Wolf. Odrik im Käfig (27, 48) stellt sich vor. Wahl: **Ihm freien Abzug anbieten** (Charisma 45, mit Korgar oder Z'zarek 35, mit Hilfe), **Ihm drei Rationen geben** (ohne Probe, verrät dazu den Stolperdraht), **Angreifen**, **Zurückweichen**. Geht Murrk, legt er den Käfigschlüssel hin und verrät: Grashak hat einen Schamanen, aus der Schlafhöhle führt ein Schleichgang direkt neben den Thron.
  5. **Odrik befreien:** Odrik ansprechen, Schloss mit Käfigschlüssel oder Knacken 50. Popups (Grubenretter, Suche nach Brann, Warnung vor Grashak), dann Beitritt. Bei voller Gruppe wartet er im Dreifurter Gasthaus.
  6. **Häuptlingshalle** (5–19, 36–48): Grashak auf dem Podest, Ork-Schamane, 2 Ork-Krieger, Ork-Schütze (ab 5 Kämpfern ein Krieger mehr). Zweiter Zugang über den Schleichgang neben dem Podest. Kriegskasse auf dem Podest: Kriegsschlüssel von Grashak oder Knacken 65.
- **Wahlen und Enden:** Reihenfolge der Äste frei. Murrk friedlich oder Kampf (flieht er, liegt der Schlüssel trotzdem da). Troll ist optional. Besiegte Gruppen kommen nicht wieder.
- **Belohnung:** Kampf-EP bei 4 Köpfen je Kopf etwa: Wache 36, Teich 47, Spinnen 23, Patrouille 25, Schlafhöhle 53, Grashak 108, Troll 100. Murrk friedlich 15 EP. Beute: Grashaks Zweihandaxt (2W6+1, Stärke 35), Kriegsschlüssel, Heiltrank; Troll: Trollzahn am Lederriemen (Hals, Kondition +5, Stärke +2), 2 Heiltränke; Kriegskasse 150 Gold, 2 Heiltränke, Brandflasche; Branns Truhe 60 Gold, 2 Heiltränke; Odriks Habe 40 Gold. Gefährte Odrik.
- **Odrik — GEFÄHRTE:** Zwerg, Weißmagier Stufe 5, Zwergisch, Gemeinsprache, Orkisch, kommt ohne Ausrüstung. Nach dem Beitritt bittet er, in ein Gasthaus mitgenommen zu werden: Betritt die Gruppe mit ihm ein Gasthaus (Zum Brückenbogen in Dreifurt, Zur Bachbrücke in Mühlbrück) oder holt sie ihn bei einem Gasthausdienst ab (Hanne, Hella, Runa, Weda), zieht er sich einmal um (»Ah, endlich wieder frische Kleidung ohne Ork-Gestank …«): neue Figur und neues Portrait, Schuppenpanzer (leicht, Rüstung 3) und Heilerkolben (einhändig 1W6+2, Durchschlag 1, INT +1, Heilung +10 %, bis 19.11.2026 der Heilerstab) werden angelegt.
- **Zum Testen:** Korgar kommentiert das Orkzeichen. Odrik kommentiert Brann, wenn er beim Fund dabei ist; erzählt man es ihm vorher, reagiert er bei der Befreiung. Überraschung in der Schlafhöhle mit/ohne Alarm. Befreiung bei voller Gruppe und Umziehen im Gasthaus. Offen laut Projektstand: Schlafhöhle geweckt leichter als gedacht. Odrik und Korgar sind Rivalen (Freunde und Rivalen): Bei der Befreiung erzählt eine kurze Szene davon. Hat man Murrk mit Korgar in der Gruppe gehen lassen, merkt Odrik sich das (+5).

### V01b Bertholds Meldungen von den Wegen (Dreifurt-Seite) · 🟢 OPTIONAL
- **Auslöser:** Unruhestufe 1 und höher (ab dem ersten Relikt). Berthold auf **Reisewege** lehrt zusätzlich **Moosfels**, Hella hat je Stufe ein eigenes Gerücht (Stufe 1 Ladungen am Moosfels, Stufe 2 Streifen auf der Nordroute, Stufe 3 Flüchtlinge im Gasthaus).
- **Lösungsweg:** Berthold nimmt Meldungen über Wörter an (jeweils nach Abschluss am anderen Ort): **Moosfels** (W01, 25 Gold, 20 EP), **Brandhof** (W05, 25 Gold, 20 EP; ab Stufe 2 lehrt **Brandhof** das Wort **Bande**), **Goblinbau** (Q26, 60 EP), **Alte Esse** (Q08 Karrfels, 30 EP).
- **Belohnung:** wie oben, je einmal.
- **Zum Testen:** Ab Unruhestufe 2 steht Thies (W05, Brandhof) am Markt (37, 33), bis er zurückgekehrt ist. Details in den Abschnitten der jeweiligen Orte.

### Freie Begegnungen um Dreifurt · 🟡 ENTDECKUNG
- Ratten (6 Ratten, Stufe 1) südlich der Stadt, Weltkarte (232, 211). Goblin-Trupp (Stufe 1–3) an der Straße von Mühlbrück, (198, 209). Wildschweine (Keiler Stufe 5, Bachen Stufe 3), (259, 214). Zwei Höhlentrolle (Stufe 5) im Granitmassiv, (191, 110) und (178, 68). Orks an der Brücke (Hinterhalt) an der Karrfels-Straße bei etwa (291, 169).

---

**Offene Enden / Rückkehr später**
- **Odrik** umziehen lassen: einmal mit ihm ein Gasthaus betreten (Dreifurt oder Mühlbrück).
- **Q02** abgeschlossen: Die Lieferung erreicht Tannried bei der nächsten Ankunft dort (Verzahnung mit Q04).
- **Vessa:** Nach Glockenwacht (Q14, Brackhafen) Briefe mit grünem Siegel bei ihr abgeben (**Briefe**).
- **Berthold:** Meldungen zu Alte Esse (nach Q08 Karrfels), Goblinbau (Q26), Moosfels (W01), Brandhof (W05) nachholen.
- **Hella** und **Berthold** haben je Unruhestufe neue Antworten auf **Reisewege**. Ab Unruhestufe 2 steht Thies am Markt (W05).
- **Orwin** auf **Flimmern** und **Hüter**: erster Bericht, Wendepunkt mit den drei Orten der Hüter, Auswertung nach jedem Relikt (Kapitel 1, „Das Flimmern“).
- **Zollhaus-Dach** als Peilstelle für Q24 (Startdreieck), Ergebnis hängt von Q19 ab.
- **Q21-Nachhall:** Berthold **Helm**, Tilda **Marder** jederzeit nach dem Urteil.
- **Vierte Furt:** Uferklappe (12, 14) bleibt dauerhafter Zugang, Ablass kann nachträglich geöffnet werden (Insel, Schatznische).

---

## Kapitel 3 · Tannried, Werkhof und Tannwald

**Anreise:** Tannried liegt rund 70 Felder südlich von Mühlbrück im Tannwald, ein Holzort hinter einer Palisade aus senkrechten Stämmen.
- Von Mühlbrück aus über das Südtor (Weltkarte (149, 205)) und die Straße nach Süden zum **Nordtor** Weltkarte (148, 270). Auf der Ortskarte kommt man im Norden (12–13, 0) an.
- Von Dreifurt (Südtor) bzw. Karrfels über die Oststraße: Die Straße gabelt sich bei Weltkarte (205, 258) und führt über (190, 270) und (172, 276) zum **Osttor** Weltkarte (154, 272). Auf der Ortskarte ist das der Ausgang Nordost (41, 6–7).
- Das **Südwesttor** Weltkarte (142, 278) führt in den Tannwald, auf der Ortskarte ist es der Waldpfad am Westrand (0, 29).
- Der **Werkhof** (Sägewerk) ist eine eigene Karte hinter Tannried und nur aus dem Ort zu erreichen: über den **Werkweg** am Ostrand (41, 16–17), hinter dem Holzplatz, oder über den **Holzlagerweg** (41, 27) vom Meilerplatz im Südosten. Auf der Weltkarte ist er die Bretterscheune als Ausbuchtung im Südosten des Stempels (155–157, 277–279), betreten kann man ihn dort nicht.
- Ortsplan Tannried (61 × 34): Holzplatz in der Mitte (14–27, 12–20) mit Runa (20, 14). Im Westen die Wohnhäuser und das **Versammlungshaus** (Tür 10, 14), im Osten **Bennos Stube** (Tür 32, 13, an der Südseite des Hauses). Im Süden der Meilerplatz (14–26, 23–30) mit drei Meilern und Asta (20, 27).

**Wann:** Im gründlichen Durchlauf direkt nach Mühlbrück und Dreifurt, sobald Korgar und Tavion dabei sind (Namar aus Dreifurt hilft spürbar). Werkhof und Holzbruch auf Stufe 2–3. Den Werkhof hat der Balance-Test mit einer Dreiergruppe auf Stufe 2 gemessen, allein ist er nicht zu schaffen. Die Kohlenfuhre (Q25) kommt erst nach dem Werkhof, ab Stufe 4 und am besten zu viert. Das leere Nest (Q26) braucht Stufe 5–6, die Trommelhalle nimmt man nur vom Sims aus.

**Dienste:**
- **Runa** am Holzplatz (20, 14) bietet beim Ansprechen „Reden“, „Schlafen und Proviant“ (2 Gold je Mitglied für die Nacht, 1 Gold je Ration) und „Gepäck verwahren“. Ein Gasthaus, einen Händler, einen Tempel oder eine Gilde gibt es in Tannried nicht. Für Ausrüstung und Training muss man nach Dreifurt.
- **Weda** im Waldlager (Weltkarte (183, 283)) bietet nach dem friedlichen Ende von E05 „Am Feuer rasten und Proviant“ an (1 Gold je Nacht, 1 Gold je Ration).
- **Ortrun** (Weltkarte (253, 315)) kauft Wolfsfelle, immer vier auf einmal für 30 Gold (siehe V01a).
- Stumme Ortsfiguren mit einer Protokollzeile: der Holzhauer (16, 18), der Mann mit der leeren Schubkarre (28, 17) und der Torposten am Werkhof-Kulissenrand, solange W1 nicht besiegt ist.

**Gefährten:** In Tannried und im Tannwald wirbt man niemanden an. Ihre Kommentare geben hier Korgar (Werk, Rückkehr, Holzbruch, die Alten im Goblinbau), Tavion (Familiensteine, Flimmern, Wagen der Kohlenfuhre, Spuren im Goblinbau, Spalt vom Hochsitz), Namar (Vertrag, die Alten) und Odrik (Barrikade im Goblinbau), jeweils nur, wenn sie dabei und handlungsfähig sind.

---

### Ankunft in Tannried · 🟡 ENTDECKUNG
- **Auslöser:** Beim ersten Betreten des Holzplatzes kommt die Ortsbeschreibung (T01), einmal je Spiel.
- **Stufe:** keine Kämpfe im Ort.
- **Lösungsweg:**
  1. Runa (20, 14) ansprechen und „Reden“ wählen. Ihre Begrüßung lehrt **Werkhof**, **Zugänge** und **Besetzung**.
  2. Umschauen lohnt an Holzstapeln, Tränkebottich, Bretterstapeln, Meilern, an der Werkbank in Bennos Stube, an den Strohlagern im Versammlungshaus und an Runas Abrechnungsbuch im Versammlungshaus. Der Text des Buches ändert sich mit Q03 und Q25.
  3. In Bennos Stube (Tür 32, 13) liegt auf dem Tisch (5, 6) die **Abschrift** des Vertrags, offen zugänglich (siehe Q03).
- **Zum Testen:** Kulissenklick auf den Werkhof-Anfang ab Spalte 41: Ein Klick läuft zum passenden Ausgang (Weg nach Norden zum Ausgang Nordost, Hof zum Werkweg, alles ab Zeile 23 zum Holzlagerweg), kein Schritt endet in der Kulisse.

### Q03 Das besetzte Sägewerk · 🟢 OPTIONAL (Hauptstrang des Startdreiecks)
- **Auslöser:** Runa nach **Arbeit** fragen: Sie erzählt von der Besetzung, lehrt **Werkhof**, **Kord**, **Werkzeuge** und **Besetzung**, und das Werk gilt als entdeckt. Danach nach **Werkhof**, **Vertrag**, **Geliehenes Geld**, **Noch offen**, **Kords Aufschlag**, **Benno** oder **Kord** fragen: Damit bittet sie ausdrücklich um Hilfe, die Aufgabe steht im Journal und der Vertrag ist bekannt. Man kann aber auch ohne Runa einfach zum Werkhof gehen. Dann starten der Blick am Werkweg (T02), der Blick vom Holzlagerweg oder Kord am Tor die Aufgabe. Fragt man nach **Zugänge**, erklärt sie Tor und Zaunlücke.
- **Stufe:** Stufe 2–3, mindestens zu dritt. Gegner:
  - W1 Tor: 2 Torwachen (Stufe 1, 16 LP).
  - W2 Sortierplatz: 2 Eintreiber (Stufe 3, 20 LP, Handbeil) und 1 Schleuderer (Stufe 1).
  - W3 Ladesteg: 1 Bogenschütze (Stufe 3) und 1 Eintreiber.
  - W4 Werkhalle: **Kord** (Stufe 6, 50 LP, Rüstung 3, Bossgegner, weicht nie, trägt einen Heiltrank) und 2 Eintreiber.
  - Balance (Balance-Test: Brydan Stufe 2 ohne Klasse mit Korgar und Tavion, je Kampf volle LP): W1 20/20 Siege. W2 19/20 mit 42 % LP übrig. W3 20/20 mit 74 %. Kord nur 9 von 20 Siegen mit 11 % LP übrig. Ein Soloheld auf Stufe 2 schafft W2 und W4 nie.
- **Lösungsweg:**
  1. Optional zuerst zu **Benno** in die Stube (Tür 32, 13). Er spricht ohne Auftrag mit dir. **Arbeit** bzw. **Reparatur** erzählen von der gebrochenen Sägeführung. **Geliehenes Geld** und **Vertrag** erzählen, dass er die Unterschrift ohne die anderen geleistet hat. **Noch offen**, **Kords Aufschlag** und **Kord** nennen die 40 Gold Restschuld und die nie vereinbarten 20 Gold je Fuhre. Dann die Abschrift auf seinem Tisch (5, 6) lesen. Kennt der Held die Abschrift, berichtet er sie Runa später selbst.
  2. **Werkhof betreten** über den Werkweg (Tannried (41, 16–17), Ankunft am Westrand des Werkhofs (0, 19–20)) oder den Holzlagerweg (Tannried (41, 27), Ankunft Werkhof (0, 30)). Am Werkweg kommt T02 (zwei Bewaffnete am Tor, eine Gestalt auf dem Ladesteg), dazu Korgars erster Kommentar.
  3. **Kord am Tor (optional):** Die Torwachen am Pfosten (6, 19) benutzen. Kord kommt heran und spricht mit dir. Kennst du die Abschrift oder das Original, hält der Held ihm vor, dass im Vertrag mit Holz bezahlt wird. Danach wählt man »Ich sehe mir das erst an.« oder »Gebt den Hof frei.«. Auf die zweite Antwort droht er, ein Kampf folgt aber nicht. Kord geht zur Halle zurück, später antwortet ein Torposten.
  4. **W1:** Den Kampf löst die Torengstelle (6, 20–21) aus, alternativ die Lücke im Südzaun am Holzlager (11, 26). Jeder Weg hat seine eigene Aufstellung. Nach dem Sieg meldet das Protokoll W02 (»Weiter hinten klappert eine Waffe gegen Holz«), dann kommt die Wahl:
     - **„Stellung halten“:** sofort der zweite Kampf gegen W2, das aus der Biegung anrückt (keine zweite Gruppe, dieselbe W2).
     - **„Zum sicheren Weg zurückziehen“:** Die Gruppe steht auf dem Querweg (17, 22), W2 wartet hinter den Stapeln am Sortierplatz (20–31, 3–12). Empfohlen, wenn die LP knapp sind: zurück nach Tannried und bei Runa schlafen.
  5. **W2 umgehen (möglich):** Vom Querweg durch die Gasse (19–31, 17–20) zum Hallenvorplatz (32–43, 13–20). So erreicht man Halle und Vertrag auch bei besetztem Werk. Am Querweg vor der Biegung (18, 9–13) warnt das Protokoll, solange W2 da ist.
  6. **W3:** Sie löst der ganze Vorplatz aus, der Steg und, wenn W2 besiegt ist, auch der Fuß von Aufgang A (32, 7–8). Der Bogenschütze steht oben auf dem Ladesteg (40, 6). Flucht führt in die Gasse (24, 18).
  7. **Werkhalle:** Die breite Tür liegt in der Westwand (33, 22–23), man erreicht sie über die Gasse (31–32, 21–23) vom Vorplatz. An der Schwelle kommt W05: Kord stellt sich dir in den Weg (»Ich bin Kord. Hier geht Ihr nicht weiter!«). Dahinter löst die ganze Halle **W4** aus. Kord ist der erste Bossgegner: vorher rasten, Tränke bereithalten, Fernkämpfer hinter dem Sägegatter.
  8. **Vertragspult** (Halle (16, 13), am Ende der Halbwand) benutzen: Vertrag und Kords Forderung liegen dort, dann **„Beide Blätter mitnehmen“** wählen (nicht „Liegen lassen“). Hast du die Abschrift gelesen, merkt das Protokoll an, dass Kords loses Blatt bei der Abschrift fehlte. Namar kommentiert.
  9. Ist die letzte Zone besiegt, kommt W06 (»Der Widerstand im Werk ist gebrochen« bzw. mit Geflohenen »Die letzten Bewaffneten ziehen sich … zurück«).
  10. **Rückkehr der Arbeiter (genau einmal):** Entweder am Werkzugang (Tor, Lücke, Werkweg oder Holzlagerweg vor dem Zaun) kommt Runa an und hört den Bericht, oder du sprichst Runa am Holzplatz an und berichtest dort. Es folgt der gemeinsame Gang durchs Werk mit Korgars Hinweis auf die Wege zwischen den Stapeln. Danach arbeiten ein Arbeiter am Sägegatter und einer mit Schubkarre im Stapelhof.
  11. **Aussprache:** Runa nach **Werkhof** oder **Vertrag** fragen, mit dem Original im Gepäck. Fehlt das Original, verweist sie auf das Schreibpult. Dann kommt die Wahl (siehe unten).
- **Wahlen und Enden:**
  - »Sprecht Ihr es vor allen an.«: Runa legt im Versammlungshaus die Blätter vor und erklärt Bennos Unterschrift.
  - »Helft Benno, es selbst zu erklären.«: erst ein Vorgespräch, dann erklärt Benno es selbst vor den anderen.
  - »Ich komme später darauf zurück.« bindet nichts.
  - Beide Enden geben denselben Lohn. Danach führen Runa und Benno das Buch im Versammlungshaus gemeinsam, und die Restschuld von 40 Gold bleibt. Benno ist danach mit Namen bekannt und grüßt je nach Ende.
  - Verzahnung: Q03 abgeschlossen schaltet **Q25 Die Kohlenfuhre** frei. Hasko (E05) und die Lieferung (Q02-Nachhall) reagieren auf den Werkstand.
  - Fluchten: Aus jeder Zone landet man auf der schon sicheren Seite, ohne Lohn. Die Zone bleibt besetzt.
- **Belohnung:** 150 EP je lebendem Mitglied, 50 Gold und 4 Rationen, einmal. Kampf-EP: W1 30, W2 85, W3 70, W4 220, zusammen 405 (bei vier Köpfen rund 100 je Kopf). Dazu Gold der Gegner (Kord 2W6+10) und Kords Heiltrank.
- **Zum Testen:**
  - Speichern und Laden mitten im Verstärkungskampf W2, die Kette läuft danach weiter.
  - Holzlagerweg mit Rückzug und W2 erst am Sortierplatz.
  - Die Reihenfolge Vertrag zuerst: W1, Rückzug, W2 umgehen, W3, Halle, Pult, W2 zuletzt.
  - Runa kennt einen Teilstand nur, wenn der Held berichtet. Mit dem Original vor W2 kehren die Arbeiter nicht zurück.
  - Kords Antwort mit und ohne Vertragskenntnis.
  - Lesbarkeit von Ladesteg, Geländer und Aufgängen in Ego, Draufsicht und Iso.
  - Spielzeit (Plan 60–85 Minuten).
  - Runas Name ist erst nach der Rückkehr bekannt, vorher fragt man nach **Name**.

### Beras Werkzeuge kommen an (Lieferung) · 🟡 ENTDECKUNG
- **Auslöser:** Die Aufgabe „Die vermisste Werkzeuglieferung“ (Q02, Dreifurt) ist abgeschlossen, egal mit welchem Ende. Danach Dreifurt verlassen und Tannried über eines der drei Tore betreten. Ohne Q02 kommt nie etwas an.
- **Stufe:** keine Kämpfe.
- **Lösungsweg:** Einfach ankommen. Ein Fuhrknecht mit Wagen steht am Holzplatz (20, 19 bzw. 21–22, 20) und bringt Beras Werkzeuge mit ihrer Nachricht. Was dann passiert, hängt vom Werkstand ab:
  - Werk noch besetzt: T03, die Kisten kommen ins Versammlungshaus (11–12, 9).
  - Werk sicher, Arbeiter noch nicht zurück: Die Kisten werden am Holzplatz (24–25, 17) abgeladen. Die spätere Rückkehrszene nimmt sie mit.
  - Arbeiter zurück: T04, der Wagen fährt weiter zum Werk, und am Sägegatter steht ein neues Blatt.
- **Wahlen und Enden:** keine. Runa antwortet auf **Werkzeuge** und **Arbeit** je nach Lieferstand (vorher: »Hier ist noch nichts angekommen.«). Fuhrknecht und Wagen bleiben, bis du Tannried verlässt.
- **Belohnung:** keine (reiner Nachhall).
- **Zum Testen:** alle drei Fassungen. Die Kisten wandern bei einer späteren Rückkehr der Arbeiter ins Werk.

### Q04 Die Grenze der Axt · 🟢 OPTIONAL
- **Auslöser:** Es gibt genau zwei Einstiege: das Gespräch mit **Asta** (Köhlerin, Meilerplatz Tannried (20, 27)) oder mit **Ilve** (Harzsammlerin, Weltkarte (105, 272) am Hainrand, unter dem überdachten Tisch). Beide stellen sich in der ersten Begrüßung vor. Jedes Streitthema (**Arbeit**, **Holz**, **Familienhain**, **Grenze**, **Steinplatte**, **Holzfällerhang**, **Ilve** bzw. **Asta**) startet ihren Auftakt und das Journal, und beide Namen werden bekannt. Funde vorher (Platte, Hang) bleiben still und tauchen erst nach dem Auftakt als Notiz auf.
- **Weg in den Tannwald:** Aus Tannried über den Waldpfad (0, 29) bzw. das Südwesttor (Weltkarte 142, 278). Der Pfad führt über (134–141, 278–281) zur Gabel (124, 281) mit dem Wegweiser (123, 282). Von dort geht der Nordpfad (y 280) nach Westen zum Familienhain, die Fahrspur nach Süden zum Holzfällerhang.
- **Stufe:** Kein Pflichtkampf. Der Kampfweg führt über den Holzbruch (siehe unten, Stufe 2–3).
- **Lösungsweg:**
  1. Asta oder Ilve ansprechen, nach **Arbeit** fragen (Auftakt). Asta: Karrfels wartet auf Kohle, vom Hang kommt nichts mehr, am Hain liegt totes Holz, Ilve lässt niemanden heran. Ilve: Der Sturm hat eine Platte der Familiensteine mitgerissen, und sie fürchtet, wer nach Asta kommt.
  2. Bei Asta nach **Goblins** fragen: Ihre Leute sind vor den Goblins am Seitenweg geflohen. Das ist eine Voraussetzung für den Kampfweg.
  3. **Familienhain** (Kuppe 90–99, 267–277, Höhe 2, Eingang durch die Lücke in der Steinreihe bei (100, 268)). Die Grenzplatte (101, 271) bzw. den Wurzelteller (101, 272) ansehen (H1, lehrt **Steinplatte**). Das Loch, in dem die Platte stand, liegt bei (100, 272).
  4. **Platte aufrichten (optional):** Wurzelteller oder Platte benutzen, dann »Wer packt die Platte?«. Es folgt eine Probe Stärke mit Athletik, Schwierigkeit 40, eine zweite Figur hilft. Brydan allein schafft das zu 37 %, Korgar mit Brydan als Helfer zu 59 %. Ein Fehlschlag kostet den Heber 1W4 LP und 30 Minuten, man darf beliebig oft wiederholen.
  5. **Ilves Tisch** (105, 270) ansehen: die Abschrift der Steinnamen (H2), freiwillig. Sie gibt in der gemeinsamen Szene eine Zeile mehr.
  6. Die jeweils andere Seite aufsuchen und ihren Auftakt hören. Fehlt eine Seite, nennt die andere bei **Grenze** ihren Ort.
  7. **Gemeinsame Szene:** Sie öffnet sich, sobald beide Seiten gehört sind und die Platte gesehen ist. Dann Asta oder Ilve nach **Grenze** fragen: Der Held schlägt das Treffen vor, und ein Popup erzählt es mit Abschrift und Tavions Bemerkung zu den abgeriebenen Namen als Zusätzen.
- **Wahlen und Enden** (»Was schlagt Ihr vor?«):
  - **»Die Grenze steht wieder. Nehmt nur das tote Holz davor.«** (Randholz): Steht die Platte schon, willigt Ilve sofort ein. Sonst holt Asta Seile und zwei Leute, nach zwei Stunden steht die Platte, und Ilve willigt knapper ein. Ein Soloheld ohne Kraft kommt so trotzdem zum Ende. Helle Kerben an den zugelassenen Stämmen (Totholz 102–103), bei der nächsten Reise sind sie fort und am Meilerplatz liegt Holz.
  - **»Ich mache den Holzfällerhang wieder sicher.«** (Kampfweg, nur mit Hang gesehen oder Astas Goblin-Bericht, Holzbruch noch nicht geräumt): Holzbruch räumen, dann Asta oder Ilve erneut ansprechen, das schließt ab. Ende **Holzfällerhang**: Der Hain bleibt unberührt, die Platte wird aufgerichtet, am Hang stehen ein Holzstapel zum Abholen und Astas Karren. Das Versprechen bindet nicht: Über **Grenze** lässt sich die Szene neu beginnen und doch verhandeln.
  - **»Der Holzfällerhang ist frei. Holt das Holz dort.«** (nur, wenn der Holzbruch schon vor der Szene geräumt ist): sofort das Ende Holzfällerhang.
  - »Ich möchte noch einmal darüber nachdenken.« ändert nichts.
  - Nach dem Randholz-Ende den Holzbruch räumen: Asta und Ilve bedanken sich je einmal, Astas Leute holen ihr Holz künftig vom Hang. Einen zweiten Q04-Lohn gibt es nicht.
- **Belohnung:** Beide Enden geben einmal 60 EP je Mitglied und 2 Rationen. Der Kampfweg bringt zusätzlich die Holzbruch-EP.
- **Zum Testen:**
  - Eine misslungene Hebeprobe (LP und Zeit).
  - Die Seil-Fassung ohne Hebeprobe.
  - Tavions Kommentar an den Familiensteinen, einmal.
  - Platte zuerst aufrichten, dann den Auftakt bei Ilve hören (eigene Fassung »Steht die Platte schon …«).
  - Nach dem Versprechen antworten nur noch **Holz** und **Holzfällerhang** damit.
  - Die Kerben verschwinden erst beim nächsten Betreten des Tannwalds.
  - Erkundungsfunde ohne Lohn: Blütenschale (95, 271), Harzfichten (106, 268 und 106, 274), alter Meilerplatz von Astas Familie (112, 282), Wegweiser.

### Flimmern am alten Harzweg · 🟡 ENTDECKUNG
- **Auslöser:** Auf dem Nordpfad (Rechteck x 84–104, y 266–280) nach Westen zum alten Harzweg (x 88, y 266–280). Zwischen zwei Fichten bei (88, 271) zittert dauerhaft die Luft. Das ist schon von weitem sichtbar.
- **Stufe:** keine Kämpfe.
- **Lösungsweg:**
  1. Den Aussichtspunkt mit Stein und Wurzel (88, 275–276) betreten, oder (88, 267/268) von Norden. Die Beobachtung erscheint als Protokollzeile, die Aufgabe ist sofort abgeschlossen, und man lernt **Flimmern**.
  2. Den Wildwechsel bei x 86 und 90, y 270–272 ansehen: Die Tierspuren biegen vor dem Flimmern ab.
  3. Optional Ilve nach **Flimmern** fragen: Der Held berichtet, aber sie weiß nichts, meidet die Stelle und schickt zu Meister Orwin nach Dreifurt. Vorher bittet sie dich, selbst hinzusehen.
- **Wahlen und Enden:** keine. Der Pfad hinter dem Flimmern verspringt nicht.
- **Belohnung:** das Wort **Flimmern** und eine Sichtung für Orwin (Hauptstrang, die zweite Stelle, nach der Orwin fragt).
- **Zum Testen:** Kommentare von Tavion (Tierspuren) und Korgar (außen herum, hier niemand lagern lassen). Stärke und Tempo des Effekts in Ego, Draufsicht und Iso.

### Holzbruch: Goblins im Holzbruch (G1–G3) · 🟢 OPTIONAL
- **Auslöser:** Ohne Auftrag zu finden. Von der Gabel (124, 281) die lange Fahrspur nach Süden über (124, 290), (92, 290) und (92, 300) zum **Holzfällerhang** (99–108, 298–311, Höhe 2). Das erste Betreten zeigt H3: trockene Stämme, und vom Süden schlägt Holz auf Holz. Der **Hochsitz** (108, 302) zeigt von oben Mulde, Stammsperre und Lager, lehrt **Goblins** und gilt als Fund. Der einzige Zugang ist der **Seitenweg** (109–113, 308). Beim ersten Betreten zeigt ein Popup einen Goblin, der Astas Karren zerschlägt und die Säcke nicht anrührt. Der Held erinnert sich an Rabans Säcke, Korgar und Tavion ergänzen.
- **Stufe:** Stufe 2–3.
  - G1 Karren: 2 Goblins (Stufe 1).
  - G2 Stammsperre: 2 Goblins und 1 Goblin-Schütze (Stufe 2).
  - G3 Lager: Goblin-Häuptling (Stufe 3, Anführer, Heiltrank), 2 Goblins und 1 Schütze.
  - Balance (Balance-Test: Brydan Stufe 2 mit Korgar und Tavion): G1 20/20, G2 20/20 über beide Wege, G3 19/20 mit 61 % LP übrig. Soloheld Stufe 2: G2 11/20, G3 0/20.
- **Lösungsweg:**
  1. **G1:** Am Karren (Auslöser x 116–118, y 304) kämpfen. Danach den Karren ansehen: Die Säcke sind verschnürt, man sieht auf die Stammsperre.
  2. **G2:** Der Zugang hat zwei Wege. Geradeaus durch den Hohlweg (122, 307), Auslöser (121, 306–308), oder über den Hang als Flanke (117–126, 304, Höhe 1), Auslöser (121–122, 304). Der Hang ist der bessere Weg gegen den Schützen.
  3. **G3:** Lagerplatz (x 127–132, Auslöser x 127). Der Häuptling ist Anführer: Fällt er, flieht der Rest leichter.
  4. Ist die letzte Gruppe besiegt, kommt das Abschluss-Popup im Lager (Schlafstellen, Vorräte, kein Schatz).
  - Flucht: G1 auf (111, 308), G2 auf (118, 307), G3 auf (121, 307). Die Zone bleibt besetzt.
- **Wahlen und Enden:** keine. Das Räumen erfüllt den Kampfweg von Q04 bzw. bietet in der Q04-Szene den freien Hang an.
- **Belohnung:** Einmal 60 EP je Mitglied und 2 Rationen. Kampf-EP: G1 40, G2 70, G3 130, zusammen 240. Dazu Goldwürfe und der Heiltrank des Häuptlings.
- **Zum Testen:**
  - Der Hochsitz nach dem Räumen zeigt ein leeres Lager.
  - Mit „Weiße Flecken“ (Q24, Fraukes Winkelbrett aus Mühlbrück) peilt man auf dem Hochsitz bei Tag: 30 EP und ein Stück Automap. Dazu kommt eine Wahrnehmungsprobe 35 mit Helfer, die den hellen Steig zum Spalt in den Südklippen zeigt (Fährte zu Q26).
  - Runa erwähnt bei **Suhle** (Q23) den geräumten Holzbruch. Nach Q26 sagt sie, die Goblins seien nicht zum Rauben gekommen, sondern geflohen.

### E05 Rauch ohne Feuer · 🟢 OPTIONAL
- **Auslöser:** Die Aufgabe beginnt erst mit Haskos Verdacht. **Hasko** steht mit zwei Begleitern am Abzweig an der Straße nach Karrfels (Weltkarte (171, 276), gleich östlich des Osttors von Tannried). Ihn nach **Waldlager** fragen: Er hat Rauch, Stoffzeichen und fremde Spuren gesehen und will hin. Seine Fassung hängt vom Werkstand ab: vor Q03 Helfer der Besatzer, danach zurückgebliebene Helfer. Das Lager allein ergibt keinen Eintrag.
- **Stufe:** keine Kämpfe, eine reine Gesprächsaufgabe.
- **Lösungsweg:**
  1. Optional zuerst das Lager: Vom Abzweig (170, 276) den Stoffstreifen nach Süden folgen zur Lichtung (177–189, 281–291) unter dunklen Fichten. Das erste Betreten zeigt ein Popup und lehrt **Waldlager**.
  2. **Weda** (183, 283) nach **Arbeit** bzw. **Waldlager** und **Lutz** (182, 288) nach **Waldlager** fragen. Weda erwähnt, dass Leute aus Tannried herüberschauen.
  3. **Belege (freiwillig):** Den Lagerboden ansehen (184–185, 287: weiche Sohlen) und die Planen ansehen (180, 283 und 187, 289: Arbeitsmarken). Dazu Räucherofen (187, 283), Wagen und Rad (181, 287 bzw. 184–185, 285) und Stoffstreifen.
  4. Hasko nach **Waldlager** fragen (hat man das Lager schon gesehen, berichtet der Held). Er zieht mit der Suchgruppe an den Lagerrand (178, 282).
  5. Das Lager erneut betreten (oder Hasko bzw. Weda dort ansprechen). Die Aussprache zeigt beide Seiten im Popup, dann kommt »Was sagt Ihr?«.
- **Wahlen und Enden:**
  - **»Seht Euch an, woran sie arbeiten.«**: Der Held zeigt Ofen, Rad und Werkzeug, mit Sohlen und Marken als Zusätzen, falls gesehen. Hasko nimmt den Vorwurf zurück, und das Lager bleibt. Weda bietet danach Rast und Proviant an.
  - **»Sie sollen den Weg verlassen.«**: Hasko gibt zu, dass nichts belegt ist. Dann kommt die Rückfrage »Auf der Vertreibung bestehen« / »Erst weiter nachsehen«, und nur das Erste bindet. Die Arbeiter packen ohne Kampf. Beim nächsten Besuch sind die Planen fort, Weda steht einmal zum Abschied am Abzweig (169, 277). Kein Rastplatz.
  - **»Ich halte mich heraus.«**: Die Aussprache bleibt offen und lässt sich bei Hasko neu beginnen.
- **Belohnung:** Friedlich 60 EP je Mitglied und 2 Rationen sowie Wedas Rastplatz (1 Gold). Vertreibung 30 EP.
- **Zum Testen:**
  - Den Abbruch bei der Rückfrage („Erst weiter nachsehen“).
  - Haskos drei Begrüßungen je Werkstand.
  - Das Lager ohne Verdacht bleibt ohne Journal.
  - Ein Sieg im Holzbruch bestätigt den Verdacht nicht.

### Q25 Die Kohlenfuhre · 🟢 OPTIONAL
- **Auslöser:** Erst nach dem Ende von Q03. Danach Tannried durch irgendeinen Ausgang verlassen (still schaltet das alles frei: Wagen, Spur, Posten, Lager). Beim nächsten Gespräch mit Runa erzählt sie im Popup vom Überfall auf **Haukes** Fuhre. Die Kasse hatte 60 Gold, davon 20 als erste Rate der Restschuld, der Rest war der Lohn der Köhler. Das lehrt **Kohlenfuhre** und startet die Aufgabe. Alternativ startet sie der leere Wagen an der Straße nach Karrfels, Weltkarte (243, 253), mit Tannrieds Brandzeichen (10 EP, Tavion kommentiert).
- **Stufe:** Stufe 4–5, am besten zu viert.
  - Gegner im Kalkbruch: **Marit** (Anführerin, Stufe 5, 38 LP, Rüstung 2), 1 Eintreiber (Stufe 3) und ab drei Kämpfern ein zweiter, 1 Bogenschütze (Stufe 3) auf dem Felsabsatz und ab fünf ein zweiter, **Tjark** der Läufer (Stufe 1, 12 LP, kämpft nicht, rennt mit der Kasse zum Ausgang) sowie Enno (Schleuderer, Stufe 1), wenn er nicht gefangen ist. Alle fliehen nie.
  - Balance (Balance-Test: Stufe 4, Siege von 16): zu dritt Mündung gewarnt 4, Mündung mit gefangenem Posten 4, **Kante 10**, Mündung bei verkeilter Kante 2. Zu viert 14 bis 16.
- **Lösungsweg:**
  1. Bei Asta (Meilerplatz) nach **Kohlenfuhre** fragen: Haukes Bericht (eine Frau führte, ein dürrer Bursche lief mit der Kasse voraus, weißer Staub an den Stiefeln). Sie nennt den **Kalkbruch**.
  2. Vom Wagen (243, 253) der **Kohlenspur** nach Süden folgen: am Westrand des Ostwalds über (244, 256) bis (242, 301), dann nach Osten zur Mündung des Kalkbruchs.
  3. **Ortrun** (253, 315, vor ihrer Hütte südlich des Bruchs) nach **Kalkbruch** fragen: Sie verrät die eingebrochene **Kante** in der Ostwand und den Sturmstamm, solange das Lager steht auch den Posten.
  4. **Kalkbruch** (Felskessel 245–260, 289–302): Die Mündung liegt im Süden (251–253, 302–303), die Kante in der Ostwand (259, 295). Der Posten **Enno** sitzt vor der Mündung (255, 304) und schnitzt. Ein Ring aus Auslösezellen umgibt ihn (x 247 und 258, y 300–307, dazu y 307). Wer ihn betritt, wählt:
     - **„Anschleichen und ihn greifen“:** Probe Schleichen 35 mit Helfer. Gelingt sie, ist Enno gefangen (20 EP). Er verrät das Lager und die Kante.
     - **„Offen auf ihn zugehen“** oder eine misslungene Probe: Er pfeift und rennt ins Lager, das Lager ist gewarnt.
     - **„Zurück zwischen die Stämme“:** Enno bleibt sitzen.
     - Wer von Osten direkt zur Kante geht, berührt den Ring nicht.
  5. **Stamm kippen (empfohlen vor dem Kampf):** Den Sturmstamm außen an der Kante (260, 294) benutzen und „Den Stamm kippen“ wählen. Die Kante ist dann für alle verkeilt, auch für Tjark, dem nur noch die Mündung bleibt. Achtung: Dann muss die Gruppe selbst durch die Mündung, und die Mündung ist bei verkeilter Kante die schwerste Fassung (zu dritt 2/16).
  6. **Einstieg** (vor beiden Zugängen kommt eine Rückfrage, „Noch nicht“ setzt die Gruppe eine Zelle zurück):
     - **Kante** („Durch die Rinne hinein“): Überraschung für die Gruppe. Ist Enno noch auf Posten, kommt er später von draußen. Bei Alarm keine Überraschung.
     - **Mündung** mit gefangenem Enno: Wahl zwischen **„Ihn gegen die Kasse tauschen“** (kein Kampf: Marit schickt Tjark mit dem Sack heraus und zieht ab) und **„Ihn anbinden und angreifen“** (Überraschung, Tjark greift erst später nach dem Sack).
     - **Mündung** nach Alarm: Marit ruft »Tjark, lauf!«.
  7. **Kasse:** Nach dem Sieg oder dem Tausch liegt sie im Sack an der Feuerstelle (252, 294). Benutzen bringt 40 EP. Bei vollem Gepäck bleibt sie dort. Unter der Plane (255, 292) liegt nach einem Kampf Kords Liste mit 25 Gold (Fuhrleute zu je 20 Gold, die letzte Zeile ist Tannried mit drei Strichen).
  8. **Tjark entkommen:** Zwei frische Abdrücke (254, 306) und (253, 308) führen zu Ortruns Wolfsgrube (253, 310). Er sitzt darin. **„Erst die Kasse, dann das Seil“** gibt die Kasse (40 EP), danach humpelt er davon. „Ihn sitzen lassen“ geht auch.
  9. Mit der Kasse zu Runa: Sie fragt »Was geschieht mit der Kasse?«.
  - Nach einer Flucht der Gruppe gilt das Lager als gewarnt. Gefallene fehlen beim nächsten Versuch, und Tjark hat keinen Rückstand mehr.
- **Wahlen und Enden:**
  - **„Sie gehört Tannried“:** 20 Gold Finderlohn und 80 EP. Runa trägt die Rate ein (Restschuld 20 Gold im Abrechnungsbuch). Am Meilerplatz steht ein beladener Karren, und Asta gibt beim nächsten Gespräch einmal einen Heiltrank. Später in Karrfels steht Hauke an seinem Kohlenwagen, und Hald reagiert darauf.
  - **„Sie bleibt bei uns“:** 60 Gold und 80 EP. Runa nennt den Preis (Benno zahlt die Rate aus seinem Anteil, die Köhler warten), kein Karren.
  - „Noch nicht“ verschiebt die Entscheidung.
  - Nach dem Tausch sagt Runa über Marit »die laufen noch frei herum«.
- **Belohnung:** Quest-EP Wagen 10, Posten 20, Kasse 40, Abschluss 80, zusammen bis 150. Kampf-EP Marit 110, Eintreiber je 35, Bogenschütze 35, Tjark 15, Enno 15. Kords Liste 25 Gold. Gold 20 bzw. 60, bei Rückgabe ein Heiltrank von Asta.
- **Zum Testen:**
  - Jede Zugangsfassung (Tabelle in technik-inhalte-westmark.md).
  - Der Läufer rennt sichtbar los. An der Mündung entkommt er fast immer, von der Kante gestellt nie.
  - Kasse bei vollem Gepäck.
  - Begrüßungen von Runa, Benno und Asta je Ausgang, die Abrechnung im Versammlungshaus.
  - Marits Angriff nach Nordwesten (bekannter Grafikfehler).
  - Wer die Kasse ohne Auftakt bringt, bekommt eine eigene Fassung mit dem Brandzeichen auf dem Deckel.

### V01a Die Fallenstellerin Ortrun · 🟢 OPTIONAL (Händlerin ohne Journal)
- **Auslöser:** Ortrun steht ab Spielbeginn vor ihrer verriegelten Blockhütte am Südrand des Ostwalds (Weltkarte (253, 315), Hütte 249–252, 312–314, Fellgestell davor). Die erste Begrüßung lehrt **Felle** und **Wölfe**.
- **Stufe:** keine eigenen Kämpfe. Wolfsfelle kommen von Wölfen und Rudelwölfen (60 % je Wolf). Rudel liegen in der Nähe etwa bei (241, 270), (238, 298), (266, 302), (228, 328) und (170, 324), viele weitere über den Tannwald verteilt.
- **Lösungsweg:**
  1. Mit vier **Wolfsfellen** im Gepäck nach **Felle** fragen: Sie kauft vier auf einmal für 30 Gold.
  2. Nach dem dritten Bündel (12 Felle) näht sie die **Wolfskappe** (Kopf, Rüstung 2).
  3. **Wölfe** (lehrt **Südklippen**), dann **Südklippen** (lehrt **Koboldsteig**), dann **Koboldsteig** oder **Goblins** fragen: Die Goblins kommen seit dem Winter nicht mehr herunter, früher tauschten sie Pilze gegen Felle. Das ist die Fährte zu Q26.
  4. **Kalkbruch** und **Kohlenfuhre** helfen bei Q25 (siehe oben).
- **Wahlen und Enden:** keine.
- **Belohnung:** 30 Gold je Bündel (zusammen 90 Gold für 12 Felle) und die Wolfskappe.
- **Zum Testen:** Zählt der Bündelzähler richtig, kommt die Kappe genau einmal? Nach Q26 legt Ortrun wieder Felle an den Tauschstein (siehe Q26). Sitzt Tjark in der Grube, hat sie eine eigene Begrüßung.

### Q26 Das leere Nest · 🟢 OPTIONAL
- **Auslöser:** Kein Auftraggeber, keine Voraussetzung. Fährten: Ortruns **Koboldsteig**, der Spalt vom Hochsitz (Q24) oder einfach die Feuerringe. **Anreise:** Die Südklippen liegen tief im Süden, südlich des Deichwegs (Straße Brackhafen–Glasgrund bei y ≈ 350–356), etwa 95 Felder südlich von Tannried quer durch den Tannwald. Am Fuß der Wand stehen drei kalte **Feuerringe** (153, 370), (155, 370), (157, 370), das erste Umschauen zeigt ein Popup, daneben der leere **Tauschstein** (161, 370). Den **Dornbusch** (162, 373) benutzen oder ansehen: Er legt den Koboldsteig frei (10 EP). Der Steig führt aus hellem Kies über (162, 374) und (162, 375–377), (161, 377), (160, 377) durch eine Felsgasse (160, 376) nach (160, 375). Von dort benutzt man das **Höhlenmaul** (160, 374). Die Aufgabe beginnt erst in der Vorhöhle (lehrt **Goblinbau**).
- **Stufe:** Stufe 5–6, zu viert. Gegner:
  - Höhlenassel: Stufe 3, 18 LP.
  - Panzerassel: Stufe 5, 34 LP, Rüstung 4.
  - Sinterling: Stufe 4, 20 LP.
  - Sinterwesen: Stufe 6, 42 LP, Rüstung 3.
  - Alle fliehen nie und lassen kein Gold fallen.
  - Balance (Balance-Test: Stufe 4, Siege von 12): zu dritt K1 11, K2 9, K3 2, K4 5, K5 2, K6 vom Kratzgang 0. Mit Namar zu viert K2 11, K4 12, K5 11, K6 vom Kratzgang 0, **vom Sims 7**.
- **Lösungsweg** (Karte des Baus 76 × 52, dunkel, Licht nur von Leuchtpilzen, Ankunft (74, 26) im Osten):
  1. **A Vorhöhle** (61–73, 22–30): Die Spuren führen alle hinaus (Tavion kommentiert). In einem Bündel liegen ein Leuchtpilz und zwei Höhlenpilze. Der Leuchtpilz gibt Licht in der linken Hand, Radius 2.
  2. **B Wohnhöhle** (43–56, 20–30): **K1**, 3 Höhlenasseln an den Vorräten (ab drei Kämpfern 4).
  3. **C Pilzgärten** (24–41, 6–19, drei Terrassen): **K2**, eine Panzerassel und 3 Asseln (ab vier Kämpfern 4). Jede der drei Beetgruppen gibt einmal 3 Höhlenpilze (heilen 1W6+2), die Leuchtpilze einmal 2.
  4. **Brutkammer** (11–20, 5–11, freiwillig): **K3**, eine Panzerassel und 3 Asseln (ab vier Kämpfern eine zweite Panzerassel). Ein Bündel mit 3 Höhlenpilzen, Asselplatten als Beute. Zu dritt kaum zu gewinnen.
  5. **D Die Alten** (44–53, 37–43): Drei alte Goblins am Feuer, eine der Alten ansprechen. Die Wahl (siehe unten) entscheidet über den **Kriechgang** hinter dem Fellgestell (44, 42). Der Gang führt auf den **Sims** über der Trommelhalle (12–15, 41–45) und ist der Weg, die Halle zu nehmen. Alternativ das Fellgestell benutzen: eine stille Wahrnehmungsprobe 30 (Misslingen kostet 5 Minuten).
  6. **E Barrikade** (Sperre (36, 25), Lücke (36, 26)): von Westen her durchbrochen (Odrik kommentiert). Benutzen und „Die Stämme zurück in die Lücke stemmen“ wählen: Probe Stärke mit Athletik 35 mit Helfer, ein Misslingen kostet 10 Minuten. Geschlossen gibt es einmal 30 EP. Die Lücke lässt sich wieder öffnen, der Kriechgang bleibt in jedem Fall offen.
  7. **F Kratzgang** (18–35, 24–31): **K4**, ein Sinterwesen und 2 Sinterlinge (ab vier ein dritter). Vorher würfelt eine stille Wahrnehmung 35: Gelingt sie, gibt es keine Überraschung, sonst überraschen die Bleichen die Gruppe.
  8. **Tropfsteinkammer** (15–25, 17–22, freiwillig): **K5**, ein Sinterwesen und 2 Sinterlinge (ab fünf ein zweites Sinterwesen). Die versinterte Truhe öffnet eine Probe Stärke mit Athletik 30. Darin liegen der **Asselschild** (Schild, Rüstung 2), 4 Höhlenpilze und 2 Leuchtpilze.
  9. **G Trommelhalle** (1–16, 27–45, zwei Stufen tiefer): Der erste Blick vom Ende des Kratzgangs oder vom Sims gibt 20 EP und lehrt **Flimmern**. Ab hier ist die Meldung möglich. **K6** (2 Sinterwesen und 3 Sinterlinge, mehr ab fünf und sechs Kämpfern) erwacht nacheinander, sobald man den Hallenboden betritt. **Vom Sims aus angreifen**: Die Gruppe steht erhöht, und die Abstände sind größer. Das große Flimmern (8, 36) bleibt auch nach dem Sieg.
  10. **Sinterscherbe:** Sie liegt nach dem ersten Sieg über Bleiche (K4, K5 oder K6) einmal da. Ein Questgegenstand ohne Wert.
  11. **Meldung:** Berthold (Dreifurt) oder Runa (Tannried) nach **Goblinbau** fragen (die Halle muss gesehen sein). Der Erste gibt 60 EP und schließt die Aufgabe, der Zweite hört denselben Bericht ohne EP. Berthold reagiert auf geschlossene Barrikade, geräumte Halle und Scherbe. Runa sagt nach geräumtem Holzbruch, die Goblins dort seien weggelaufen und nicht zum Rauben gekommen.
  - Rast im Bau lockt zu 20 % Asseln an.
- **Wahlen und Enden:**
  - Bei den Alten (»Die drei sehen Euch an und warten.«):
    - **„Die leeren Hände zeigen“:** Die Älteste zeichnet einen Kreis mit Wellen, Striche, die weglaufen, und einen Stein quer über die Linie (20 EP).
    - **„Zwei Rationen ans Feuer legen“:** nur mit zwei Rationen. Wie oben, dazu zeigen sie dir das Loch hinter dem Fellgestell und geben einen Korb mit 4 Höhlenpilzen.
    - **„Die Waffe ziehen“:** Die drei verschwinden durchs Loch, der Kriechgang steht offen. Keine EP, und Ortrun bekommt später keinen Tausch mehr.
    - **„Gehen“** ändert nichts.
  - Nach geräumter Halle und gesehener Zeichnung zieht die Älteste beim nächsten Ansprechen die Striche zum Kreis hin nach.
  - Halle räumen oder vorher umkehren: Beides schließt mit der Meldung ab.
  - **Ortrun** nach **Goblinbau** fragen, solange die Alten noch da sind: Sie legt wieder Felle an den Tauschstein (Bündel auf (160, 370)). Sind die Alten vertrieben, bleibt der Stein leer.
- **Belohnung:** Quest-EP Steig 10, Zeichnung 20, Barrikade 30, Halle gesehen 20, Halle geräumt 100, Meldung 60, zusammen bis 240. Kampf-EP zu viert: K1 120, K2 200, K3 250, K4 260, K5 210, K6 370, zusammen 1410 (rund 353 je Kopf). Außerdem Asselschild, viele Höhlenpilze, Leuchtpilze, Asselplatten (8 Gold) und die Sinterscherbe.
- **Zum Testen:**
  - Lesbarkeit von Dornbusch, Steig und Maul in allen drei Ansichten.
  - Ist der Bau dunkel und doch lesbar?
  - Alle vier Wege bei den Alten.
  - Den Kriechgang mit und ohne Hinweis.
  - Die Halle von beiden Seiten.
  - Bekannte Lücken: schwarze Flecken in den Laufbildern des Sinterlings (Südost und West), die Asseln haben kein Angriffsbild.

---

**Empfohlene Reihenfolge in der Region:**
1. Tannried: Runa, Benno und die Abschrift.
2. Werkhof (Q03), mit Rast bei Runa vor Kord.
3. Asta: Q04-Auftakt und **Goblins**.
4. Tannwald: Hain, Platte, Ilve, Flimmern, Hochsitz.
5. Holzbruch.
6. Die Q04-Szene.
7. E05 am Abzweig östlich von Tannried.
8. Tannried einmal verlassen und wieder betreten: Q25 bei Runa, Ortrun, Kalkbruch.
9. Felle sammeln für Ortrun.
10. Mit Stufe 5–6 der Goblinbau (Q26) und die Meldung bei Runa oder Berthold.

**EP-Bilanz (Quest-EP je Mitglied, ohne Kampf):** Q03 150, Q04 60, Holzbruch 60, E05 60 (bzw. 30), Q25 bis 150, Q26 bis 240.

**Offene Enden / Rückkehr später:**
- **Lieferung von Beras Werkzeugen:** kommt erst nach Q02 (Dreifurt) und dem Verlassen von Dreifurt, danach wieder in Tannried ankommen.
- **Q25 Die Kohlenfuhre:** erst nach Q03 und einmal Tannried verlassen. Die Rückgabe der Kasse zeigt sich später in Karrfels: Hauke an seinem Kohlenwagen, Halds Antwort.
- **Hochsitz mit Fraukes Winkelbrett (Q24):** Peilung nur bei Tag. Die Probe zeigt den Spalt zum Goblinbau.
- **Q26 Meldung:** Berthold in Dreifurt ist der zweite Empfänger (ohne EP). Ortruns Tauschbündel am Stein kommt nur, solange die Alten leben.
- **Q04 nach dem Kompromiss:** Wer den Holzbruch später räumt, bekommt den Dank von Asta und Ilve (ohne Lohn). Die Kerben verschwinden erst bei der nächsten Reise.
- **Suhle (Q23, Mühlbrück):** Runa erklärt sie, mit eigener Fassung nach geräumtem Holzbruch.
- **In Akt I bewusst offen:** Marit nach dem Tausch, Kords Liste und der auswärtige Gläubiger, das Flimmern im Goblinbau.
- **Unruhe:** Die Unruhe-Stufen (Relikte) verändern in dieser Region nach Datenlage nichts.

---

## Kapitel 4 · Karrfels und Graufelspfad

**Anreise:** Karrfels liegt im Nordosten der Westmark am Fels (Ort „Karrfels“ um Weltkarte (315, 104)). Zwei Tore führen in die Ortskarte:
- **Südtor** Weltkarte (307, 112), über die Straße von Tannried bzw. Dreifurt (am Abzweig nach Karrfels). Ankunft im Vorfeld vor dem Tor, Ortskarte (8, 50). Unterwegs: Hinterhalt der Orks an der Brücke der Karrfelsstraße (Weltkarte (286, 164..166), Gegner Stufe 4 bis 5) und Riesenratten vor der Stadt (Weltkarte (290, 98), Stufe 6).
- **Osttor** Weltkarte (324, 97), von der Straße zum Graufelspfad. Ankunft auf der Werkterrasse am Osttor, Ortskarte (54, 13). Wer von Osten kommt, bekommt den Torspruch des Südtors gleich mit, die Ostwache fragt in einem Popup nach.
- Der erste Besuch gibt 20 EP (je Tor ein eigener Ankunftstext).
- **Graufelspfad:** vom Osttor nach Osten und Süden Richtung Lichtenruh. Am Pfad liegen der Wegweiser zur Seilklamm (Weltkarte (336, 118)) und weiter südlich der Handelsstein (Weltkarte (348, 144)) mit Haldaar. Am Pass weiter östlich lauert eine freie Gruppe Klammspinnen (Weltkarte (379, 115), Stufe 7).

**Aufbau der Stadt** (Ortskarte 56 × 52, vier Terrassen am Hang, Treppen aus zwei Stufen, Eintritt von Süden):
- **Vorfeld** (Zeilen 44..51): Straße, Varkas Lager östlich der Straße (21..24, 46..47).
- **Torterrasse** (Zeilen 30..43): Südtor (8..9, 43) mit Torwächter Folke (10, 44), Zeugschmiede (Tür (6, 36), Borga tags an der Esse (12, 35)), Fuhrplatz mit Kohlenwagen und Tränke (Gießer Wibo (17, 39), nach Q25 Fuhrmann Hauke (22, 37)), Schichtkrug (Tür (37, 37)), Krämer (Tür (48, 36)), Fuhrhof (Tür (48, 41), davor Fuhrherr Gisbert (42, 40)).
- **Wohnterrasse** (Zeilen 17..29, Treppe hinauf bei (26..27, 29..30)): Kämpfergilde (Tür (6, 23)), Glockenturm (26..28, 18..20) mit Glöckner Ingvar (28, 21), Becken (18..23, 20..23) mit der Ältesten Hedda (24, 22), Brandhaus (Tür (35, 22)), Magiergilde (Tür (47, 23)).
- **Werkterrasse** (Zeilen 6..16, Treppen bei (13..14, 16..17) im Westen und (40..41, 16..17) im Osten): vernageltes Hallentor der Schmelzhalle (10..11, 13) mit Vorarbeiterin Svea links daneben (9, 14) und Beric rechts davor (13, 14). Gießerei mit dem einzigen rauchenden Schlot (Tür (27, 9), Gießermeister Hald tags im Hof (23, 12)), Kontor (Tür (36, 10)), Schlackenhalde mit dem Schlackenring (46..50, 8..11) im Osten, Osttor (55, 13..14).
- **Grubenplatz** (Zeilen 3..5, Treppe (40..41, 5..6)): Lore, Winde mit dem alten Runolf (42, 3), Grubenmund (40, 2).

**Wann:** Karrfels ist ab Spielbeginn offen, kein Kampf an den Toren. Im gründlichen Weg kommt man nach Dreifurt und dem Startdreieck mit **Stufe 7 bis 8** an (4 Köpfe). Alle Kämpfe der Region sind auf eine Vierergruppe der **Stufe 7** gemessen (Held als Kämpfer mit Korgar, Tavion und Namar, dazu die Fünfergruppe mit Varka). Gegner der Region Stufe 6 bis 9. Wer auf dem reinen Pflichtweg allein hierherkommt, sollte erst Gefährten holen (Varka, Beric stehen gleich hier).

**Dienste:**
- **Schichtkrug** (Tür (37, 37), eigene Innenkarte): Wirtin Imke am Tresen (5, 2). Gefährten (Wartebank), Reden, Zimmer (6 Gold die Nacht, Proviant 1 Gold), Lager. Gerüchte: **Arbeit** → **Stiller Gast**, **Vermesser** → **Seilklamm**, **Reisewege** je nach Unruhe (siehe unten). Nachts sitzen Wibo (und nach Q25 Hauke) hier. Schiefertafel der Zeche, Eckkammer (das Zimmer des Fremden).
- **Zeugschmiede Borga** (tags an der Esse (12, 35), nachts an der Tür (6, 36)): Karrfelser Klinge (1W8+2, 160), Gießhammer (1W12+1, 170), Grubenmesser (1W6+1, 90), Armbrust (1W10+1, 180), Kettenhemd (Rüstung 4, 220), Eisenhut (Rüstung 3, 110), Beschlagener Schild (Rüstung 3, 130), Handbeil, Kurzbogen, Lederrüstung und **Eisenbarren** (24 Gold, für den Handelsstein). Borga kennt **Handelsstein** vom Hörensagen.
- **Krämer Ebbo** (Tür (48, 36)): Fackel, Heiltrank, Gegengift, Brandflasche, Schleuder, Lederkappe. Fackeln braucht man in der Grube (Q27).
- **Brandhaus Heilerin Sigrun** (Tür (35, 22)): Heilen (1 Gold je LP), heilt Gift (15), Verletzung (20), Verlangsamung (10), Lähmung (25), Verwirrung (15). Gegengift und Heilung sind vor der Grube (Speiottern) nützlich.
- **Kämpfergilde Waffenmeister Torvid** (Tür (6, 23)): Kämpfer, Schütze, Dieb (Training, Wort **Training** über **Arbeit**).
- **Magiergilde Meister Onno** (Tür (47, 23)): Weißmagier, Graumagier, Schwarzmagier. Zu **Herz** (nach Q08) hat er eine Vermutung.
- **Fuhrhof** (Tür (48, 41)): nur Kulisse (Stände leer).
- Nachts ändern sich die Plätze: Wibo im Krug, Borga an der Tür der Zeugschmiede, Hald antwortet an der Kontortür (36, 10). Svea, Ingvar, Hedda (am Becken), Gisbert und die Ringkämpfer sind nachts fort.

**Gefährten:**
- **Varka** (Orkin, Graumagierin, Stufe 6, Magierstab, Zauber Verlangsamen, Bann, Frosthauch, spricht Orkisch und Gemeinsprache). Lager im Vorfeld (23, 47), Tag und Nacht. Bedingung: nur ein freier Platz (Gruppe unter sechs). 30 EP beim Beitritt.
- **Beric** (Zwerg, Kämpfer, tritt mit **Stufe 7** bei, Handbeil, Holzschild, Lederrüstung, fromm, spricht Zwergisch und Gemeinsprache). Vor dem Hallentor (13, 14), Blick West. Ohne Bedingung, 30 EP beim Beitritt. Beziehungen: Freund von Haldaar (+60), mag Odrik (+35), Rivale von Z'zarek (−45), kleine Vorbehalte gegen Jaro und Venya (siehe „Freunde und Rivalen“). Beric ist praktisch nötig, um Haldaar anzusprechen (Zwergisch).
- **Haldaar** (Hüne, Weißmagier, tritt mit **Stufe 7** bei, Kriegshammer, klaustrophobisch, spricht nur Hünisch und Zwergisch). Auf einem Felsblock am Steinring des Handelssteins, Weltkarte (352, 144). Ohne Bedingung, aber nur mit einem Zwergisch- oder Hünischsprecher in der Gruppe (Beric, sonst nur der Fremdentext). 30 EP.

---

### Karrfels: Ankunft, Wörter und Stadtszenen · 🟡 ENTDECKUNG

- **Auslöser:** Betreten der Ortskarte. Keine Aufgabe, alles ist Vorlauf für Q08, Q27 und E06.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. **Südtor:** Folke spricht beim ersten Durchschreiten den Torspruch. Ist **Korgar** dabei, fragt er, wer für den Ork bürgt: »Ich bürge für ihn.« oder »Er hat an meiner Seite gekämpft. Das muss reichen.« (beide lassen ihn durch, Korgar kommentiert). Mit **Varka** in der Gruppe sagt Folke einen eigenen Satz. Folke: **Arbeit** → **Schmelzhalle**, **Orks**, **Vermesser** → **Seilklamm**, **Karrfels**.
  2. **Fuhrplatz:** Kohlenwagen ansehen (mit Q25 erledigt steht Hauke da, sonst eine alte Fuhre). Wibo: **Arbeit** lehrt **Schmelzhalle**, **Kohle** und **Schlackenring**. Hauke (nur nach Q25): **Arbeit** → **Kohle**, **Tannried**, **Schmelzhalle**.
  3. **Krug:** Imke **Arbeit** → **Stiller Gast** (der Fremde: zahlte mit alter Münze, fragte nach den Gängen unter der Halle) → **Schmelzhalle**.
  4. **Glocke:** Beim ersten Aufstieg auf die Wohnterrasse bei Tag schlägt die Schichtglocke (Kamerafahrt zum Turm, Klang). Nachts schweigt sie, dann holt man es bei Tag nach.
  5. **Brandhaus:** Beim ersten Betreten zeigt Sigrun drei Verbrannte mit weißer Haut, 20 EP, Wort **Verbrannte**. Danach Reden oder Heilen. Sigrun **Verbrannte** → **Schmelzhalle**.
  6. Ingvar (Glockenturm): **Arbeit** → **Schicht**, **Zwerge** → **Grube**. Hedda (Becken): **Arbeit** → **Grube** → **Schicht**.
  7. **Gießerei:** Auftragsbuch auf dem Pult (linke Seite voll, rechte leer), Gussform, Schlote. Hald: **Arbeit** → **Schmelzhalle**, **Kohle**, **Stiller Gast** (wollte die Baupläne mit den Gängen sehen).
  8. **Hallentor:** Svea: **Arbeit** → **Schmelzhalle** → lehrt **Verbrannte** und **Alte Esse**. Fragt man Svea nach **Verbrannte**, sagt sie »Legt die Hand an die Angel dort«: die eiserne Angel des Tors anfassen, 10 EP (Fingerkuppen werden weiß).
- **Belohnung:** Ankunft 20 EP, Brandhaus 20 EP, Angel 10 EP. Wörter: Schmelzhalle, Verbrannte, Stiller Gast, Kohle, Grube, Schicht, Wärme, Alte Esse, Schlackenring, Seilklamm.
- **Zum Testen:** Ansichten der Terrassen und Treppen. Tag/Nacht-Plätze der Bewohner. Borga verkauft tags draußen, nachts an der Tür. Hald antwortet nachts nur an der Kontortür. Varkas Kommentare an Tor, Brandhaus und Hallentor (je einmal).

### Varka vor dem Tor · 🔵 GEFÄHRTE

- **Auslöser:** Varka am Lager im Vorfeld (23, 47) ansprechen, jederzeit.
- **Stufe:** kein Kampf. Varka kommt mit Stufe 6, ist damit etwas unter der Gruppe.
- **Lösungsweg:**
  1. **Name** (stellt sie vor, lehrt **Wärme**), **Arbeit** (lehrt **Wärme**), **Wärme** (ihre Sippe: die warmen Quellen jenseits des Ostkamms sind kalt geworden, lehrt **Verbrannte**).
  2. **Verbrannte**: Hat man das Brandhaus schon gesehen, erzählt man ihr, dass die Haut weiß wird (20 EP einmal). Sonst fragt sie nur danach.
  3. Anheuern im Dialog (Gruppe unter sechs). 30 EP, Korgar kommentiert, ihr Lager wird abgebaut (kalter Feuerring).
- **Wahlen und Enden:** keine. Ohne freien Platz lehnt sie ab und wartet.
- **Belohnung:** 30 EP (Beitritt), 20 EP (Verbrennungen erzählt).
- **Zum Testen:** Varka hat Einwürfe am Südtor, im Brandhaus, am Hallentor, beim Betreten der Schmelzhalle, an der Treppe zum Ofenraum, beim Fremden, beim Ring, am Rand der Seilklamm, an den Echsen der Halde, am Feuerkorb, an der Fackel und am Sumpf der Grube. Sie ist die Fünfte der Balance-Bezugsgruppe.

### Beric vor dem Hallentor · 🔵 GEFÄHRTE

- **Auslöser:** Beric vor dem Hallentor (13, 14) ansprechen.
- **Stufe:** tritt mit Stufe 7 bei.
- **Lösungsweg:** **Name** (lehrt **Zwerge** und **Wärme**), **Arbeit**, **Wärme** (»Geht Ihr hinein, gehe ich mit«, nach Q08: »Nehmt mich mit, wenn Ihr weiterzieht«), **Zwerge**, **Drachen**, **Goblins**. Anheuern im Dialog, ohne Bedingung. 30 EP, Kommentare von Korgar und Jaro (beide mögen ihn nicht).
- **Empfehlung:** Vor Q08 anwerben. Er erkennt am Portal das Heiligtum der ersten Familien und nennt die Haken im Sturz eine Entweihung, hat einen Satz am Sockel, am Messbuch der Seilklamm und am Handelsstein. Ohne ihn kann man Haldaar nicht ansprechen.
- **Belohnung:** 30 EP.

### Q08 Die kalte Esse · 🔴 PFLICHT (Relikt „Fassung“)

- **Auslöser:** Mit Orwins Wort **Hüter** lehrt die Älteste Hedda (Becken) **Alte Esse** und **Schmelzhalle**. Sonst lernt man über **Schmelzhalle** bei Svea oder Hald das Wort **Alte Esse**. Die Aufgabe beginnt, sobald Svea oder Hald zu **Alte Esse** gefragt wird (Reihenfolge frei). Keine Vorbedingung aus anderen Regionen.
- **Stufe:** Gruppe Stufe 7 bis 8, besser fünf Köpfe für den Ofenraum. Gegner (alle mit Glutleib: wer sie im Nahkampf aus dem Nachbarfeld trifft, verliert selbst 2 bzw. 4 LP, mindestens 1 LP bleibt. Feuer immun, Kälte −50 %):
  - K1 Werkbankhalle: 1 Glutgestalt (Stufe 8) und 3 Glutlinge (Stufe 6), ab fünf Figuren ein vierter Glutling.
  - K2 Ofengasse: 2 Glutgestalten und 2 Glutlinge, ab fünf ein dritter Glutling.
  - K3 Ofenraum: 1 Tiegelglut (Stufe 9, wirft Funken, tritt verzögert aus einem Riss), 1 Glutgestalt, 2 Glutlinge, ab fünf ein dritter Glutling (ebenfalls verzögert).
  - Balance-Messung (vier Köpfe Stufe 7, KI ohne Schürstangen): K1 11 von 12 Siegen, K2 6 (mit offenen Luftklappen 9), K3 5 von 12, zu fünft 12. Der Ofenraum ist zu viert hart.
- **Lösungsweg:**
  1. Tagsüber Svea am Hallentor (9, 14): **Arbeit** → **Schmelzhalle** → **Alte Esse**. Sie geht mit hinein, aber nur mit Halds Wort.
  2. Hald im Hof der Gießerei (23, 12) (nachts an der Kontortür (36, 10)): **Alte Esse**. Er gibt sein Wort unter der Bedingung: »Was im Sockel sitzt, bleibt im Sockel.«
  3. Bei Tag am Hallentor Svea **um Einlass bitten**: Sie hebelt die Bretter ab (20 Minuten), Svea ist in der Halle dabei (als Figur, nicht in der Gruppe).
     Alternative bei **Nacht** ohne Svea und ohne Hald: am Tor **Die Bretter abhebeln** (Probe Stärke mit Athletik 40, Helfer zählen, Fehlschlag 10 Minuten). Die Aufgabe beginnt dann beim Eintreten, Wort **Alte Esse** wird gelernt.
  4. **Vorraum** (Ankunft (15, 37)): Werkzeugwand (10, 36): zwei **Schürstangen** nehmen (Speer, zweihändig, 1W8+1, Reichweite 1 bis 2). Damit trifft man aus zwei Feldern Abstand ohne Rückschlag. Schichtbrett (10, 35), gefrorener Löschtrog.
  5. **Werkbankhalle** (Zeilen 26..33): Kampf K1 beim Betreten (Auslöser (14..17, 32..33)). Flucht zurück in den Vorraum. **Sveas Spind** (5, 28): mit Svea ohne Probe offen, sonst Schloss 35. Inhalt Gießerschürze (Rüstung 3) und zwei Heiltränke.
  6. **Vorbereitung K2:** Aus der Werkbankhalle in den **westlichen Schürgang** (hinter der westlichen Ofenreihe), ohne die Ofengasse zu betreten: **Winde** der Luftklappen (10, 13), Probe Athletik 35 (Helfer zählen, Fehlschlag 10 Minuten). Dann beginnt K2 mit Überraschung für die Gruppe, die Gegner treten verzögert an.
  7. **Östlicher Schürgang:** Versteck im Kohlenhaufen (21, 13), Probe Wahrnehmung 40 (Fehlschlag 5 Minuten): Lohnbeutel eines Gießers (Zettel: »Drei Monate halber Lohn, zurückgelegt für Mutter«). Wahl **Den Beutel nehmen** (60 Gold) oder **Den Beutel zurücklegen**.
  8. **Ofengasse** (Zeilen 14..25): Kampf K2 beim Betreten (13..18, 23..25 und Quergänge). Flucht zurück in die Werkbankhalle.
  9. **Portal und Treppe** (Zeilen 9..13): Portal ansehen (Zeichen Hammer im Berg, Beric kommentiert), Treppe (14..17, 12) hinab, Varka kommentiert.
  10. **Ofenraum:** Kampf K3 (Auslöser (12..19, 9) und (14..17, 10)). Nach dem Sieg steht die Gruppe auf (15, 8), Svea kommt herunter. Flucht zurück auf (15, 13).
  11. **Am Sockel** (15, 4): Beim ersten Schritt an den Sockel (oder an Kurbel, Schieber, Platte, Tafel) erklärt Svea Trittsteine und Handgriffe, ohne Svea liest man sie von der **Messingtafel** (9, 5): »Kurbel, Wasser, Platte«. Wort **Herz**. Hier erscheint ggf. der Fremde (Q15a, unten).
  12. Reihenfolge der Handgriffe (falsche Reihenfolge gibt nur einen Hinweistext):
      a. **Kurbel** (22, 4) an der Ostwand drehen: Der Ring zieht hinter die Schutzplatte.
      b. **Wasserschieber** (22, 6) öffnen: 30 Minuten, die Risse werden kalt.
      c. **Schutzplatte** (17, 4) heben: **Fassung** (der Ring) in die Gruppe, 100 EP. Damit zählt das Relikt (Unruhe steigt um eine Stufe).
  13. **Hinausgehen** durch die Hallentür (15..16, 38): Man steht wieder vor dem Hallentor (10, 14), Hald und Svea warten. Hald fragt, wie es weitergehen soll.
- **Wahlen und Enden:**
  - **Svea soll jeden Ofen abnehmen:** In der Halle brennt danach ein Ofen (12, 22), Svea steht daneben (13, 23). Hald grüßt entsprechend.
  - **Hald soll bauen, wie er es für richtig hält:** Zwei Öfen brennen (12, 22) und (19, 22), Svea steht draußen am Tor.
  - Beide: der Ring geht mit, 120 Gold, 120 EP, Aufgabe erledigt. Halds Bedingung („bleibt im Sockel“) bricht man in jedem Fall.
  - Danach denkt {held} an das Sockelband: mit Orwins Blatt erkennt er die drei Zeichen wieder, ohne es verweist der Text auf Onno. Onno deutet auf **Herz** Quelle und Haus mit Fächern als Lichtenruh und das Moor bei Brackhafen (Hauptstrang).
  - Tor bei Tag mit Svea oder nachts allein: ändert Texte (Svea erklärt vs. Messingtafel, Gate-Szene „allein“), Spind mit oder ohne Probe.
  - Luftklappen: leichterer K2. Lohnbeutel: 60 Gold oder nicht, ohne spätere Folge.
- **Belohnung:** Ring 100 EP, Tor 120 EP und 120 Gold, Meldung bei Berthold in Dreifurt (**Alte Esse** nach Abschluss) 30 EP. Kampf-EP bei vier Köpfen etwa 92 + 115 + 130 je Kopf. Gegenstände: Fassung (Relikt), 2 Schürstangen, Gießerschürze, 2 Heiltränke, Glutkerne als Beute (Wert 30, Glutgestalt 60 %, Tiegelglut sicher 2), Lohnbeutel 60 Gold. Wort **Herz**. Neue Begrüßungen bei Folke, Wibo, Imke, Ingvar, Hedda, Sigrun, Onno, Hald, Svea, Beric.
- **Zum Testen:** Rückschlag-Meldung und Kampfzahl am Angreifer. Schürstange aus zwei Feldern. K2 mit und ohne Klappen. Tiegelglut verzögert aus dem Riss. Handgriffe in falscher Reihenfolge. Ist die Begegnung in Karrfels schon erledigt (`flag.q15a_done`), fehlt der Fremde und der Sockel bleibt ganz. Varka- und Beric-Einwürfe. Halle danach mit einem oder zwei brennenden Öfen. Bekannte Lücken: Halle innen größer als ihr Grundriss, das Gitter öffnet sich nicht sichtbar.

### Q15a Der Fremde am Ring · 🔴 PFLICHT

- **Auslöser:** Immer, solange die Kurbel noch nicht gedreht ist (seit Ä45 an jedem Relikt, als erste, zweite oder dritte Begegnung). Nach K3 beim ersten Schritt an den Sockel (oder an Kurbel, Schieber, Platte, Tafel): Doppelton, Lichtblitz, hinter dem Sockel (15, 3) steht ein Fremder und setzt einen Keil an den Ring. Ab der zweiten Begegnung erkennt man ihn wieder. Mit Svea: »Durch mein Tor ist er nicht gekommen.«
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Optional den Fremden ansprechen (er schweigt vorerst).
  2. **Kurbel** (22, 4) drehen: Der Keil reißt den alten Sockel auf. Vorwurf des Fremden: »Ihr wollt das Herz wecken.«
  3. Wahl (erste Begegnung): **Fragen, was er gesehen hat** (das Blatt mit den verzweigten Linien, 20 EP einmal), **Nach oben zeigen, zur Halle voll Reif** (er nennt selbst die drei Verbrannten: wer den Ring holt, trägt ihn dorthin, wohin die Zeichen zeigen), **Schweigen**. Nach der ersten Frage kann man die andere noch nachschieben. Als zweite Begegnung erkennt {held} ihn wieder: Er arbeitet schneller, bereut, beim letzten Mal geredet zu haben, und die Fragen lauten **»Wer seid Ihr?«** und **»Woher wusstet Ihr, wohin wir gehen?«** (20 EP für die erste). Als dritte weiß er, dass es das Letzte ist, was der Gruppe fehlt: **»Warum greift Ihr uns nicht an?«**, **»Was werdet Ihr jetzt tun?«** und, wer Wildas Bericht aus F01 kennt, **»Und die Frau an der Rinne in Lichtenruh?«** (20 EP für die erste). Er schließt mit »Dort bin ich vor Euch.« Die Frage nach den Leuten vor Ort gibt es in jeder Begegnung.
  4. Er geht über (16, 3), (17, 2), (17, 1) durch das Gitter des Wartungsgangs im Nordosten. 40 EP. Dann weiter mit Wasserschieber und Platte wie in Q08.
- **Wahlen und Enden:** Keine Folgen außer EP und Wissen. Szene und 40 EP zählen, sobald die Kurbel gedreht ist, auch wenn man das Gespräch mit Esc abbricht (dann geht er, sobald man ihn anspricht). Steht der Fremde gerade an einem anderen Relikt (man ist dort mitten in der Szene gegangen), wechselt er hierher.
- **Belohnung:** 40 EP Szene, 20 EP Frage, in jeder der drei Begegnungen.
- **Zum Testen:** Der Wartungsgang ist der Gang, nach dem der „stille Gast“ bei Imke und Hald gefragt hat. Varka kommentiert den Fremden in der ersten Begegnung, Beric in der zweiten, Jaro in der dritten (falls dabei).

### E06 Die Seile der Toten · 🟢 OPTIONAL

- **Auslöser:** Fährten: Frauke in Mühlbrück wartet auf ihren Messtrupp (Q24, Wort **Vermesser**). Gisbert, Folke und Imke nennen die **Seilklamm**. Am Graufelspfad steht ein **Wegweiser** (Weltkarte (336, 118), ansehen lehrt **Seilklamm**): »Seilklamm«, darunter ein helleres Brett »Der Korb steht.« Der Karrenweg in Zeile 119 führt nach Osten zum Eingang Weltkarte (344, 119). Die Aufgabe beginnt beim ersten Schritt an den Rand der Klamm (oder an Winde oder Eisenring). Auch ohne jede Vorgeschichte spielbar.
- **Stufe:** Stufe 7, vier Köpfe. Volles Nest: 2 Klammweberinnen (Stufe 7, werfen Fäden: verlangsamt) und 3 Klammspinnen (Stufe 7), ab fünf eine vierte Spinne verzögert. Nach dem Sturz des Korbs: 1 Weberin, 2 Spinnen (ab fünf eine dritte). Messung: Nest über den Steig zu viert 12 von 12 Siegen bei 44 % LP, Notabstieg 9 bei 32 %, ausgedünntes Nest 12 bei 66 %.
- **Lösungsweg** (Ortskarte Seilklamm, Ankunft (2, 5), Hochfläche auf Höhe 12, Absatz darunter auf Höhe 6):
  1. An den **Rand** treten: der halbe Korb am Tragseil über dem Absatz, darin ein Kasten mit Messingecken, darunter Gespinst mit zwei menschengroßen Bündeln. Wer **Vermesser** kennt, denkt an Fraukes Messtrupp (Journalzeile). Varka kommentiert.
  2. **Windenhaus** (8..12, 2..4, Tür (10, 4)): **Das Schloss öffnen** (Geschick mit Fingerfertigkeit 40) oder **Die Tür aufbrechen** (Stärke mit Athletik 45), Fehlschlag je 10 Minuten. Drinnen: Kreidebrett (letzte Fahrt „Zwei vom Bund, Messgerät, talwärts“), **Abstiegsseil** mit Zettel „Eisenring am Westrand“, Kiste „Für den Stein“ mit drei Strichen (Wort **Handelsstein**). Wahl **Die drei Barren einstecken** oder **Die Barren liegen lassen**.
  3. **Winde** (20, 7), solange der Korb hängt und das Nest lebt:
     - **Den Korbteil heraufkurbeln** (Stärke mit Athletik 45, Helfer zählen): Messkasten unbeschädigt nach oben.
     - **Die Sperrklinke zurückschlagen**: Der Korb stürzt ins Nest, das Nest ist ausgedünnt, der Messkasten ist verloren.
     - **Nichts anrühren.**
  4. Hinab, zwei Wege:
     - **Felssteig** im Osten (34..35, 9..14, sechs Stufen): Fäden melden die Gruppe, Kampf ohne Überraschung (Auslöser (32..33, 12..14)).
     - **Notabstieg** am **Eisenring** (9, 8) im Westen, braucht das Seil: **Am Seil hinabsteigen**, Landung (10, 10), Kampf mit Überraschung für die Gruppe (das Nest sitzt dann im Osten, die Nachzüglerin kommt aus der Ostnische). Das Seil bleibt als Weg.
     - Flucht führt an den Fuß des Steigs (34, 11).
  5. Nach dem Sieg die **Bündel** (21, 10) und (23, 10) aufschneiden: **Marken des Handelsbunds** (Harm, Lisbet), dann das **Messbuch** (Randnotiz: Tragseil aufgescheuert, dem Fuhrherrn in Karrfels gemeldet). Beric kommentiert. Wahl **Die beiden hinauftragen und oben begraben** (120 Minuten, 60 EP, zwei Steinhügel bei (14, 3)/(15, 3), Korgar kommentiert) oder **Sie liegen lassen**.
  6. Messkasten, falls nicht heraufgekurbelt und nicht zerschlagen: am hängenden Korbteil (22, 9) vom Absatz aus nehmen.
  7. **Gisbert** in Karrfels vor dem Fuhrhof (42, 40), nur bei Tag. Vorher lügt er (»leer abgegangen«, nach dem Blick vom Rand »Holz und Seil«). Mit dem Buch nach **Seilklamm** oder **Vermesser** fragen. Wahl:
     - **Die Seite laut vorlesen, hier auf dem Hof** (er steht öffentlich dafür ein): 50 EP.
     - **Verlangen, dass er den Familien zahlt**: Geldkatze des Fuhrherrn (für Frauke), 50 EP.
     - **Fragen, was ihm das Buch wert ist** (nur, solange Frauke den Eintrag nicht abgeschrieben hat): Rückfrage, **Das Geld nehmen** = 150 Gold, er nimmt das Buch, oder **Ablehnen**.
     - **Das Buch zurücknehmen und gehen.**
  8. **Frauke** in Mühlbrück, **Vermesser** mit den Marken: Sie nimmt die Nachricht (begraben oder nicht macht ihre Antwort anders), zahlt den Messkasten mit 60 Gold, und je nach Stand: öffentlich → nimmt das Buch, 40 EP; leise geregelt → nimmt Geldkatze und Buch, 40 EP; Buch verkauft → fragt nach dem Buch, 20 EP. Noch nicht bei Gisbert gewesen → sie **schreibt den Eintrag ab** (40 EP) und schickt die Gruppe mit dem Buch zu Gisbert, der Verkauf ist dann vom Tisch. Danach noch einmal zu ihr (**Vermesser**) zum Abschluss bzw. um die Geldkatze abzugeben.
- **Wahlen und Enden:** Abschluss, wenn Frauke Bescheid weiß und bei Gisbert geklärt ist (leise geregelt erst mit abgegebener Geldkatze). Bester Ausgang in EP: begraben + öffentlich/leise + Kasten = 150 EP + 60 Gold. Schnellster mit meistem Gold: Buch verkauft (150 Gold, nur 20 EP bei Frauke, Gisbert grüßt wie einen Geschäftsfreund). Korb fallen lassen: leichterer Kampf, kein Kasten. Windenhaus ausgelassen: kein Seil (nur Steig), keine Barren, kein Wort Handelsstein von hier.
- **Belohnung:** Begräbnis 60, Gisbert 50, Frauke 40 (verkauft 20). Kampf etwa 122 EP je Kopf. Kasten 60 Gold, Buch verkauft 150 Gold. Drei Eisenbarren (für V03). Wörter Seilklamm, Handelsstein.
- **Zum Testen:** Nach Heraufkurbeln steht der Korbteil neben der Winde (23, 7). Kämpfe beginnen mit fester Schrägsicht nach Norden. Beide Reihenfolgen Frauke/Gisbert. Bekannte Lücke: Dreht man die Schrägsicht von Hand, verdeckt die Nordwand Teile des Absatzes.

### V03 Der Handelsstein · 🟡 ENTDECKUNG

- **Auslöser:** Am Graufelspfad südlich des Seilklamm-Abzweigs, westlich des Pfads: eine Fläche aus blankem Fels mit einem hüfthohen Stein, Weltkarte (348, 144). Von Osten her nähern (Zellen um die Felsfläche). Kein Auftraggeber.
- **Stufe:** Stufe 7, vier Köpfe. Bei Tag 3 Kammechsen (Stufe 7, gepanzert, Stachelkamm: 40 % Gegenschlag auf Nahkampftreffer), ab fünf eine vierte verzögert. Messung: zu viert 10 von 12 Siegen bei 32 % LP. Bei Nacht liegen die Echsen starr, kein Kampf (und keine Kampf-EP).
- **Lösungsweg:**
  1. Annäherung: Beschreibung der Felsfläche, Haldaar kommentiert (falls dabei). Bei Tag Probe Wahrnehmung 40 (Helfer zählen): Wer die grauen Buckel als Tiere erkennt, beginnt den Kampf mit Überraschung.
  2. Die Platten um den Stein betreten: bei Tag Kampf gegen die Kammechsen (Flucht zurück auf den Pfad (353, 146)), bei Nacht nur eine Zeile.
  3. Am Stein (Wort **Handelsstein**): drei Kerben, drei Schneefelle unter einem Kiesel. Wahl:
     - Mit drei Eisenbarren (Windenhaus der Seilklamm oder Borga): **Drei Eisenbarren in die Kerben legen und die Felle nehmen** (fairer Tausch).
     - **Die Felle nehmen** (ohne etwas hinzulegen = Diebstahl).
     - **Alles liegen lassen.**
  4. Nach einem Diebstahl kann man später mit drei Barren zurückkommen: **Drei Eisenbarren in die Kerben legen** (nachgelegt, zählt dann als fair).
- **Wahlen und Enden:** Drei Schneefelle sind 210 Gold wert, drei Barren 72. Fair/Diebstahl/Nachgelegt verändern Haldaars Antwort auf **Handelsstein**, Kommentare von Haldaar und Beric und später das Gastrecht im **Sommerlager der Hünen** (Kapitel 7, Ulgaar und Händler Vaarek reagieren auf fair, Diebstahl oder Nachlegen, dort kann man die Felle auch zurückgeben).
- **Belohnung:** Kampf etwa 90 EP je Kopf, 3 Schneefelle (je 70). Keine Quest-EP.
- **Zum Testen:** Kampf bei Tag mit und ohne erkannte Gefahr, Nacht ohne Kampf, Tausch, Diebstahl, Nachlegen. Bekannte Lücke: Das Maul der Kammechse öffnet sich beim Angriff in manchen Richtungen kaum.

### Haldaar am Handelsstein · 🔵 GEFÄHRTE

- **Auslöser:** Haldaar sitzt auf einem Felsblock am Steinring, Weltkarte (352, 144), Blick West. Ansprechen von (353, 144) oder (352, 145). **Braucht einen Zwergischsprecher in der Gruppe** (Beric), sonst nur der Fremdentext.
- **Stufe:** tritt mit Stufe 7 bei.
- **Lösungsweg:** **Name** (lehrt **Hünen** und **Handelsstein**), **Arbeit**, **Handelsstein** (drei Antworten: neutral, nach fairem Tausch, nach Diebstahl), **Hünen**, **Zwerge**, **Goblins**. Anheuern im Dialog, ohne Bedingung. 30 EP, Kommentare von Beric und Korgar.
- **Empfehlung:** Erst den Stein fair bedienen, dann ansprechen (andere Antwort). Haldaar ist klaustrophobisch, also eher kein Kandidat für Grube und Dungeons. Er ist der Türöffner zum Sommerlager der Hünen (Kapitel 7).
- **Belohnung:** 30 EP.

### Q27 Die letzte Schicht · 🟢 OPTIONAL

- **Auslöser:** Erster Schritt auf den Grubenplatz (40..41, 4) oder Griff an den Grubenmund (40, 2), ohne Vorbedingung: Der alte Zwerg an der Winde (Runolf) hält das schlaffe Seil, an der Tafel hängt eine Marke. Aufgabe beginnt, Wort **Schicht**. Danach steht Hedda am Grubenmund (39, 3) (bei Tag).
- **Stufe:** Stufe 7 bis 8, vier Köpfe. Gegner (alle sehen im Dunkeln):
  - Tür (K1): 3 Grubenottern (Stufe 7, Biss 1W8+1) und 1 Speiotter (Stufe 7, speit Gift auf vier Felder), ab fünf eine vierte Otter.
  - Erzstoß (nur bei Kampfwahl): 2 Grubenottern, 1 Speiotter, ab fünf eine dritte Otter.
  - Haltekampf: Südwelle und Ostwelle, 4 Grubenottern, 2 Speiottern, zuletzt die **Alte Otter** (Stufe 9, 64 LP, Rüstung 3, Biss 2W6+2), ab fünf eine weitere Otter. Mit verkeilter Wettertür nur die Südwelle (2 Ottern, 1 Speiotter, Alte Otter).
  - Messung zu viert (12 Seeds): Tür 10 Siege, Erzstoß 12, Halten 18 Ticks 12, mit Trage (27 Ticks) ohne Vorbereitung nur 6, mit Feuerkorb 12, mit Wettertür 12, mit beidem 12 bei 71 % LP. **Vorbereitung lohnt sich deutlich.**
- **Lösungsweg** (Ortskarte Grube, tiefe Sohle):
  0. Vorher: Fackeln beim Krämer Ebbo, Gegengift (Speiotter vergiftet). Mit Runolf reden: **Arbeit** → **Schicht** (vier Namen, Klopfzeichen: drei Schläge heißt ziehen) → **Grube** → **Grubenottern** (die Ottern am warmen Sumpf).
  1. Am Grubenmund **einfahren** (10 Minuten). Ankunft am Füllort (22, 3). Korb (22, 2): jederzeit **Zweimal am Seil rucken und ausfahren**, solange die Schicht nicht oben ist.
  2. **Weststrecke** zur Weitung: Kampf K1 vor der verriegelten Tür (Auslöser (13, 5)/(13, 6)). Flucht zum Füllort (20, 6).
  3. **Tür der Zimmerkammer** (7, 6) anklopfen: Steiger Ketil öffnet, Jorid (am Arm gebissen) und Odd sind drin. 40 EP, Wort **Grubenottern**. Ketil nennt Arne, Feuerkorb, Wettertür und den Korb.
  4. **Brett** (1, 6): Keile und Hebebaum (ohne Probe für Tür und Stempel) und eine Fackel.
  5. **Feuerkorb** in der östlichen Ausweiche der Südstrecke (24, 13): **Den Feuerkorb anzünden** (10 Minuten). Die Südwelle kommt im Haltekampf später.
  6. **Wettertür** in der Oststrecke (32, 5): **Die Tür schließen und verkeilen** (mit Keilen ohne Probe, 10 Minuten, sonst Stärke mit Athletik 45). Im Haltekampf fehlt dann die Ostwelle.
  7. **Erzstrecke** (Auslöser (10, 18)/(10, 19)): Arne (Sveas Bruder) liegt unter einem Stempel (5, 18), Schlangen wärmen sich an ihm. Wahl:
     - **Eine Fackel anzünden und in die Nische legen** (Nische (7, 14)/(7, 15), kostet eine Fackel, 10 Minuten, 30 EP, kein Kampf, die Ottern liegen im Kreis um die Flamme).
     - **Die Schlangen mit der Waffe von ihm herunterholen** (Kampf, Arne wird gebissen, Flucht nach (14, 18)).
     - **Zurücktreten.**
  8. **Stempel** (5, 19) heben: mit Hebebaum ohne Probe (10 Minuten), sonst Stärke mit Athletik 45. 50 EP. Arne erzählt vom Eis am Sumpf. Ist die Kammer offen, tragen Ketil und Odd ihn auf die Trage (2, 8), sonst wartet er und wird geholt, sobald die Kammer offen ist.
  9. Freiwillig: **Sumpf** (Zeilen 21..30, Auslöser Zeile 25): Eisrand mitten im Berg, abgestreifte Häute, 20 EP, Varka kommentiert.
  10. **Klopfplatte** (25, 3) am Füllort (nur mit offener Kammer): **Drei Schläge**. Fehlt Arne, legt Ketil die Hand auf die Platte und nennt die Erzstrecke, Wahl **Jetzt schlagen, ohne Arne** (Arne bleibt zurück) oder den Hammer zurückhängen.
  11. **Haltekampf** am Füllort: Frist 18 Ticks (ohne Arne) bzw. 27 Ticks (mit Arne auf der Trage), Marke „Der Korb ist oben“. Fristende und Sieg zählen gleich. Flucht in die Kammer (5, 6), der Kampf lässt sich wiederholen. Danach stehen alle oben am Grubenplatz (41, 4), 70 EP.
  12. **Meldung** bei Hedda am Grubenmund (39, 3), auch nachts: **Schicht**.
- **Wahlen und Enden:**
  - Alle vier oben: 40 EP, 120 Gold und die **Grubenlampe** ihres Mannes (linke Hand, Licht 4 Felder, 48 Stunden). Ist kein Platz, hebt Hedda sie auf (später **Schicht** bei ihr).
  - Arne zurückgelassen: 40 EP, 90 Gold, keine Lampe, der vierte Teil geht an Svea. Runolf, Ketil, Svea und Hedda reden danach anders.
  - Fackel statt Kampf am Erzstoß: 30 EP und kein Biss. Ohne Fackel nur Kampf oder Rückzug.
  - Danach ist die Grube zu (keine Beute, kein Erz).
- **Belohnung:** 200 EP (Kammer 40, Arne 50, Halten 70, Meldung 40) plus 30 Fackel und 20 Sumpf. Kampf-EP je Kopf etwa 85 (Tür) + 65 (Erzstoß) + 175 (Halten). 120 Gold, Grubenlampe. Neue Zeilen bei Ingvar, Sigrun, Torvid, Yrsa, Runolf, Ketil.
- **Zum Testen:** Haltekampf in vier Lagen (nichts, Korb, Tür, beides), Wellen aus Süd und Ost, Marke der Frist. Spielstand ohne Arne. Lampe in einem dunklen Ort. Bekannte Lücken: Die Schicht steht oben nicht als Figuren (nur Ketil (37, 5)), Grube nach der Meldung gesperrt.

### V04 Der Schlackenring · 🟢 OPTIONAL

- **Auslöser:** Bei Tag auf der Schlackenhalde der Werkterrasse (Ring 46..50, 8..11): Tebbe (45, 9), Bolko (45, 10), Yrsa (51, 10). Wibo nennt den Ring (**Schlackenring**), ebenso der Blick auf die Halde. Zwei reglose Kammechsen am Rand (51, 7)/(52, 7) (Varka kommentiert).
- **Stufe:** Zweikampf **allein**: Es kämpft nur die gerade aktive (ausgewählte) Figur der Gruppe, also vorher den stärksten Nahkämpfer auswählen. Tebbe Stufe 6 (30 LP), Bolko Stufe 7 (40 LP, langsam, schlägt hart), Yrsa Stufe 9 (44 LP). Keiner stirbt. Messung (Held als Kämpfer Stufe 7 allein): Tebbe 12 von 12, Bolko 7, Yrsa 4.
- **Lösungsweg:**
  1. Tebbe ansprechen: **In den Ring treten**, **Reden** oder **Gehen**. Kampf im Ring.
  2. Danach Bolko (vorher schickt er einen zu Tebbe), dann Yrsa (erst nach den beiden).
  3. Eine Niederlage kostet nichts, man kann es wiederholen (»Der Ring ist morgen auch noch da.«). Flucht = aus dem Kreis steigen.
- **Wahlen und Enden:** Feste Reihenfolge. Nach dem dritten Sieg gilt man als Champion: Yrsas **Hauerkappe** (Kopf, Rüstung 2, Stärke +2), Korgar kommentiert, neue Antworten bei Tebbe, Bolko, Yrsa, Wibo, Imke, Folke.
- **Belohnung:** je Sieg 30 EP und 10, 20 bzw. 30 Gold aus dem Helm der Zuschauer (zusammen 90 EP, 60 Gold), Kampf-EP gering (15/20/30). Hauerkappe.
- **Zum Testen:** einmal verlieren, mit Korgar als aktiver Figur wiederholen. Bekannte Lücken: kein Einsatz der Gruppe, Waffenregel „Faust oder flache Klinge“ nur im Text, Zuschauer fehlen.

### Unruhe 2 und 3 in Karrfels · 🟡 ENTDECKUNG

- **Auslöser:** Unruhe = Zahl der geholten Relikte (Fassung, Abschrift, Antwort). Die Fassung zählt ab dem Moment, in dem man den Ring aus dem Sockel nimmt.
- **Was sich ändert:** In Karrfels ändert sich mit der Unruhe nur Imkes Antwort auf **Reisewege**: Stufe 1 (Kesselflicker kommen nicht mehr, Schranke am Moosfels, lehrt **Moosfels**), Stufe 2 (Orks auf der Nordroute, besser über Dreifurt, lehrt **Moosfels**), Stufe 3 (»In der Grube sagen sie, die Wärme geht. Jetzt gehen auch die Leute.«). Die Ortskarten von Karrfels, Seilklamm und Handelsstein haben keine Unruhe-Zustände (geprüft in Ortskarte, Ereignissen und Figuren). Die Weltkarten-Änderungen der Unruhe (Moosfels, Brandhof, Riss am Südweg) liegen in anderen Regionen.

---

**Empfohlene Reihenfolge (gründlich, vier Köpfe, Stufe 7 bis 8):**
1. Ankunft am Südtor, Varka anwerben, Wörter auf der Torterrasse sammeln, Brandhaus, Glocke, Hedda, Ingvar.
2. Beric vor dem Hallentor anwerben. Svea und Hald zu **Alte Esse**, Q08 bei Tag mit Svea (Pflicht, ggf. Q15a).
3. Schlackenring (V04) bei Tag mit dem stärksten Nahkämpfer.
4. Grube (Q27) mit Fackeln und Gegengift, Feuerkorb und Wettertür vorbereiten.
5. Osttor hinaus: Seilklamm (E06), dann Handelsstein (V03) mit Barren aus dem Windenhaus, Haldaar (mit Beric) anwerben.
6. Zurück nach Karrfels zu Gisbert, dann Frauke in Mühlbrück, Berthold in Dreifurt (Q08-Meldung).

**Offene Enden / Rückkehr später:**
- **Berthold** (Dreifurt) nimmt die Meldung zur **Alten Esse** jederzeit nach Q08 (30 EP).
- **Frauke** (Mühlbrück) für E06, ggf. zweimal (Abschrift, dann Abschluss nach Gisbert bzw. Geldkatze).
- **Handelsstein** nach einem Diebstahl mit drei Barren nachlegen (Barren bei Borga). Wirkt sich auf das **Sommerlager der Hünen** (Kapitel 7) aus.
- **Grubenlampe** bei Hedda abholen, falls beim Abschluss kein Platz war. **Hauerkappe** bei Yrsa ebenso.
- **Herz:** Onno (Karrfels) und Alva (Glasgrund) antworten auf das Wort aus dem Ofenraum. Die Fassung selbst wird erst in der Herzsenke (Herzkammer) gebraucht.
- **Imke** nach jedem weiteren Relikt nach **Reisewege** fragen (Unruhe 2 und 3).
- Hauke und seine Fuhre erscheinen erst, wenn Q25 (Kohlenfuhre, Startdreieck) erledigt ist, dann tags am Wagen (22, 37), nachts im Krug.
- Der Fremde kommt in Karrfels immer. War Karrfels nicht das erste Relikt, erkennt die Gruppe ihn wieder (zweite oder dritte Begegnung).

---

## Kapitel 5 · Brackhafen und Glockenwacht

**Anreise:** Brackhafen liegt an der Westküste, beiderseits der Mündung der Brack. Drei Tore auf der Weltkarte führen in die Ortskarte:
- **Nordtor** Weltkarte (64, 83): Straße von Mühlbrück nach Süden. Ankunft am Nordtor der Stadt (38, 1).
- **Osttor** Weltkarte (72, 91): Küstenstraße von Dreifurt bzw. Damm nach Osten. Ankunft am Osttor (58, 16). Hinter diesem Tor zweigt später der Steinweg zum Moorarchiv ab.
- **Südtor** Weltkarte (64, 103): Brücke nach Süden, Deichweg Richtung Glasgrund. Ankunft am Südtor (38, 48).
Wer die Stadt verlässt, steht auf der Zelle vor dem jeweiligen Tor: (64, 82), (73, 91) bzw. (64, 104). Die Stadt betritt man ohne Kampf. Die erste Ankunft gibt 20 EP und einen Text je nach Tageszeit (Tag, Dämmerung, Nacht).
Glockenwacht (Insel westlich der Stadt, Weltkarte ab (18, 68)) ist nur mit dem Lotsen Oshe vom Lotsensteg der Stadt zu erreichen; ein Strömungsring aus Wasser um die Insel lässt weder Boot noch Schwimmen durch. Die Leitfeuerbank (Weltkarte 35..51 / 75..82) erreicht man nur mit Sives Kahn oder Tedes Boot, das Nordufer (47, 71) nach Q05 mit Sives Fähre.

**Wann:** Nach Karrfels. Gründlicher Weg mit vier Köpfen: beim Betreten etwa Stufe 10–11, beim Verlassen 12–13. Wer Karrfels nicht vollständig gemacht hat, kommt mit 8 aber auch durch. Gegner der Region Stufe 8 bis 12 (Hocker 9, Alter Hocker 11, Schlickegel 8, Archivwächter 12, Flimmervogel 9, Höhlenkrabbe 9, Strandräuber 8–9). Die Balance-Tests messen mit Held als Kämpfer plus drei bzw. vier Gefährten auf Stufe 8 (Leitfeuerbank, Moorarchiv) bzw. Stufe 9 (Turm, Höhle, Strand). Empfehlung: mindestens Stufe 8 und vier Köpfe; Moorarchiv (Pflicht) und Leitfeuerbank zuerst, Glockenwacht ab Stufe 9.

**Die Stadt in zwei Schichten:** Menschen stehen bei Tag und in der Dämmerung draußen (Eren, Tede, Maren, Fenna, Neve, Tagwache, Wirtin Geske), das Katzenvolk in der Dämmerung und bei Nacht (Sive, Tesh, Mirr, Nachtwache Ishan, Wirt Rasho). In der **Dämmerung** stehen beide Schichten am Kai, das ist die beste Uhrzeit für einen Rundgang. Ashka flickt zu jeder Stunde Netze. Wer schläft, antwortet hinter seiner Tür: Eren (Hafenamt, Tür (23, 12)), Neve (Pegelhaus, Tür (22, 34)) und Maren (Haus an der Salzzeile, Tür (44, 13)) bei Nacht, Sive (Fährhaus, Tür (22, 4)) bei Tag.

**Dienste:**
- **Gasthaus „Zur Aalreuse“**, Tür (32, 5) am Nordufer: bei Tag und Dämmerung Wirtin **Geske**, bei Nacht Wirt **Rasho**, beide hinter dem Schanktisch (5, 2). Zimmer 6 Gold die Nacht, Proviant 1 Gold, Gefährten (Wartebank), Gepäck verwahren. Geske fragt man nach **Reisewege** (Gerüchte je Unruhestufe: Schranke am Moosfels, Orks auf der Nordroute, Fremde, die nach Land fragen).
- **Krämer Hayo**, Tür (31, 34) am Südufer, nur bei Tag (nur hinter der Tür, keine Figur): Fackel, Heiltrank, Gegengift, Schleuder, Lederkappe. Bei Nacht nennt die Tür das Wort **Pfahlgasse**.
- **Händler Mirr**, Nachtstand in der Pfahlgasse (14, 15), Dämmerung und Nacht: Fischspeer (1W6+1, Reichweite 1–2), Fackel, Heiltrank, Feuerflasche, Holzschild.
- **Baderin Wiebke**, Tür (50, 13) an der Salzzeile, zu jeder Stunde (nur hinter der Tür): Heilung 1 Gold je LP, heilt Gift, Verletzung, Verlangsamung, Lähmung, Verwirrung.
- Keine Gilden, kein Tempel.
- Auf Glockenwacht: Odo gibt nach Q13 einmal sechs Rationen, sonst keine Dienste.

**Gefährten:** **Jaro** (Gnom, Graumagier, tritt mit Stufe 8 bei) kniet am Ostpfahl (31, 29), spricht aber nur Elfisch und Gnomisch: **Tavion** übersetzt, siehe Eintrag K Jaro. **Rhiann** (Mensch, Schützin, Stufe 8) auf Glockenwacht nach Q13. Namar (aus Dreifurt) und Varka und Beric kommentieren hier vieles, nötig ist keiner.

---

### Ankunft und kleine Funde in Brackhafen · 🟡 ENTDECKUNG
- **Auslöser:** Betreten der Stadt; die Funde liegen frei herum.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Erste Ankunft durch ein beliebiges Tor: 20 EP.
  2. **Fährseil** am Westkai: den Seilpoller (14..16, 2) ansehen oder benutzen. Das Seil ist dreimal angespleißt und reicht nicht mehr hinüber. 10 EP, Wort **Fähre**. Wichtig: erst damit nennt Sive später das Wort **Rinne** (Start von Q05).
  3. **Zwei Lichter:** bei **Nacht** ans Ende des Fährstegs gehen, Zellen (8, 9) oder (9, 9) betreten. Zwei Lichter über dem Wasser, wo eines sein sollte. 10 EP, Wort **Zwei Lichter** (Namar: »Als ich ging, war es eines.«). Bei Tag nur eine Zeile ohne EP.
  4. **Gästebuch** in der Aalreuse auf dem Schanktisch (5, 3) ansehen oder benutzen: zwei Handschriften. 10 EP, Wort **Zwei Schichten**.
  5. **Flößerpfähle** am Kai (30, 22): nur wenn Q22 (Hinnerks Floß) erledigt ist, erkennt man die Flößerkerben. 10 EP.
  6. Stimmung ohne EP: Pegel am Südkai (17, 31), Haspel mit Neves Messleine (26, 30, zweimal verlängert), Wasserstein (36, 30), Siedehütten, Pfannen (kalte Pfanne Marens bei (56, 7)), Boote, Netzgestelle der Pfahlgasse.
- **Wahlen und Enden:** keine.
- **Belohnung:** 20 + 4 × 10 EP, Wörter Fähre, Zwei Lichter, Zwei Schichten. Weitere Wörter der Stadt aus Gesprächen: Salz, Waage, Nebel, Pfahlgasse, Pegel, Kesh, Das gute Boot, Glockenwacht.
- **Zum Testen:** Tag/Nacht-Belegung der Figuren, Dämmerung als Schichtwechsel, Türen bei Nacht, Pfahlgasse auf Stegen über dem Schlick, Automap-Namen (Hafenamt, Salzspeicher, Fährhaus, Pegelhaus, Salzzeile, Pfahlgasse). Zeichen des Unterstroms nur als Beobachtung: zu kurzes Seil, verlängerte Messleine, Lichter zu weit draußen.

### Q07 Das Gewicht des Salzes · 🟢 OPTIONAL
- **Auslöser:** Salzsiederin **Maren** (Witwe) steht bei Tag und Dämmerung an ihrer kalten Pfanne im Nordosten der Salzzeile (55, 7), bei Nacht hinter ihrer Haustür (44, 13). Nach **Arbeit** fragen (lehrt **Salz**), dann nach **Salz**: Sie erzählt von vier fehlenden Pfund je Sack und dem Schwundzoll (lehrt **Waage**, **Nebel**, **Glockenwacht**). Vorher schweigt die Waage und Eren weicht aus.
- **Stufe:** kein Kampf.
- **Lösungsweg (voller Weg):**
  1. Maren auf **Salz** ansprechen (Auftakt).
  2. An der **Hafenwaage** vor dem Hafenamt (25, 14) den Sack mit der Marke wiegen (Benutzen, 10 Minuten, 20 EP): bei Nacht oder Dämmerung **hundert Pfund** (Leinen klamm), bei Tag **sechsundneunzig Pfund**.
  3. Bis zur anderen Tageszeit warten bzw. rasten und erneut wiegen (wieder 20 EP). Mit beiden Zahlen erklärt sich der „Schwund“ als Feuchtigkeit.
  4. Hafenmeister **Eren** an der Waage (24, 14), Tag und Dämmerung, auf **Salz** ansprechen, Wahl **„Beide Gewichte desselben Sacks nennen“**: Eren streicht den Schwundzoll und führt einen Nebelabzug ein. 80 EP, Quest erledigt.
  5. Zurück zu Maren, **Salz**: 30 Gold und das **Ölzeug** ihres Mannes (leichte Rüstung 3). Danach brennt ihre Pfanne wieder.
- **Wahlen und Enden:**
  - **Raten (kürzer, schwächer):** Schon mit null oder einer Zahl kann man Eren um **„Raten für die Witwe bitten“**: Probe Charisma 45 mit Hilfe, nur ein Versuch. Gelingt sie: 50 EP, Quest erledigt, Maren zahlt auf **Salz** 10 Gold, der Zoll bleibt. Misslingt sie: Es bleibt der Weg über die Zahlen (keine Sackgasse).
  - Nach den Raten beide Zahlen nachreichen (Eren, **Salz**): Eintrag berichtigt, 30 EP; Maren zahlt dann 20 Gold mehr und gibt das Ölzeug.
  - Verzahnung: Mit Erens berichtigtem Buch zahlt er in Q05 für das Leitfeuer am meisten (60 Gold).
- **Belohnung:** Wiegen 2 × 20, Abschluss 80 (bzw. Raten 50 + Berichtigung 30) = 120 EP; 30 Gold und Ölzeug (oder nur 10 Gold bei Raten ohne Nachreichen).
- **Zum Testen:** Wer bei Nacht ankommt, findet Maren hinter der Tür und kann sofort im Nebel wiegen. Erneutes Wiegen gibt nur eine Logzeile. Marens Pfanne nach dem Abschluss (Kartenzustand). Ölzeug bei vollem Gepäck (eigener Text).

### V05 Namars Leute (Bootsschuld) · 🟢 OPTIONAL
- **Auslöser:** Netzmacherin **Ashka** (Katzenvolk) flickt zu jeder Stunde Netze im Netzboden der Pfahlgasse (7, 21), im Westen der Stadt auf den Stegen über dem Schlick.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. **Mit Namar in der Gruppe** (Gefährte aus Dreifurt): Ashka ansprechen. Sie erkennt ihren Neffen, der vor vier Wintern das dichte Boot nahm. Die Szene läuft einmal: 20 EP, Wörter **Kesh** und **Das gute Boot**.
  2. **Ohne Namar:** Ashka nach **Arbeit** fragen (lehrt **Kesh**), dann nach **Kesh**: Sie erzählt von ihrer Tochter Kesh, die vor neun Nächten mit Jirr auf das Feuer von Glockenwacht zu hinausfuhr und nicht zurückkam (20 EP, lehrt **Das gute Boot**, **Zwei Lichter**, **Glockenwacht**).
  3. Danach die Wahl **„Versprechen, drüben nach Kesh zu suchen“** (20 EP, Namar: »Ich hätte es selbst sagen sollen.«) oder **„Nichts versprechen“** (kein Nachteil).
  4. **Bootsschuld:** Mit Namar in der Gruppe Ashka nach **Das gute Boot** fragen: Angebot, das Boot zu bezahlen, 40 Gold. Bezahlt: 30 EP. Ashka nimmt es an und vergibt nichts.
- **Wahlen und Enden:** Versprechen oder Schweigen; eingelöst wird es in E09 (Kesh in der Höhle unter Glockenwacht), mit Versprechen hört man dort von Ashka einen eigenen Satz. Die Bootsschuld ist unabhängig davon.
- **Belohnung:** 20 + 20 EP, mit Bootsschuld + 30 EP (für 40 Gold). V05 hat keinen Tagebucheintrag. Ist Rhiann dabei, wenn Namar das Boot bezahlt, +15 zwischen den beiden (Freunde und Rivalen).
- **Zum Testen:** Beide Fassungen (mit/ohne Namar), Bootsschuld mit und ohne 40 Gold. Nach Kesh Rückkehr hat Ashka eine neue Begrüßung. Später (Lichtenruh, Q11) kennt sie das Wort **Pilgerweg**.

### Q05 Das Fahrwasser ohne Ufer (Leitfeuerbank) · 🟢 OPTIONAL
- **Auslöser (zwei Einstiege):**
  - **Sive** (Fährfrau, Katzenvolk), nur Dämmerung und Nacht am Fährseil (17, 3) am Westkai: Erst **nachdem man das Fährseil angesehen hat** (H4), antwortet sie auf **Fähre** mit dem Wort **Rinne**. **Rinne** startet die Aufgabe (10 EP, lehrt **Leitfeuer**, **Baken**, **Überfahrt**, **Hocker**).
  - **Eren** (Hafenmeister, Tag und Dämmerung, Waage (24, 14)): **Arbeit** lehrt **Fähre**, **Fähre** lehrt **Leitfeuer**, **Leitfeuer** startet (10 EP, lehrt **Überfahrt**, **Hocker**).
  - Wer ohne Auftrag auf die Bank gerät und siegt, hat die Aufgabe ebenfalls.
- **Stufe:** Stufe 8–9 mit vier Köpfen. Gegner: **Alter Hocker** (Stufe 11, 70 LP, Schalenplatte vorn 8) und **drei Hocker** (Stufe 9, 32 LP, Platte vorn 6), ab fünf und sechs Figuren je ein Hocker mehr, furchtlos. Balance-Test: Held (Kämpfer), Korgar, Tavion, Namar auf Stufe 8. Messung: vom Westende bei Nacht mit Überraschung 12 von 12 gewonnen (26 % LP übrig), vom Ostende bei Tag nur 6 von 12, vom Westende bei Tag 0 von 12. **Dringende Empfehlung: mit Sive bei Nacht vom Westende.**
- **Lösungsweg:**
  1. Überfahrt wählen:
     - **Sive auf Überfahrt** (nur Dämmerung/Nacht): 40 Minuten, sie stakt an das **Westende** der Bank, Landestelle (36, 79), und nennt unterwegs ihre Regel für das Wasser: »Glatt und dunkel trägt. Kraus und hell trägt nicht.«
     - **Eren auf Überfahrt** (bei Tag): Tede rudert in 60 Minuten an das **Ostende**, Landestelle (50, 79). Keine Regel, keine Überraschung.
  2. Auf den Sand gehen: Jede Sandzelle der Spalten 39..49 löst den Kampf aus (ebenso das Benutzen der Gruppe auf dem Feuerpodest (43, 79) oder die Bakenplätze B, D, E). Vom Westende außerhalb des Tages beginnt die Gruppe mit Überraschung.
  3. **Kampf:** Die Hocker sind von vorn gepanzert (Frontpanzer), von der Seite und von hinten weich. Umgehen statt Anrennen. Hinweis im ersten Zug. Flucht führt an die Landestelle zurück. Sieg: 100 EP, Bank frei.
  4. **Baken ziehen:** die drei alten Baken im Sand benutzen: (44, 77), (44, 81), (46, 78). Jede gibt eine Bake ins Gepäck (Gepäck muss Platz haben).
  5. **Baken setzen:** Bakenplätze am Rand der Bank betreten, das Wasser wird beschrieben, dann setzen. Plätze: A (37, 76), B (43, 75), C (36, 81), D (42, 82), E (49, 81). **Richtig sind A, C und D** (glattes, dunkles Wasser), falsch B und E (hell, kraus). Ohne Sives Regel läuft am ersten Platz einmal eine Probe Wahrnehmung 50 mit Hilfe. Gesetzte Baken lassen sich wieder herausziehen, bis die Aufgabe erledigt ist.
  6. **Feuerkorb** (42, 79) auf dem Podest nach dem Sieg wahlweise anzünden (Licht Radius 6) oder kalt lassen, auch wieder löschen.
  7. Zurück: beim Fährmann an der Bank (Sive bzw. Tede) **Überfahrt** oder die Zelle am Kahn benutzen. Ankunft am Westkai (18, 3) bzw. am Steg (16, 9).
  8. **Sive auf Baken** (Dämmerung/Nacht): Mit A, C, D richtig 100 EP und die **Blendlaterne** (Licht Radius 5, 72 Stunden), Aufgabe erledigt. Mit drei Baken an anderen Plätzen setzt sie selbst um: 60 EP, erledigt. Fehlt eine Bake oder liegt eine im Gepäck, wartet sie.
  9. **Eren auf Leitfeuer** nach dem Sieg (einmal): 50 EP und Gold: **60** mit berichtigtem Buch aus Q07, sonst **40** bei brennendem Feuer, **25** bei kaltem.
- **Wahlen und Enden:** Überfahrt West (Nacht, Überraschung, Regel) oder Ost (Tag); Feuer an oder aus (Eren zahlt mehr, Sive merkt an, dass es an der falschen Stelle leuchtet); Baken richtig oder falsch (endet in beiden Fällen). **Folge:** Sive fährt danach auf **Fähre**/**Überfahrt** zum **Nordufer**, Landestelle Weltkarte (47, 71), für 6 Gold (3 Gold, wenn die Baken richtig standen), 30 Minuten; am alten Pfahl (48, 71) ruft man sie zum selben Lohn herüber. Zur Bank fährt sie weiter umsonst. Q05 öffnet bei Neve die Messleine (Q06) und bei Eren das Wort für die Strandräuber (V07).
- **Belohnung:** 10 + 10 (beide Auftaktgeber) + 100 (Sieg) + 100 (Sive, bzw. 60) + 50 (Eren) = bis 270 EP, Kampf bei 4 Köpfen etwa 162 EP je Kopf; 25/40/60 Gold, Blendlaterne.
- **Zum Testen:** Frontpanzer spürbar? Hocker im Dunkeln zu finden? Bakenbeschreibungen mit und ohne Regel. Feuer bei Nacht von der Stadt aus. Fähre mit zu wenig Gold. Bekannt: Vom Westende bei Tag (wer auf der Bank den Morgen abwartet) ist der Kampf kaum zu gewinnen; am Nordufer steht nur der Pfahl.

### Q06 Das Gedächtnis des Moors (Moorarchiv) · 🔴 PFLICHT (Relikt „Abschrift“)
- **Auslöser:** Pegelschreiberin **Neve** steht bei Tag und Dämmerung am Pegelhaus am Südufer (25, 30), bei Nacht hinter der Tür (22, 34). Mit Orwins Wort **Hüter** gibt sie die Messleine sofort und erklärt die Messung (Hauptstrang), Hafenmeister Eren schickt auf **Hüter** zu ihr. Auf **Pegel** gibt sie die Messleine erst, wenn die Gruppe einen der beiden **Pegelpfähle** angesehen oder benutzt hat (oder Q05 bzw. Q07 erledigt ist). Pegelpfähle: West (23, 28), Ost (31, 28), im Wasser der Mündung, vom Südkai aus zu benutzen (z. B. von (23, 29)). Das Wort **Pegel** lehrt Neve auf **Arbeit**, ebenso Hayo auf **Brackhafen** und Jaro.
- **Stufe:** Stufe 8–9 mit vier Köpfen. Gegner: **Schlickegel** (Stufe 8, 34 LP, Biss 1W8+2, vier, ab fünf und sechs Figuren je einer mehr) im Ablaufraum, **Archivwächter** (Stufe 12, 180 LP, Rüstung 3, Steinfäuste 2W8+5, allein) in der Halle. Balance-Test: Held (Kämpfer), Korgar, Tavion, Namar auf Stufe 8: Egel 12 von 12 (44 % LP übrig), Wächter trocken 9 von 12 (19 %), mit Überraschung 9 von 12, im Wasser 9 von 12; zu fünft (mit Varka) 12 von 12. Der Wächter ist der schwerste Kampf der Region: ausgeruht und geheilt hineingehen.
- **Lösungsweg (kürzester Weg):**
  1. Bei Tag in die Stadt, Neve auf **Arbeit** (lehrt **Pegel**).
  2. Den Westpfahl (23, 28) ansehen.
  3. Neve auf **Pegel**: Sie gibt **Neves Messleine** (sagt die Zahl nicht).
  4. Einen Pfahl benutzen (Leine einhängen), dann den anderen (messen): 10 Minuten, **41 Knoten**, 20 EP. Reihenfolge egal.
  5. Neve erneut auf **Pegel**: Sie schlägt das Pegelbuch auf (38 Knoten bei ihrem Vater, 39 und 40 bei ihr), beschreibt den Weg, sagt den Satz ihres Vaters »Erst das Wasser, dann die Tür.« und gibt den **Schlüssel zum Moorarchiv**. Lehrt **Moorarchiv**, **Vater**, **Steher**.
  6. Durch das **Osttor** hinaus. Laut Neve: der Straße über den ersten Plankensteg folgen, kurz danach, noch vor dem zweiten Steg, zweigt ein **Steinweg** nach Süden in den Moorsee ab (Weltkarte (88, 98..101)). Er knickt bei (86, 103) nach Westen und endet an der **Archivinsel** (82..87 / 105..108) mit einem gemauerten Hügel. Neve rät, bei Tag zu gehen: Bei Nacht stehen Irrlichter über dem Wasser, am Knick einmal Probe Wahrnehmung 40 mit Hilfe (misslungen 1W4 Schaden, 20 Minuten).
  7. Von (85, 107) die Tür (85, 106) im Hügel benutzen (braucht den Schlüssel). Ankunft im Archiv (12, 21), 20 EP für das Betreten.
  8. **Obere Kammer:** Pult (11, 17) mit den Zetteln des Vaters (»Erst das Wasser, dann die Tür. Der Schieber sitzt im Westen, im Nassen. Dort beißt etwas.«), Relief (8, 18) zeigt eine volle und eine leere Kammer. Obere Tür (12, 15) öffnen.
  9. **Schleusenkammer** (knöcheltief unter Wasser): **nicht** zuerst die untere Tür (12, 11) öffnen. Stattdessen nach Westen durch den Gang (6..8, 13; einmal Wahrnehmung 35 mit Hilfe: Wer die Egel bemerkt, beginnt den Kampf mit Überraschung) in den **Ablaufraum**.
  10. **Kampf Schlickegel** beim Betreten von (6, 13) oder des Raums. Flucht zurück auf (12, 13). Die Egel kommen von mehreren Seiten: nicht umstellen lassen.
  11. **Schieber** (2, 16) benutzen: Probe Athletik bzw. Stärke 40 mit Hilfe, beliebig oft (je Fehlschlag 10 Minuten). Die Kammer läuft leer.
  12. Jetzt die **untere Tür** (12, 11): Sie öffnet trocken, 40 EP. Die Halle bleibt trocken.
  13. An der Schwelle (12, 10) einmal Wahrnehmung 40 mit Hilfe: Wer bemerkt, dass der Kopf der Steinfigur sich bewegt, überrascht den Wächter.
  14. **Kampf Archivwächter** (steht auf (12, 6), löst in den Zeilen 2 bis 9 oder beim Benutzen aus). Langsam, hart, Regale geben Deckung. Flucht zurück in die Schleusenkammer (12, 13), er folgt nicht über die Schwelle. Sieg: 60 EP.
  15. **Pegelblätter der Hüter** aus dem untersten Fach (8, 8) nehmen (nur trocken, 36 Knoten, älteste Zahl der Reihe).
  16. Jetzt **Q15b** (nächster Eintrag) erledigen, solange der Fremde hinter dem Altar steht, flackert er nur.
  17. **Schwarzer Altar** (12, 3) benutzen: Er erwacht. Drei Kerben nacheinander berühren: **linke** (Bogen mit drei Kerben schließt sich zum Ring und senkt sich in eine Mulde; mit dem Ring aus Q08 erkennt die Gruppe die Fassung), **mittlere** (Welle steigt über die oberste Pegelmarke, daneben ein Warnzeichen aus drei gebrochenen Balken), **rechte** (Kreis mit Punkt, sieben Zeichen und Gegenzeichen, am Rand derselbe Kreis offen und durchgestrichen). Danach **„Alles abzeichnen“**: eine Stunde, **Abschrift vom schwarzen Altar**, 80 EP. Das ist das Pflicht-Relikt.
  18. Ausgang (12, 22) zurück auf die Insel.
  19. Zurück in Brackhafen Neve auf **Moorarchiv**: Sie liest die Abschrift, 60 Gold, 80 EP, nimmt die Leine zurück, Quest erledigt. Mit den Pegelblättern dazu 40 Gold und das Wort **Herz**. Die Abschrift bleibt bei der Gruppe.
- **Wahlen und Enden:**
  - **Nasser Weg:** Wer zuerst die untere Tür aufzieht (Rückfrage „Die Tür aufziehen“), flutet die Halle. Spart Egel und Schieber, kostet aber die Pegelblätter (grauer Brei), die 40 EP der Schleuse, Neves zweiten Lohn (40 Gold, Wort Herz von ihr) und die Überraschung gegen den Wächter. Im Wasser kostet jeder Schritt doppelt, auch für den Wächter. Die Abschrift bleibt möglich. Der Schieber leert danach nur noch die Kammer.
  - Die Insel ist auch schwimmend erreichbar, die Tür braucht trotzdem den Schlüssel.
  - Verzahnung: Die Abschrift ist eines der drei Relikte für die Herzsenke und erhöht die Unruhe um eins. Neve trägt alle Pflichtauskünfte, kein Gefährte ist nötig.
- **Hauptstrang:** Beim Lesen der Abschrift deutet Neve den Ring mit drei Kerben auf Karrfels und den Kreis mit sieben Antworten auf die Quelle von Lichtenruh, solange diese Stücke noch fehlen.
- **Belohnung:** Messen 20, Betreten 20, Schleuse 40, Wächter 60, Abschrift 80, Neve 80 = 300 EP; Kämpfe bei vier Köpfen etwa 90 (Egel) + 125 (Wächter) je Kopf; 60 + 40 Gold, Abschrift, Wort Herz.
- **Zum Testen:** Beide Schleusenfolgen in je einem Spielstand. Kommentare: Jaro (Relief: »Voll und leer, nebeneinander …«, mittlere Kerbe), Varka (Halle, der Fremde), Beric (Altar, Abschrift). Irrlichter bei Nacht (Objekte auf (84, 102), (89, 104), (88, 106), (81, 105)). Bekannt: Irrlichter erscheinen erst nach einem Ereignis, nicht genau mit der Dämmerung; der Fremde steht aufrecht statt gebeugt.

### Q15b Der Fremde am Altar · 🔴 PFLICHT
- **Auslöser:** Immer, solange Abschrift und Hebel offen sind (seit Ä45 an jedem Relikt, als erste, zweite oder dritte Begegnung). Nach dem Sieg über den Archivwächter steht er hinter dem schwarzen Altar (12, 2), tief über den Stein gebeugt; an seinen Schultern hätte Varka ihn nicht kommen hören.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Den Altar berühren: Die Zeichen flackern und reißen ab, hinter dem Altar glüht eine Naht, daneben ein Hebel. Den Fremden ansprechen: »Nicht jetzt. Fasst den Altar nicht an.«
  2. Den **Wartungshebel** (14, 1) in der Nordwand benutzen: Eine Abdeckung schiebt sich vor die Rückseite. Der Fremde steht auf und wirft der Gruppe vor, das Herz wecken zu wollen. Wort **Herz**.
  3. Wahl (erste Begegnung): **„Was habt Ihr gesehen?“** (er zeigt ein Blatt mit dem immer gleichen Muster in wachsendem Maßstab, 20 EP) oder **„Und die Leute, die am Wasser leben?“** (er weiß von den Pfählen und der Schreiberin). Als zweite Begegnung erkennt {held} ihn wieder: Er arbeitet schneller, bereut, beim letzten Mal geredet zu haben, und die Fragen lauten **»Wer seid Ihr?«** und **»Woher wusstet Ihr, wohin wir gehen?«** (20 EP für die erste). Als dritte weiß er, dass es das Letzte ist, was der Gruppe fehlt: **»Warum greift Ihr uns nicht an?«**, **»Was werdet Ihr jetzt tun?«** und, wer Wildas Bericht aus F01 kennt, **»Und die Frau an der Rinne in Lichtenruh?«** (20 EP für die erste). Er schließt mit »Dort bin ich vor Euch.« Die Frage nach den Leuten vor Ort gibt es in jeder Begegnung.
  4. Er geht durch das Gitter (10, 1) in der Nordwand, Abblende. 40 EP. Danach den Altar normal nutzen (Q06 Schritt 17).
- **Wahlen und Enden:** Frage (mehr Wissen, 20 EP) oder Einwand. Wer erst später an den Altar kommt (etwa weil der Fremde gerade an einem anderen Relikt stand), trifft ihn beim nächsten Anfassen von Altar oder Hebel.
- **Belohnung:** 40 EP, mit der Frage 60 EP, Wort Herz, in jeder der drei Begegnungen.
- **Zum Testen:** Spielstand mit vorheriger Begegnung in Karrfels: Altar steht allein, Hebel ohne Szene.

### Jaro · 🔵 GEFÄHRTE
- **Auslöser:** Jaro kniet zu jeder Stunde am Südufer vor dem östlichen Pegelpfahl (31, 29) und schreibt die Kerben ab. **Er spricht nur Elfisch (und Gnomisch)**: Ohne ein Gruppenmitglied, das Elfisch spricht, versteht man ihn nicht (nur „Gehen“). Elfisch sprechen in der Westmark **Tavion** (ab Mühlbrück dabei) und **Venya** (Lichtenruh): Tavion also nach Brackhafen mitnehmen.
- **Stufe:** Graumagier, tritt mit **Stufe 8** bei (wird angehoben). Gnom.
- **Lösungsweg:**
  1. Mit einem Elfisch-Sprecher Jaro auf **Name** ansprechen (Jaro Kupferfinger, Graumagier, lehrt **Pegel**, **Gold**).
  2. Nach **Pegel** fragen: Die untersten Kerben im Ostpfahl sind älter als Neves Buch, er will mit, wenn die Gruppe herausfindet, wo es steht. Nach Q06 fragt er stattdessen nach dem Archiv. Beides öffnet die Aufnahme.
  3. Im Dialog aufnehmen. Vorher nur Ablehnung (»Mitgehen? Wohin denn, und wozu?«).
- **Wahlen und Enden:** keine.
- **Belohnung:** einmalig 30 EP beim Beitritt (Beric: »Ein Gnom? Dann zähle ich besser mein Gold.«).
- **Zum Testen:** Gespräch vor/nach der Frage nach dem Pegel, Beitritt bei voller Gruppe, ohne Elfisch-Sprecher.

### Überfahrt nach Glockenwacht · 🟢 OPTIONAL
- **Auslöser:** Der Lotse **Oshe** (Katzenvolk) steht am Ende des Lotsenstegs (17, 10) im Westen der Stadt, Blick nach Süden. Sive und Tesh nennen ihn auf **Glockenwacht**. Ansprechen ist ohne Vorbedingung möglich.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Oshe ansprechen (Vorstellung beim ersten Mal), Wahl **„Zur Insel übersetzen“**. Bei Tag (vor Q13) fährt er nicht, bietet aber **„Bis zur Dämmerung warten“** an.
  2. Bezahlen (**15 Gold**, schweigende Fahrt, 20 EP) oder **„Im Bug sitzen und Ausschau halten“** (Mitarbeit, 40 EP) mit drei Entscheidungen; jede falsche kostet 60 Minuten, nie den Weg:
     - Wonach steuern? **„Nach der Laterne im Rücken“** (richtig).
     - Das gelbe Feuer verschwindet: **„Kurs halten“** (richtig; wo man das Feuer sieht, liegt jetzt die Bank).
     - Worauf im Dunst zuhalten? **„Auf die Glocke“** (richtig; die Brandung links ist der Zahn).
  3. 90 Minuten Fahrt, Ankunft am Inselsteg (36, 10). Erste Ankunft 20 EP.
  4. Zurück: Oshe auf der Insel (38, 10), **„Zurück nach Brackhafen“** (90 Minuten, Ankunft Lotsensteg (16, 10)). Alle späteren Fahrten sind frei, nach Q13 auch bei Tag.
- **Wahlen und Enden:** Zahlen oder Mitarbeit. Die Mitarbeit lehrt die drei Marken (Laterne am Lotsensteg, Spalt der Blende, Zahn), die man oben am Turm braucht; wer zahlt, erfährt es auf der Insel von Rhiann. Oshe lehrt auf **Arbeit** **Rinne**, **Glockenwacht**, **Zwei Lichter**, auf **Rinne** **Der Zahn**.
- **Belohnung:** 20 (bezahlt) oder 40 EP (Mitarbeit) + 20 Ankunft.
- **Zum Testen:** Oshe bei Tag und bei Nacht, zu wenig Gold, Fahrt mit falschen Wahlen. Namar kommentiert die Überfahrt (»Als Kind durfte ich im Bug sitzen …«). Die Insel ist eigene Karte (40 × 21), Musik traurig, nachts sehr dunkel.

**Die Insel Glockenwacht (Ortskarte):** Steg und Oshe im Osten (36..38, 10), Nebelglocke (31, 9, ansehen und läuten), Verwalter **Odo** am Tisch (22, 9), Lager 1 (Tür 20, 8), Lager 2 (Tür 26, 15), Wohnhaus (Türen 15, 14 und 18, 14, nur Text), Lagerfeuer der Gestrandeten (16, 16) mit **Dasho** (15, 16), **Frieda** (17, 16), **Jost** (16, 17), Salzkäufer **Halvar** (22, 14) bei seinen Säcken, Turm im Westen mit Tür (11, 7), Fenster (9, 9) mit dem bleichen Licht, Lotsin **Rhiann** (9, 11), Fisch im Fels am Westhang (3, 7).

### Q13 Das falsche Licht · 🟢 OPTIONAL
- **Auslöser:** Auf der Insel das **Fenster** in der Südwand des Turms (9, 9) ansehen (bleiches Licht, 20 EP) oder **Rhiann** (9, 11) auf **Fenster** bzw. **Zwei Lichter** ansprechen (dieselben 20 EP, einmal). Rhiann lehrt auf **Name** **Fenster**, auf **Fenster** **Blende** und **Leuchtfeuer**, auf **Blende** **Rinne** und **Der Zahn**. Odo erklärt auf **Leuchtfeuer** den Weg nach oben (Winde, Korb, Schacht; die große Leiter ist versperrt).
- **Stufe:** Stufe 9 mit vier Köpfen. Gegner: **Flimmervögel** (Stufe 9, 30 LP, Schnabel 1W8+1, Dunkelsicht), vier, ab vier, fünf und sechs Figuren je einer mehr (zu viert also fünf). Fähigkeit **Flimmern**: 2 AP, für einen Zug verschwunden (nicht zu sehen, nicht zu treffen), dreimal je Kampf. Balance-Test: Held (Kämpfer), Korgar, Tavion, Namar Stufe 9: 10 von 12 gewonnen (21 % LP übrig), zu fünft 12 von 12.
- **Lösungsweg:**
  1. Turmtür (11, 7) benutzen: Holzlager, Ebene 0 (Ankunft 11, 7).
  2. **Winde** (4, 3) benutzen: Der Korb fährt im Schacht hoch und rastet ein.
  3. Über die Seitenleiter (3, 5) auf die **Kammerebene** (Ebene 1). Dort: Gezeitentafel (9, 5) mit Bruns letztem Eintrag (»Knirschen in der Blende, hole Baumeister. Stifte nicht anrühren.«), Bett (3, 10), Kammertür (6, 8) ohne Griff (bleiches, kaltes Licht, geht nicht auf; Varka kommentiert).
  4. **Schacht** (3, 3) benutzen: Mit dem Korb oben ohne Probe auf die Plattform; ohne Korb klettern (Athletik bzw. Stärke 45, misslungen 1W6 Schaden und 10 Minuten, beliebig oft). Erste Ankunft oben: 30 EP.
  5. **Plattform** (Ebene 2, Ankunft 4, 3): Wer sich den Feldern um das Feuer (Ring 6..8 / 6..8) nähert, löst den Kampf aus. **Kampf Flimmervögel**: schnell, schwach, verschwinden immer wieder; Hinweis im Kampf. Flucht zurück auf die Kammerebene. Sieg 60 EP.
  6. Die vier **Ausgucke** an der Brüstung lesen: (12, 8) Osten = Leitfeuer auf der Sandbank (Zeichen **Flamme**), (12, 11) Südosten = Laterne am Haken des Lotsenstegs (**Haken**), (9, 12) rechts davon der Zahn im Riff (**Zacken**), (6, 12) Süden = alter Turm (**Turm**).
  7. **Blende** am Feuer (7, 7) nach dem Sieg: Beim ersten Mal Probe Wahrnehmung 45 (gelingt sie: die Löcher bei Haken und Zacken sind glatt gerieben, Tagebuchnotiz). **„Die Stifte umstecken“**: erster Stift **„Zum Zacken“**, zweiter **„Zum Haken“** (Reihenfolge egal). Der Spalt zeigt auf die Rinne zwischen Lotsensteg und Zahn: 80 EP.
  8. Zu **Rhiann** am Fuß des Turms (9, 11): Sie sieht, dass das Feuer stimmt. 60 EP, Quest erledigt. Odo nimmt den Balken von der Hauptleiter (11, 11), Oshe fährt jetzt auch bei Tag.
- **Wahlen und Enden:** Falsche Stellungen: Zacken + Turm zeigt nach Süden übers Riff, Flamme + Haken stellt den alten (falschen) Zustand wieder her, alles andere klafft breit. Rhiann schickt die Gruppe dann wieder hinauf; die richtige Stellung bringt danach nur 40 statt 80 EP. Nach dem Abschluss lässt sich die Blende nicht mehr verstellen. Das bleiche Licht und der Wärter Brun bleiben ungeklärt (offen für später).
- **Belohnung:** Auftakt 20, Plattform 30, Vögel 60, Blende 80 (40), Rhiann 60 = 250 EP; Kampf bei vier Köpfen etwa 137 EP je Kopf. Nach Q13: Odo auf **Brotliste** einmal **sechs Rationen**. Kein Gold.
- **Zum Testen:** Winde, Korb und Schacht ohne Hinweis verständlich? Vögel als eine sichtbare Gruppenmarke vor dem Kampf (bekannte Lücke). Eine falsche Stellung ausprobieren, berichtigen. Die Vögel verbrauchen ihr Flimmern stets ganz.

### Rhiann · 🔵 GEFÄHRTE
- **Auslöser:** Rhiann (9, 11) am Fuß des Turms. Aufnahme im Dialog erst mit **erledigtem Q13** und weniger als sechs Figuren, vorher Ablehnung.
- **Stufe:** Mensch, **Schützin Stufe 8**, 50 LP, **Lotsenbogen** (1W8+1, Reichweite 2 bis 8, 5 AP, zweihändig), Lederrüstung, ein Heiltrank. Spricht Gemeinsprache. Verlangt keinen Lohn.
- **Lösungsweg:** Q13 abschließen, Rhiann ansprechen, aufnehmen.
- **Belohnung:** einmalig 30 EP.
- **Zum Testen:** Kampf mit ihr (Reichweite des Bogens). Sie kommentiert in E09 die Kisten des Hospizes.

### Q14 Briefe ohne Empfänger (erste Hälfte) · 🟢 OPTIONAL
- **Auslöser:** Zweites Lager auf der Insel, Tür (26, 15): Postsack mit zwei Briefen. **„Die Briefe mitnehmen“**: **Brief mit grünem Siegel** (für Vessa in Dreifurt, von ihrem Bruder Arn) und **Brief mit rotem Siegel** (für den Pfleger Ennis im Hospiz von Lichtenruh). Wort **Briefe**. Odo kennt **Briefe** ebenfalls.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Briefe im Lager 2 nehmen.
  2. In **Dreifurt** Händlerin **Vessa** am Markt (Dreifurt (33, 29)) auf **Briefe** ansprechen: Sie nimmt den grünen Brief, 40 EP.
  3. Zweite Hälfte: Ennis im Hospiz von Lichtenruh auf **Briefe** mit dem roten Brief (40 EP), siehe Region Lichtenruh. Erst beide zusammen schließen die Aufgabe.
- **Wahlen und Enden:** Reihenfolge frei. Das Tagebuch nennt den noch offenen Brief.
- **Belohnung:** 40 + 40 EP.

### E09 Was die Flut zurückgibt · 🟢 OPTIONAL
- **Auslöser:** Am Westhang der Insel ist ein frischer **Fisch** in den Fels geritzt (Wand (3, 7), von (4, 7) aus). Ansehen lehrt **Fischzeichen**; Dasho am Lagerfeuer liest ihn auf **Fischzeichen** als Zeichen der Pfahlgasse und nennt **Kesh**. Die Aufgabe beginnt im Tagebuch erst bei Kesh selbst. Keine Voraussetzung außer der Überfahrt (Q13 nicht nötig).
- **Stufe:** Stufe 9 mit vier Köpfen. Gegner: **Höhlenkrabben** (Stufe 9, 36 LP, Rückenschild: Rüstung von vorn +5), vier, ab fünf und sechs Figuren je eine mehr. Seit v0.7.0 halten sie etwa doppelt so viel aus und beißen härter. Balance-Test: Held (Kämpfer), Korgar, Tavion, Namar Stufe 9: von vorn 5 von 8 Siegen, aus der Flanke nicht schwerer. Ein harter Kampf von vorn, aus der Flanke leichter.
- **Lösungsweg:**
  1. Die Wand mit dem Fisch benutzen, **hinabsteigen** (fünf Minuten). Ankunft in der Höhle (21, 1), dunkel: **Fackel oder Licht mitnehmen**.
  2. Den Gang hinab; bei (18..19, 3) öffnet sich die Halle mit dem Becken.
  3. Zwei Wege zur Kammer im Süden:
     - **Kurz:** über die Kiesbank (12..16, 7..10) am Boot (14, 9) vorbei. Die Felder (14..20, 6) lösen den Kampf **von vorn** aus (die Scheren zeigen zum Gang). Flucht nach (18, 4).
     - **Lang:** über das Sims am Nordrand (Reihen 4 und 5) bis zum Westende (4, 4), über den **Felsbogen** (3, 8) (einmal Probe Athletik bzw. Geschick 40 mit Hilfe, Ausrutscher 1W6 Schaden, nie der Weg) und das Südufer zur Kammer. Erreicht Kesh ohne Kampf.
  4. **Kammer** (Durchgang (9, 13), Raum 7..12 / 14..16): **Kesh** (11, 16) mit geschientem Bein, ein Messer in der Hand. Erstes Treffen 20 EP, Wörter **Kesh**, **Krabben**. Sie ruft nicht nach Odo, weil Odo alles aufschreibt und hier unverstempeltes Salz liegt.
  5. Ohne Kampf gekommen: von der Kammer nach Osten weiter, die Felder (12, 10..12) lösen den Kampf **aus der Flanke** mit Überraschung der Gruppe aus (Flucht nach (10, 11)).
  6. **Kampf Höhlenkrabben:** von der Seite und von hinten trifft jeder Hieb das Weiche.
  7. **Fracht** untersuchen: altes Salz in der Kammer ((12, 14), (7, 15), (7, 16), (8, 16); ohne Stempel, darüber ein alter Fisch im Fels: Schmuggelsalz, 15 EP), Säcke im **Boot** (14, 9) nach dem Sieg (Waagstempel von Brackhafen: Keshs gekaufte Ware, 15 EP), **Kisten** (16, 8) und (18, 10) nach dem Sieg (Blatt im Kreis: Arznei für das Hospiz von Lichtenruh, Wort **Arznei**, wahlweise **„Die Arznei zu einem Bündel schnüren“**). Beide Säcke-Fundstellen lehren **Salz**. Rhiann kommentiert die Kisten.
  8. Kesh ansprechen, **„Kesh hinaufbringen“** (nur nach dem Sieg): 30 Minuten, sie sitzt danach am Feuer der Gestrandeten (17, 17). 50 EP.
  9. Mit Oshe **„Zurück nach Brackhafen“**: Kesh fährt mit (Popup am Steg) und steht danach in der Pfahlgasse bei Ashka (8, 21). Damit ist die Aufgabe erfüllt.
  10. **Ashka** auf **Kesh**, sobald Kesh draußen ist: 20 EP, mit Versprechen aus V05 ein eigener Satz.
- **Wahlen und Enden:**
  - **Arznei** (mit dem Bündel): Odo auf **Arznei** (er schickt sie mit Oshe ans Hospiz, 40 EP) oder Halvar auf **Arznei** (**„Für 90 Gold verkaufen“**, keine EP) oder behalten. Behaltene Arznei kann man in Lichtenruh selbst Venya auf **Arznei** geben (20 EP, Region Lichtenruh). Odo und Halvar schließen einander aus.
  - **Salz** (nur wer beide Zeichen gesehen hat, Boot und Kammer): Odo auf **Salz** melden (**„Von den Säcken in der Kammer erzählen“**, er schreibt es auf, Eren bekommt die Abschrift, Keshs gestempelte Säcke bleiben ihr, 20 EP) oder Kesh auf **Salz** das Schweigen zusagen (**„Zusagen, darüber zu schweigen“**, 20 EP). Schließen einander aus; wer nichts tut, verliert nichts.
  - Folgen von Arznei und gemeldetem Salz sind laut Projektstand nur als Flags gesetzt (Ausnahme: Venyas Antworten in Lichtenruh).
- **Belohnung:** Kesh 20, Boot 15, Kammer 15, hinaus 50, Arznei 40, Salz 20, Ashka 20 = bis 180 EP; Kampf bei vier Köpfen etwa 120 EP je Kopf; wahlweise 90 Gold statt der Arznei-EP. Sind Rhiann und Namar dabei, wenn Kesh hinauskommt, +15 zwischen den beiden (Freunde und Rivalen).
- **Zum Testen:** Fisch bei Tag als Eingang erkennbar? Höhle mit Fackel hell genug? Beide Wege (Front und Flanke). Kesh steht statt zu liegen (bekannt). Die Krabben sitzen als Gruppenmarke neben dem Boot.

### V07 Strandrecht · 🟢 OPTIONAL
- **Auslöser:** Am **Nordstrand** jenseits der Bucht liegt ein Lager aus Strandgut, Weltkarte 40..47 / 54..59 (nördlich der Fährstelle am Nordufer (47, 71)). Am besten nach Q05 mit Sives Fähre zum Nordufer übersetzen (6 bzw. 3 Gold) und nach Norden gehen; der Landweg um die Bucht ist laut Dossier offen (genauer Pfad unklar). Das Lager steht zu jeder Tageszeit. Ansprechen: **Volkert** am Feuer (44, 57) oder Bootsmann **Lüder** bei seinem angeketteten Boot (41, 59); beide lehren **Bergelohn**. Dazu Träger **Ubbo** (45, 58, **Arbeit** lehrt **Träger**) und Schleuderer **Sönke** (43, 56).
- **Stufe:** Stufe 9 mit vier Köpfen. Gegner: **Volkert** (Stufe 9, 50 LP), zwei **Laternenträger** (Stufe 8, 34 LP, Licht 4), zwei **Schleuderer** (Stufe 8, 24 LP), ab fünf und sechs Figuren je einer mehr. Kampf **ohne Tote**. Balance-Test (Stufe 9, vier Köpfe): ein schwerer Kampf, mindestens 4 von 12 Siegen verlangt.
- **Lösungsweg (bester Weg, die meisten EP):**
  1. Q05 abschließen.
  2. Das Wort **Träger** holen (Ubbo auf **Arbeit** oder Volkerts Antwort auf das Auffordern).
  3. In Brackhafen **Eren** auf **Träger**: Er gibt sein Wort für vier Träger und einen Seilhüter am Nordpfahl, 10 EP.
  4. Zurück zu Volkert, **„Ihn auffordern, den Strand zu räumen“**: Mit Erens Wort räumen sie den Strand am selben Abend. 100 EP, dazu wird Lüders Boot frei (50 EP). Volkert steht danach am Fährpfahl (49, 71), die Truhe im Lager ist leer.
- **Wahlen und Enden:**
  - **„Den Bergelohn für das Boot zahlen (30 Gold)“**: Lüder rudert davon, 50 EP, das Lager bleibt, die Aufgabe bleibt offen.
  - **Auffordern ohne Erens Wort**, dann **„Ihm drohen“**: Probe Charisma 50 mit Hilfe. Gelingt sie: Sie ziehen nach Norden ab und lassen das Strandgut liegen, 80 EP (+ 50 Boot). Misslingt sie: Kampf.
  - **Angreifen** (oder misslungene Drohung): Kampf ohne Tote auf offenem Sand, Gruppe startet bei (43, 60) mit Blick nach Norden, Gegner verborgen. Sieg 60 EP (+ 50 Boot). Flucht nach (43, 61). Niederlage: Die Gruppe wacht südlich bei (47, 69) auf, das Lager bleibt.
  - **Truhe** (45, 55): nach Drohung oder Sieg zwei Heiltränke, eine Blendlaterne, drei Fackeln, 45 Gold; nach dem Reden leer; sonst bewacht.
  - **Verzahnung:** Wer gedroht oder gekämpft hat, trifft Volkert und Ubbo später als Wegsperre am **Moosfels** wieder (W01, Region Wege); dort hilft Erens Wort (Eren auf **Träger** nach Q05 und abgezogenem Lager, 10 EP) ebenfalls.
- **Belohnung:** Boot frei 50 + Räumung 100 (Reden) / 80 (Drohen) / 60 (Kampf) + Erens Wort 10 = höchstens 160 EP; Kampf bei vier Köpfen etwa 130 EP je Kopf; Truhe nur nach Drohung oder Kampf.
- **Zum Testen:** Findet man das Lager von der Fährstelle? Alle vier Wege, den Kampf einmal verlieren. Volkert danach am Fährpfahl. Bekannt: Volkerts Antwort auf das Auffordern wiederholt sich bei jedem Versuch; kein eigener Nachtkampf.

---

**Offene Enden / Rückkehr später**
- **Jaro** anwerben, sobald ein Elfisch-Sprecher in der Gruppe ist (Venya aus Lichtenruh); nach Q06 bietet er sich trotzdem an.
- **Q14** roter Brief an Ennis im Hospiz von Lichtenruh, grüner an Vessa in Dreifurt.
- **Arznei** aus E09 behalten und in Lichtenruh Venya geben (Alternative zu Odo/Halvar).
- **Ashka** kennt nach Lichtenruh (Q11) das Wort **Pilgerweg**.
- **Volkert** nach Drohung/Kampf als Schranke am Moosfels (W01, Region Wege), Eren auf **Träger** liefert dort das lösende Wort.
- **V05 Bootsschuld** (40 Gold), falls Namar erst später in die Gruppe kommt.
- **Q07 nachreichen:** Nach den Raten beide Zahlen bringen (30 EP, mehr Gold, Ölzeug).
- **Geske** auf **Reisewege** bei jeder neuen Unruhestufe (1–3) für neue Gerüchte.
- Ungeklärt im Spiel und bewusst offen: das bleiche Licht hinter der Kammertür im Turm, der verschwundene Wärter Brun.

---

## Kapitel 6 · Lichtenruh und Glasgrund

### 📍 Teil A · Lichtenruh

**Anreise:** Drei Tore auf der Weltkarte (Stempel „Lichtenruh“, rund 361..374 × 153..167):
- **Westtor** Weltkarte (361, 158), Ankunft auf der Ortskarte (1, 39): über den Graufelspfad vom Osttor Karrfels (Seilklamm, Handelsstein mit Haldaar bei (352, 144)).
- **Nordtor** Weltkarte (368, 153), Ankunft (22, 1): über die nördliche Landroute von Brackhafen (Sives Fähre), an der auch der alte Pilgerweg (Q11) abzweigt.
- **Südtor** Weltkarte (368, 167), Ankunft (24, 42): Südweg nach Glasgrund, unterwegs der Abzweig zur Herzsenke (etwa 374, 215).
Der Ort ist ohne Kampf zu betreten. Die erste Ankunft gibt 20 EP und je nach Tageszeit einen eigenen Ankunftstext.

**Ortskarte (48 × 44, Norden ist bergauf, drei Terrassen):**
- Unten (Höhe 0): Straße vom Westtor nach Osten, **Herberge** (Tür 8, 36) gleich hinter dem Westtor, **Südtor** (24..25, 43), ganz im Südosten die moosige **Gartenmauer** (30..46, 41) mit dem **Gartentor** (31, 41), erreichbar von der Straße davor (31, 40).
- Mitte (Höhe 2): **Pilgermarkt** im Westen (1..20, 13..26) mit Wenna (9, 18) und dem Pilger Barend (12, 23). Das **Kloster** als Geviert um den **Klostergarten** (23..37, 18..25): Brunnen (30, 21), Beet mit dem zweiten Blühen (27, 21), Gedenkstein (35, 25). **Kapelle** an der Nordseite (Tür 31, 16), **Skriptorium** an der Ostseite (Tür 38, 22).
- Oben (Höhe 4): **Hospiz** (Tür 10, 8) im Nordwesten, **Glockenstuhl** (27, 4), **Nordtor** (22..23, 0), im Nordosten der **Vorhof** (33..46, 2..8) mit Steinrinne und Knoten und ganz am Ostrand die verschlossene **Quellpforte** (47, 4).
- Hinweis zur Unruhe: Ab Unruhe 2 (zwei Relikte) ist der Vorhof verändert (zerschnittene Rinne, ein flimmerndes Band zwischen Vorhof und Quellpforte, die Helferin Wilda) – das gehört zu F01/Q16 und steht in einem anderen Abschnitt. Für Q10 heißt das nur: Wer die Quelle als drittes Relikt holt, muss durch das Band (kostet die Gruppe 2W6 LP, auf dem Rückweg aus der Quelle steht man innen).

**Wann:** Gründlicher Weg (4 Köpfe): nach Karrfels und Brackhafen, beim Betreten Stufe 12–13. Kürzester Story-Weg: jederzeit nach Mühlbrück als eines der drei Relikte; der Pflichtkampf (Dornwuchs) ist gegen eine Vierergruppe auf Stufe 9 gemessen. Gegner der Region Stufe 7 bis 11.

**Dienste:**
- **Herberge** (Tür 8, 36), Wirt **Lorenz** hinter der Tür: Wahl Gefährten (Wartebank abholen/abgeben), Reden, Zimmer und Proviant (5 Gold die Nacht, Ration 1 Gold), dazu **Lager** (Einlagern).
- **Heilerin Irmel** im Hospiz (9, 3): Reden oder Heilen (LP für 1 Gold je Punkt, heilt Gift, Verletzung, Verlangsamung, Lähmung, Verwirrung).
- **Händlerin Wenna** auf dem Pilgermarkt (9, 18), nur bei Tag: Heiltrank, Gegengift, Fackel (kauft zum halben Preis an).
- Keine Gilde, kein Tempel. Schreiberin **Aelis** (Skriptorium, Tür 38, 22, nur bei Tag, spricht hinter der Tür) und Pilger **Barend** (Zwerg aus Karrfels, außer nachts) sind Gerüchte- und Wortgeber (Abschriften, Quellbezirk, Glocke, Fieber, Karrfels).

**Personen und Aufenthalte:** Priorin **Meret** bei Tag im Klostergarten (33, 18), in der Dämmerung am Glockenstuhl (27, 5), nachts antwortet sie durch die Kapellentür (31, 16). Gärtner **Tomm** bei Tag (29, 22), abends am Brunnen (31, 21). Im **Hospiz** (eigene Karte 20 × 12, Ankunft 9, 10): Pfleger **Ennis** am Fieberbuch (15, 6), **Venya** an ihrem Tisch (3, 6), **Irmel** (9, 3), am Tisch die drei Wartenden **Mira** (12, 10), **Hennek** (14, 10), **Ilsabe** (13, 9) und die Laienschwester **Hilde** (2, 4). Die Kranken in den Betten (Fischer vom Katzenvolk, Hauer aus Karrfels, Pilgerin, Schläfer) sind Gegenstände mit Text.

**Gefährten:** **Venya** (Elfin, Schwarzmagierin, Begabung Grau und Schwarz, tritt mit Stufe 9 bei) nach Q28. Siehe K03 unten.

### Ankunft und Unterstrom von Lichtenruh · 🟡 ENTDECKUNG
- **Auslöser:** einfach umsehen. Niemand erklärt, warum hier alles zweimal geschieht.
- **Lösungsweg:**
  1. **Doppelte Fußspuren** am Westtor (1, 38) umschauen: 5 EP.
  2. **Zweites Blühen** im Beet am Brunnen des Klostergartens (27, 21): 5 EP, Wort **Garten**.
  3. **Glockenstuhl** (27, 4) umschauen lehrt **Glocke**. In der **Dämmerung** benutzen: Die Glocke schlägt zweimal, obwohl nur eine hängt und ein Haken leer ist: 5 EP (einmalig).
  4. **Fieberbuch** auf Ennis' Pult im Hospiz (14, 6): 5 EP, Wort **Fieber** (dieselbe Stunde bei Kranken aus weit auseinanderliegenden Orten). Hat man den roten Brief schon abgegeben (Q14), steht Talkes Eintrag mit drin.
  5. Wortnetz: Meret **Name** lehrt **Lichtenruh** und **Abschriften**, **Lichtenruh** lehrt **Quellbezirk**, **Pilger**, **Garten**. Tomm **Arbeit** lehrt **Garten**, **Glocke**, **Quellbezirk**. Barend **Name** lehrt **Fieber**, **Karrfels**. Pilgermarkt umschauen lehrt **Abschriften**, die Quellpforte benutzen lehrt **Quellbezirk**.
- **Belohnung:** Ankunft 20 EP, vier Funde je 5 EP. Kein Gold.
- **Zum Testen:** Stadt bei Tag, Dämmerung, Nacht; Treppen zwischen den Terrassen in allen drei Ansichten; zweiter Glockenschlag in der Dämmerung; Meret durch die Kapellentür bei Nacht; Aelis im Skriptorium (nachts zu).

### Q14 Briefe ohne Empfänger (zweite Hälfte) · 🟢 OPTIONAL
- **Auslöser:** den **roten Brief** aus der Glockenwacht (Brackhafen, zweites Lager, Q14) im Gepäck.
- **Lösungsweg:**
  1. Ins Hospiz (Tür 10, 8), **Ennis** (15, 6) nach **Briefe** fragen.
  2. Er nimmt den Brief: Er ist von Talke, einer früheren Kranken aus Brackhafen, deren Fieber ein Jahr nach der Entlassung für eine Nacht zur selben Stunde wiederkam. Ennis trägt es ins Fieberbuch ein (Fährte zu Q28).
  3. Den grünen Brief bekommt Vessa in Dreifurt. Die Aufgabe ist fertig, sobald beide Briefe angekommen sind, egal in welcher Reihenfolge.
- **Belohnung:** 40 EP.
- **Zum Testen:** einmal Hospiz zuerst, einmal Vessa zuerst, Tagebuch dazwischen (Vermerk zum fehlenden Brief). Ohne Brief antwortet Ennis nur allgemein.

### E09-Folge Die Arznei · 🟢 OPTIONAL
- **Auslöser:** Venya (Hospiz, 3, 6) nach **Arbeit** fragen, das lehrt **Arznei** und **Fieber**.
- **Lösungsweg:** Venya nach **Arznei** fragen. Die Antwort hängt an Flut und Strandrecht (E09, Brackhafen):
  - Bündel Arznei (aus den Kisten in der Höhle) **selbst im Gepäck**: Venya nimmt es, 20 EP.
  - Bündel bei **Odo** auf Oshes Liste gesetzt: Die Kisten sind angekommen.
  - Bündel an **Halvar** verkauft: Nichts kam, Venya rechnet, wem sie den Fiebersaft nun nicht geben kann.
  - Ohne E09: Sie wartet noch.
- **Wahlen und Enden:** Mit Arznei (selbst gebracht oder über Odo) gibt Venya in der Q28-Nachtwache beiden Kranken Fiebersaft und dankt im Bericht; verkauft gibt sie die letzte Flasche dem Älteren; ohne teilt sie den alten Rest.
- **Belohnung:** 20 EP (nur mit dem Bündel im Gepäck).

### Q10 Die Antwort der Quelle (mit Q15c) · 🔴 PFLICHT (Relikt „Antwort“)
- **Auslöser:** **Meret** (bei Tag im Klostergarten 33, 18) nach **Name** → **Lichtenruh** → **Quellbezirk** fragen, oder mit Orwins Wort direkt nach **Hüter** (lehrt **Quellbezirk** und **Antwort**). Quellbezirk lehrt **Antwort**. Erst auf **Antwort** gibt sie den **Schlüssel zur Quellpforte** und damit die Aufgabe. Nochmal gefragt, wartet sie auf den Bericht.
- **Stufe:** Bezugsstufe der Balance-Test 9 (Held als Kämpfer mit Korgar, Tavion, Namar; zweite Fassung mit Varka). Gegner:
  - **Quellziegen** (optional): 3 × Stufe 9 (32 LP, je 100 EP), ab 5 und ab 6 Köpfen je eine mehr. Schnell, schwer zu treffen (zweiter Schatten), springen vor und zurück.
  - **Dornwuchs** (Pflicht): **Dornwurzel** Stufe 11 (70 LP, Rüstung 2, spuckt Dornen auf 2–5 Felder, verlässt ihr Feld nie, wirft **Dornenranken** auf ein Feld mit Nachbarn: Gift und zwei Züge festgewurzelt, 220 EP) und 3 **Dorntriebe** Stufe 9 (26 LP, Peitsche Reichweite 1–2, wachsen jeden Zug 6 LP nach, solange die Wurzel steht, 90 EP), ab 5 und ab 6 Köpfen je ein Trieb mehr. Beide Gruppen furchtlos.
  - Kampf-EP je Kopf bei vier: rund 197 (Ziegen und Dornen zusammen).
- **Lösungsweg:**
  1. Mit dem Schlüssel zur **Quellpforte** (47, 4) ganz im Osten des Vorhofs (oben rechts in der Stadt). Benutzen öffnet die Kette, man steht im Quellbezirk (Karte 30 × 28, vier Terrassen, Norden bergauf), Ankunft im verwilderten Garten (1, 24).
  2. Optional zuerst **Tomm** nach **Quellbezirk** fragen (mit begonnener Aufgabe): Er verrät den Schieber auf der Wiese (Tagebuchvermerk). Nicht Pflicht.
  3. **Garten (Höhe 0):** Blühen (14, 24) umschauen: einmal 5 EP. Treppe (3..4, 20..21) hinauf.
  4. **Wiese (Höhe 2):** Ganz im Westen den **Schieber** (1, 14) benutzen: 30 EP. Danach führt die Westrinne Wasser, die **Ostrinne** (26, 14..20) wird trocken und begehbar, man kommt an den Ziegen vorbei. Ohne Schieber führt der Weg mitten durch die Herde: Wer die Felder (5..16, 13..18) betritt, löst den Ziegenkampf aus (Flucht führt zurück in den Garten).
  5. **Riss (Höhe 4):** Über die Treppen (9..10 oder 25..26, 12..13) hinauf. Wer die Zeilen 7 bis 11 betritt oder die Wurzel (18, 7) benutzt, weckt den **Dornwuchs**. Taktik: zuerst die **Wurzel** fällen (sie steht fest auf (18, 7) und schießt nur auf Abstand), dann wachsen die Triebe nicht mehr nach. Sieg 80 EP. Flucht führt auf die Wiese (20, 14).
  6. **Q15c (immer, seit Ä45):** Nach dem Sieg steht der Fremde in der Nische (20, 2) an der offenen Verkleidung, den Hammer gegen die schwarze Fläche erhoben. Die Schalen bleiben stumm, solange er dort steht. Den **Hebel** (19, 1) im Schalenhof benutzen: Das Gitter fällt, eine Steinplatte schiebt sich vor die Fläche. Vorwurf, Wort **Herz**, dann Wahl **„Was habt Ihr gesehen?“** (20 EP) oder **„Hier warten Leute auf diese Antwort.“**. Er geht über den Wartungsweg: 40 EP. Das ist die erste Begegnung. Als zweite Begegnung erkennt {held} ihn wieder: Er arbeitet schneller, bereut, beim letzten Mal geredet zu haben, und die Fragen lauten **»Wer seid Ihr?«** und **»Woher wusstet Ihr, wohin wir gehen?«** (20 EP für die erste). Als dritte weiß er, dass es das Letzte ist, was der Gruppe fehlt: **»Warum greift Ihr uns nicht an?«**, **»Was werdet Ihr jetzt tun?«** und, wer Wildas Bericht aus F01 kennt, **»Und die Frau an der Rinne in Lichtenruh?«** (20 EP für die erste). Er schließt mit »Dort bin ich vor Euch.« Die Frage nach den Leuten vor Ort gibt es in jeder Begegnung. Ist die Quelle das dritte Relikt, kommt man durch das Band (F01), und er sieht die Brandstellen an den Händen.
  7. **Schalenhof (Höhe 6),** Treppe (14..15, 5..6): Das **Wandbild** (9, 1) zeigt die Reihenfolge (größte, kleinste, mittlere Schale). Zuerst den **Zulauf** (11, 1) benutzen, das füllt das Becken (ohne Wasser klingen die Schalen dumpf).
  8. Schalen in dieser Folge benutzen: **groß (14, 1) → klein (12, 1) → mittel (16, 1)**. Falsche Folge: Missklang, zurück auf Anfang, kein Schaden. Richtig: Wasser steigt, Lichtmuster, doppelter Ton, Brydan wiederholt die Folge bewusst. Das Relikt **Antwort** ist erlangt: 120 EP, Wort **Antwort**.
  9. Über den Garten (0, 23..24) zurück nach Lichtenruh, **Meret** nach **Antwort** fragen: Bericht, 70 EP. Hat die Gruppe die Abschrift (Moorarchiv) oder die Fassung mit dem Ring (Karrfels), kommt je ein Satz zu denselben Zeichen bzw. den drei Kerben dazu.
- **Wahlen und Enden:** Ziegen kämpfen oder per Schieber umgehen. Q15c-Wahl ändert nur 20 EP und Text. Der Schlüssel bleibt bei der Gruppe, der Quellbezirk bleibt offen. Das Relikt zählt zur Unruhe.
- **Belohnung:** Q10 300 EP (Schieber 30, Dornwuchs 80, Antwort 120, Meret 70), Q15c bis 60 EP (in jeder der drei Begegnungen), Blühen 5 EP, Kampf-EP. Kein Gold.
- **Zum Testen:** Merets Auftakt; Ostrinne nass und trocken in allen Ansichten; zweiter Schatten der Ziegen und das Nachwachsen der Triebe lesbar? Fällt die Wurzel als erstes Ziel auf (der Kampf dauert sonst 40–50 Züge)? Fremder mit beiden Wahlen, einmal als zweite und einmal als dritte Begegnung (nach der Sabotage mit Brandstellen); Rätsel mit falscher und richtiger Folge, Becken leer/voll. Kommentare von Jaro und Beric beim Erklingen, falls dabei.

### Q28 Die Stunde, die wiederkehrt · 🟢 OPTIONAL
- **Auslöser:** **Venya** im Hospiz (3, 6): **Arbeit** → **Fieber** (lehrt **Stunde**) → **Stunde**. Sie bittet, eine Nacht mit ihr zu wachen.
- **Stufe:** Bezugsstufe 9 (vier Köpfe, zweite Fassung mit Varka). Gegner: **Nachhall** 3 × Stufe 10 (38 LP, Rüstung 1, Kalte Hand 1W8+2, je 120 EP), ab 5 und ab 6 Köpfen je einer mehr, furchtlos. Kampf-EP je Kopf bei vier rund 90. Ein „schwerer Pflichtkampf, der zu viert offen ist“, teuer aber sicher.
- **Lösungsweg:**
  1. **Nachtwache:** Zwischen 00:00 und 02:00 beginnt sie sofort, sonst Wahl **„Bis zur Stunde wachen“** (Uhr springt auf 00:10) oder **„Später wiederkommen“**. Die Kranken setzen sich zur selben Stunde auf. Je nach Arznei (E09) gibt Venya beiden Fiebersaft, nur dem Älteren oder teilt den Rest.
  2. **Probe Wahrnehmung 40 (mit Hilfe):** Erfolg = man hört den tiefen Ton aus dem Hang und den Nachklang (20 EP), sonst hört ihn nur Venya. Sie zeigt auf die Kapelle, lehrt **Gruft**: 40 EP, eine Stunde vergeht.
  3. Danach ist es Nacht: an die **Kapellentür** (31, 16), Meret antwortet durch die Tür. Nach **Stunde** oder **Gruft** fragen: Sie schließt die Treppe hinter dem Altar auf. (Bei Tag im Garten geht es ebenso.)
  4. Kapellentür erneut benutzen: **„In die Gruft hinabsteigen“**. Gruft (Dungeon 22 × 14), Ankunft (2, 3) an der Treppe.
  5. Gang nach Süden mit acht Steinsärgen. Optional die **Namen** in der Südwand (4, 10) lesen (eine Schwester steht zweimal da). Durch den niedrigen Durchgang nach Osten (7..9, 7): Wer (9, 7) bzw. die **Glockenkammer** (10..18, 5..9) betritt, weckt die Gestalten.
  6. **Kampf:** Wen ein Nachhall im Nahkampf trifft, um den legt sich ein Ring. Wer zwei Ticks später noch auf dem Feld steht, wird ein zweites Mal getroffen (2W6+4), auch ein Verbündeter, der hineintritt. Also nach einem Treffer aus dem Ring treten. Sieg 60 EP. Flucht in den Gang (4, 7).
  7. **Glocke** (14, 7) benutzen, Wahl: **„Die Glocke mit Decken dämpfen“** (Uhr auf 00:20, 40 EP) oder **„Bis zur Stunde warten und zählen“** (Uhr auf 01:30, der Nachklang kommt bei vierzig, 40 EP) oder **„Die Glocke lassen, wie sie ist“** (später wiederkommen).
  8. Zurück zu **Venya**, **Stunde**: Bericht, 60 EP.
- **Wahlen und Enden:** Gedämpft: In dieser Nacht steigt bei keinem das Fieber (Ennis bestätigt es auf **Stunde**), Venya sagt, heute schlafen alle durch. Gezählt: Venya schreibt die Zahl mit und fragt nach weiteren solchen Glocken. Mit Arznei ein eigener Dank. Venyas Aufnahme hängt nicht davon ab.
- **Belohnung:** 220 EP (Wache 40, Hören 20, Kampf 60, Glocke 40, Bericht 60), Kampf-EP, Wort **Gruft**. Kein Gold.
- **Zum Testen:** Wache einmal zur Stunde und einmal mit Warten, mit Fiebersaft, ohne und mit verkauftem Saft; Gruft in allen Ansichten, Glocke vor und nach dem Dämpfen; ist der Nachklang-Ring sichtbar und rechtzeitig zu verlassen? Eigener Angriffsklang (Klopfen mit Glockenton).

### Venya · 🔵 GEFÄHRTE
- **Auslöser:** Q28 abgeschlossen (Bericht gehört), freier Platz in der Gruppe (weniger als sechs).
- **Lösungsweg:** Venya im Hospiz ansprechen und **Anheuern**. Bei voller Gruppe lehnt sie ab und bleibt im Hospiz.
- **Belohnung:** Venya, Elfin, **Stufe 9**, Schwarzmagierin (Begabung Grau und Schwarz, Kämpfer gesperrt), Dolch, Lederrüstung, ein Heiltrank. Spricht Elfisch und Gemeinsprache (kann damit für Jaro übersetzen). Einmalig 30 EP.
- **Zum Testen:** Aussehen (bronzene Haut, goldbraunes Haar mit blonden Strähnen) in acht Richtungen, Laufen, Dolch, Zaubergebärde; Absage bei voller Gruppe. Kein persönlicher Auftrag nach der Aufnahme.

### Q11 Was wir den Toten schulden · 🟢 OPTIONAL
- **Auslöser:** Im Hospiz am Tisch **Mira** (12, 10), **Hennek** (14, 10), **Ilsabe** (13, 9). Einen nach **Arbeit** (lehrt **Pilger**), dann **Pilger** oder **Pilgerweg** fragen. Mira beschreibt den Weg (nördlich an der Straße beim Stein mit der Muschel, nach Osten übers Joch). Wort **Pilgerweg**.
- **Stufe:** Bezugsstufe 9. **Aaskrähen** Stufe 7 (14 LP, je 25 EP): Anführerin und vier, ab 5 und ab 6 Köpfen je eine mehr; nicht furchtlos (Moral 40), fliehen nach den ersten Verlusten. Freiwillig, umgehbar, leicht.
- **Lösungsweg:**
  1. Aus dem Nordtor die Nordroute hinauf zum **Muschelstein** Weltkarte (376, 106).
  2. Den überwachsenen Pfad nach Osten (376..386, 107) zum **Rastplatz** (387..392, 106..108): zwei Steinbänke, kalte Feuerstelle. Den flachen Stein (390, 108) benutzen: **Widos Blatt** (Schnee am Joch, das Dach des Unterstands brach ein, Jorin liegt darunter, Wido bringt Grete und Bosse über die Fähre zurück nach Brackhafen; Rana steht nicht darin). 20 EP, auch ohne angenommene Aufgabe.
  3. Pfad weiter (393..396, 107) und nach Süden (396, 108..112) zum Aufstieg (396, 113)/(397, 114): Die **Krähen** auf dem eingestürzten **Unterstand** (398, 114) zeigen sich einmal von selbst (Gruppe auf 398, 113). Wahl:
     - **„Mit Steinen verscheuchen“**: Probe Fernkampf 40 mit Hilfe. Erfolg: Der Schwarm fliegt übers Joch, 30 EP. Fehlwurf: Kampf.
     - **„Angreifen“**: Kampf (Flucht zum Rastplatz 390, 107).
     - **„Gehen“**.
  4. Ohne Krähen den Unterstand benutzen: Das Dach anheben, Jorin liegt darunter, um den Hals ein **bronzenes Pilgerzeichen** mit eingeritztem M: 20 EP. Wahl **„Steine aufschichten“** (30 Minuten, danach steht ein Steinhügel bei 398, 115) oder **„Ihn liegen lassen“** (das Aufschichten bleibt später möglich).
  5. Berichte im Hospiz, jeweils auf **Pilgerweg**:
     - **Mira:** Mit dem Blatt hört sie, was es sagt. Erst mit dem **Zeichen** schließt sie ab (40 EP): Sie fragt nach den Steinen, dann Wahl **„Mira geben“** oder **„Für den Gedenkstein anbieten“**. Daher erst zum Unterstand, dann zu Mira.
     - **Hennek:** Mit dem Blatt: Wido kehrte um und brachte die Alten heim (20 EP).
     - **Ilsabe:** Mit Blatt oder Zeichen: Rana steht nicht im Blatt und lag nicht unter dem Dach (10 EP). Sie wartet weiter.
  6. Bei Angebot für den Gedenkstein: **Meret** nach **Pilgerweg** fragen, sie legt das Zeichen auf den **Gedenkstein** (35, 25) im Klostergarten (Kartenänderung).
  7. Optional: In **Brackhafen** (Pfahlgasse) **Ashka** mit dem Blatt nach **Pilgerweg** fragen: Wido kam im Herbst mit zwei Alten über die Fähre und flickt seither neben ihr Netze. Danach **Hennek** erneut auf **Pilgerweg**: 20 EP.
  8. Sobald Mira (mit Zeichen), Hennek (Blatt) und Ilsabe berichtet sind: Abschluss 20 EP.
- **Wahlen und Enden:** Krähen verscheuchen oder kämpfen; Steinhügel ja/nein (Mira reagiert darauf); Zeichen an Mira oder an den Gedenkstein. Ranas Schicksal bleibt in Akt I offen.
- **Belohnung:** 150 EP (Blatt 20, Zeichen 20, Mira 40, Hennek 20 + 20, Ilsabe 10, Abschluss 20), dazu 30 EP fürs Verscheuchen oder die Kampf-EP (rund 31 je Kopf bei vier). Kein Gold.
- **Zum Testen:** Angriffsklang der Krähe (zwei Fassungen); Weg vom Muschelstein zum Unterstand in allen Ansichten, Steinhügel danach; Gedenkstein mit Zeichen (niedrig, in Ego nur aus zwei Feldern ganz zu sehen).

### E07 Der Garten hinter der Mauer · 🟢 OPTIONAL
- **Auslöser:** **Hilde** im Hospiz (2, 4), faltet Leinen: **Arbeit** (lehrt **Garten**), dann **Garten**: Sie erzählt von ihrer Schwester Gerlind, der früheren Klostergärtnerin hinter der Mauer, und bittet um Nachricht. Wörter **Gärtnerin**, **Schwester**. (Tomm auf **Gärtnerin**: Gerlind war seine Lehrmeisterin und sah das zweite Blühen zuerst.)
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Unten an der Straße zum **Gartentor** (31, 41), von Norden (31, 40) aus benutzen.
  2. **Bei Tag** öffnet Gerlind, man steht im Garten (Karte 18 × 14, Ankunft 8, 1). In Dämmerung und Nacht: Wahl **„Klopfen“** (drinnen bleibt es still, Gerlind erwähnt es später) oder **„Gehen“**.
  3. **Gerlind** (9, 7, nur bei Tag) ansprechen: erste Begegnung 20 EP.
  4. Sie nach **Schwester** fragen (geht erst mit Hildes Bitte). Wahl:
     - **„Ihre Grenzen ausrichten“**: Hilde soll fragen, bevor sie etwas bringt. Zwei **Kräutermischungen** (heilen 2W6+4), 40 EP.
     - **„Einen Besuch verabreden“**: am Vormittag nach dem Gießen, mit zwei Zeilen für Hilde. 40 EP.
     - **„Sie zur Rückkehr drängen“**: Sie bricht ab, das Tor bleibt danach zu.
  5. Zurück zu **Hilde**, **Gärtnerin**: Bericht, 20 EP.
- **Wahlen und Enden:** Nach Besuch und Bericht steht Hilde bei Tag im Garten (6, 4), und Gerlind lädt einmal zum Essen ein (**„Mitessen“**: eine Stunde, alle LP geheilt). Nach dem Drängen antwortet Gerlind nur noch durchs Holz.
- **Belohnung:** 80 EP (Begegnung 20, Grenzen oder Besuch 40, Bericht 20), Kräutermischungen oder das Essen. Kein Gold.
- **Zum Testen:** Tor bei Nacht und bei Tag; Garten mit Gerlind, danach mit Hilde und das Essen. Hütte nicht betretbar (nur Blick durchs Fenster).

---

### 📍 Teil B · Glasgrund

**Anreise:** Drei Tore (Stempel „Glasgrund“ ab etwa (345, 284)):
- **Nordtor** Weltkarte (352, 284), Ankunft (12, 1): Südweg von Lichtenruh (Südtor 368, 168) über den Abzweig zur Herzsenke. Hinweis: Mit drei Relikten (Unruhe 3) liegt auf dem Südweg nördlich von Glasgrund der Riss W06 mit einem Kampf (anderer Abschnitt).
- **Westtor** Weltkarte (345, 292), Ankunft (1, 20): Deichweg von Brackhafen.
- **Südtor** Weltkarte (352, 295), Ankunft (12, 38): ins Tal, gleich dahinter die leuchtende Furche (Q12).
Die erste Ankunft gibt 20 EP, das Wort **Glasgrund** und einen Text je nach Tageszeit. Kein Kampf.

**Ortskarte (48 × 40):** Unten (Höhe 0, x bis 29) das Dorf an der Straße vom Nordtor (12..13, 0) zum Südtor (12..13, 39). **Wachstube** (Tür 16, 5) gleich hinter dem Nordtor rechts, **Dorfplatz** in der Mitte (9..18, 17..24) mit Brunnen (10, 18), Lagerplatz und Brits Zähltafel (15, 20). **Gerdas Hof** im Südwesten (Hoftor 10..11, 28, Haus mit halbem Kreis, Tür 6, 26, Stall 4, 32, Wagen 7, 30). **Baros Werkstatt** (Tür 16, 28) mit Steinhof. Die Türen tragen Kreidezeichen: Kreis = fortgegangen, Strich = geblieben. Hinter der Ostmauer (Durchgang y 19..20, Treppe 29, 19..20) der **Gnomenweiler** am Osthang in drei Stufen: Stufe 1 (x 30..33) mit **Sylis** und dem Schlüsselbrett (31, 12), Stufe 2 (x 34..38) mit **Tibbes** verglaster Tür (36, 22), Stufe 3 (x 39..47) mit **Wemke**, Horchrohr (42, 12), Ahnenstein (44, 11) und dem leeren Erdbau der Brenns (Tür 43, 23). Treppen jeweils mit Aufgang von Westen: (33, 9..10), (33, 27..28), (38, 15..16).

**Wann:** Gründlicher Weg (4 Köpfe): nach Lichtenruh, beim Betreten Stufe 13–14. Glasgrund ist **kein** Teil des Pflichtwegs (kein Relikt). Gegner der Region Stufe 9 bis 12 (Scherbenläufer, Kolk), die stärksten außerhalb der Herzsenke.

**Dienste:**
- **Wachstube** (Tür 16, 5): Wahl **„Mit der Grenzwächterin sprechen“** (Alva), **„Eine Pritsche nehmen“** (Rast, 2 Gold, Ration 1 Gold), Gehen. **Alva** steht außer nachts vor der Tür (14, 6).
- **Brit** am Lagerplatz (16, 20, außer nachts): **„Restwaren“** (Fackel, Heiltrank, Gegengift – teuer, 120 % Preis, kauft nur zu 40 % an).
- Kein Tempel, keine Gilde, kein Heiler.

**Personen:** Wachmann **Ude** am Nordtor (14, 3) zu jeder Stunde. **Alva** (14, 6) außer nachts. **Brit** (16, 20) außer nachts. **Gerda** bei Tag am Wagen (8, 30), abends vor ihrem Haus (7, 26). **Baro** bei Tag im Steinhof (20, 33), abends an der Werkstatt (15, 28). **Sylis** (30, 13) außer nachts. **Wemke** bei Tag am Horchrohr (41, 11), abends vor ihrem Bau (42, 5). Nach Dornwacht: **Hanno** (15, 4) und **Fenke** (15, 8) am Nordtor.

**Gefährten:** **Sylis** (Gnomin, Diebin, Stufe 10) nach Q29. **Z'zarek** (Drachenblütiger, Schwarzmagier, Stufe 10) am Steinbruch östlich des Dorfs (O10), braucht einen Orkischsprecher.

### Ankunft und Unterstrom von Glasgrund · 🟡 ENTDECKUNG
- **Auslöser:** umsehen und reden. Niemand bittet in diesem Teil um Hilfe.
- **Lösungsweg:**
  1. **Gartenzaun vor Haus A** (1..4 und 7..9, 7; Haus mit Kreis, Tür 5, 5) **bei Tag** umschauen: Der Zaun wirft einen zweiten, blasseren Schatten zu einer Sonne im Süden: 5 EP, Wort **Schatten**.
  2. **Haus C** (Tür 16, 13, Kreis über Strich) benutzen: gedeckter Tisch mit zwei staubigen Tellern: 5 EP.
  3. **Horchrohr** der Gnome (42, 12) **nachts** benutzen: Schritte im Lehm, wo keiner gräbt: 5 EP.
  4. Ohne EP: Schlüsselbrett (31, 12, Wort **Schlüssel**), leerer Erdbau (Tür 31, 23), Tibbes Tür unter Glas (36, 22, einmal Klopfen, Wort **Tibbe**, Umschauen lehrt **Glas**), Glasadern, Ahnenstein (44, 11), leere Nische in Baros Hof (21, 34), Gerdas Wagen (7, 30, lehrt **Saatgut**).
  5. Wortnetz: Ude **Name** → **Glasgrund**, **Arbeit** → **Kreidezeichen**, **Gnome** → **Schlüssel**. Alva **Name** → **Glasgrund**, **Kreidezeichen**; **Arbeit** → **Dornwacht**; **Glasgrund** → **Glas**, **Dornwacht**; **Saatgut** → **Furche**. Brit **Glasgrund** → **Saatgut**, **Saatgut** → **Furche**. Gerda **Arbeit** → **Saatgut**, **Lichtenruh**; **Saatgut** → **Dornwacht**, **Furche**. Baro **Arbeit** → **Gnome**, **Saatgut**; **Gnome** → **Tibbe**. Sylis **Arbeit** → **Schlüssel** → **Tibbe**. Wemke **Arbeit** → **Gnome**, **Tibbe**.
- **Belohnung:** Ankunft 20 EP, drei Funde je 5 EP.
- **Zum Testen:** Ankunft über alle drei Tore; Hangtreppen in Iso und Ego (Verdeckung schneidet Stücke heraus); Kreidezeichen in Ego lesbar; Rast in der Wachstube; Brits Laden.

### Q12 Die leuchtende Furche · 🟢 OPTIONAL
- **Auslöser:** Wort **Furche** (von Brit, Alva, Gerda, Baro auf **Saatgut** oder beim Umschauen an der Furche). **Alva** auf **Furche**: Ihre Leute halten die Straße, zwei sitzen in Dornwacht, für den Hof hat sie niemanden. Aufgabe beginnt, Wort **Speicher**. Wer vorher schon zum Hof geht, kann ihn trotzdem sichern; Alva gibt die Bitte dann als Bericht.
- **Stufe:** Bezugsstufe 11 (vier Köpfe, auch mit Varka und zu sechst gemessen). **Scherbenläufer** 3 × Stufe 12 (36 LP, schnell, furchtlos, je 140 EP), ab 5 und ab 6 Köpfen je einer mehr. Jeder zerspringt beim Tod in **zwei Splitter** (Stufe 9, 10 LP) auf freien Nachbarfeldern, die sofort handeln; wenig Platz = weniger Splitter. Man fällt also bis zu dreimal so viele Gegner. Kampf-EP je Kopf bei vier rund 105. Schwerer Pflichtkampf für die Säcke.
- **Lösungsweg:**
  1. Aus dem **Südtor** (Weltkarte 352, 296). Direkt südlich quer über y 304 die **Furche**: ein leuchtender Riss, unbegehbar. Dahinter der „Alte Talhof“ mit Steinmauer.
  2. Optional zuerst auf die **Anhöhe** im Osthang (375, 300, Höhe 2): Blick auf drei Gestalten im Hof und beide Übergänge: 20 EP, Wörter **Scherbenläufer**, **Furche**.
  3. Übergang wählen, der erste Schritt startet den Kampf:
     - **Westen, Zaunsteg** (349, 304): Die Gruppe steht vor der Bresche (349, 305) in den dachlosen Stall (halbhohe Mauern), ein Läufer im Stall, die übrigen kommen durch die schmale Stalltür (352, 307). Engstellen, Nahkampf zuerst. Kampfhinweis: An der Tür nimmt man sie einzeln.
     - **Osten, Geröllriegel** (366, 304): Die Gruppe steht hinter der Hecke des Gartens (Deckung), die Läufer verteilt im Hof, einer auf dem Speichersockel (Höhe für ihn, Fernkampf für die Gruppe).
     - Sieg 70 EP, Wort **Scherbenläufer**. Flucht: zurück vor die Furche (349, 302 bzw. 366, 302), die Gegner bleiben.
  4. **Wohnhaus** (Tür 353, 313) benutzen: ein **glattes Werkzeug** (glatt, ohne Naht, kalt, Schlüsselgegenstand), 5 EP, Wort **Glattes Werkzeug**. Im Dorf zeigen bzw. danach fragen: nur Vermutungen.
  5. **Speicher** (Tür 366, 313, auf dem Sockel, Höhe 1). Zwei Wege:
     - **Sylis** (Glasgrund, 30, 13) vorher nach **Speicher** fragen: Sie gibt den Schlüssel vom Brett (Tibbes Schloss). Mit Schlüssel öffnen.
     - Ohne Schlüssel: **„Zur Luke hochklettern“**, Probe Athletik 45 mit Hilfe (Fehlschlag: Kratzer, neuer Versuch möglich).
     - Darin sechs Säcke: 30 EP.
  6. **Wichtig für die beste Lösung:** Danach die **Speichertür umschauen** (nicht benutzen): Drei Säcke sind rötlich gebeizt (Saatkorn), drei sind Speisekorn. Erst dann gibt es die vermittelnde Wahl.
  7. Zurück ins Dorf, **Brit** am Lagerplatz nach **Saatgut** oder **Furche** fragen. Wahl:
     - **„Alle Säcke an Gerda“** (60 EP): Ihr Wagen fährt voll, die Bleibenden säen nicht.
     - **„Alle Säcke an die, die bleiben“** (60 EP): Baro verteilt die Saat, Gerda fährt mit halbem Wagen.
     - **„Halb und halb“** (60 EP, nur ohne gesehenen Unterschied): keiner hat genug.
     - **„Gerda das Speisekorn und einen Sack Saat, den Bleibenden zwei Sack Saat“** (80 EP, nur mit gesehenem Unterschied).
     - **„Noch nicht“**.
- **Wahlen und Enden:** Nach der Verteilung zieht Gerda fort, sobald die Gruppe das Dorf durch ein beliebiges Tor verlässt (ihr Hof ist danach leer). Bei Baro stehen Säcke in der Werkstatt (wenn er welche bekam). Brit, Alva, Gerda und Baro antworten auf **Furche** je nach Ausgang. Verzahnung: Gerdas Wagen steht später voll oder halb beladen im Lager am Deich (W02).
- **Belohnung:** bis 205 EP (Anhöhe 20, Hof 70, Speicher 30, Verteilung 60 oder 80, Werkzeug 5), Kampf-EP. Kein Gold.
- **Zum Testen:** Kampf von beiden Seiten (Bresche/Stalltür, Hecke/Speichersockel); Zerspringen (Splitter erscheinen ohne eigene Animation); Lesbarkeit der Furche bei Tag und Nacht (nachts schwach); Klettern; Verteilung mit und ohne gesehenen Unterschied; Gerdas leerer Hof nach dem Torgang; Klänge Klirren/Sirren.

### E08 Die Standarte von Dornwacht · 🟢 OPTIONAL
- **Auslöser:** **Alva** nach **Dornwacht** fragen (Wort von ihrer **Arbeit**): Auf der Ruine wurden die Hofstellen des Tals verzeichnet, sie schickte Hanno und Fenke hin, die nicht zurückkamen. Lehrt **Hofstellen**, startet die Aufgabe. Optional **Sylis** danach auf **Dornwacht**: Sie gibt den **Messingschlüssel** für die Truhe.
- **Stufe:** Bezugsstufe 11. Plünderer: **Kolk** Stufe 12 (52 LP, 160 EP), 2 **Plünderer** Stufe 10 (38 LP), **Plünderin mit Bogen** Stufe 10 (auf der Turmterrasse), **Junger Plünderer** Stufe 8; ab 5 und ab 6 Köpfen je ein Plünderer mehr. Nicht furchtlos. Kampf-EP je Kopf bei vier rund 140. „Ein ordentlicher Kampf, der zu viert meist gelingt.“
- **Lösungsweg:**
  1. Ruine auf dem Felsrücken nördlich des Dorfs (Weltkarte 346..362 × 244..259). Das eingestürzte **Tor** liegt im Süden (353..355, 257) über einen **Damm** (353..355, 258); Halt davor bei etwa (354, 260).
  2. **Am Tor** steht Kolk (ein Mann aus dem Tal). Wahl:
     - **„Über die Hofstellen reden“** (nur, wenn man das Wort **Hofstellen** von Alva kennt): Probe Charisma 50 mit Hilfe. Erfolg: Kolk gibt die vierzehn Namen seiner Leute für Alvas Liste und zieht ab, die Wachen sind frei (40 EP). Fehlschlag: Kampf am Tor.
     - **„Ihm 40 Gold für die beiden Wachen bieten“**: Sie ziehen ab, Wachen frei (40 EP).
     - **„Angreifen“**: Kampf durch die drei Felder breite Bresche.
     - **„Zurückgehen“**.
  3. Alternativ ohne Tor: im Westen in den **Graben** (etwa 347, 256), über die Schutthalde zur eingestürzten **Krone** (348, 251, Höhe 6). Wahl **„Von der Mauer aus angreifen“** (Kampf mit Überraschung für die Gruppe) oder **„Leise in den Graben zurück“**. Auch der **Sprung** vom Mauerrand in den Hof (349, 250..252) gibt einen Kampf mit Überraschung.
  4. **Kampf:** Fällt **Kolk**, ergeben sich die übrigen, Kolk bittet für seine Leute, sie ziehen ab. Ein voller Sieg führt zum selben Ergebnis (40 EP). Flucht nach (354, 260).
  5. Im Hof: Hanno und Fenke sind frei (stehen danach am Nordtor von Glasgrund). Am **Pult** der Wachstube (349, 256) den Truhenschlüssel nehmen.
  6. **Archiv** (Tür 350, 249, an der Nordseite) benutzen: die **Urkunden** (Blechlade, Schlüsselgegenstand), 30 EP, Wort **Hofstellen**. Dann die **Truhe** daneben: mit Pultschlüssel oder Sylis' Schlüssel, sonst Schloss 60. Inhalt: 2 Heiltränke, Gegengift, 3 Fackeln, 30 Gold.
  7. **Standarte** auf der Turmterrasse (359, 249): **„Abnehmen und mitnehmen“** oder **„Hängen lassen“**. Mitgenommen: **Brit** nach **Standarte** fragen, sie hängt sie über den Lagerplatz (keine EP).
  8. **Alva** nach **Dornwacht** oder **Hofstellen** mit den Urkunden: Abschriften mit Siegel für jeden Wagen, 50 EP. Nach erfolgreichem Reden ergänzt sie Kolks Leute.
- **Wahlen und Enden:** Reden, Zahlen, Kampf (am Tor oder mit Überraschung). Wirkt in Kapitel 7: Im **Lager am Deich** (W02) lässt Harmen nur Familien mit gesiegelter Abschrift auf das Vorland, Kolk lagert dort je nach Ausgang (bezahlt: spöttisch abseits; verhandelt: seine Leute stehen auf der Liste; besiegt: still). Ohne E08 hat niemand eine Abschrift.
- **Belohnung:** 120 EP (Hof 40 auf jedem Weg, Archiv 30, Abgabe 50), Kampf-EP, Truhe. Zahlen kostet 40 Gold.
- **Zum Testen:** alle vier Wege am Tor (zahlen, reden mit und ohne Erfolg, kämpfen, gehen); Krone über Graben und Halde; Sprung in den Hof; Ergeben nach Kolks Fall; Archiv und Truhe mit beiden Schlüsseln; Standarte über dem Lagerplatz; Hanno und Fenke am Nordtor.

### O10 Der singende Steinbruch und die Sternwarte · 🟡 ENTDECKUNG
- **Auslöser:** keiner, Fundort am Talrand östlich von Glasgrund (Weltkarte 374..398 × 282..295). Aus Nord- oder Südtor außen herum nach Osten, Zugang von Westen etwa bei (372, 289).
- **Lösungsweg (Reihenfolge frei):**
  1. **Tafel** am Kran (381, 284, an der Westwand des Schuppens) benutzen: das erste Glas zum Erntefest, 10 EP, Wort **Steinbruch**.
  2. **Geräteschuppen** (383, 285): Kreide und ein Glassplitter (Schlüsselgegenstände), 10 EP.
  3. **Spiegelader** (385, 289): ein Himmel ohne Wolken im Glas, 5 EP.
  4. **Messhütte** (390, 290): Z'zareks Zettel (erst das Flimmern, dann das Glas, unten der Erdrutsch beim ersten Frost). Mit gelesener Tafel: Vergleich, 10 EP (das Glas war vor dem Erdrutsch da).
  5. **Sternwarte** (395, 287): zu, das Rohr steht oben, 5 EP, Wort **Sternwarte**.
  6. **Vermessungsrahmen** auf der Kuppe (393, 283): zielt auf eine Senke im Norden mit einem Ring aus Mauerresten, 10 EP, Wort **Herz**.
- **Belohnung:** 50 EP. Ist Z'zarek dabei, kommentiert er einmal.
- **Zum Testen:** Steinbruch mit Z'zarek und Korgar; Blick durch den Rahmen.

### Z'zarek an seiner Sternwarte · 🔵 GEFÄHRTE
- **Auslöser:** **Z'zarek** sitzt vor der Messhütte (388, 290). Er spricht nur **Orkisch** und Drakonisch: Ohne Korgar, Varka oder Odrik in der Gruppe kein Gespräch und keine Aufnahme.
- **Lösungsweg:** **Name** (lehrt **Orks**, **Sternwarte**), **Sternwarte** (lehrt **Glas**, **Steinbruch**; er hat Angst vor der Enge unter der Kuppel), **Glas** (mit gelesener Tafel verknüpft er Tafel und Zettel: Vergleich, 10 EP, falls noch nicht). Dann **Anheuern**: Er will sehen, ob das Glas anderswo genauso wächst.
- **Belohnung:** Z'zarek, Drachenblütiger, Schwarzmagier, tritt mit **Stufe 10** bei (Vorlage Stufe 3, beim Beitritt angehoben). Einmalig 30 EP. Rivale von Beric (−45), mag Korgar (+40) und Varka (+35).

### Q29 Das letzte Schloss · 🟢 OPTIONAL
- **Auslöser:** **Sylis** (Weiler Stufe 1, 30, 13) nach **Tibbe** fragen (Wort aus **Arbeit** → **Schlüssel** → **Tibbe**). Sie erzählt vom Wintergang unter dem Hang, den sie selbst nicht betritt, und gibt den **Werkstattschlüssel** aus ihrer Lehrzeit. Wort **Gang**.
- **Stufe:** Bezugsstufe 12. Ein **Scherbenläufer** Stufe 12 (zerspringt in zwei Splitter) und 4 **Splitter** Stufe 9, ab 5 und ab 6 Köpfen je ein Splitter mehr, alle im Mittelband. Kampf-EP je Kopf bei vier rund 65. Laut Messung leicht.
- **Lösungsweg:**
  1. **Wemke** (Stufe 3, 41, 11) nach **Tibbe** fragen: Er bleibt wegen der Ahnennische in der Werkstattwand, eine Nische bricht, wenn man sie mitnimmt. Wort **Nische**.
  2. **Baro** (bei Tag 20, 33) nach **Nische** fragen: Man schlägt den Fels dahinter frei und hebt sie mit ihrem Stein. Er gibt sein **Setzeisen**. (Ohne Setzeisen bleibt nur der Weg, auf dem Tibbe bleibt.)
  3. Zum leeren Erdbau der Brenns (Weiler Stufe 3, Tür 43, 23, von 42, 23 aus): Erst mit begonnener Aufgabe **„Hinuntersteigen“** in den Keller (Karte „Tibbes Gänge“ 22 × 12, Ankunft 2, 3).
  4. Wintergang nach Osten (4, 5), dann die **Kammer** (4..16 × 3..8): Betreten löst den Kampf aus. Das Glas wächst alle 9 Ticks eine Stufe aus Nord- und Südwand (y 3 und 8, dann 4 und 7, zuletzt an den Ausgängen), bis nur das Band y 5..6 frei ist. Umrandete Felder wachsen als Nächstes zu (Marke in der Zeitleiste). Wer auf einem Feld steht, hält es frei. Sieg 50 EP. Flucht in den Keller.
  5. **Werkstatttür** (17, 6, von 16, 6 aus). Wahl:
     - **„Sylis' Schlüssel versuchen“**: Er dreht sich nicht, das Schloss ist neu, Tibbes letztes (nur Text).
     - **„Von Baros Weg erzählen“** (nur mit Setzeisen): Tibbe öffnet von innen.
     - **„Das Schloss öffnen“**: Fingerfertigkeit gegen 70, beliebig viele Versuche, Zeit vergeht.
     - **„Gehen“**.
     - Offen: 30 EP.
  6. **Werkstatt:** Tibbe an der Werkbank (19, 5), Nische (20, 6) benutzen:
     - Mit Setzeisen: **„Die Nische freischlagen, wie Baro es beschrieb“** (eine Stunde): Die Nische kommt heil heraus, **Tibbe geht** (40 EP). Danach steht er vor Wemkes Bau (42, 9), die Nische auf einer Trage.
     - Ohne Setzeisen: **„Wir sagen es ihr“**: **Tibbe bleibt**, gibt seine Werkzeugrolle für Sylis mit (40 EP). Oder **„Noch nicht“** (mit Setzeisen später der andere Weg).
  7. **Sylis** auf **Tibbe**: Bericht, 60 EP (bleibt Tibbe, nimmt sie die Werkzeugrolle).
- **Wahlen und Enden:** Tibbe geht oder bleibt. Wemke streicht ihre Liste anders (zwei Kerben weniger bzw. eine). Verzahnung: Ist Tibbe gegangen, taucht er nach der Einigung am Lehmhang (W04, Kapitel 7) dort auf und hat ein Wort **Lehmhang**.
- **Belohnung:** 180 EP (Kammer 50, Tür 30, Entscheidung 40, Bericht 60), Kampf-EP. Kein Gold. Sind Jaro und Sylis dabei, +10 zwischen den beiden, das versöhnt sie.
- **Zum Testen:** Tür der Brenns vor und nach dem Auftakt; Kammer: Umrisse, Zeitleistenmarke, Figur auf Glaszelle; Flucht; Werkstatttür auf allen vier Wegen; Tibbe geht (Trage) oder bleibt; Bericht und Aufnahme, auch bei voller Gruppe.

### Sylis · 🔵 GEFÄHRTE
- **Auslöser:** Q29 abgeschlossen (Bericht), freier Platz (weniger als sechs).
- **Lösungsweg:** Sylis am Schlüsselbrett ansprechen, **Anheuern**. Bei voller Gruppe Absage, sie bleibt am Brett.
- **Belohnung:** Sylis, Gnomin, **Stufe 10**, Diebin (Begabung Dieb und Schütze, Kämpfer gesperrt), Schleuder und Dolch, Lederrüstung, hohe Fingerfertigkeit und Wahrnehmung. Spricht Gnomisch und Gemeinsprache (kann für Jaro übersetzen). Einmalig 30 EP.
- **Zum Testen:** Angriff nach Süden schwach; Kommentare an anderen Orten fehlen noch.

---

### ↩️ Offene Enden und Rückkehr später
- **Q14:** Der rote Brief kommt erst aus der Glockenwacht (Brackhafen); Ennis kann ihn jederzeit später bekommen.
- **E09-Arznei:** Venyas Antwort und ihr Verhalten in der Nachtwache hängen an Brackhafen (Odo, Halvar oder das Bündel im Gepäck). Wer zuerst Lichtenruh macht, sieht die Wartetexte. Das Bündel lässt sich auch nach Q28 noch übergeben (20 EP), ändert die Wache aber nicht mehr.
- **Q10 als letztes Relikt:** Merets Abschlussbericht enthält mit Abschrift (Q06) und Fassung mit Ring (Q08) zusätzliche Sätze. Als drittes Relikt muss man durch das Band im Vorhof (F01, Unruhe 2).
- **Q15c** gibt es immer. Als zweite oder dritte Begegnung erkennt die Gruppe ihn wieder, als dritte nach der Sabotage sieht er die Brandstellen vom Band.
- **Q11:** Henneks zweiter Bericht braucht Ashka in Brackhafen (mit Widos Blatt). Der Steinhügel über Jorin lässt sich später nachholen.
- **Unruhe 2 und 3:** In Lichtenruh antworten Meret, Tomm, Ennis und Irmel auf **Rinne**, ab Unruhe 3 bietet Meret auf **Schutzleitung** den Versuch an (F01/Q16, anderer Abschnitt). Auf dem Südweg nördlich von Glasgrund erscheint bei Unruhe 3 der Riss W06.
- **Glasgrund in den Wegen (Kapitel 7):** Urkunden (E08), Kolks Ausgang und Gerdas Wagen (Q12) zeigen sich im Lager am Deich (W02); Tibbe zieht nach der Einigung am Lehmhang (W04) dorthin.
- **Gefährten:** Jaro, Beric, Haldaar, Z'zarek können jederzeit an ihren Orten nachgeholt werden; durch die Beitrittsstufe kommen sie auch spät nicht zu schwach.

---

## Kapitel 7 · Die Wege zwischen den Orten

**Anreise:** Kein eigener Ort, sondern Schauplätze an den Straßen der Weltkarte. Moosfels an der Nordroute Brackhafen–Lichtenruh (Kuppe um Weltkarte (111, 43), Schranke auf (112, 31–33)). Lager am Deich am Deichweg Brackhafen–Glasgrund (Deich Weltkarte (59–61, 300–327)), der Glockengarten nördlich davon als Insel vor dem Strand (Weltkarte (33–37, 242–250)). Lehmhang nordöstlich der Straße Dreifurt–Brackhafen (Weltkarte (146–167, 108–127), die Straße führt bei (150, 134) vorbei). Brandhof an der Gabel nordöstlich der Weggabel nach Tannried und Karrfels (Gabel Weltkarte (205, 258), Hof (223–237, 240–250), Tor (229, 250)). Sommerlager der Hünen über die Viehtrift vom Handelsstein (Weltkarte (348, 144)) nach Osten auf die Kuppe der Hochweide (Weltkarte (399–421, 143–152)).
**Wann:** Die Wege hängen an der **Unruhe** (Zahl der Relikte Fassung, Abschrift, Antwort). Brandhof und Lehmhang kann man schon früh besuchen, die Kämpfe an den Wegen liegen auf Stufe 9 (Bande) bis 13 (Ogerin). Auf dem gründlichen Weg (4 Köpfe) endet man die Wege mit Stufe 14–15 (mit freien Gruppen 15). Empfehlung: Brandhof einmal vor dem zweiten Relikt lebend besuchen, Moosfels, Deich und Hünen mit Gruppenstufe 12 oder mehr.
**Dienste:** Thies auf dem Brandhof: Rast in der Scheune 2 Gold, Ration 1 Gold (nur solange der Hof steht und nach seiner Rückkehr). Sonst keine Händler oder Gilden an den Wegen. Gerüchte über die Wege bei den Wirtinnen Hanne (Mühlbrück), Hella (Dreifurt), Geske (Brackhafen) und Imke (Karrfels) sowie bei Hauptmann Berthold in Dreifurt (Ortskarte (43, 22)), jeweils auf **Reisewege**.
**Gefährten:** Hier wirbt man niemanden an. Ruumar, der Jäger der Hünen, kämpft im Felskessel als Verbündeter mit. Wichtige Sprachkenntnisse: Hünisch spricht nur Haldaar, Zwergisch Beric, Odrik und Haldaar.

### V01b Unruhe auf den Wegen · 🟡 ENTDECKUNG
- **Auslöser:** Automatisch. Die Stufe zählt die Relikte: Fassung (Q08, Karrfels), Abschrift (Q06, Brackhafen), Antwort (Q10, Lichtenruh).
- **Stufe:** keine eigene Prüfung.
- **Was sich ändert:**
  1. **Stufe 0** (kein Relikt): Wege still, Brandhof lebt, Nordroute frei.
  2. **Stufe 1** (erstes Relikt): An der Nordroute Spuren, ein umgestürzter Karren (Weltkarte (100, 37), einmal 12 Gold) und ein Wagenrad (129, 40). Am Moosfels steht eine Schranke (Orks mit Hornist, oder Volkerts Leute, wenn man sie in Brackhafen vertrieben hat, siehe W01). Wirte reden vom Moosfels und lehren **Moosfels**.
  3. **Stufe 2** (zweites Relikt): Ork-Streife zieht östlich der Kuppe zwischen Weltkarte (129, 39) und (150, 41) den Weg entlang (Ork-Plünderer und Späher, Stufe 10, ab 5 Köpfen ein zweiter Plünderer). Brandhof abgebrannt, Thies sitzt in Dreifurt am Markt (W05). In Lichtenruh die zerschnittene Schutzleitung (F01). Wirte reden von der Streife.
  4. **Stufe 3** (alle drei Relikte): Riss am Südweg Lichtenruh–Glasgrund (W06), Meret schlägt den Versuch vor (Q16). Wirte reden von Leuten, die alles verlassen (die Gasthäuser bleiben offen).
- **Gerüchte:** Hanne, Hella, Geske, Imke auf **Reisewege**: je Stufe ein anderer Satz (Stufe 1 und 2 lehren **Moosfels**). Berthold auf **Reisewege** ab Stufe 1 mit Warnung vor der Schranke, auf **Moosfels** vier Fassungen (Hörensagen, gesehen, Meldung, danach). Meldungen bei Berthold: Moosfels (W01) und Brandhof (W05), je 25 Gold und 20 EP.
- **Zum Testen:** Wege ohne Relikt still; mit dem ersten Relikt Spuren, Karren, Rad, Gerüchte bei allen vier Wirtinnen; ab dem zweiten die Streife. Kein Text nennt Relikte oder die Gruppe als Ursache.

### W05 Der Brandhof an der Gabel · 🟢 OPTIONAL
- **Auslöser:** Zwei Phasen. **Vor dem zweiten Relikt** ist der Hof lebendig: Thies (231, 246), Frau Hedwig (226, 247), Knechte Jorn (233, 248) und Matthis (224, 248). Am Ostzaun (x 237, y 242–248) beim ersten Blick fremde Stiefelspuren, Wort **Spuren am Zaun**, Thies darauf ansprechen (lehrt **Thies' Ochsen**). **Ab dem zweiten Relikt** ist der Hof ausgebrannt (Popup beim Betreten am Tor oder Ostzaun, anderer Text, wenn man ihn vorher lebend sah), Thies sitzt in Dreifurt am Markt (Ortskarte (37, 33)).
- **Stufe:** Empfohlen 9+. Bande auf dem Hügel: Anführer der Bande (Stufe 9), 2 Plünderer (Stufe 8), Schütze der Bande (Stufe 8), ab 5 Köpfen ein Schläger (Stufe 7), ab 6 ein dritter Plünderer. Balance-Test: Held mit 3 Gefährten auf Stufe 9 gewinnt 12 von 12, allein 0.
- **Lösungsweg:**
  1. Ab Unruhe 2 den Hof betreten. Spur nach Osten auf Weltkarte x 238 (y 243–247), x 245 (y 242–246), x 251 (y 240–244): einmal Popup, Wort **Bande**, 10 EP. Alternativ in Dreifurt Thies am Markt nach **Brandhof** fragen (startet die Aufgabe, lehrt **Bande**, **Thies' Ochsen**, **Tannried**).
  2. Der Spur nach Osten zum Lager auf dem Hügel folgen (Weltkarte 254–267, 231–244, Feuer (260, 238), Pferch mit den Ochsen 263–266 × 238–241). Am Rand: **Angreifen**, **Sich anschleichen** (Probe Geschick 55 mit Hilfe; Erfolg: Sprung nach (256, 240) und Kampf mit Überraschung der Gruppe; Misserfolg: ein Ochse schnaubt, offener Kampf) oder **Zurückgehen**.
  3. Sieg: 40 EP, Vieh frei. Flucht: zurück nach (250, 244).
  4. In Dreifurt Thies nach **Brandhof** oder **Thies' Ochsen** fragen: 40 Gold, 30 EP, er kehrt heim.
  5. Berthold auf **Brandhof**: Meldung, 25 Gold, 20 EP.
- **Wahlen und Enden:** Anschleichen oder offen kämpfen, Lager meiden (dann bleibt Thies in Dreifurt, nichts geht verloren, Rast und Rationen gibt es in Dreifurt). Nach der Rückkehr: Plane, neue Planken, Ochsen im Hof, Thies, Hedwig und Jorn wieder dort, Rast unter der Plane (2 Gold).
- **Belohnung:** 10 (Spur) + 40 (Lager) + 30 (Rückkehr) + 20 (Berthold) = 100 Quest-EP, 65 Gold, dazu Kampf-EP (etwa 100 je Kopf zu viert).
- **Zum Testen:** Hof vor der Unruhe besuchen (Rast, Spuren), dann nach dem zweiten Relikt den Brand mit dem „wiedererkannt“-Text; ohne vorherigen Besuch den anderen Text. Anschleichen mit Erfolg und Misserfolg. Der Schütze hat Moral 100 (er flieht nicht außer Sicht). Freie Wildschweine stehen jetzt auf (259, 214), nicht im Lager.

### W04 Der Lehmhang · 🟢 OPTIONAL
- **Auslöser:** Arnold vor seiner Scheune (Weltkarte (155, 124)) grüßt und lehrt **Lehmhang**. Auf **Lehmhang** erzählt er von der Gnomenfamilie Quast im Hang (startet die Aufgabe, lehrt **Gnome**). Jederzeit, keine Unruhe nötig. Volle Fassung erst nach Q29 (Tibbes Gänge, Glasgrund): dann graben drei Familien statt einer.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Optional Ebba Quast vor ihrem Erdbau (Weltkarte (157, 117), Stufe 1 des Hangs, Tür (157, 116)) nach **Lehmhang** fragen.
  2. Die nasse Stelle über der Scheune benutzen (Weltkarte 151–154, 117–118): Probe Wahrnehmung 45 mit Hilfe. Erfolg: Wort **Quelle im Lehm**, 15 EP. Misserfolg: 10 Minuten, erneut versuchen.
  3. Optional Ebba auf **Quelle im Lehm**: Wasser führt man, eine Rinne zur alten Tränke (150, 125).
  4. Die nasse Stelle erneut benutzen: **Eine Rinne graben** (eine Stunde, Athletik 45 mit Hilfe; Misserfolg kostet die Stunde, erneut möglich). Erfolg: 20 EP, Wassergraben bis zur Tränke.
  5. Arnold auf **Lehmhang**: Einigung, 25 EP, 20 Gold.
  6. Ebba auf **Lehmhang**: zwei Heiltränke.
- **Wahlen und Enden:** **Einigung** (Rinne gegraben, die Gnome bleiben, nach Q29 auch die anderen Familien mit zwei neuen Erdbauten (162, 116) und (150, 111)). **Nein**: Arnold auf **Lehmhang** nach Aufgabenstart, solange keine Rinne gegraben ist, Wahl „Arnold hat recht, die Familie muss gehen“ (25 EP, 20 Gold, die Quasts ziehen fort, Tür zugeschüttet, Ebba fort; die Quelle weicht den Hang weiter auf). „Noch nicht“ lässt die Wahl offen. Verzahnung Q29: Ist Tibbe mit seiner Ahnennische gegangen und steht die Einigung, steht er hier (164, 117) neben dem Ahnenstein (164, 116), nicht mehr in Glasgrund. Ebba auf **Glasgrund** und **Tibbe** je nach Q29.
- **Belohnung:** 15 + 20 + 25 = 60 EP und 20 Gold mit zwei Heiltränken (Einigung), oder 15 + 25 = 40 EP und 20 Gold (Nein).
- **Zum Testen:** Blick und Benutzen der nassen Stelle in allen Zuständen, Tränke vor und nach der Rinne, Scheune nass/trocken, Q29-Varianten mit und ohne Tibbe.

### W01 Die Schranke am Moosfels · 🟢 OPTIONAL
- **Auslöser:** Ab dem ersten Relikt (Unruhe 1). Auf der Nordroute von Brackhafen Richtung Lichtenruh bis zur Kuppe Moosfels; die Straße biegt bei Weltkarte (107, 32) nördlich um den Fels. Auslöser beim Betreten auf x 108 (y 29–35, von Westen) oder x 117 (y 28–35, von Osten). Welche Fassung dort steht:
  - **Orks** (Normalfall): Barrikade aus Brettern und Deichseln, Ork-Bande mit Hornist.
  - **Volkerts Schranke**: nur wenn man Volkerts Leute in Brackhafen (V07 Strandrecht) per Drohung oder Kampf vertrieben hat und die Orks noch nicht gesehen hat. Ein Baumstamm, davor Volkert (113, 32) und Ubbo (113, 33).
- **Stufe:** Empfohlen 12. Orks: 3 Ork-Plünderer (Stufe 10), Ork-Späher (Stufe 10), Ork-Hornist (Stufe 11), ab 5 Köpfen ein 4., ab 6 ein 5. Plünderer. Furchtlos. Verstärkung: alle 18 Ticks ein Plünderer vom Nordrand, höchstens 2 Wellen, nur solange der Hornist steht (Marke „Horn“ in der Zeitleiste, Hornklang). Volkerts Leute: Volkert (Stufe 9), 2 Laternenträger, 2 Schleuderer (Stufe 8), mehr ab 5/6 Köpfen, Kampf ohne Tote. Balance-Test: Stufe 12, Held mit 3 Gefährten: Orks 9 von 12, angeschlichen 10, Schranke 12. Auf Stufe 10 nur 4 (offen) bzw. 9 (angeschlichen).
- **Lösungsweg (Orks):**
  1. Auslöserlinie betreten: Popup, Wort **Moosfels**.
  2. Wahl **Angreifen**, **Über den Hang des Moosfels anschleichen** (Probe Geschick 55 mit Hilfe, Kampf vom Hang (111, 36); Erfolg mit Überraschung, Misserfolg ohne) oder **Zurückweichen**.
  3. Den Hornisten zuerst ausschalten, dann endet der Nachschub.
  4. Sieg: 2 Heiltränke, 30 Gold, 60 EP. Flucht: zurück nach (104, 35), die Bande bleibt.
  5. Berthold in Dreifurt auf **Moosfels**: 25 Gold, 20 EP.
- **Lösungsweg (Volkert):** Wahl **Zwanzig Gold zahlen** (20 EP, Durchlass, Aufgabe bleibt offen), **Fragen, warum sie hier stehen** (Wort **Träger**, Gespräch mit Volkert: **Name**, **Arbeit**, **Träger**, **Moosfels**, **Orks**), **Erens Wort überbringen** (nur mit Erens Wort: Eren in Brackhafen auf **Träger**, wenn die Fähre wieder fährt (Q05) und Volkert vertrieben ist; Volkert geht mit seinen Leuten zum Fährpfahl (Weltkarte (49, 71)), 60 EP), **Den Stamm beiseiteräumen** (Kampf ohne Tote, Sieg 40 EP; Niederlage oder Flucht: aufwachen bei (104, 35)), **Weitergehen**.
- **Wahlen und Enden:** Orks besiegt, Erens Wort (bester Ausgang, 60 EP) oder Schranke freigekämpft (40 EP). Zahlen öffnet nur den Weg. Umgehen über die Wiese ist möglich. Wer die Orks einmal gesehen hat, behält die Orks.
- **Belohnung:** 60 (Orks/Erens Wort) bzw. 40 (Kampf Schranke) + ggf. 20 (Zahlen) + 20 (Berthold) EP, Gold 30 + 25 + 12 (Karren); Kampf-EP Orks etwa 200 je Kopf zu viert.
- **Zum Testen:** Orks auf allen drei Wegen, Hinweis im Kampf, Horn-Marke mit Zahl, Ende der Verstärkung nach dem Hornisten, Flucht. Volkerts Sperre: zahlen, zu wenig Gold, reden, Erens Wort, kämpfen und verlieren, danach Volkert am Fährpfahl. Ab Unruhe 2 die Streife.

### W02 Das Lager am Deich · 🟢 OPTIONAL
- **Auslöser:** Deichvogt Harmen an der Rampe in den Koog (Weltkarte (61, 309)) grüßt mit dem Wort **Siel**. Auf **Siel** erteilt er den Auftrag. Talke am nördlichen Feuer (52, 307) lehrt ebenfalls **Siel**. Keine Unruhe nötig. Ideal nach E08 (Dornwacht, Urkunden), Q12 (Gerdas Wagen) und Q13 (Glockenwacht), weil diese den Zustand verändern.
- **Stufe:** Empfohlen 12. Gegner: Sielegel (Stufe 10, 52 LP), 3 Schlickegel (Stufe 8), ab 5/6 Köpfen je einer mehr. Nachschub: alle 12 Ticks 2 Schlickegel aus dem Außentief, höchstens 4 Wellen. Balance-Test: Stufe 12, zu viert 11 von 12 (7 davon am Ziel), allein 0.
- **Lösungsweg:**
  1. Harmen auf **Siel** (Aufgabe beginnt). **Arbeit** lehrt **Hofstellen**.
  2. Über die Deichkrone nach Süden gehen. Auf der Krone (59–61, 317–327), am Deichfuß oder im Außentief beginnt der Kampf.
  3. **Kampfziel:** Eine Figur der Gruppe muss eine Zelle auf der Krone neben dem Schieber erreichen (61, 322–324, gelb markiert). Dann wird der Schieber gezogen und der Kampf endet. Ein voller Sieg führt zum selben Ergebnis. 80 EP, der Koog läuft leer.
  4. Harmen (steht jetzt bei (61, 321)) auf **Siel**: 40 Gold, 20 EP.
  5. Fluchthügel (siehe O06): Harmen auf **Fluchthügel**, nachdem man die Inschrift im Glockengarten gelesen hat: 50 EP, der Hügel ist offen (vor oder nach dem Siel möglich).
- **Wahlen und Enden:** Flucht: zurück auf die Krone (60, 314), das Siel bleibt zu. Verzahnung: Mit E08 erledigt ziehen die Familien mit Abschrift nach dem Siel in den Koog (Talke dann (66, 308)). Kolk (am Rand (49, 304)) je nach E08: bezahlt spöttisch, verhandelt mit seinen Leuten im Koog (68, 310), besiegt verwundet und nach geöffnetem Hügel auf dem Hügel (53, 316). Gerda (57, 312) nach Q12 mit vollem oder halbem Wagen. Mit offenem Hügel ziehen Talke und Wiebke hinauf.
- **Belohnung:** 80 + 20 + 50 = 150 EP, 40 Gold; Kampf-EP etwa 285 je Kopf zu viert (mit allen Wellen).
- **Zum Testen:** Warnung im Log auf der Krone vor dem Auftrag, Blicke auf Planen, Feuer, Sperre (62, 309), Schlick, Schieber (62, 323), Hochwasserstein (51, 317). Kampf mit gelbem Ziel, Hinweis und Egel-Marke, Ende am Schieber, Flucht. Der trockene Koog danach.

### O06 Der versunkene Glockengarten · 🟡 ENTDECKUNG
- **Auslöser:** Insel vor dem Strand (Weltkarte 33–37, 242–250), über die Furt aus flachem Wasser (38–39, 246) neben einem umgestürzten Baum (40, 245). Harmen erklärt auf **Glockengarten** den Weg (Wort von Harmen auf **Glasgrund** oder Talke auf **Arbeit**).
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Opferstein (36, 245) benutzen: einmal ein Heiltrank.
  2. Inschrift am Kapellenfundament (35, 249) lesen: Wort **Fluchthügel**, 10 EP (dann bei Harmen, siehe W02).
  3. Strandnelken (36, 248) einmal pflücken, dann die Gräber (34–36, 246) benutzen: Blüten ablegen, 20 EP.
  4. Glocke (35, 244) und gesprungener Bogen (34, 244) ansehen/benutzen.
  5. Nachts auf (35, 242) nach Norden sehen: das Feuer der Glockenwacht und ein zweites, bleiches Licht (nach Q13 steht das echte Feuer ruhig).
- **Belohnung:** 30 EP, ein Heiltrank.
- **Zum Testen:** Tag und Nacht, mit und ohne Q13. Die Glocke hat keinen Klang.

### W03 Das Sommerlager der Hünen · 🟢 OPTIONAL
- **Auslöser:** Viehtrift (Weg auf y 146) vom Graufelspfad beim Handelsstein (Weltkarte (348, 144)) nach Osten auf die Kuppe (399–421, 143–152). Beim Betreten des Kuppenrands ein Empfang je nach V03 (Handelsstein, Karrfels-Region):
  - fair getauscht oder nachgelegt: Gastrecht sofort, 30 EP;
  - Felle genommen ohne Ausgleich: kein Gastrecht;
  - nie am Stein: „Fremde ohne Zeichen“.
  Haldaar in der Gruppe kommentiert jeden Fall.
- **Stufe:** Empfohlen 12–13. Ogerin (Stufe 13, 95 LP, wirft dreimal je Kampf Felsbrocken, die einen Zug später in einem Kreis Radius 1 einschlagen), Oger (Stufe 12, 110 LP), ab 5 Köpfen ein 2., ab 6 ein 3. Oger. Ruumar zählt als Kopf: Zu viert mit Ruumar steht also schon der zweite Oger da. Balance-Test: Stufe 12, zu viert mit Ruumar 12 von 12, allein 0.
- **Lösungsweg:**
  1. **Gastrecht** holen, falls nicht schon da: Feuer (409, 148) benutzen. Nach Diebstahl mit drei Schneefellen: **Die drei Schneefelle zurückgeben**. Als Fremder mit zwei Rationen: **Brot teilen (zwei Rationen)**. Jeweils 30 EP. (Alternative nach Diebstahl: am Handelsstein drei Barren nachlegen.)
  2. Vaarek (Zwergisch, (413, 148)) grüßt und lehrt **Oberes Pferch**. Ulgaar (nur Hünisch, am Feuer (409, 147)) auf **Name**, **Gastrecht**, **Herde**, **Sommerlager**, **Alter Pass**.
  3. Oberes Pferch im Südosten betreten (416–422, 157–165): Popup, Wörter **Oger** und **Oberes Pferch**, 10 EP.
  4. Mit Gastrecht Ulgaar, Vaarek oder Ruumar (Hünisch, (406, 152)) nach **Oger** fragen: die Jagd beginnt, Ruumar wartet am oberen Pferch (417, 161).
  5. Durch die Lücke (423, 160–162) in den Felskessel: Kampf. Aus den Wurfkreisen der Ogerin heraustreten.
  6. Sieg: 90 EP. Flucht: zurück ins Pferch (418, 161).
  7. Feuer benutzen oder Ulgaar auf **Oger**: Gastgeschenk **Schnur der Sippe** (Hals, Ausdauer +4, Stärke +3), 20 EP.
- **Wahlen und Enden:** Ohne Sprache (kein Haldaar, Beric oder Odrik) gibt es keine Jagd mit Ruumar, der Kessel steht aber offen (allein ist er härter). Ohne Gastrecht nach dem Sieg nimmt Ulgaar die Gruppe trotzdem ans Feuer (30 EP Gastrecht dazu). Nach Felldiebstahl bleibt ein Satz als offene Rechnung.
- **Belohnung:** 30 + 10 + 90 + 20 = 150 EP, Schnur der Sippe; Kampf-EP etwa 250 je Kopf zu viert.
- **Zum Testen:** Empfang je V03 (fair, Diebstahl, ohne), Gespräche mit und ohne Haldaar, Felle zurück oder Brot. Kampf mit Hinweis, Wurfkreis, Aufschlagklang, Ruumar an der Seite, Flucht. Nachts die Herde (alle Köpfe nach Westen, Haldaars Einwurf). Der freie Bergtroll steht jetzt auf (412, 202).

### Freie Begegnungen auf der Weltkarte · 🟢 OPTIONAL
- **Auslöser:** 40 sichtbare Gegnergruppen ohne Text auf der Weltkarte, dazu ein Hinterhalt. Unabhängig von der Unruhe. Sie kehren nach dem Sieg nicht zurück. Schwache Gruppen erledigen sich bei hoher Stufe per Auto-Sieg. Gruppengröße wächst mit der Gruppe (allein 1–2, voll 4–6 Gegner).
- **Startdreieck (Stufe 1–5):** Ratten (Stufe 1) östlich und westlich von Mühlbrück (167, 146), (125, 146), bei Tannried (156, 291), bei Dreifurt (232, 211). Goblinbanden (Goblins Stufe 1–3, an Wegen stehend) am Bachweg (151, 231), Küstenweg (69, 225), Dreifurtweg (198, 209), Karrfelsweg (206, 250), Südklippen (98, 356). Spinnen (Kellerspinnen Stufe 1–3) Tannwald West (92, 319), Tannwald Mitte (201, 287), Westhain (90, 252). Wildschweine (Bache 3, Keiler 5) Feld (120, 212), Waldrand (259, 214), Südwest (65, 352). Strandkrabben (Stufe 3) am Strand (40, 179), (50, 265), (36, 346).
- **Mitte und Norden (Stufe 3–9):** Höhlentroll (Stufe 5) am Granitmassiv (191, 110) und (178, 68). Orks (Stufe 3–4) Nordebene (174, 42) und (292, 54). Wolfsrudel mit Leitwolf (Stufe 6) Nordebene (112, 79) und bei Karrfels (330, 182). Felsenkrabben (Höhlenkrabben Stufe 9) an der Küste bei Brackhafen (50, 17) und (48, 124). Schlickegel (Stufe 8) im Moor (108, 113) und am Fluss (148, 137). Riesenratten (Stufe 6) bei Brackhafen (78, 73) und Karrfels (290, 98).
- **Hinterhalt an der Brücke der Karrfelsstraße:** Betreten der Brücke (286, 164–166): Orks brechen aus dem Schilf (Ork-Krieger, Ork-Schützen Stufe 4, ab 5 Köpfen ein Ork-Schamane Stufe 5), Überraschung der Gegner. Flucht nach Norden (284, 162), der Hinterhalt wiederholt sich bis zum Sieg.
- **Gebirge und Osten (Stufe 7–11):** Klammspinnen (Stufe 7) am Pass (379, 115). Bergtroll (Stufe 11, 130 LP, 400 EP, ein Heiltrank) Ostgebirge (412, 202) und Südgebirge (415, 323). Aaskrähen (Stufe 7) bei Lichtenruh (362, 186) und im Südosten (295, 342). Kammechsen (Stufe 7) (315, 222). Flimmervögel (Stufe 9) bei Glasgrund (315, 284) und (350, 350). Orktrupp (Plünderer und Späher Stufe 10) im Südosten (310, 253) und am Ostweg (392, 229).
- **Belohnung:** zusammen rund 8 400 EP für eine Vierergruppe (etwa 2 100 je Kopf), etwa eine Stufe mehr am Ende von Akt I.
- **Zum Testen:** Wirkt die Karte belebt, aber passierbar? Wandernde Gruppen nahe Wegen, Hinterhalt (Text, Überraschung, Flucht, Wiederholung, Ruhe nach dem Sieg), Auto-Sieg in hoher Stufe. Strandkrabbe, Riesenratte und Bergtroll tragen fremde Figuren.

**Offene Enden / Rückkehr später (Wege):**
- Brandhof erst lebend besuchen (vor dem zweiten Relikt), sonst fehlt der Wiedererkennungstext. Den Kampf gibt es erst ab Unruhe 2.
- Lehmhang nach Q29 erneut besuchen (neue Erdbauten, ggf. Tibbe).
- Moosfels: Volkerts Fassung nur nach V07 mit Vertreibung; Erens Wort erst nach Q05 (Fähre) holen. Meldungen bei Berthold nicht vergessen (Moosfels, Brandhof).
- Deich: nach E08 und Q12 zurückkehren, damit Familien, Kolk und Gerda ihre Endzustände zeigen. Glockengarten nachts nach Q13.
- Hünen: am besten nach fairem Handel am Handelsstein (V03) und mit Haldaar in der Gruppe.

## Kapitel 8 · Das Finale

**Anreise:** Lichtenruh (Weltkarte um (361, 153), Tore West, Nord, Süd), der Vorhof oben über die obere Terrasse (Ortskarte (32, 7–8)), Knoten (36, 4), Quellpforte (47, 4). Rast der drei Steine am äußeren Weg zur Herzsenke, westlich vor dem Ruinenring (Weltkarte um (377–382, 211–213)). Herzsenke: Ruinenring Weltkarte (404, 216), Abstieg unter dem geborstenen Torbogen (409, 221). W06 am Südweg Lichtenruh–Glasgrund (Weltkarte (363–366, 258–267)).
**Wann:** F01 ab dem zweiten Relikt, Q16, O12 und W06 erst mit allen drei. Der Abstieg in die Herzsenke ist verschüttet, bis Merets Karte aus Q16 den Weg der Hüter zeigt, das innere Tor öffnet sich nur mit Fassung, Abschrift und Antwort. Gründlich (4 Köpfe): Ankunft in der Herzsenke mit Stufe 15 (mit freien Gruppen 17), nach dem Fremden 16. Pflichtweg allein: mindestens Stufe 9. Empfehlung: Stufe 14+ für Ring und Galerie, Stufe 15 für den Fremden, mit Heiler und möglichst fünf Köpfen.
**Dienste:** Tomm an der Rast der drei Steine (nach Q16): Gasthaus 1 Gold je Nacht, Ration 1 Gold; zugleich Wartebank der Gefährten (wie ein Gasthaus). Vor Q16 kann man am kalten Feuer rasten. In der Herzsenke keine Dienste, in der Bedienkammer eine Truhe mit zwei Heiltränken. Lichtenruh-Dienste siehe dortigen Abschnitt.
**Gefährten:** Keine neuen. An der Rast stehen die angeworbenen Gefährten, die auf der Wartebank sind; dort kann man die Gruppe für das Finale zusammenstellen. Ab dem Schritt durch den Durchgang in C04 sind alle Gefährten fort (Akt II beginnt mit dem Helden allein).

### F01 Die zerschnittene Leitung · 🟣 HAUPTGESCHICHTE
- **Auslöser:** Ab dem zweiten Relikt (Unruhe 2). Den Weg südlich des Vorhofs (Ortskarte 32–46, 9–10) oder die Westöffnung (32, 7–8) betreten: Popup, Wort **Rinne**, Aufgabe beginnt. In der Rinne (39–43, 4) fehlen die schwarzen Streifen, Wildas Handkarren (41, 7) liegt umgestürzt, ein flimmerndes Band (44, 2–6 und 45–46, 6) sperrt die Tasche vor der Quellpforte. Dahinter sitzt die Steinsetzerin Wilda (45, 3) mit verbranntem Bein.
- **Stufe:** kein Kampf. Das Band kostet beim Durchqueren jede Figur 2W6 LP (nie unter 1).
- **Lösungsweg:**
  1. Band anlaufen oder benutzen: **Hindurchgehen**, **Hinüberrufen** (Wildas Bericht vom Mann im staubigen Mantel, 20 EP, wer dem Fremden schon begegnet ist, erkennt ihn in der Beschreibung wieder), **Einen Heiltrank hinüberwerfen** (nur mit Heiltrank, 10 EP), **Zurücktreten**.
  2. Oder hindurchgehen und Wilda direkt ansprechen: **Name**/**Arbeit** lehren **Rinne**, **Rinne** gibt den Bericht (20 EP, nur einmal insgesamt), **Schutzleitung**. Einen Heiltrank als Geschenk geben (10 EP).
  3. Meret auf **Rinne** (lehrt **Schutzleitung**) oder **Schutzleitung**: 10 EP. Meret steht tagsüber im Skriptorium (33, 18), in der Dämmerung bei (27, 5), nachts nicht ansprechbar.
  4. Optional Ennis, Irmel (Hospiz) und Tomm auf **Rinne**, Tomm auch auf **Schutzleitung**.
- **Wahlen und Enden:** Erledigt mit Bericht und Merets Erklärung. Das Band bleibt bis Q16. Wilda wartet ohne Frist. Pflichtweg-Hinweis: Holt man die Antwort (Q10) als drittes Relikt, sperrt das Band schon den Weg zur Quellpforte. Man muss hindurch (Schaden). Kommt man mit Unruhe 2 aus dem Quellbezirk zurück, steht man in der Tasche neben Wilda (eigener Text).
- **Belohnung:** 20 + 10 + 10 = 40 EP.
- **Zum Testen:** Anblick vom Weg, von der Westöffnung und beim Anlaufen ohne vorherigen Anblick, Rufen einmal, Hindurchgehen in beide Richtungen ohne Tod, Heiltrank werfen oder schenken, Rückkehr aus der Quelle. Das Band ist vor Mauern gut, aus der Tasche über den Hof kaum zu sehen.

### Q16 Der Versuch im Kleinen · 🔴 PFLICHT
- **Auslöser:** Mit allen drei Relikten (Unruhe 3) grüßt Meret anders und lehrt **Schutzleitung**. Auf **Schutzleitung** oder **Versuch** schlägt sie den Versuch am heilen Knoten vor (Wort **Versuch**, 10 EP, falls F01 bei ihr noch offen war) und wartet im Vorhof (34, 5).
- **Stufe:** kein Kampf. Nötig: Fassung im Gepäck.
- **Lösungsweg:**
  1. Den Knoten (36, 4) benutzen: Fassung einsetzen.
  2. Zeichen in der Folge der Abschrift berühren: **Den Bogen mit den drei Kerben berühren.**, dann **Die Welle berühren.**, dann **Den Kreis mit dem Punkt berühren.** Eine falsche Wahl löscht die Zeichen, ohne Schaden, von vorn.
  3. {held} gibt die Antwort: doppelter Ton, Lichtblitz, das Band erlischt, Wilda humpelt herüber (steht dann bei (42, 6)), das Band flimmert wieder. 80 EP, die Fassung bleibt bei der Gruppe.
  4. Der Fremde tritt an der Westöffnung (33, 7) hervor. Wahlbaum: **Fragen, was er will** (lehrt **Risse**), **Nach Beweisen fragen**, **Nach Wilda fragen**, **Fragen, ob es keinen anderen Weg gibt**. Die letzte Frage beendet das Gespräch: Merets Gegenrede mit den Karten, er geht nach Westen ab (40 EP).
  5. Meret gibt die **Karte der Leitungen**, lehrt **Wartungsgang** und erklärt: Alle Leitungen laufen im **Herz** in der Senke im Osten zusammen, der Knoten hielt nur einen Atemzug, mit dem Herz hält vielleicht das ganze Netz. Der Abstieg unter dem Torbogen ist verschüttet, die Karte zeigt den Weg der Hüter. Sie lädt die Gefährten an die Rast der drei Steine ein (30 EP).
- **Wahlen und Enden:** Alle vier Fragen stellen für den ganzen Text, oder gleich nach dem anderen Weg fragen. Mit Esc bleibt der Fremde stehen und lässt sich später ansprechen. Nach dem Versuch fragt das Band nur noch **Hindurchgehen** oder **Zurücktreten**. Tomm verlässt Lichtenruh und bewirtet die Rast. Die Karte erleichtert den äußeren Ring.
- **Belohnung:** 80 + 40 + 30 (+10) = 150 bis 160 EP, Karte der Leitungen, Wörter **Versuch**, **Risse**, **Wartungsgang**.
- **Zum Testen:** Meret ohne drei Relikte, Knoten erst nach dem Vorschlag, ohne Fassung, falsche Folgen und Zurücktreten, Wilda läuft herüber, Gespräch ganz und kurz. Wilda und der Fremde haben nur die Standpose.

### O12 Die Rast der drei Steine · 🟣 HAUPTGESCHICHTE
- **Auslöser:** Rastplatz mit drei aufrechten Steinen (Bogen (378, 211), Welle (381, 211), Kreis (377, 213)), Unterstand (382, 212) und Feuer (379, 213), am Weg zum Ruinenring der Herzsenke. Vor Q16 leer, kaltes Feuer zum Rasten. Nach Q16 brennt das Feuer, Tomm (381, 213) bewirtet.
- **Stufe:** kein Kampf.
- **Lösungsweg:**
  1. Vor dem Aufbruch Gefährten, die man im Finale nicht dabeihaben will, in einem Gasthaus auf die Wartebank setzen. Sie stehen dann hier.
  2. Nach Q16 die Rast betreten: Begrüßung (mit oder ohne Gefährten), 20 EP, höchstens drei Gefährtenzeilen in zufälliger Reihenfolge.
  3. Bei Tomm die Gruppe für die Herzsenke zusammenstellen, rasten, Rationen kaufen.
- **Belohnung:** 20 EP.
- **Zum Testen:** Vor Q16, mit Wartenden, allein, nachts. Alle zwölf Gefährten haben eine Zeile mit Portrait. Die Zeichen auf den Steinen sind in der Schrägsicht klein, in der Ego-Ansicht deutlich.

### W06 Der Riss am Südweg · 🟢 OPTIONAL
- **Auslöser:** Ab Unruhe 3. Am Südweg Lichtenruh–Glasgrund hängt östlich bei Weltkarte (369, 262) ein Riss, auf dem Weg davor (366, 263) stehen Risswesen. Auf dem Weg von Norden (363–366, 258) oder Süden (363–366, 267) kommend oder beim Benutzen der Gruppe: **Angreifen** oder **Zurückweichen**. Über die Wiese daneben kommt man ohne Frage vorbei.
- **Stufe:** Empfohlen 13. 2 Rissnachhalle (Stufe 12, 46 LP), 2 Rissgluten (Stufe 11), ab 5/6 Köpfen je eine Glut mehr. Balance-Test: Stufe 13, zu viert 12 von 12, allein 0.
- **Lösungsweg:** Angreifen, Sieg: 40 EP, der Riss erlischt. Flucht: zurück auf den Weg nach Norden (366, 252) bzw. Süden (363, 271).
- **Belohnung:** 40 EP, Kampf-EP etwa 150 je Kopf zu viert.
- **Zum Testen:** Annäherung von Norden, von Süden, über die Wiese.

### Q17a Der äußere Ring · 🔴 PFLICHT
- **Auslöser:** Den Torbogen im Ruinenring betreten (Weltkarte (409, 221)). Vor Q16 ist der Abstieg verschüttet: Geröll auf der Stufe hinter dem Bogen, beim ersten Betreten ein Popup, danach eine Protokollzeile, Umschauen zeigt das Geröll. Nach Q16 legt Merets Karte beim ersten Betreten die Stufen frei (Popup), dann geht es ohne Rückfrage hinab. Ankunft im Süden des äußeren Rings (Ortskarte (49, 90)), der erste Schritt zeigt den Hof. Nötig ist Q16, kein einzelnes Relikt. Die Treppe zurück liegt bei (49, 91).
- **Stufe:** Empfohlen 14+. 4 Ringwächter (Stufe 12, 42 LP, vorn Steinpanzer +2 Rüstung), 2 Laufwächter (Stufe 13, 20 LP, werfen Steinsplitter, Reichweite 2–7, vom Umgang auf Höhe 2), ab 5/6 Köpfen je ein Ringwächter mehr. Alle sehen 8 Felder weiter (Steinsinn). Balance-Test: Stufe 14, zu viert mit Laufwächtern 5 von 12, ohne Laufwächter 10 von 12, allein 0.
- **Lösungsweg:**
  1. Über den Umgang (Höhe 2) laufen, Statuen ansprechen (Beschreibung).
  2. Auf dem östlichen Umgang (57, 80–82) einmalig: Mit der Karte der Leitungen (Q16) zeigt sich der Wartungsgang sofort. Sonst stille Probe Wahrnehmung 50. Sonst am Spalt (58, 81) benutzen: **Den Mauerfuß absuchen** (Wahrnehmung 50 mit Hilfe, 10 Minuten bei Fehlschlag). Fund: Wort **Wartungsgang**, 20 EP.
  3. Durch den Gang in die Bedienkammer. Pult (63, 81) benutzen: mit der Fassung legt {held} die Laufwächter still (die Fassung bleibt), sonst **Die beiden Hebel in die Reihe legen** (Fingerfertigkeit 60 mit Hilfe, 10 Minuten bei Fehlschlag) oder **Lieber nichts anrühren**. Erfolg: 20 EP, Klang.
  4. Truhe (64, 79): zwei Heiltränke. Seit HZ1 glimmen die Fugen der beiden Laufwächter, bis das Pult sie stilllegt, die Sichtscharte (60, 80) zeigt es, die Relieftafel (62, 78) den Grundriss der Anlage.
  5. Eine der Treppen in die Mitte hinab (Treppenfüße (45, 85) oder (53, 85)): die Wächter erwachen, Kampf (ohne Laufwächter, wenn stillgelegt).
  6. Sieg: 80 EP, das Tor im Norden (49, 73) öffnet sich zum Wachgang. Flucht: zurück an die Ankunft (49, 90), die Wächter stehen wieder still.
- **Wahlen und Enden:** Mit oder ohne Bedienkammer. Gleiche EP, aber ohne Pult ist der Kampf deutlich schwerer (Laufwächter von oben). Der Ring bleibt nach dem Sieg ruhig.
- **Belohnung:** 20 + 20 + 80 = 120 EP, zwei Heiltränke; Kampf-EP etwa 350 je Kopf zu viert.
- **Zum Testen:** Den Hof von oben ansehen, Statuen, östlicher Umgang mit und ohne Karte, Pult mit und ohne Fassung, Kampf mit und ohne Laufwächter, Flucht. Die Angriffsbilder der Wächter tragen in zwei Richtungen noch kleine graue Schwungbögen. Bilder -- --herzring.

### Q17c Die Herzanlage und die drei Zeichen am Tor · 🔴 PFLICHT
- **Auslöser:** Durch das offene Ringtor (49, 73) nach Norden in den Wachgang. Die Anlage liegt zwischen Ring und Galerie (Ausbau HZ1 bis HZ5, [planung-herzsenke-ausbau.md](planung-herzsenke-ausbau.md)). Aufgabe »Drei Zeichen am Tor« ab dem ersten Blick auf das Zeichentor.
- **Stufe:** Empfohlen 14+, Torwächter 15. Wachsaal: 2 Rissgluten, 1 Rissnachhall (zu viert 5 von 6). Hammerhalle: 3 Ringwächter, 2 Laufwächter oben auf dem Steg (zu viert 6 von 6). Archiv: Archivwächter, 2 Laufwächter (6 von 6). Quellgrund: 2 Rissnachhalle, 2 Rissgluten, 2 Wellen je eine Glut (5 von 6). Torwächter (Stufe 15, 260 LP, groß, Steinpanzer vorn, Wuchtschlag gegen alle Nachbarn) mit 2 Ringwächtern (4 von 6, knapp). Freiwillig: Brunnenkammer, 2 Ringwächter. Ab 5/6 Köpfen je ein Gegner mehr.
- **Lösungsweg:**
  1. **Wachgang und Wachsaal** (49, 48–72): Beim Betreten des Saals Kampf, aus dem Riss (55, 64) kommt Nachschub. {held} zu Zugbeginn neben dem Riss schließt ihn. Danach schließt er ihn endgültig (20 EP). Die aufgebrochene Rinne erinnert an Lichtenruh.
  2. **Wärterstube** (39–45, 51–57): Truhe (40, 52) mit drei Heiltränken und 40 Gold, ruhiger Ort zum Rasten. Gegenüber die **Rüstkammer** (Tor 52, 54), zu bis zum Kerbstein (Schritt 6).
  3. **Kreuzhalle** (42–56, 33–47): Drei Flügel in freier Reihenfolge, je ein Tor mit Zeichen, das bei Berührung zur Seite gleitet. Im Westen der Säulengang zur Zeichenhalle.
  4. **Hammerhalle** (Osttor 56, 40): Kampf beim Betreten. Vor der Hammerkammer hängt ein Vorhang aus blauem Licht (68–72, 34): hindurch kostet 2W6 LP je Figur in beide Richtungen, oder der **Sperrhebel** oben am Oststeg (78, 44) löscht ihn (über die Treppen 64, 49–50 oder 76, 49–50). In der Kammer der **Hammerhebel** (70, 29): Stärke oder Athletik mit Helfer gegen 35, jeder Fehlschlag (10 Minuten) lockert ihn um 10, nach dem dritten gibt er ohne Wurf nach. Die Hammerplatte leuchtet (30 EP). Truhe (74, 29): 80 Gold, zwei Heiltränke.
  5. **Archiv der Hüter** (Nordtor 49, 33): Kampf zwischen den Regalen. In der Lesekammer (31–35, 10–15) steht die Bildfolge auf dem Pult. An der **Zeichenwand** (46–52, 3) die Tafeln ziehen: **Bogen, Welle, Kreis** (Bogen 50, 3, Welle 47, 3, Kreis 52, 3). Der erste Fehlgriff ruft einen Archivwächter aus der Nische (Kampf), jeder weitere setzt nur zurück. Die Hausplatte leuchtet (30 EP).
  6. **Quellgrund** (Schachtblock 48–50, 39–41): Die Südseite (49, 41) berühren, Stufen hinab auf Ebene 1. Freiwillig die **Brunnenkammer** im Norden (Kampf, Truhe mit 60 Gold und dem **Kerbstein**). Beim Betreten des Quellgrunds Kampf auf den Stegen über dem Becken, Riss (51, 55) vom Steg aus schließen (20 EP). **Ostschieber** (67, 58) trocken über den dunklen Kanal, **Westschieber** (31, 58) über den Weststeg, die Lücke im Oststeg geht nur schwimmend. Nach beiden läuft das Becken leer. Am Grund den **Quellstein** (44, 61) berühren: Die Quellplatte leuchtet (30 EP). Treppe hinauf an der Südwand des Schachtraums (47, 44).
  7. **Rüstkammer** (freiwillig): Mit dem Kerbstein öffnet das schmale Tor, in der Truhe (58, 54) der **Schild der Wache** (einzigartig, Rang 6).
  8. **Zeichenhalle** (1–17, 34–46): Mit jedem Zeichen leuchtet ein Drittel der Lampen im Säulengang, hinter dem Tor scharrt es lauter. Mit drei hellen Platten tritt beim Betreten der **Torwächter** aus der Wand, zwei Ringwächter aus den Nischen. Sieg: 80 EP, das Zeichentor öffnet (40 EP). Flucht: zurück in den Säulengang (24, 40), er steht wieder in der Wand.
- **Wahlen und Enden:** Reihenfolge der Flügel frei. Vorhang hindurch oder Sperrhebel. Brunnenkammer und Rüstkammer freiwillig.
- **Belohnung:** Quest-EP etwa 420, Kampf-EP etwa 1570 je Kopf zu viert, Schild der Wache, Gold und Heiltränke.
- **Zum Testen:** Entwicklereinstieg »Herzsenke: Kreuzhalle«. Jeder Flügel einzeln, Vorhang beide Wege, Hammerhebel mit schwacher Gruppe, Zeichenwand falsch und richtig, Becken mit einem und mit beiden Schiebern, Rüstkammer mit und ohne Kerbstein, Torwächter mit Flucht. Bilder `-- --herzhammer`, `--herzarchiv`, `--herzquelle`, `--herztor`.

### Q17b Die gebrochene Galerie und das innere Tor · 🔴 PFLICHT
- **Auslöser:** Durch das offene Zeichentor (8–10, 33) nach Norden in die Galerie (Ortskarte x 8–10, y 17–31). Der Riss (8, 24) vor dem Seitenbogen ist offen.
- **Stufe:** Empfohlen 14+. Großer Scharrer (Stufe 13, 60 LP), 3 Scharrer (Stufe 12, 26 LP), ab 5 Köpfen ein 4. Nachschub aus dem Riss: alle 12 Ticks 2 Scharrer, höchstens 2 Wellen. Balance-Test: Stufe 14, zu viert von vorn 7 von 12, von hinten 9 von 12, allein 0 (die KI schließt den Riss nicht, im Spiel ist es mit der Antwort leichter).
- **Lösungsweg:**
  1. **Weg A, von vorn:** Galerie nach Norden, beim Schritt auf Zeile 28 beginnt der Kampf.
  2. **Weg B, von hinten (besser):** Durch den Bogen in der Ostwand (11, 29) in den dunklen Seitengang (12, 20–29). Auf (12, 21) beginnt der Kampf, die Gruppe steht im Rücken des großen Scharrers, {held} zieht zuerst.
  3. Mit der Antwort (Q10): {held} zu Zugbeginn auf (8, 23), (9, 24) oder (8, 25) stellen. Der Riss schließt sich, kein Nachschub mehr.
  4. Sieg: 80 EP. Mit der Antwort schließt {held} den Riss danach (20 EP). Ohne die Antwort bleibt er still offen und lässt sich später mit ihr benutzen und schließen (20 EP). Flucht: zurück auf (9, 31).
  5. Auf Zeile 18 der erste Blick durch den Spalt des inneren Tors auf das Herz (höchstens drei Gefährtenzeilen).
  6. Inneres Tor (9, 17) benutzen. Mit Fassung, Abschrift und Antwort: Hinweis „Hinter diesem Tor endet der erste Akt. Speichert vorher …“, Wahl **Das Tor öffnen** (20 EP) oder **Noch nicht**. Fehlt etwas, nennt das Tor jedes fehlende Stück einzeln (drei Kerben = Fassung, unbekannte Folge = Abschrift, Takt, den man nicht erwidern kann = Antwort), nach Merets Vorschlag mit ihrem Satz dazu.
- **Wahlen und Enden:** Front oder Flanke, Riss im Kampf schließen oder nicht. Speichern vor dem Öffnen: danach führt die Kammer ohne Rückweg in Akt II.
- **Belohnung:** 80 + 20 (Riss) + 20 (Tor) = 120 EP; Kampf-EP etwa 320 je Kopf zu viert (mit allen Wellen).
- **Zum Testen:** Mit Fassung und Abschrift, aber ohne Antwort von vorn (Riss bleibt offen), dann mit Antwort zurück und den Riss benutzen. Mit allen drei Stücken über den Seitengang, im Kampf neben den Riss treten. Tor vor und nach allen Stücken.

### C02 bis C04 Der Fremde und das Herz · 🔴 PFLICHT
- **Auslöser:** Erster Schritt in die Herzkammer (Zeile 15). Die Kamera wechselt in die Schrägsicht, der Fremde tritt hinter dem Herz hervor vor den Altar, kurzer Redewechsel, Kampf ohne Frage.
- **Stufe:** Empfohlen 15, fünf Köpfe mit Heiler. Der Fremde (Stufe 15, 210 LP, Rüstung 3, schmale Klinge, Schutzfeld schluckt 50 % von Treffern ab 8 Schaden, bis 60 Punkte verbraucht sind, greift bevorzugt {held} an, zweimal im Kampf **Erdstampfer**: nach kurzer Vorbereitung 3W6+4 auf alle Nachbarn, also nicht dicht um ihn stehen bleiben). Balance-Test (Stufe 15, seit v0.7.0): fünf Figuren 4 von 6 (im Mittel bleibt ein Viertel der LP), sechs Figuren 6 von 6, vier mit Heiler deutlich seltener. Auf Stufe 12 nur mit Glück.
- **Lösungsweg:**
  1. **C02 Kampf:** Das Schutzfeld zuerst mit vielen Treffern über 8 Schaden aufbrauchen (Meldung „Das Lichtmuster zerspringt in Funken“). Sieg: Er bleibt liegend am Umgang (3, 10). Flucht durch das innere Tor: der Kampf kommt beim nächsten Betreten wieder. Niederlage ist ein echtes Spielende.
  2. **C03 Altar** (9, 9) benutzen: **Die Fassung einsetzen.** (sie bleibt im Altar), dann steigen die Runen auf und schweben um den Altar (seit HZ5). Die Runen einzeln berühren: **Bogen mit den drei Kerben** (11, 9), **Welle** (7, 9), **Kreis mit dem Punkt** (8, 10). Jede richtige bleibt hell, falsch: alle erlöschen, von vorn ohne Strafe, die gebrochene Linie (10, 10) ist immer falsch. Am Altar zeigt **Die Abschrift ansehen.** die Folge. Mit dem Kreis sinken die Zeichen auf den Altar, dann am Altar **Die Hand auflegen.** Beben, Blitz, das Herz erwacht, der Riss in der Galerie schließt sich, Tageslicht fällt herein. {held}: »Er ist geschlossen.«, höchstens drei Gefährtenzeilen.
  3. **C04:** Auf der Ausgangsreihe zum inneren Tor (9, 15) steht der Fremde wieder auf und stürzt auf {held} zu. Eine Frau tritt aus einem Lichtspalt und öffnet einen Durchgang im inneren Tor (9, 16). Nur dieser Schritt ist frei. Die Frau ansprechen: »Hierher! Schnell!«. Speichern ist hier noch erlaubt.
  4. In den Durchgang treten: Der Fremde trifft die Vorrichtung, alles zerspringt, Weiß, Übergang zur Zukunftsstraße. Alle Gefährten (in der Gruppe und auf der Wartebank) sind von hier an fort.
- **Wahlen und Enden:** keine echten Wahlen. Altar verlangt alle drei Stücke, sonst bleiben die Runen still.
- **Belohnung:** Kampf-EP des Fremden 750 (etwa 190 je Kopf zu viert); kein Quest-EP.
- **Zum Testen:** Vom Tor aus ist der Fremde nicht zu sehen. Gefährtenzeilen in fester Reihenfolge (Korgar, Beric, Tavion, Namar, Odrik, Jaro, Z'zarek, Haldaar), höchstens drei. Flucht und Wiederkehr. Laden in C04. Entwicklermenü „Vor die Herzkammer“ (siehe D01), dann Altar, Fremder und Zukunftsstraße.

### C05 bis C08 Zukunftsstraße und Krankenstation · 🔴 PFLICHT (Übergang in Akt II)
- **Auslöser:** Folgt zwingend auf den Durchgang. Im Schwarz Rufe, dann eine Straße mit Schusswechsel zwischen Sicherheitskräften hinter einer Sperre im Westen und Räubern im Osten. {held} landet allein auf (12, 12), die Frau in einer Mauernische (12, 7).
- **Stufe:** Unbesiegbar. Fünf Schützen (Stufe 12, 60 LP, Rüstung 8, Lichtwaffe Reichweite 2–14) auf zwei Erkern (Höhe 4) und hinter einem Transporter. Keine Flucht, nur {held}. Balance-Test: 0 Siege in 144 Kämpfen (auch auf Stufe 16), im Mittel 2–3 eigene Züge. Zwei Räuber im Süden sind über eine Lücke bei (17, 13) erreichbar.
- **Lösungsweg:**
  1. **C06** Kampf beginnt ohne Frage, {held} zieht zuerst. Kämpfen, bis {held} fällt (Deckung am Wrack (10–12, 10) verlängert den Kampf).
  2. **C07** Spielende-Bildschirm wie echt (Knöpfe reagieren nicht), Störbild, Herzmonitor, »Wir verlieren ihn!«, »Stabilisieren!«, Weiß. Speichern ist gesperrt.
  3. **C08** Erwachen im Med-Bett der Krankenstation. Fester Redewechsel (Jahrhunderte vergangen). Gespräch mit der Frau aus dem Licht über **Gefährten**, **Name** (sie heißt Sera), **Risse**, **Der Fremde**, **Warum**, dann Gehen. Fragt man nicht nach dem Namen, fragt {held} an der Tür selbst.
  4. Die Frau in Weiß: »Ihr dürft aufstehen. Langsam.« Volle LP, Aufgabe „Wo sind die anderen?“.
  5. Monitor (3, 1), Schränke (8, 1–2), Bett umschauen. Zur Tür (4, 8) gehen oder sie benutzen: »Die Tür hat keinen Griff. Als {held} davortritt, gleitet sie zur Seite.« Dahinter beginnt Akt II (Klinik von Meridian), weiter in der [Komplettlösung Akt II](Komplettloesung-Akt2.md).
- **Wahlen und Enden:** Hier endet Akt I. Die Gefährten bleiben vorerst fort, in Akt II holt {held} sie nach und nach zurück.
- **Belohnung:** keine EP (die Schützen geben keine EP und keine Beute).
- **Zum Testen:** Rufe, Schüsse, Kampf ohne Frage, Hintergrund-Schusswechsel, Niederlage ohne Meldung direkt zum Spielende-Bild, Speichersperre, Namensfrage an der Tür nur ohne Namen im Gespräch, Stille nach dem Aufstehen, Tür öffnet beim Davortreten, Spielstand mit getrennter Gruppe. Bilder -- --strasse, -- --station.

### Entwickler-Abkürzung · 🛠️ NUR TESTER-BUILDS
- **Auslöser:** Spielmenü, Zeile „Entwickler“, „Teleport zu Ortschaft“.
- **Lösungsweg:** „Herzsenke (Westtor)“ setzt die Gruppe vor den Ruinenring (Weltkarte (403, 221)). „Vor die Herzkammer (Stufe 15, Relikte)“ hebt jedes Mitglied auf mindestens Stufe 15, gibt Fassung und Abschrift, setzt Relikte, Antwort, alle drei Begegnungen von Q15, F01, Q16, Ring und Galerie als erledigt und stellt die Gruppe vor das innere Tor (Ortskarte (9, 18)). Dann Tor öffnen, Fremder, Altar, Straße.
- **Zum Testen:** Nur beim Erkunden verfügbar. Das Tor fragt nach allen drei Stücken, die Abkürzung erfüllt sie.

**Offene Enden / Rückkehr später (Finale):**
- F01 erscheint erst mit dem zweiten Relikt, Q16, O12 und W06 erst mit dem dritten. Meret ist nachts nicht ansprechbar. Ohne Q16 bleibt der Abstieg in die Herzsenke verschüttet.
- Der äußere Ring öffnet sich erst nach Q16 (Merets Karte). Das innere Tor wartet auf alle drei Stücke. Wer die Galerie ohne Antwort räumt, schließt den Riss später mit ihr (20 EP).
- Q16 vor der Herzsenke erledigen: Die Karte der Leitungen macht den Wartungsgang leicht, und die Rast sammelt die Gefährten.
- Vor dem Öffnen des inneren Tors speichern und alle Nebenaufgaben von Akt I abschließen: Danach führt der Weg ohne Rückkehr in Akt II, zunächst ohne Gefährten. Wer in Akt I gefallen ist, kann in Akt II zurückkehren, wer die Gruppe für immer verlassen hat, nicht.

---

## Abhakliste

Zum Ausdrucken oder Abhaken beim Spielen. 🔴 sind Pflicht, alles andere ist freiwillig.

**Kapitel 1 · Westmark-Start und Mühlbrück**

- [ ] 🔴 Q00 Rabans Konvoi (Überfall auf der Landstraße)
- [ ] 🟡 Mühlbrück kennenlernen (Gesprächsnetz)
- [ ] 🔵 Korgar und Tavion anwerben
- [ ] 🟢 Q01 Das versiegende Wasser (Wasserstollen)
- [ ] 🟣 Das Flimmern (Hauptstrang, Orwin und die Hüter)
- [ ] 🟢 E01 Die fremden Zeichen am Bienenhaus (Apfelhang)
- [ ] 🟢 Q23 Die Nacht im Korn
- [ ] 🟢 Alter Seewachturm
- [ ] 🟢 Q24 Weiße Flecken
- [ ] 🟢 Wolfsrudel der Westmark
- [ ] 🟡 Weltkarte des Startdreiecks

**Kapitel 2 · Dreifurt und Umgebung**

- [ ] 🟡 Ankunft in Dreifurt
- [ ] 🔵 Namar
- [ ] 🟢 Q02 Die vermisste Werkzeuglieferung
- [ ] 🟢 E03 Die letzte Nacht im Zollhaus
- [ ] 🟢 Q21 Die Wette der Kinder
- [ ] 🟢 Q18 Die Probe auf dem Wachhof
- [ ] 🟢 Q19 Der stumme Posten
- [ ] 🟢 Q20 Die Meute am Karrweg
- [ ] 🟡 Die vierte Furt
- [ ] 🟢 Q22 Die letzte Kerbe
- [ ] 🔵 Orkhöhle mit Odrik · 🟡 ENTDECKUNG
- [ ] 🟢 V01b Bertholds Meldungen von den Wegen (Dreifurt-Seite)
- [ ] 🟡 Freie Begegnungen um Dreifurt

**Kapitel 3 · Tannried, Werkhof und Tannwald**

- [ ] 🟡 Ankunft in Tannried
- [ ] 🟢 Q03 Das besetzte Sägewerk
- [ ] 🟡 Beras Werkzeuge kommen an (Lieferung)
- [ ] 🟢 Q04 Die Grenze der Axt
- [ ] 🟡 Flimmern am alten Harzweg
- [ ] 🟢 Holzbruch: Goblins im Holzbruch (G1–G3)
- [ ] 🟢 E05 Rauch ohne Feuer
- [ ] 🟢 Q25 Die Kohlenfuhre
- [ ] 🟢 V01a Die Fallenstellerin Ortrun
- [ ] 🟢 Q26 Das leere Nest

**Kapitel 4 · Karrfels und Graufelspfad**

- [ ] 🟡 Karrfels: Ankunft, Wörter und Stadtszenen
- [ ] 🔵 Varka vor dem Tor
- [ ] 🔵 Beric vor dem Hallentor
- [ ] 🔴 Q08 Die kalte Esse
- [ ] 🔴 Q15a Der Fremde am Ring
- [ ] 🟢 E06 Die Seile der Toten
- [ ] 🟡 V03 Der Handelsstein
- [ ] 🔵 Haldaar am Handelsstein
- [ ] 🟢 Q27 Die letzte Schicht
- [ ] 🟢 V04 Der Schlackenring
- [ ] 🟡 Unruhe 2 und 3 in Karrfels

**Kapitel 5 · Brackhafen und Glockenwacht**

- [ ] 🟡 Ankunft und kleine Funde in Brackhafen
- [ ] 🟢 Q07 Das Gewicht des Salzes
- [ ] 🟢 V05 Namars Leute (Bootsschuld)
- [ ] 🟢 Q05 Das Fahrwasser ohne Ufer (Leitfeuerbank)
- [ ] 🔴 Q06 Das Gedächtnis des Moors (Moorarchiv)
- [ ] 🔴 Q15b Der Fremde am Altar
- [ ] 🔵 Jaro
- [ ] 🟢 Überfahrt nach Glockenwacht
- [ ] 🟢 Q13 Das falsche Licht
- [ ] 🔵 Rhiann
- [ ] 🟢 Q14 Briefe ohne Empfänger (erste Hälfte)
- [ ] 🟢 E09 Was die Flut zurückgibt
- [ ] 🟢 V07 Strandrecht

**Kapitel 6 · Lichtenruh und Glasgrund**

- [ ] 🟡 Ankunft und Unterstrom von Lichtenruh
- [ ] 🟢 Q14 Briefe ohne Empfänger (zweite Hälfte)
- [ ] 🟢 E09-Folge Die Arznei
- [ ] 🔴 Q10 Die Antwort der Quelle (mit Q15c)
- [ ] 🟢 Q28 Die Stunde, die wiederkehrt
- [ ] 🔵 Venya
- [ ] 🟢 Q11 Was wir den Toten schulden
- [ ] 🟢 E07 Der Garten hinter der Mauer
- [ ] 🟡 Ankunft und Unterstrom von Glasgrund
- [ ] 🟢 Q12 Die leuchtende Furche
- [ ] 🟢 E08 Die Standarte von Dornwacht
- [ ] 🟡 O10 Der singende Steinbruch und die Sternwarte
- [ ] 🔵 Z'zarek an seiner Sternwarte
- [ ] 🟢 Q29 Das letzte Schloss
- [ ] 🔵 Sylis

**Kapitel 7 · Die Wege zwischen den Orten**

- [ ] 🟡 V01b Unruhe auf den Wegen
- [ ] 🟢 W05 Der Brandhof an der Gabel
- [ ] 🟢 W04 Der Lehmhang
- [ ] 🟢 W01 Die Schranke am Moosfels
- [ ] 🟢 W02 Das Lager am Deich
- [ ] 🟡 O06 Der versunkene Glockengarten
- [ ] 🟢 W03 Das Sommerlager der Hünen
- [ ] 🟢 Freie Begegnungen auf der Weltkarte

**Kapitel 8 · Das Finale**

- [ ] 🟣 F01 Die zerschnittene Leitung
- [ ] 🔴 Q16 Der Versuch im Kleinen
- [ ] 🟣 O12 Die Rast der drei Steine
- [ ] 🟢 W06 Der Riss am Südweg
- [ ] 🔴 Q17a Der äußere Ring
- [ ] 🔴 Q17b Die gebrochene Galerie und das innere Tor
- [ ] 🔴 C02 bis C04 Der Fremde und das Herz
- [ ] 🔴 C05 bis C08 Zukunftsstraße und Krankenstation

---

*Erstellt am 16.11.2026 aus dem Spielinhalt (Ereignisse, Karten, Texte) und den automatischen Tests. Kein Teil dieses Leitfadens wurde bisher von Hand durchgespielt: Stufenangaben sind Rechen- und Simulationswerte. Wer an einer Stelle hängen bleibt, eine andere Lösung findet oder einen Kampf viel zu leicht oder zu schwer findet, meldet das bitte mit Kapitel und Kennung (z. B. „Kapitel 5, Q06“).*
