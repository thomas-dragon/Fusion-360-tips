# Fusion 360 Checkliste

# Design

## Skizzen

- Ordne das Grunddesign durch mehrere miteinander verknüpfte (Projektions) Skizzen. Am besten eine pro Achse.
- Nimmt nicht zu viele Spiegelungen und Muster in die Skizze auf. Fusion bekommt damit schnell Probleme.
- Versuche möglichst viel mit Abhängigkeiten zu ordnen.
- Verlasse die Skizze erst wenn alle Abhängigkeiten und Bemaßungen vollständig sind.
- Nutze den Koordinatenursprung als Mittelpunkt für Symmetrische Teile.
- Projiziere die Koordinatenachsen in die Skizze für Spiegelungen, Symmetrien etc.
- Fixiere die Skizze am Koordinatenursprung oder an den Achsen.
- Auch Skizzen lassen sich kopieren, drehen, verschieben.
- Nutze für Bemaßungen Formeln. In der Skizzenbemaßung als auch in der Parametertabelle.
- Nutze für symmetrische Elemente Spiegelungen und Muster.
- Nutze intensiv Projektionen um Abhängigkeiten zu anderen Skizzen oder Körper/Komponenten zu definieren.
- Definieren eigene Referenzlinien (Konstruktionslinien).
- Wandle Linien welche nicht für weitere Operationen benötigt werden (Extrusion etc.) in Konstruktionslinien um.
- Lege die Skizze in der richtigen Ebene an.
- Skizzen lassen sich im Gegensatz zu Körpern, Komponenten direkt in andere Fusion Dateien kopieren und einfügen.
- Aktivierung die „Projektionsverknüpfung&quot; bei der Projektion von Skizzen/Körpern damit Änderungen übernommen werden.

## Parameter

- Nutze die Parametertabelle für Bemaßungen.
- Bilde Parameter für häufig genutzte Werte und Werte welche sich ändern können.
- Nutze Formeln.
- Ein Parameter kann andere Parameter enthalten.
- Per Plugin lassen sich die Parameter im csv Format im- und exportieren.
- Nimm sprechende Namen.
- Definiere den Parameter ohne Einheit, wenn du eine Anzahl definieren möchtest.

## Ablauf

- Definiere globale Skizzen um spätere Teile anzuordnen. Das ist oftmals übersichtlicher als „Gelenke&quot; zu verwenden. Fixiere diese Teile.
- Definiere für jedes Bauteil eine Komponente. Aktiviere diese und arbeite innerhalb dieser Komponente. Deine Skizzen und Körper werden hier angelegt.
- Bei späteren Änderungen aktiviere wieder diese Komponente und gehe auch in der Zeitleiste auf diese Komponente zurück.
- Komponenten könne auch nur der Ordnung dienen und einfach nur Baugruppen zusammenfassen.
- Fixiere Skizzen und Komponenten wenn möglich.
- Speichere oft.
- Lagere komplexe Bauteile in andere Fusion Dateien aus und verknüpfe sie durch „Gelenke&quot;.

## Gelenke

- Nutze „Gelenke&quot; wenn keine Lagebestimmung durch Skizzen und keine Fixierung gegeben ist.
- Nutze wenn möglich „Verbinden wie modelliert&quot;.

## Bauteilbibliotheken

Besitzt Fusion 360 leider nicht.

- Lege eigene Fusion-Dateien, Step und andere CAD Daten als Bibliothek an.
- Verändere nachträglich nie den Ort der Datei oder lösche sie, wenn sie irgendwo verwendet wird. Veränderungen am Design sind möglich.
- Du musste nicht alles selber erfinden. Nutze GrabCAD, McMaster Car, Part4CAD usw. als Quelle.

## Ausssehen

- Definiere Material und Darstellung (nur Komponenten).
- Beides lässt sich ändern bzw. neu definieren.
- Das Material definiert physikalische Eigenschaften wie Gewicht.
- Die Darstellung definiert das Aussehen. Insbesondere beim Rendern.
- Die Modellierung von Gewinden ist extrem rechenintensiv. Du benötigst sie aber beim 3D-Druck und beim Rendern. Ansonsten deaktiviere sie.

## Komponenten

Komponenten haben folgende Vorteile gegenüber Körpern.

- „Gelenke&quot; und Animationen sind nur mit Komponenten möglich.
- Nur Komponenten sind in der Stückliste der Zeichnung.
- Mit Kopieren und Einfügen erzeugt man identische Kopien einer Komponente. Änderungen wirken sich auf alle aus!
- Mehrere Komponenten können zu einer starren Gruppe zusammengefasst werden. Das spart „Gelenke&quot; und erleichtern die Verwendung in anderen Modellen.
- Nur Komponenten lassen sich verschieben.
- Vor dem 3D-Druck kombiniere die Körper zu einem oder bilde eine Komponente.

## Test

- Prüfe ob die Skizzen vollständig mit Anhängigkeiten versehen sind, sich also nicht durch Ziehen verändern lassen bzw. alle Linien komplett schwarz sind.
- Prüfe komplexe Körper Komponenten auf verdeckte Fehler mit Hilfe der Schnittanalyse.
- Prüfe ob alle Komponenten fixiert sind. Sie können durch eine Skizze, ein Gelenk oder den Befehl „fixieren&quot; festgelegt werden. Nur dort wo bewegliche „Gelenke&quot; definiert wurden sollte eine Bewegung möglich sein.
- Prüfe die Skzizzen durch Maßänderungen.

