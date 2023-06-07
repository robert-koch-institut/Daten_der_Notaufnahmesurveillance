Datensatzdokumentation
# Notaufnahmesurveillance - Daten des Wochenberichts

**[Robert Koch-Institut | RKI](http://www.rki.de)**  
*<sup>1</sup> Fachgebiet 32 | Surveillance*  
*<sup>2</sup> Fachgebiet MF4 | Informations- und Forschungsdatenmanagement*  
Nordufer 20  
13353 Berlin  


**[AKTIN-Notaufnahmeregister](http://aktin.org)**  
*<sup>3</sup> AKTIN-Geschäftsstelle und TDAC*  
c/o Otto-von-Guericke Universität Magdeburg  
Universitätsklinik für Unfallchirurgie  
Leipziger Straße 44  
39120 Magdeburg  


*<sup>4</sup> AKTIN-IT*  
c/o Institut für medizinische Informatik  
Uniklinik RWTH Aachen  
Pauwelsstraße 30  
52057 Aachen  

**Beitragende Personen**  

[Michaela Diercke](https://orcid.org/0000-0002-4678-1813)<sup>1</sup>, [Madlen Schranz](https://orcid.org/0000-0002-2426-5770)<sup>1</sup>, [Birte Wagner](https://orcid.org/0000-0002-5725-3020)<sup>1</sup>, [Alexander Ullrich](https://orcid.org/0000-0002-4894-6124)<sup>1</sup>, [Linus Grabenhenrich](https://orcid.org/0000-0002-9300-6625)<sup>2</sup>, [Theresa Kocher](https://orcid.org/0000-0002-9300-6625)<sup>2</sup>, Felix Walcher<sup>3</sup>, Wiebke Schirrmeister<sup>3</sup>, Susanne Drynda<sup>3</sup>
Ronny Otto<sup>3</sup>, Saskia Ehrentreich<sup>3</sup>, Rainer Röhrig<sup>4</sup>, Raphael Majeed<sup>4</sup>, Jonas Bienzeisler<sup>4</sup>, Alexander Kombeiz<sup>4</sup> und Lukas Triefenbach<sup>4</sup>

---  
**Zitieren**  

Robert Koch-Institut und AKTIN-Notaufnahmeregister (2023): Notaufnahmesurveillance - Daten des Wochenberichts. DOI:[10.5281/zenodo.8012446](http://doi.org/10.5281/zenodo.8012446).  

## Informationen zum Datensatz und Entstehungskontext  

Der Datensatz „Notaufnahmesurveillance - Daten des Wochenberichts“ enthält aggregierte Daten der Routinedokumentation aus einer Auswahl deutscher Notaufnahmen aus dem [AKTIN-Notaufnahmeregister](https://www.aktin.org/de-de/). Diese sind  Teil der Notaufnahmesurveillance am Robert Koch-Institut und bilden die Grundlage für den [Notaufnahmesurveillance Wochenbericht](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG32/sumo/sumo.html) des RKI. 

### Datenerhebung und Datenverarbeitung  

Die zugrundeliegenden Daten aus der Routinedokumentation von Notaufnahmen werden im Rahmen des AKTIN-Notaufnahmeregisters erhoben, wie in [Brammen et al. 2020](https://doi.org/10.1007/s00063-020-00764-2) beschrieben, und anschließend dem RKI als tägliche Datenlieferungen über eine SFTP-Server-API täglich bereitgestellt. 

> Brammen, D., Greiner, F., Kulla, M. et al. Das AKTIN-Notaufnahmeregister – kontinuierlich aktuelle Daten aus der Akutmedizin. Med Klin Intensivmed Notfmed 117, 24–33 (2022). DOI: [10.1007/s00063-020-00764-2](https://doi.org/10.1007/s00063-020-00764-2) 

Die Verarbeitung, Aufbereitung und automatisierte Qualitätsprüfung sowie die Veröffentlichung der Daten erfolgen durch das [Fachgebiet MF 4 | Informations- und Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MF/MF4/mf4_node.html). Fragen zum Datenmanagement und zur Publikationsinfrastruktur können an das Open Data Team des Fachgebiets MF4 unter [OpenData@rki.de](mailto:opendata@rki.de) gerichtet werden. Die epidemiologisch-fachliche Expertise für die Notaufnahmesurveillance liegt bei dem [Fachgebiet FG 32 | Surveillance | ÖGD Kontaktstelle](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG32/FG32_node.html) des RKI, Fragen an das Team der Notaufnahmesurveillance können unter [sumo@rki.de](mailto:sumo@rki.de) gestellt werden. Das Monitoring der Notaufnahme-spezifischen Datenqualität und etwaige Abstimmungen mit den Notaufnahmen erfolgt im AKTIN TDAC. Für den Kontakt und Koordination der teilnehmenden Notaufnahmen ist das AKTIN-Office verantwortlich. Bei Fragen bitte an [office@aktin.org](mailto:office@aktin.org) wenden.

### Datengrundlage und Einschlusskriterien  

Die Auswahl der Notaufnahmen basiert auf der individuellen Bereitschaft zur Teilnahme und wird pro Quartal abhängig von der Verfügbarkeit der Daten je Notaufnahme bestimmt.
Notaufnahmen werden in den Bericht eingeschlossen, wenn Datenlücken, an denen keine Notaufnahmevorstellungen übermittelt wurden, nicht größer als 6 aufeinanderfolgende Tage sind. Um im aktuellsten Quartal eingeschlossen zu werden, muss in einer Notaufnahme außerdem für jeden der letzten 7 Tage mindestens eine Vorstellung vorliegen. Die gleichen Kriterien gelten für die Auswertungen zur Dringlichkeitseinschätzung und den Vorstellungsgründen (nach CEDIS-PCL Gruppen), wobei sich hier die Verfügbarkeit auf die jeweilige betrachtete Variable bezieht. Für den Einschluss in die Auswertungen zur syndromischen Surveillance muss pro Falldefinition in einer Notaufnahme mindestens ein Fall im jeweiligen Quartal vorliegen.
Durch Veränderung der Verfügbarkeit der Daten kann es zu einer unterschiedlichen Anzahl von Notaufnahmen je Quartal und in den unterschiedlichen Auswertungen sowie zu Unterschieden zwischen den Berichten kommen. Da die Notaufnahmen jeweils unterschiedlich groß sind, kann es bei gleicher Anzahl von Notaufnahmen zu Unterschieden in der Höhe der Fallzahlen zwischen Quartalen kommen.

### Falldefinitionen  

Wir berichten die Dringlichkeitseinschätzung basierend auf dem Emergency Severity Index (ESI, [AHRQ 2012](https://www.ahrq.gov/patient-safety/settings/emergency-dept/esi.html)) oder dem Manchester-Triage-System (MTS, [Mackway-Jones et al. 2018](http://doi.org/10.1024/86085-000)). Die berichteten Vorstellungsgründe wurden nach Canadian Emergency Department Information System – Presenting Complaint List (CEDIS-PCL, [Grafenstein et al. 2008](https://doi.org/10.1017/s1481803500009878 )) und Diagnosen nach der Internationalen Klassifikation der Krankheiten, 10. Revision (ICD-10, [DIMDI 2019](https://www.dimdi.de/static/de/klassifikationen/icd/icd-10-gm/kode-suche/htmlgm2019/)) codiert.
Die Falldefinitionen für akute respiratorische Erkrankungen (ARE) und schwere akute respiratorische Infektionen (SARI) basieren auf einer Kombination aus Diagnosen, Vorstellungsgründen und Hospitalisierung, wie in [Boender et al. 2022](https://doi.org/10.2807/1560-7917.ES.2022.27.27.2100865) näher beschrieben. Die Falldefinition für grippeähnliche Erkrankungen (Influenzalike-illness, ILI) basiert auf den ICD-10-Diagnosen: J09, J10.-, J11.-. Die Falldefinitionen für respiratorische, kardiovaskuläre und neurologische Vorstellungsgründe basieren auf den CEDIS-PCL Codes: RC – Respiratorisch (651-661), CV – Kardiovaskulär (001-012) und NC – Neurologisch (401-411).

>  Boender T. Sonia, Cai Wei, Schranz Madlen, Kocher Theresa, Wagner Birte, Ullrich Alexander, Buda Silke, Zöllner Rebecca, Greiner Felix, Diercke Michaela, Grabenhenrich Linus. Using routine emergency department data for syndromic surveillance of acute respiratory illness, Germany, week 10 2017 until week 10 2021. Euro Surveill. 2022;27(27):pii=2100865. DOI: [10.2807/1560-7917.ES.2022.27.27.2100865](https://doi.org/10.2807/1560-7917.ES.2022.27.27.2100865)

### Berechnung der Baseline  

Für jede Kategorie (Notaufnahmevorstellungen, nach Alter bzw. Dringlichkeitseinschätzung stratifiziert, Falldefinitionen) wird ein Erwartungswert und ein zugehöriges 95% Prädiktionsintervall auf Ebene der einzelnen Notaufnahmen berechnet, welche dann über alle Notaufnahmen zu einem Erwartungswert bzw. Prädiktionsintervall aufsummiert werden. Der Erwartungswert wird mit Hilfe eines Negativ-Binomial Regressionsmodells berechnet.
Dabei wird ein globales Regressionsmodell auf den Daten aller vorhandenen Notaufnahmen bis zum letzten vollständigen Quartal trainiert (`model_data_start`, `model_data_end`). Dies erlaubt die Inklusion von Notaufnahmen, die nicht über den gesamten Referenzzeitraum (01.01.2017 – heute) Daten geliefert haben. Das Modell wird am Ende jeden Quartals neu berechnet (`model_version`). Die Metadaten zum Regressionsmodell sind in der [Regressionsmodell_Metadaten.json](/Metadaten/Regressionsmodell_Metadaten.json) hinterlegt.
Das Regressionsmodell verwendet Variablen für die jeweilige Notaufnahme, Saisonalität, einen zeitlichen Trend und Phasen der Pandemie. Dies erlaubt es, eine präpandemische Baseline für jeden Zeitpunkt und jede Notaufnahme zu berechnen. Die Summe über alle eingeschlossenen Notaufnahmen ergibt die dargestellte Gesamt-Baseline.


### Interpretation der Daten  

Die Daten lassen sich nur mit Kenntnis der Prozesse und Strukturen in den jeweiligen Notaufnahmen bzw. in Rücksprache mit den Notaufnahmen sinnvoll interpretieren. Weiterhin ist es bei der Interpretation von Surveillance-Daten wichtig, einige Limitationen zu beachten:
* Die Stichprobe an Notaufnahmen ist nicht repräsentativ für Deutschland.
* Die Anzahl an Notaufnahmen im Wochenbericht kann sich wöchentlich ändern, weil nicht jede Notaufnahme jede Woche Daten liefert.
* Aus den Fallzahlen lassen sich keine bevölkerungsbezogenen Daten (z. B. Inzidenzen) ableiten.
* Vorstellungsgründe sind nicht mit klinisch bestätigten Diagnosen gleichzusetzen. Auch bei den in der Notaufnahme vergebenen Diagnosen handelt es sich in vielen Fällen erst um Verdachtsdiagnosen.
* Bei den Indikatoren der syndromischen Surveillance kann es dazu kommen, dass Fälle nicht erkannt werden, da sowohl Vorstellungsgründe als auch Diagnosen fehlende Werte aufweisen können. Dadurch kann es zu einer Untererfassung der Fallzahlen kommen.
* Veränderungen im Zeitverlauf können neben realen Änderungen der Inanspruchnahme auch verschiedene andere Ursachen haben (bspw. veränderte Dokumentationspraxis oder Versorgungsprozesse). Die vorliegenden Daten sollten daher nicht ohne vorherige direkte Kommunikation mit den Notaufnahmen interpretiert werden.


## Inhalt und Aufbau des Datensatzes  

Der Datensatz enthält aggregierte Daten aus der Routinedokumentation aus einer Auswahl deutscher Notaufnahmen. Im Datensatz enthalten sind:

* Aggregierte Surveillancedaten, stratifiziert nach den Kategorien
* Informationen über die Vollständigkeit ausgewählter Variablen
* Standortdaten eingeschlossener Notaufnahmen
* Übersetzungstabelle der Variablenausprägungen
* Metadaten Datei zum Import in Zenodo
* Lizenzdatei
* Datensatzdokumentation in deutscher Sprache

Die Daten werden jede Woche Mittwochs mit Daten bis einschließlich Sonntags aktualisiert. Die Modelle der Baseline werden am Ende jeden Quartals mit den bis dahin verfügbaren Daten neu trainiert

### Standortdaten eingeschlossener Notaufnahmen 

Die Datei "[Notaufnahmesurveillance_Standorte.csv](/Notaufnahmesurveillance_Standorte.csv)" enthält die Standort- und Metainformationen aller  eingeschlossenen Notaufnahmen, unter anderem die IK-Nummer, den Namen, die Koordinaten und das Bundesland sowie die Versorgungsstufe jeder Notaufnahme.

> [Notaufnahmesurveillance_Standorte.csv](/Notaufnahmesurveillance_Standorte.csv)

#### Variablen und Variablenausprägung

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
ik_number   | Text   |  | ID der Notaufnahme
ed_name   | Text   |  | Name der Notaufnahme
available   | Text   | `current quarter`, `any quarter` | Verfügbarkeit der Notaufnahme: current quarter = in diesem Quartal verfügbar, any quarter = in mind. einem der vorherigen Quartale verfügbar, aber nicht in diesem
latitude   | Dezimalzahl   | `≥0.0` | Breitengrad des Standorts der Notaufnahme
longitude   | Dezimalzahl   | `≥0.0` | Längengrad des Standorts der Notaufnahme
state_id  | Text   | `01`, ... `16` | [Länderschlüssel](https://de.wikipedia.org/wiki/Amtlicher_Gemeindeschl%C3%BCssel) des Bundeslandes 
level_of_care_id  | Text   | `01`, `02`, `03` | [Versorgungsstufe](https://www.g-ba.de/downloads/62-492-2340/Not-Kra-R_2020-11-20_iK-2020-11-01.pdf) der Notaufnahme
state_DE  | Text   | `Schleswig-Holstein`, ... `Thüringen` | Bundesland (deutsch)
state_EN  | Text   | `Schleswig-Holstein`, ... `Thuringia` | Bundesland (englisch)
level_of_care_DE  | Text   | `Basisnotfallversorgung`, `Erweiterte Versorgung`, `Umfassende Versorgung` | Versorgungsstufe (deutsch)
level_of_care_EN  | Text   | `basic`, `extended`, `comprehensive` | Versorgungsstufe (englisch)

### Vollständigkeit ausgewählter Variablen  

Die Datei "[Notaufnahmesurveillance_Datenqualitaet.csv](/Notaufnahmesurveillance_Datenqualitaet.csv)" enthält Informationen zur täglichen Anzahl der Notaufnahmevorstellungen sowie der Vollständigkeit ausgewählter Variablen in Prozent. 

> [Notaufnahmesurveillance_Datenqualitaet.csv](/Notaufnahmesurveillance_Datenqualitaet.csv)

#### Variablen und Variablenausprägung

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
date   | Text   | `JJJJ-MM-TT` | Datum; JJJJ entspricht dem Jahr, MM dem Monat und TT dem Tag
visit_count   | Ganze Zahl   | `≥0` | Anzahl Notaufnahmevorstellungen an diesem Tag
visit_mean   | Ganze Zahl   | `≥0` | Durchschnittliche Anzahl Vorstellungen pro Notaufnahme, gerundet auf ganze Zahlen
ed_count  | Ganze Zahl   | `≥0` | Anzahl von eingeschlossenen Notaufnahmen in diesem Quartal
triage_completeness   | Ganze Zahl   | `≥0` | Anteil von Fällen, bei denen die Dringlichkeitseinschätzung vorhanden ist (%)
cedis_completeness  | Ganze Zahl    | `≥0` | Anteil von Fällen, bei denen der Vorstellungsgrund nach Canadian Emergency Department Information System - Presenting Complaint List (CEDIS-PCL) vorhanden ist (%)
diagnosis_completeness  | Ganze Zahl   | `≥0` | Anteil von Fällen, bei denen mindestens eine Diagnose nach ICD-10 vorhanden ist (%)
disposition_completeness  | Ganze Zahl   | `≥0` | Anteil von Fällen, bei denen die Angabe über den Verbleib vorhanden ist (%)


### Anzahl der Notaufnahmevorstellungen

Die Datei "[Notaufnahmesurveillance_Zeitreihen_Vorstellungen.csv](/Notaufnahmesurveillance_Zeitreihen_Vorstellungen.csv)" enthält neben der Anzahl täglicher Notaufnahmevorstellungen und dem gleitenden 7-Tage Durchschnitt auch den modellbasierten Erwartungswert inklusive Konfidenzintervall und die Anzahl eingeschlossener Notaufnahmen je Quartal.  

> [Notaufnahmesurveillance_Zeitreihen_Vorstellungen.csv](/Notaufnahmesurveillance_Zeitreihen_Vorstellungen.csv)

#### Variablen und Variablenausprägung

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
date   | Text   | `JJJJ-MM-TT` | Datum; JJJJ entspricht dem Jahr, MM dem Monat und TT dem Tag
visit_count   | Ganze Zahl   | `≥0` | Anzahl Notaufnahmevorstellungen an diesem Tag, Summe über alle Notaufnahmen in diesem Quartal
visit_7day_mean   | Dezimalzahl   | `≥0.0` | Gleitender 7-Tage Durchschnitt der Notaufnahmevorstellungen
baseline   | Dezimalzahl   | `≥0.0` | Modellierter Erwartungswert der Anzahl an Notaufnahmevorstellungen an diesem Tag für die Notaufnahmen in diesem Quartal
baseline_lowerbound   | Dezimalzahl   | `≥0.0` | Untere Grenze des 95%-Konfidenzintervalls der Baseline
baseline_upperbound  | Dezimalzahl   | `≥0.0` | Obere Grenze des 95%-Konfidenzintervalls der Baseline
ed_count  | Ganze Zahl   | `≥0` | Anzahl von eingeschlossenen Notaufnahmen in diesem Quartal

### Altersverteilung der Notaufnahmevorstellungen

Die Datei "[Notaufnahmesurveillance_Zeitreihen_Alter.csv](/Notaufnahmesurveillance_Zeitreihen_Alter.csv)" enthält die Anzahl der Notaufnahmevorstellungen und den berechneten Erwartungswert stratifiziert nach Altersgruppen. 

> [Notaufnahmesurveillance_Zeitreihen_Alter.csv](/Notaufnahmesurveillance_Zeitreihen_Alter.csv)

#### Variablen und Variablenausprägung
Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
date   | Text   | `JJJJ-MM-TT` | Datum; JJJJ entspricht dem Jahr, MM dem Monat und TT dem Tag
age   | Text   | `0-19`, `20-39`, `40-59`, `60-79`, `80+` | Altersgruppe
visit_count   | Ganze Zahl   | `≥0` | Anzahl Notaufnahmevorstellungen an diesem Tag, Summe über alle Notaufnahmen in diesem Quartal
visit_7day_mean   | Dezimalzahl   | `≥0.0` | Gleitender 7-Tage Durchschnitt der Notaufnahmevorstellungen
baseline   | Dezimalzahl   | `≥0.0` | Modellierter Erwartungswert der Anzahl an Notaufnahmevorstellungen an diesem Tag für die Notaufnahmen in diesem Quartal
baseline_lowerbound   | Dezimalzahl   | `≥0.0` | Untere Grenze des 95%-Konfidenzintervalls der Baseline
baseline_upperbound  | Dezimalzahl   | `≥0.0` | Obere Grenze des 95%-Konfidenzintervalls der Baseline
ed_count  | Ganze Zahl   | `≥0` | Anzahl von eingeschlossenen Notaufnahmen in diesem Quartal

### Dringlichkeitseinschätzung der Notaufnahmevorstellungen

Die Datei "[Notaufnahmesurveillance_Zeitreihen_Dringlichkeit.csv](/Notaufnahmesurveillance_Zeitreihen_Dringlichkeit.csv)" enthält die Anzahl der Notaufnahmevorstellungen und den berechneten Erwartungswert stratifiziert nach Dringlichkeitseinschätzung.

> [Notaufnahmesurveillance_Zeitreihen_Dringlichkeit.csv](/Notaufnahmesurveillance_Zeitreihen_Dringlichkeit.csv)


#### Variablen und Variablenausprägung

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
date   | Text   | `JJJJ-MM-TT` | Datum; JJJJ entspricht dem Jahr, MM dem Monat und TT dem Tag
triage   | Text   | `1`, `2`, `3`, `4`, `5` | Dringlichkeitseinschätzung. 1 - sofort, 2 - sehr dringend, 3 - dringend, 4 - normal, 5 - nicht dringend.
visit_count   | Ganze Zahl   | `≥0` | Anzahl Notaufnahmevorstellungen an diesem Tag, Summe über alle Notaufnahmen in diesem Quartal
visit_7day_mean   | Dezimalzahl   | `≥0.0` | Gleitender 7-Tage Durchschnitt der Notaufnahmevorstellungen
baseline   | Dezimalzahl   | `≥0.0` | Modellierter Erwartungswert der Anzahl an Notaufnahmevorstellungen an diesem Tag für die Notaufnahmen in diesem Quartal
baseline_lowerbound   | Dezimalzahl   | `≥0.0` | Untere Grenze des 95%-Konfidenzintervalls der Baseline
baseline_upperbound  | Dezimalzahl   | `≥0.0` | Obere Grenze des 95%-Konfidenzintervalls der Baseline
ed_count  | Ganze Zahl   | `≥0` | Anzahl von eingeschlossenen Notaufnahmen in diesem Quartal

### Notaufnahmevorstellungen für ausgewählte Falldefinitionen

Wie im Abschnitt [Falldefinitionen](#Falldefinitionen) beschrieben, werden die Notaufnahmevorstellungen unter anderem nach respiratorischen, kardiovaskulären und neurologischen Vorstellungsgründen sowie akuten respiratorischen Erkrankungen (ARE) und schweren akuten respiratorischen Infektionen (SARI) und grippeähnlichen Erkrankungen (ILI) unterschieden. 

Die Dateien "[Notaufnahmesurveillance_Zeitreihen_CEDIS.csv](/Notaufnahmesurveillance_Zeitreihen_CEDIS.csv)" enthält die Anzahl der Notaufnahmevorstellungen und den berechneten Erwartungswert für die Falldefinitionen von respiratorischen, kardiologischen und neurologischen Vorstellungsgründen,  basierend auf Canadian Emergency Department Information System - Presenting Complaint List (CEDIS-PCL, [Grafenstein et al. 2008](https://doi.org/10.1017/s1481803500009878 )).

> [Notaufnahmesurveillance_Zeitreihen_CEDIS.csv](/Notaufnahmesurveillance_Zeitreihen_CEDIS.csv)

#### Variablen und Variablenausprägung

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
date   | Text   | `JJJJ-MM-TT` | Datum; JJJJ entspricht dem Jahr, MM dem Monat und TT dem Tag
cedis   | Text   | `CV`, `RC`, `NC` | Vorstellungsgrund basierend auf Canadian Emergency Department Information System - Presenting Complaint List (CEDIS-PCL). RC - Respiratorisch (651-661), CV - Kardiovaskulär (001-012), NC - Neurologisch (401-411)
visit_count   | Ganze Zahl   | `≥0` | Anzahl Notaufnahmevorstellungen an diesem Tag, Summe über alle Notaufnahmen in diesem Quartal
visit_7day_mean   | Dezimalzahl   | `≥0.0` | Gleitender 7-Tage Durchschnitt der Notaufnahmevorstellungen
baseline   | Dezimalzahl   | `≥0.0` | Modellierter Erwartungswert der Anzahl an Notaufnahmevorstellungen an diesem Tag für die Notaufnahmen in diesem Quartal
baseline_lowerbound   | Dezimalzahl   | `≥0.0` | Untere Grenze des 95%-Konfidenzintervalls der Baseline
baseline_upperbound  | Dezimalzahl   | `≥0.0` | Obere Grenze des 95%-Konfidenzintervalls der Baseline
ed_count  | Ganze Zahl   | `≥0` | Anzahl von eingeschlossenen Notaufnahmen in diesem Quartal


Die Datei "[Notaufnahmesurveillance_Zeitreihen_Syndrome.csv](/Notaufnahmesurveillance_Zeitreihen_Syndrome.csv)" enthält die Anzahl der Notaufnahmevorstellungen und den berechneten Erwartungswert der Falldefinitionen für akute respiratorische Erkrankungen (ARE/ARI), schwere akute respiratorische Infektionen (SARI) und grippeähnliche Erkrankungen (Influenza-like-illness, ILI).  

> [Notaufnahmesurveillance_Zeitreihen_Syndrome.csv](/Notaufnahmesurveillance_Zeitreihen_Syndrome.csv)

#### Variablen und Variablenausprägung

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
date   | Text   | `JJJJ-MM-TT` | Datum; JJJJ entspricht dem Jahr, MM dem Monat und TT dem Tag
syndrome   | Text   | `ARI`, `SARI`, `ILI` | Falldefinitionen für akute respiratorische Erkrankungen (ARE/ARI), schwere akute respiratorische Infektionen (SARI) und grippeähnliche Erkrankungen (Influenza-like-illness, ILI), siehe [Boender et al. 2022](https://www.eurosurveillance.org/content/10.2807/1560-7917.ES.2022.27.27.2100865?TRACK=RSS)
visit_count   | Ganze Zahl   | `≥0` | Anzahl Notaufnahmevorstellungen an diesem Tag, Summe über alle Notaufnahmen in diesem Quartal
visit_7day_mean   | Dezimalzahl   | `≥0.0` | Gleitender 7-Tage Durchschnitt der Notaufnahmevorstellungen
baseline   | Dezimalzahl   | `≥0.0` | Modellierter Erwartungswert der Anzahl an Notaufnahmevorstellungen an diesem Tag für die Notaufnahmen in diesem Quartal
baseline_lowerbound   | Dezimalzahl   | `≥0.0` | Untere Grenze des 95%-Konfidenzintervalls der Baseline
baseline_upperbound  | Dezimalzahl   | `≥0.0` | Obere Grenze des 95%-Konfidenzintervalls der Baseline
ed_count  | Ganze Zahl   | `≥0` | Anzahl von eingeschlossenen Notaufnahmen in diesem Quartal

### Formatierung der Daten  

Die Notaufnahmesurveillance Daten sind im Datensatz als kommaseparierte .csv-Datei enthalten. Der verwendete Zeichensatz der .csv-Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Komma ",". Datumsangaben sind im ISO-8601-Standard formatiert.

* Zeichensatz: UTF-8
* Datumsformat: ISO 8601
* .csv-Trennzeichen: Komma ","

### Metadaten  

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:

> [Metadaten/](/Metadaten/)  

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.   

> [Metadaten/zenodo.json](/Metadaten/zenodo.json)  

## Hinweise zur Nachnutzung der Daten

Offene Forschungsdaten des RKI werden auf [GitHub.com](http://GitHub.com/), [Zenodo.org](http://Zenodo.org/) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:

- [https://github.com/robert-koch-institut](https://github.com/robert-koch-institut)
- [https://zenodo.org/communities/robertkochinstitut](https://zenodo.org/communities/robertkochinstitut)
- [https://edoc.rki.de](https://edoc.rki.de/)


### Lizenz

Der Datensatz "Notaufnahmesurveillance - Daten des Wochenberichts" ist lizenziert unter  der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](/LICENSE) bzw. [LIZENZ](/LIZENZ) Datei des Datensatzes.

