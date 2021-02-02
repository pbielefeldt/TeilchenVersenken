TeilchenVersenken
=================

Schiffe-Versenken mit Spuren in Teilchendetektoren

Idee
----

Die Spielidee ist wie bei Schiffe-Versenken auch:
Jede:r Spieler:in hat vor sich ein Spielfeld mit der „eigenen Aufstellung“.
In unserem Fall ist das ein schematischer Detektor, in dem mehrere Teilchen ihre Spuren hinterlassen haben.

Abwechselnd wird dann geraten, wo beim anderen Mitspielenden Teilchensignale im Detektor zu finden sind.
Dabei kommt es darauf an, zu verstehen, wie die verschiedenen Teilchen im Detektor „aussehen“ – nur so kommt man mit wenig raten schnell zum Ergebnis!

Aufbau des Detektors
--------------------

Das Spielfeld ist unterteilt in viele kleine Blöcke.
Diese werden zusammengefasst in
* Elektromagnetisches Kalorimeter (__E__ 01–24)
* Hadronisches Kalorimeter (__H__ 01-16)
* Myonenkammern (__M__ 01-16)

![Spielfeld](https://raw.githubusercontent.com/pbielefeldt/TeilchenVersenken/main/det/det-00.png)
Im Prinzip richtet sich das nach dem Design von MINERVA aus der Masterclass: http://atlas.physicsmasterclasses.org/de/wpath_teilchenid2.htm

Teilchen
--------

__Achtung: Das ist noch gar nicht getestet; erst mal nur eine Idee!__

Zum Beispiel könnte jede:r Spieler:in folgende Teilchen im Detektor haben:
* 2 Elektronen (bzw. Positronen, Ladung wird beim ganzen Spiel ignoriert)
  * Spur *nur* im __E__
  * Da sind immer *drei hintereinander liegende* und *ein* daneben liegender Block getroffen
* 1 Jet (hadronisches Signal)
  * Hat immer *fünf* beieinander liegende Einträge im __E__ und
  * *Drei* Einträge im __H__
* 2 Myonen (bzw. Anti-Myonen)
  * Hat Einträge in allen drei Subdetektoren
  * Je *ein* Eintrag in in beiden Lagen der __M__
  * Genau *je ein* Eintrag in __H__ und __E__, auf der Teilchenbahn
