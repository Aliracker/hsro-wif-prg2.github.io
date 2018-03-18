# Programmieren 2

_Pflichtmodul im [Bachelorstudiengang Wirtschaftsinformatik](https://www.fh-rosenheim.de/technik/informatik-mathematik/wirtschaftsinformatik-bachelor/) an der [Hochschule Rosenheim](https://www.fh-rosenheim.de)._

## Organisatorisches

**Vorlesungstermin**: Mittwochs, 8:00 R0.02

**Übungen**: Mittwochs, 2./4./5. Stunde, A0.03; Tutor: Lukas Grams

**Kommunikation**: via Mattermost ([einschreiben](https://inf-mattermost.fh-rosenheim.de/signup_user_complete/?id=wp3dau8xmigxtmf93z5ixur1ta))

**Wichtige Termine**:

- **20.-30. April:** Prüfungsanmeldung (incl. PStA)
- **25. Mai:** Einführung in das Contestsystem der PStA (persönliche Anwesenheit erforderlich!)
- **4. Juli.:** Testat zur PStA (statt Übung)


## Leistungsnachweis

Der Leistungsnachweis ist aufgeteilt in eine 

- (unbenotete) praktische Studienarbeit (PStA), abzulegen während des Semesters (mit Abschlusstestat)
- schriftliche Prüfung (SP, 90 Minuten) am Ende des Semesters


## Empfohlene Literatur


## Inhalt
- **21. März: Professionelle Softwareentwicklung**
	
	Nach ein paar organisatorischen Dingen widmen wir uns dem Handwerkszeug professioneller Softwareentwicklung: Spezifikation mit UML, Versionierung mit git, Tests und Ausnahmebehandlung.

- **28. März: Liste als Sequenzielle Datenstruktur**

	Bisher haben wir größere Mengen von gleichen Objekten in Feldern (Arrays) gespeichert, welche aber in ihrer Größe in Java unveränderlich sind.
	Wir erarbeiten uns nun mit Hilfe von Objektorientierung eine dynamische Datenstruktur, welche nach Bedarf wachsen und schrumpfen kann, und so Daten effizient verwaltet.

- **4. April: Set als Menge Eindeutiger Elemente**

	Eine Liste speichert Daten sequenziell ab, und achtet dabei nicht auf Duplikate.
	Ein _Set_ (aus dem engl. _set_: Menge, Gruppe) ist ein Containertyp, welcher der mathematischen Menge nachempfunden ist: jedes Element kann genau einmal vorkommen, und es gibt keine Reihenfolge; ein Element ist entweder enthalten, oder nicht.

- **11. April: Map als Assoziativer Container**

	Eine Liste ist sequenziell mit potentiellen Duplikaten, ein Set ist duplikatfrei, aber ohne Reihenfolge.
	Eine _Map_ (aus dem engl. _map_: Abbildung) ist ein assoziativer Container, welcher einem Schlüssel (_key_) einen Wert (_value_) zuordnet.

- **18. April: Generics**

	Bisher waren die Containerklassen entweder für genau einen Datentyp, oder für die `Object`, welche für jedes Objekt verwendet werden kann.
	_Generics_ erlauben es nun mit beliebigen _aber festgelegten_ Datentypen zu arbeiten.
	Wir lernen ausserdem die Interfaces `Comparable` und `Comparator` kennen.

- **25. April: Annotationen; Einführung in die PStA**
	
	Nach einem kurzen Exkurs zum Thema Annotationen und deren Einsatzgebiete gibt es eine kurze Einführung in die PStA.

- **2. Mai: Iteratoren**

	Arrays und Listen verfügen über einen Indexoperator (`[]` bzw. `get(int)`) welcher verwendet werden kann um alle Elemente zu besuchen.
	Der _Iterator_ abstrahiert dieses Prinzip: Bereitgestellt vom Container selbst, ist er ein Hilfsobjekt mit dem jedes Element des Containers besucht werden kann.

- **9. Mai: Vererbung**

	Bisher waren unsere Klassenbeziehungen vorwiegend strukturell bzw. funktional: Ein Monat besteht aus Tagen, ein Auto aus Bauteilen, usw.
	_Vererbung_ erlaubt es nun verwandschaftliche Beziehungen zu modellieren, und so Gemeinsamkeiten in Oberklassen zu bündeln.
	So sind z.B. sowohl Audis als auch BMWs im Grunde genommen _Autos_, doch gibt es sowohl geteilte Eigenschaften als auch spezielle.

- **16. Mai: Abstrakte Basisklassen**
	
	Abstrakte Basisklassen sind ein weiteres Syntaxmittel, um verwandschaftliche Beziehungen zu beschreiben.
	Da abstrakte Klassen nicht instanziiert werden können, sind sie im Grunde ähnlich zu Schnittstellen (_Interfaces_), erlauben aber genauere modellierung der Sichtbarkeiten.

- **23. Mai: Rekursion**

	Ging es um das Abarbeiten von Daten bzw. implementieren von Algorithmen, so gingen wir bisher meist iterativ vor, also mit `for` bzw. `while`.
	Rekursion ist nun ein Mittel, bei der eine Methode sich selbst wieder (mit veränderten Argumenten) aufrufen, und so ohne `for` bzw. `while` auskommen.

- **30. Mai: Sortieren**
	
	Gewappnet mit Datenstrukturen, Iteration und Rekursion erarbeiten wir Algorithmen zum Sortieren von Daten.

- **6. Juni: Arbeiten mit Containern**

	Wir lernen die Containerklassen der Java Bibliothek kennen, und wie man sie nutzt um schnell (und übersichtlich) Daten zu verarbeiten.
	Klassischerweise ist die Datenverarbeitung hier in drei Schritten zu machen: filtern, abbilden und reduzieren.

- **13. Juni: Parallele Verarbeitung**
	
	Folgten unsere Programme bisher einem vorgesehenen Ablaufplan, so erlauben _Threads_ die parallele Verarbeitung von Daten.
	Wir beginnen mit der Basisimplementierung und erarbeiten einige knifflige Situationen.

- **20. Juni: Design Pattern**
	
	Professionelle Softwareentwicklung greift oft auf Entwurfsmuster (_design pattern_) zurück.
	Wir wiederholen einige welche wir bereits kennen gelernt haben, und erarbeiten eine Systematik für weitere Muster.

- **27. Juni: Zusammenfassung**
- **4. Juli: Testat für PStA (Anwesenheitspflicht)**



_Abboniere das [https://github.com/hsro-wif-prg2/hsro-wif-prg2.github.io Repository](https://github.com/hsro-wif-prg2/hsro-wif-prg2.github.io) um bei Updates benachrichtigt zu werden._