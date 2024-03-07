# AdventureWorks Purchasing & Inventory Analysis Dashboard

Dieses Power BI Dashboard wurde aus einer der Microsoft-Beispieldatenbanken erstellt: AdventureWorks 2022. AdventureWorks ist ein fiktives Unternehmen, das Fahrräder und Zubehör herstellt und seine Produkte in insgesamt sechs Ländern in Nordamerika, Europa und im asiatisch-pazifischen Raum verkauft. Die Datenbank wurde in SQL Server 2022 gehostet und mit Hilfe von SQL-Abfragen in Power BI eingebracht.

Das Ziel dieses Dashboards ist es, Einblicke in die Einkaufs- und Bestandsdaten des Unternehmens zu geben und so Teile der Supply Chain des Unternehmens zu beleuchten. Das Dashboard besteht aus zwei Seiten: Purchasing/Supplier analysis (Einkauf/Lieferantenanalyse) und Inventory analysis (Bestandsanalyse).

## Purchasing/Supplier analysis (Einkauf/Lieferantenanalyse)

* Die Datentabelle zeigt die Kreditwürdigkeit der Lieferanten (basierend auf ihrer Leistung), den Prozentsatz der Ablehnungen und die durchschnittliche Durchlaufzeit der einzelnen Lieferanten. Daraus lässt sich ein Überblick über die Qualität, die Geschwindigkeit und das Leistungsniveau der Lieferanten gewinnen.

* Das Donut-Diagramm zur Pünktlichkeit der Auftragserfüllung zeigt, dass mit Ausnahme eines geringen Prozentsatzes von Bestellungen, die pünktlich oder verspätet waren, ein großer Teil der Bestellungen (99,86 %) frühzeitig, d. h. vor der erwarteten Lieferung, erfüllt wurde. Dies deutet darauf hin, dass die Lieferanten von AdventureWorks in Bezug auf rechtzeitige Lieferungen sehr zuverlässig sind.

* Bei der Analyse der Genauigkeit der Bestellmenge wurde festgestellt, dass 8,8 % der Bestellungen unvollständig waren, d. h. der Lieferant lieferte eine geringere Anzahl von Komponenten als bestellt. Unvollständige Bestellungen können zu unerwarteten Engpässen im Lagerbestand führen. Die Einkäufer können versuchen, diesen Prozentsatz durch Gespräche mit den Lieferanten und sorgfältige Überwachung zu minimieren.

* Das Diagramm "Rückweisungsmenge und Rückweisungsprozentsatz" zeigt die Gesamtmenge der von den einzelnen Lieferanten zurückgewiesenen Komponenten und den Prozentsatz. Die höchsten Rückweisungsmengen stammen von SUPERSALES, Vision Cycles und Proseware. Die höchsten Rückweisungsprozentsätze kamen von International (5,88 %), Anderson's Custom Bikes (5,38 %) und Signature Cycles (5,35 %). Diese Lieferanten müssen überwacht und dazu angehalten werden, ihre Qualitätskontrollen vor dem Versand zu verstärken.

* Der Status der Bestellungen zeigt, dass 92,36 % aller Bestellungen abgeschlossen sind und 5,39 % der Bestellungen zur Genehmigung anstehen.

## Inventory Analysis (Bestandsanalyse)

* Die Analyse des Lagerbestands nach Materialart zeigt, dass der größte Teil des Lagerbestands (19 Mio. $) auf Fertigerzeugnisse und 9 Mio. $ auf Rohmaterialien entfällt.

* Der derzeitige Gesamtwert der Vorräte wurde auf 28,18 Mio. $ analysiert, verglichen mit dem Zielwert von 33,66 Mio. $. Der Zielwert wurde ermittelt, indem die Kosten für die Haltung aller Materialien und Produkte auf dem Niveau des Sicherheitsbestands berechnet wurden. In diesem Fall ist der derzeitige Bestand niedriger als der Zielwert, was ein gutes Zeichen dafür ist, dass der Bestand innerhalb des optimalen Niveaus liegt.

* Die Rohstofftabelle zeigt die von den Lieferanten gekauften Komponenten, die nachbestellt oder überwacht werden müssen. Die Komponenten, die unter den Nachbestellungspunkt gefallen sind, müssen nachbestellt werden ("Hex Nut 1" und "Lower Head Race"), und die Komponenten, die unter dem Sicherheitsbestand, aber über dem Nachbestellungspunkt liegen, müssen vom Einkaufsteam genau überwacht werden.

* Die Analyse des Materialbestands ergab, dass insgesamt 363 Komponenten/Produkte einen ausreichenden Bestand aufweisen, 79 nachbestellt werden müssen und 62 überwacht werden müssen. Die 79 Komponenten, die nachbestellt werden müssen, bedürfen der sofortigen Aufmerksamkeit, um Probleme in der Supply Chain zu vermeiden.

* Die Bestandswerttabelle zeigt den gesamten aktuellen Bestandswert jedes einzelnen Materials oder Produkts. Die Tabelle zeigt, dass HL Mountain Frame Black den höchsten Bestandswert hat (0,6 Mio. $).

* Bei der Analyse des Vorratswertes nach Unterkategorien der Fertigerzeugnisse wiesen Road Bikes ($6,9 Mio.) den höchsten Vorratswert auf, gefolgt von Mountain Bikes ($4,8 Mio.) und Touring Bikes ($2,9 Mio.).

## Fazit

Dieses Dashboard bietet Einblicke in die Einkaufs- und Bestandsdaten des Unternehmens, die für die Fachleute des Einkaufs und der Supply Chain innerhalb des Unternehmens wertvoll sind, um die Kosten zu überwachen und die Materialverfügbarkeit für die Fertigung sicherzustellen.
