# TrappiPost – dein E-Mail-Programm zum Üben

**Jetzt spielen:** https://altra102.github.io/trappipost/

Ein kinderfreundliches E-Mail-Programm für den Informatikunterricht (Klasse 5/6).
Nichts wird wirklich verschickt: Alle Personen und Adressen sind erfunden.

## Was man übt

Zehn Aufträge, von leicht nach schwer:

1. eine E-Mail lesen
2. Werbung löschen
3. eine E-Mail archivieren
4. eine E-Mail aus dem Papierkorb zurückholen
5. eine neue E-Mail schreiben
6. antworten
7. weiterleiten, mit einem eigenen Satz
8. antworten mit einer Frage
9. antworten mit Infos aus einer anderen E-Mail
10. den Posteingang aufräumen

Nach dem Senden prüft das Programm die Form: Adresse, Betreff, Anrede, Gruß, Name
und die verlangte Info. Es sagt, was noch fehlt. Eine falsche Adresse kommt als
„Nicht zugestellt“ zurück.

## Der Laptop

Das Programm läuft auf einem gezeichneten Laptop auf einem Schreibtisch. Die
Tastatur (deutsches QWERTZ, mit Umschalt- und AltGr-Zeichen) leuchtet bei jedem
Tastendruck mit. „Näher ran“ zoomt an den Bildschirm heran, „Ganzer Laptop“ wieder
zurück. Das Maskottchen ist der Trappi-Wagen aus [Trappi](https://trappi.eu) als
Postwagen.

## Spiel auf Zeit

Nach den zehn Aufträgen kommen endlos neue Aufgaben (antworten, neu schreiben,
weiterleiten, löschen, archivieren, zurückholen, aufräumen), jede mit Countdown.
Läuft die Zeit ab, ist ein Herz weg. Nach drei Herzen ist die Runde vorbei;
„Nochmal“ startet neu, der Rekord bleibt.

## Technik

Eine einzelne HTML-Datei ohne Abhängigkeiten, alle Bilder als selbst gezeichnetes SVG. Der Stand wird im Browser gespeichert
(`localStorage`, Schlüssel `trappipost-v1`); „Von vorn“ setzt alles zurück.

## Lizenz

CC BY-SA 4.0
