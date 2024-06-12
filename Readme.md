Datensatzdokumentation
# Daten der Notaufnahmesurveillance 

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

Robert Koch-Institut, AKTIN-Notaufnahmeregister: Daten der Notaufnahmesurveillance. DOI:[10.5281/zenodo.813758](https://doi.org/10.5281/zenodo.11615713).  



## Informationen zum Datensatz und Entstehungskontext  

Der Datensatz „Notaufnahmesurveillance“ enthält aggregierte Daten der Routinedokumentation aus einer Auswahl deutscher Notaufnahmen aus dem [AKTIN-Notaufnahmeregister](https://www.aktin.org/de-de/) und bildet die Grundlage für die [Notaufnahmesurveillance](https://www.rki.de/sumo) am RKI.   

### Datenerhebung und Datenverarbeitung  

Die zugrundeliegenden Daten aus der Routinedokumentation von Notaufnahmen werden im Rahmen des AKTIN-Notaufnahmeregisters erhoben, wie in [Brammen et al. 2020](https://doi.org/10.1007/s00063-020-00764-2) beschrieben, und anschließend dem RKI als tägliche Datenlieferungen über eine SFTP-Server-API täglich bereitgestellt.   

> Brammen, D., Greiner, F., Kulla, M. et al. Das AKTIN-Notaufnahmeregister – kontinuierlich aktuelle Daten aus der Akutmedizin. Med Klin Intensivmed Notfmed 117, 24–33 (2022). DOI: [10.1007/s00063-020-00764-2](https://doi.org/10.1007/s00063-020-00764-2)   

Die Verarbeitung, Aufbereitung und automatisierte Qualitätsprüfung sowie die Veröffentlichung der Daten erfolgen durch das [Fachgebiet MF 4 | Fach- und Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MFI/MF4/mf4_node.html). Fragen zum Datenmanagement und zur Publikationsinfrastruktur können an das Open Data Team des Fachgebiets MF4 unter [OpenData@rki.de](mailto:opendata@rki.de) gerichtet werden. Die epidemiologisch-fachliche Expertise für die Notaufnahmesurveillance liegt bei dem [Fachgebiet FG 32 | Surveillance und elektronisches Melde- und Informationssystem (DEMIS) | ÖGD Kontaktstelle](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG32/FG32_node.html) des RKI, Fragen an das Team der Notaufnahmesurveillance können unter [sumo@rki.de](mailto:sumo@rki.de) gestellt werden. Das Monitoring der Notaufnahme-spezifischen Datenqualität und etwaige Abstimmungen mit den Notaufnahmen erfolgt im AKTIN TDAC. Für den Kontakt und Koordination der teilnehmenden Notaufnahmen ist das AKTIN-Office verantwortlich. Bei Fragen bitte an [office@aktin.org](mailto:office@aktin.org) wenden.  
  
### Datengrundlage und Einschlusskriterien  

Für die Berichterstattung der Notaufnahmesurveillance werden Routinedaten aus dem AKTIN-Notaufnahmeregister in täglichen Datenlieferungen bereitgestellt. Die Daten enthalten Informationen zu den liefernden Notaufnahme (inkl. Stufe der Notfallversorgung), den Altersgruppen, dem Vorstellungsgrund klassifiziert nach *Canadian Emergency Department Information System – Presenting Complaint List (CEDIS-PCL3.0, [Grafenstein et al. 2008](https://doi.org/10.1017/s1481803500009878 ))* , Diagnosen codiert nach der *Internationalen Klassifikation der Krankheiten, 10. Revision (International Classification of Diseases, ICD-10, [DIMDI 2019](https://www.dimdi.de/static/de/klassifikationen/icd/icd-10-gm/kode-suche/htmlgm2019/))* sowie Informationen über eine stationäre Aufnahme im Anschluss an den Notaufnahmeaufenthalt.  
Die Auswahl der Notaufnahmen basiert auf der individuellen Bereitschaft zur Teilnahme an der Berichterstattung der Notaufnahmesurveillance. Die Anzahl der einbezogenen Notaufnahmen kann dabei je Syndromdefinition variieren: Voraussetzung für die Berücksichtigung der Notaufnahmen in der Darstellung der jeweiligen Syndrome ist eine Vollständigkeit von mindestens 80 % für Angaben zu jenen Variablen, die Teil der Syndromdefinition sind (bspw. wird für die Aufnahme in die Darstellung des ARE-Syndroms eine Vollständigkeit von mind. 80 % bei Angaben zu ICD-10-Diagnosen oder bei Angaben zu CEDIS-PCL Vorstellungsgründen vorausgesetzt). Durch Veränderung der Verfügbarkeit der Daten kann es insgesamt zu einer unterschiedlichen Anzahl von Notaufnahmen je Berichtsdatum kommen. Da die Notaufnahmen jeweils unterschiedlich groß sind, kann es bei gleicher Anzahl von Notaufnahmen zu Unterschieden in der Höhe der Fallzahlen zwischen Berichtszeiträumen kommen. In die aktuelle Berichterstattung fließen Daten aus zentralen Notaufnahmen sowie pädiatrischen Notaufnahmen ein. Die unterschiedlichen Versorgungsschwerpunkte der eingeschlossenen Notaufnahmen können ebenfalls zu Variationen in den Fallzahlen führen.   


### Syndromdefinitionen  

Die Syndromdefinitionen für grippeähnliche Erkrankungen (Influenza-like illness, ILI) und Coronavirus Erkrankungen (COVID-19) basieren auf ICD-10-Diagnosen. Die Syndromdefinitionen für akute respiratorische Erkrankungen (ARE) und gastrointestinale Infektionen (GI) basieren auf einer Auswahl von CEDIS-PCL Vorstellungsgründen und ICD-10-Diagnosen. Zur Definition schwerer akuter respiratorischer Infektionen (SARI) werden ICD-10-Diagnosen in Verbindung mit einer stationären Aufnahme berücksichtigt. Details dazu werden in [Boender et al. 2022](https://doi.org/10.2807/1560-7917.ES.2022.27.27.2100865) und [Baum et al. 2023](https://doi.org/10.1101/2023.11.28.23298985) näher beschrieben.  

>  Boender T. Sonia, Cai Wei, Schranz Madlen, Kocher Theresa, Wagner Birte, Ullrich Alexander, Buda Silke, Zöllner Rebecca, Greiner Felix, Diercke Michaela, Grabenhenrich Linus. Using routine emergency department data for syndromic surveillance of acute respiratory illness, Germany, week 10 2017 until week 10 2021. Euro Surveill. 2022;27(27):pii=2100865. DOI: [10.2807/1560-7917.ES.2022.27.27.2100865](https://doi.org/10.2807/1560-7917.ES.2022.27.27.2100865)  

>  Jonathan Hans Josef Baum, Achim Dörre, Tamara Sonia Boender, Katharina Heldt, Hendrik Wilking, Susanne Drynda, Bernadett Erdmann, Rupert Grashey, Caroline Grupp, Kirsten Habbinga, Eckard Hamelmann, Amrei Heining, Heike Höger-Schmidt, Clemens Kill, Friedrich Reichert, Joachim Riße, Tobias Schilling, AKTIN Research Group, Madlen Schranz. Establishing syndromic surveillance of gastrointestinal infections in emergency departments using routine emergency department data and validating it against laboratory-based surveillance, Germany, January 2019 – June 2023. medRxiv 2023.11.28.23298985. DOI: [10.1101/2023.11.28.23298985](https://doi.org/10.1101/2023.11.28.23298985)  

### Berechnung des relativen Anteils  

Alle identifizierten Fälle der jeweiligen Syndrome werden als relativer Anteil dargestellt, der Nenner berechnet sich dabei individuell je Syndrom: die Fallzahlen werden anteilig an den Notaufnahmevorstellungen berechnet, die vollständige Angaben zu jenen Variablen haben, die Teil der Syndromdefinition sind (bspw. werden für die Berechnung des relativen Anteils der ARE-Fälle alle Vorstellungen berücksichtigt, die entweder Angaben zur ICD-10-Diagnose oder zum CEDIS-PCL Vorstellungsgrund haben). Innerhalb der Filterkategorien für Altersgruppe und Notaufnahmetyp ergibt sich der Nenner jeweils aus der gewählten Filterkombination (bspw. werden bei Auswahl der Gruppe „80+“ nur Vorstellungen dieser Altersgruppe im Nenner berücksichtigt).   

### Berechnung des Erwartungswertes  
Für jede Syndromdefinition sowie Filtermöglichkeit (Altersgruppe und Notaufnahmetyp) wird ein Erwartungswert des relativen Anteils und ein zugehöriges 80% Prädiktionsintervall berechnet. Der Erwartungswert wird mit Hilfe eines Negativ-Binomial Regressionsmodells auf der Zeitreihe der relativen Anteile berechnet und berücksichtigt die jährliche Saisonalität mittels Sinus-/Cosinus-Funktionen. Das Prädiktionsintervall wird wie von [Noufaily 2012](https://doi.org/10.1002/sim.5595) beschrieben berechnet. Als Referenzzeitraum für die Berechnung werden die jeweiligen Daten ab 01.01.2019 und bis 365 Tage vor dem aktuellen Berichtsdatum verwendet (bspw. entspricht der Referenzzeitraum am 23.08.2023 dem Zeitraum von 01.01.2019 bis 23.08.2022). Für die Darstellung der Notaufnahmevorstellungen mit COVID-19 wird aktuell auf die Berechnung eines Erwartungswertes verzichtet, da hierfür gegenwärtig noch nicht genug retrospektive Daten zur Verfügung stehen.  


### Interpretation der Daten  

Die Daten lassen sich nur mit Kenntnis der Prozesse und Strukturen in den jeweiligen Notaufnahmen bzw. in Rücksprache mit den Notaufnahmen sinnvoll interpretieren. Weiterhin ist es bei der Interpretation von Surveillance-Daten wichtig, einige Limitationen zu beachten:
* Die Stichprobe an Notaufnahmen ist nicht repräsentativ für Deutschland.
* Die Anzahl an Notaufnahmen in der Berichterstattung kann sich aufgrund unterschiedlicher Datenverfügbarkeiten und technischer Gegebenheiten ändern.
* Bei den hier dargestellten Daten handelt es sich um Routinedaten, die im Rahmen der Notfallversorgung erhoben werden. Daraus ergeben sich einige Limitationen, die Einfluss auf die Qualität der Berichterstattung haben können:
    * Fehlende Angaben bspw. in Vorstellungsgründen und Diagnosen können zu einer Untererfassung der Fallzahlen führen.
    * In einigen Notaufnahmen werden ICD-10-Diagnosen nicht unmittelbar während der Notaufnahmebehandlung, sondern mit einer Verzögerung von mehreren Tagen codiert. Dies kann sich auf die Fallzahlen in der tagesaktuellen Berichterstattung auswirken.
    * Vorstellungsgründe sind nicht mit klinisch bestätigten Diagnosen gleichzusetzen. Auch bei den vergebenen ICD-10-Diagnosen handelt es sich zunächst oft um Verdachtsdiagnosen, die bspw. noch nicht mit einer Labordiagnostik bestätigt wurden. 
* Veränderungen im Zeitverlauf können neben realen Änderungen der Inanspruchnahme auch verschiedene andere Ursachen haben (bspw. veränderte Dokumentationspraxis oder Versorgungsprozesse). Die vorliegenden Daten können daher nicht ohne vorherige direkte Kommunikation mit den Notaufnahmen interpretiert werden.  

## Inhalt und Aufbau des Datensatzes  

Der Datensatz enthält aggregierte Daten aus der Routinedokumentation aus einer Auswahl deutscher Notaufnahmen. Im Datensatz enthalten sind:  

* Aggregierte Surveillancedaten, stratifiziert nach den Kategorien 'Syndrom', 'Notaufnahmetyp', 'Altersgruppe'  
* Standortdaten aller angeschlossener Notaufnahmen  
* Übersetzungstabelle der Variablenausprägungen  
* Datenstand Datei zum Import in Zenodo  
* Lizenzdatei  
* Datensatzdokumentation in deutscher Sprache  

Die Daten werden täglich mit Daten bis einschließlich dem Vorvortag aktualisiert. Die Erwartungswerte werden basierdend auf verfügbaren Daten bis vor 365 Tagen berechnet.  

### Standortdaten eingeschlossener Notaufnahmen   

Die Datei [`Notaufnahmesurveillance_Standorte.tsv`](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/Notaufnahmesurveillance_Standorte.csv) enthält die Standort- und Metainformationen aller  angeschlossenen Notaufnahmen, wie die IK-Nummer, den Namen, die Koordinaten und das Bundesland sowie die Versorgungsstufe und den Notaufnahmetyp jeder Notaufnahme.  

> [Notaufnahmesurveillance_Standorte.tsv](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/Notaufnahmesurveillance_Standorte.csv)  

#### Variablen und Variablenausprägung  

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
ik_number   | Text   | `260102081`, ... | ID der Notaufnahme
ed_name   | Text   | `Paracelsus Kinik Henstedt-Ulzburg`, .. | Name der Notaufnahme
ed_type   | Text   | `central`, `pediatric`   | Notaufnahmetyp (`central`: Zentrale Notaufnahme, `pediatric`: Kindernotaufnahme)
level_of_care  | Text   | `Basisnotfallversorgung`, `Erweiterte Versorgung`, `Umfassende Versorgung` | [Versorgungsstufe](https://www.g-ba.de/downloads/62-492-2340/Not-Kra-R_2020-11-20_iK-2020-11-01.pdf) der Notaufnahme (deutsch)
state  | Text   | `Schleswig-Holstein`, ... `Thüringen` | Bundesland (deutsch) 
state_id  | Text   | `01`, ..., `16` | [Länderschlüssel](https://de.wikipedia.org/wiki/Amtlicher_Gemeindeschl%C3%BCssel) des Bundeslandes 
latitude   | Dezimalzahl   | `≥0.0` | Breitengrad des Standorts der Notaufnahme
longitude   | Dezimalzahl   | `≥0.0` | Längengrad des Standorts der Notaufnahme



### Notaufnahmevorstellungen für ausgewählte Syndromdefinitionen  

Wie im Abschnitt [Syndromdefinitionen](#Syndromdefinitionen) beschrieben, werden die Notaufnahmevorstellungen derzeit nach akuten respiratorischen Erkrankungen (ARE), schweren akuten respiratorischen Infektionen (SARI),  grippeähnlichen Erkrankungen (ILI), Coronavirus Erkrankungen (COVID-19) und gastrointestinalen Infektionen (GI) unterschieden.   


Die Datei [`Notaufnahmesurveillance_Zeitreihen_Syndrome.tsv`](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/Notaufnahmesurveillance_Zeitreihen_Syndrome.tsv)" enthält die Anzahl der Notaufnahmevorstellungen und den berechneten Erwartungswert der Anteile der Fälle an den Gesamtvorstellungen für die oben aufgelisteten Syndromdefinitionen.  

> [Notaufnahmesurveillance_Zeitreihen_Syndrome.tsv](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/Notaufnahmesurveillance_Zeitreihen_Syndrome.tsv)  

#### Variablen und Variablenausprägung

Variable | Typ | Ausprägung | Erläuterung
-------- | -------- | -------- | --------
date   | Text   | `JJJJ-MM-TT` | Datum; JJJJ entspricht dem Jahr, MM dem Monat und TT dem Tag
ed_type   | Text   | `all`,`central`, `pediatric`   | Notaufnahmetyp (`all`: alle Notaufnahmen, `central`: Zentrale Notaufnahme, _pediatric_: Kindernotaufnahme)
age_group   | Text   |  `00+`, `0-4`, `5-9`, `10-14`, `15-19`, `20-39`, `40-59`, `60-79`, `80+`  | Altersgruppe (`00+`: alle Altersgruppen, `0-4`: 0-4 Jahre, ...)
syndrome   | Text   | `ARI`, `SARI`, `ILI`, `COVID`, `GI` | Syndromdefinitionen für akute respiratorische Erkrankungen (ARE/ARI), schwere akute respiratorische Infektionen (SARI) und grippeähnliche Erkrankungen (Influenza-like-illness, ILI), siehe [Boender et al. 2022](https://www.eurosurveillance.org/content/10.2807/1560-7917.ES.2022.27.27.2100865?TRACK=RSS). Für gastrointestinale Infektionen (GI) siehe [Baum et al. 2023](https://doi.org/10.1101/2023.11.28.23298985).
relative_cases   | Dezimalzahl   | `≥0` | Relativer Anteil Notaufnahmevorstellungen an diesem Tag mit gegebenem Syndrom an allen Notaufnahmevorstellungen in gegebenen Notaufnahmen von gegebenem Typ 
relative_cases_7day_ma   | Dezimalzahl   | `≥0.0` | Gleitender 7-Tage Durchschnitt des relativen Anteil von Fällen des Syndroms an den Gesamtvorstellungen
expected_value   | Dezimalzahl   | `≥0.0` oder `NA` | Erwartungswert des relativen Anteils von Fällen des Syndroms an den Gesamtvorstellungen
expected_lowerbound   | Dezimalzahl   | `≥0.0` oder `NA` | Untere Grenze des 80%-Prädiktionsintervalls des Erwartungswerts
expected_upperbound  | Dezimalzahl   | `≥0.0` oder `NA` | Obere Grenze des 80%-Prädiktionsintervalls des Erwartungswerts 
ed_count  | Ganze Zahl   | `≥0` | Anzahl von eingeschlossenen Notaufnahmen an diesem Tag in den Notaufnahmen vom gegebenen Notaufnahmetyp

### Formatierung der Daten  

Die Notaufnahmesurveillance Daten sind im Datensatz als tabseparierte .tsv-Datei enthalten. Der verwendete Zeichensatz der .tsv-Datei ist UTF-8. Trennzeichen der einzelnen Werte ist ein Tab "\t". Datumsangaben sind im ISO-8601-Standard formatiert.  

* Zeichensatz: UTF-8  
* Datumsformat: ISO 8601  
* .tsv-Trennzeichen: Tab "\t"  

### Metadaten  

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:  

> [Metadaten/](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/Metadaten/)    

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.   
 
> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/Metadaten/zenodo.json)  

In der zenodo.json ist neben der Publikationsdatum (`"publication_date"`) auch der Datenstand enthalten:  

```
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Collected",
      "description": "Date when the Dataset was created"
    }
  ],
```    

## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:  

- https://zenodo.org/communities/robertkochinstitut  
- https://github.com/robert-koch-institut  
- https://gitlab.opencode.de/robert-koch-institut  
- https://edoc.rki.de/  
 
### Lizenz  

Der Datensatz "Daten der Notaufnahmesurveillance" ist lizenziert unter  der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/Daten_der_Notaufnahmesurveillance/blob/main/LIZENZ) Datei des Datensatzes.  

