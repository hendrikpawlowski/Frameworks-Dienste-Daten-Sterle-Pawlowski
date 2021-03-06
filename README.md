# Frameworks-Dienste-Daten-Sterle-Pawlowski


Willkommen auf unserem Repository! Im Folgenden finden Sie den Verlauf unseres Projektes, welches im Rahmen der Veranstaltung "Frameworks, Daten und Dienste im Web" an der TH-Köln in Gummersbach stattfindet.


## Projektaufgabe


Die Projektaufgabe ergibt sich aus mehreren Problemszenarien, welche zur Auswahl standen.
Wir haben uns für ein Szenario mit dem Titel "Marskolonialisierung" entschieden.


## Problemszenario


In den letzten Jahren ist das Ziel einer Kolonialisierung des Mars deutlich konkreter und realistischer geworden. Weltraumorganisationen, wie NASA oder SpaceX, planen erste bemannte Missionen ab 2030. Für diese Kolonialisierung sind geeignete IT-Systeme notwendig. So müssen Astronauten über Änderungen bestimmter Messwerte informiert werden und zusätzliche Daten zu den eigenen Aufgaben erhalten. Außerdem müssen die Astronauten auch mit Informationen von zu Hause versorgt werden, um die eigene Moral hoch zu halten. Hinzu kommt, dass eine einfache Übertragung im Schnitt zwischen 13 und 24 Minuten dauert, was zusätzlich berücksichtigt werden muss. Darüber hinaus sollen die Astronauten auch erstmals Zugriff auf Daten aus dem Internet erhalten. Die NASA möchte daher eine geeignete Testimplementierung für webbasierte Systeme in einer Marsstation, welche die Kommunikation von der Erde zur Station, sowie innerhalb der Station erlaubt. Da die Station aus einzelnen Modulen besteht, die untereinander kommunizieren müssen, welche aber nicht zwangsweise über eine einheitliche Schnittstelle verfügen, soll eine übergeordnete und eventbasierte Architektur implementiert werden. Diese Architektur soll eine asynchrone Kommunikation zwischen den einzelnen Modulen erlauben, sodass Astronauten Informationen über Luftdruck, Temperaturen oder andere relevante Daten erhalten können. Hinzu kommt, dass derartige Systeme üblicherweise geschlossene Systeme sind - also ohne Verbindung zum Internet. Da auf Dauer auch ein interplanetares Internet geschaffen werden soll gilt es geeignete Services zu implementieren, welche Daten aus dem Web verwenden. Dabei verlangt die NASA die Verwendung von Open Data Portalen, um den Astronauten so viel Informationen wie möglich zukommen zu lassen.
