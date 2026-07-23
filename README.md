## **Cyclistic Bike-Share Analyse**



##### **1. Ausgangslage \& Geschäftsziel**

Ziel dieses Projekts war es, datengetriebene Marketingstrategien für das fiktive Fahrradverleih-Unternehmen Cyclistic zu entwickeln. Die zentrale Geschäftsfrage lautete:

&#x20;Wie unterscheiden sich Jahresabonnenten (Members) und Gelegenheitsfahrer (Casuals) in der Nutzung der Fahrräder?

Die Erkenntnisse sollen genutzt werden, um Gelegenheitsfahrer durch gezielte Kampagnen in profitable Jahresabonnenten umzuwandeln.





##### **2. Datenbasis \& Technische Umsetzung**

Für die Analyse wurde ein Dataset mit fast 6 Millionen aufgezeichneten Einzelfahrten (ca. 588 MB) herangezogen.



**Umgebung:**	 Lokale Datenverarbeitung.

**Werkzeuge:**	 Python (Jupyter Lab) für den gesamten Analyseprozess.

**Bibliotheken:**	 pandas für Data Cleaning und komplexe Aggregationen, matplotlib und seaborn für die visuelle Aufbereitung.

**Data Cleaning:**	 Konvertierung von Textfeldern in DateTime-Format zur präzisen Berechnung sowie Bereinigung logischer Ausreißer (z.B. Fahrten unter 0 Minuten).





##### **3. Zentrale Erkenntnisse**

Die Daten offenbaren ein fundamental unterschiedliches Nutzungsverhalten der beiden Kundengruppen:



\-Members sind Pendler: 	Jahresabonnenten machen den Großteil der Fahrten aus. Sie fahren primär unter der Woche (Spitzen von Dienstag bis Donnerstag), nutzen die Räder für kurze Distanzen (ø 12,5 Min.) und starten an klassischen 				Knotenpunkten der städtischen Infrastruktur. Zudem greifen sie auffällig oft zu E-Bikes.



\-Casuals sind Freizeitfahrer: 	Gelegenheitsfahrer nutzen den Service seltener, behalten die Räder aber deutlich länger (ø 21,7 Min. – ein Plus von ≈ 74 %). Ihre Nutzung explodiert am Wochenende (insbesondere samstags), und ihre 					präferierten Startstationen liegen an touristischen Hotspots wie Parks, Küsten oder Museen.





##### **4. Marketing-Strategie**

Um Gelegenheitsfahrer in Abonnenten zu konvertieren, ergeben sich aus den Daten drei konkrete Lösungsansätze:



\-Einführung eines "Wochenend-Tarifs": Da Casuals den Service primär am Wochenende nutzen, ist ein klassisches 24/7-Abo oft unattraktiv. Ein maßgeschneidertes Jahresabo für die Wochenendnutzung senkt die Einstiegshürde erheblich.



\-Ortsbasierte Werbekampagnen: Marketingbudgets sollten fokussiert an den identifizierten Top-Startstationen der Casuals (Touristen- und Freizeit-Hotspots) eingesetzt werden, anstatt sie breit über die ganze Stadt zu streuen.



\-Fokus auf E-Bikes: Da E-Bikes stark nachgefragt werden, könnte ein neues Mitgliedschaftsmodell eine garantierte Anzahl an "E-Bike-Freiminuten" beinhalten, um den Wechsel für Freizeitfahrer attraktiver zu gestalten.

















Quellen:

https://divvy-tripdata.s3.amazonaws.com/index.html

https://divvybikes.com/data-license-agreement





Hinweis:

Für die effiziente Generierung des Python-Codes und zur Unterstützung bei der Textstrukturierung wurde ein KI-Sprachmodell als Copilot genutzt. Die analytische Strategie, die Interpretation der Daten und die Ableitung der geschäftlichen Handlungsempfehlungen sind meine eigenen Leistungen.

