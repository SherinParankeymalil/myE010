<h1> Dokumentation M901 - Linux


### Inhaltsverzeichnis
- [1. Einrichtung](#1-Einrichtung)
  - [1.1 Dokumentation](#11-Dokumentation)
  - [1.2 Installation](#12-Installation)
- [2. Kapitel Abarbeitung](#2-Kapitel-Abarbeitung)
  - [2.1.1 Linux](#211-Linux)
  - [2.1.2 Distributionen](#212-Distributionen)
  - [2.1.3 Embedded Systems](#213-Embedded-Systems)
  - [2.1.4 Linux in the Cloud](#214-Linux-in-the-Cloud)
  - [2.2.1 Major Open Source Applications](#221-Major-Open-Source-Applications)
  - [2.3.1 Open Source Software and Licensing](#231-Open-Source-Software-and-Licensing)
  - [2.3.2 GPL/Copyleft Lizenz](#232-GPLCopyleft-Lizenz)
  - [2.4.1 ICT Skills and Working Linux](#241-ICT-Skills-and-Working-Linux)
  - [2.5.1 Choosing an Operating System](#251-Choosing-an-Operating-System)
  - [2.5.2 Distribution Lifecycle Management](#252-Distribution-Lifecycle-Management)
  - [2.5.3 Hardware](#253-Hardware)
- [3. Fahrplan](#3-Fahrplan)
- [4. Lernprozess / Reflexion](#4-Lernprozess--Reflexion)
  - [4.1 Command Line Basics](#41-Command-Line-Basics)

<br>

## 1. Einrichtung
Zwar wurde das GitHub Repo vom Original in meines kopiert, via "Fork" Befehl, habe dennoch eine neue "eigene" Dokumentation erstellt. 

### 1.1 Dokumentation
Die Aufträge werden nacheinander abgearbeitet, hier dokumentiert und praktisch umgesetzt. Die Dokumentation wird im Markdown Editor geschrieben und verwaltet. Danach wird sie auf GitHub hochgeladen.

### 1.2 Installation
Vagrant und zugehörige VMs waren bereits vom Modul 300 auf meinem Rechner installiert. Für die Umsetzung der Aufgaben, habe ich mit einer Ubuntu 18.04 VM gearbeitet. 
<br>
<br>
<br>

## 2. Kapitel Abarbeitung
Die Kapitel werden einzeln nach Vorgaben abgearbeitet und hier festgehalten.

### 2.1.1 Linux
Linux ist ein von Unix inspiriertes Betriebssystem, welches von Linus Torvalds als Experiment im Jahre 1991 etwickelt wurde. Die ursprüngliche Idee war es, einen freien Unix-Klon, an dem jeder mitentwickeln kann, zu erschaffen. Seine erstee veröffnetlichte Version, hatte relativ viel Beschränkungen. Darauf testeten einige Unix-Fans, jegliche Treiber und stellten erste Programme zur Wahl. Dazu kamen, die vom GNU Projekt vorgestellten klassischen Unix Tools, welche so umprogrammiert werden konnten, dass sie für das Linux Betriebssystem verwendet werden konnten. Zuletzt stellte Linux Torvalds noch den Linux Kernel zusammen und erschuf das komplettierte Linux Betriebssystem, welches er dann weiterentwickelte und schliesslich im Jahre 1992 die nächste Version von Linux erstmals unter GPL veröffentlichte. Danach wurden der Kernel und weitere Betriebsteile stark verbessert und ausgebaut, was die Grundlage für den heutigen grossen Linux Markt bildete. 
Die Bezeichnung ist eine Mischung aus seinem Namen und Unix.

### 2.1.2 Distributionen
Linux hat eine grosse Anzahl unterschiedlichster Distributionen. Damit ist eine komplette vorgefertigte Betriebsumgebung auf der Basis von Linux (dem Betriebskern) gemeint. Fast jede Distribution ist um eine Paketverwaltung herum zusammengestellt. Die Pakete werden dazu online in sogenannten Repositories zu finden. Im Punkt Paketformate unterscheiden sich die Distributionen, wobei es zwei hauptsächlich konkurrierende Ansätze gibt: Debian (deb) und Red Hat (rpm). Die deb-Paketformate werden von Debian GNU/Linux, Ubuntu und anderen Debian-Nachkommen verwendet, während Red Hat, SUSE und diverse andere abgeleitete Distributionen auf rpm setzen. <br>
Zu den grösseren Bekanntheiten zählen folgende: 
Debian, Ubuntu (LTS), CentOS, openSUSE, Red Hat, SUSE, Linux Mint, Raspberry Pi, "Android". Die erstern Linux Distributionen kamen im Jahr 1992 heraus, aber kaum eine aus der damaligen Zeit wird heute noch weiterentwickelt, ausser Slackware und Debian. Die Firma SUSE wurde 1992 unter dem Namen »Gesellschaft für Software- und System-Entwicklung« als Unix-Beratungshaus gegründet. Sie ist speziell für Unternehmungskunden ausgelegt und ein Zusammenschluss von Freiwilligen. Zurzeit gehört das Ubuntu zu den beliebtesten Betriebsystemen und wurde von südafrikanischen Unternehmen, Mark Shuttleworth im Jahre 2004 erstmals veröffentlicht. 

### 2.1.3 Embedded Systems 
Das Embedded System ist eine Distributionsart von Linux und ist ein Betriebssystem basierend auf einemm Linux Kernel. Ihre Wurzeln kommt vom Linux Kernel Version 1.2, welches im März des Jahres 1995 entwickelt wurde und die Basis für viele Geräte wie Router, Smartphones und Grossrechner bildet. Die Ressourcen sind bei einem Embedded System abgespeckter und auf bestimmte Aufgaben ausgelegt. Es ist meistens auf ein bestimmtes Gerät beschränkt. Das Yocto Projekt istl beispielsweise ein Open Source Projekt, dass sich für die Kreation und Weiterentwicklung von Embedded Systems unter Linux einsetzt. 

### 2.1.4 Linux in the Cloud
Häufig wird hier von Cloud Computing gesprochen, womit die Bereitstellung von Computerressoursen in der Cloud gemeint ist. Es gibt unterschiedlichste Cloud Optionen. Grob werden in drei Kategorien aufgeteilt; die Desktop-artigen, virtuelle und   Systeme. Dabei gibt es einige Anwendungen wie Dropbox, Google Drive oder One Drvie und Weitere. 

### 2.2.1 Major Open Source Applications
Einige vorgeschlagene Programme, wurden auf meiner VM installiert und eingerichtet.
Vorinstallierte Programme: LibreOffice, Firefox, Thunderbird, Python
Zusätzlich installiert: Maria DB, GIMP, GNOME, apt-get, sed, php,   
Die Installationen können simpel über den Befehl "apt-get" installiert werden. Die Einrichtung wird dann für jedes Programm einzeln vorgenommen. Die Repositories variieren je nach Distributionen. Die rpm und yum CMDs gehören zu den Red Hat Paketmanager, wobei die dpkg und apt-get zu den Debian Distributionen gehören. 

Desktop Applikationen: LibreOffice ist die Open Source Variante von Microsoft Office. Thunderbird ist ein Open Source Mail Programm. Gimp ist ein Grafikprogramm, wie Paint bei Microsoft Windows. 

Server Applikationene: NFS ist das Network File System. Ein Protokoll, dass den Zugriff auf Dateien über eine Netzwerk ermöglicht. Samba ermöglicht Windows-Funktionen, wie die Datei- und Druckdienste unter einem anderen Betriebssystem zu nutzen. Nextcloud ist eine freie Software zum Soeichern von Dateien auf einem eigenen Server. Apache, NGINX, MariaDB und MySQL sind alles unterschiedliche Webserver und Datenbanken.


### 2.3.1 Open Source Software and Licensing
Durch das Urheberrecht steht einem Urheber eines Werks das Recht zu, als Einziger über sein Werk zu verfügen. Dagegen wird bei einer Open-Source Lizenz dem Erwerber der Software erlaubt, Dinge vorzunehmen, die er eigentlich laut dem Urheberrechtsgesetzt nicht machen dürfte. Das Konzept der "freien Software" geht auf RMS (Richard M.Stallman) und FSF (Free Software Foundation) zurück und dessen vier Bedingungen, welche für dies erfüllt sein müssen. 
  * Man muss das Programm für jeden beliebigen Zweck benutzen dürfen
  * Man muss studieren können, wie das Programm funktioniert, und es an seine       eigenen Bedürfnisse anpassen
  * Man muss das Programm weitergeben dürfen, um seinem Nächsten zu helfen
  * Man muss das Programm verbessern und die Verbesserungen veröffentlichen
    dürfen, um der Allgemeinheit zu nutzen
Zugang zum Quellcode ist Vorgabe. 
Der Begriff "frei" sollte nicht mit kostenlos verwechselt werden. Gemeint ist eher, dass der Benutzer "frei" ist, verschieden Dinge zu tun. <br>
Der kleine Unterschied zwischen der Freien und der Open Source Software ist, dass dahinter zwei unterschiedliche Pholosophien und Organisationen stehen. Open Source betont Entwicklungsprozess und Quelloffenheit, wobei Freie Software für alles in Bezug auf ihre vier Grundsätze steht. 
Es gibt noch weiter wichtige Modelle der Freien Software, zum Beispiel das BSD. Das BSD ist ein Unix ähnliches Betriebssystem. Dabei gibt es drei wesentliche Ausgaben: FreeBSD, NetBSD und OpenBSD. FreeBSD wird am häufigsten für Internetdienstanbietern angewendet; z.B. Netflich oder Yahoo. Ausserdem ist es teilweise die Grundlage für Darwin, dies Open Source Plattform für Apple und macOS.  


### 2.3.2 GPL/Copyleft Lizenz
Der Linux und seine weitere Komponenten, stehen unter GPL (General Public Lincense). Diese Lizenz wurde von RMS für das GNU Projekt entworfen. Ziel ist es, unter GPL stehende Software, weiterhin unter dieser Lizenz zu behalten. Gemäss GPL ist es erlaubt den Quellcode für beliebige Zwecke zu nutzen, zu ändern und in geänderter Form weiterzugeben oder gar zu verkaufen. Wichtig ist aber, dass alles im Namen der GPL veröffentlicht oder weitergegeben wird und der Quellcode immer zur Verfügung stehen muss. Oft werden solche Lizenzen auch Copyleft (Kontrast zu Copyright) genannt. Die aktuelle GPL Version ist die Ve
rsion 3, welche 2007 veröffentlicht wurde.     

### 2.4.1 ICT Skills and Working Linux
Bei Linux Distributionen gibt es grundlegend die Möglichkeit mir der grafischen Desktopoberfläche oder mit der Console/Terminal und den Befehlen zu arbeiten. Ubuntu wird häufig über eine grafische Oberfläche bedient, im Gegensatz zu z.B. CentOS. Häufig verwendete grafische Oberflächen sind Gnome, KDE, LXDe, Fluxbox, Xfce. Die Grafikumgebung erleichtert die Bedienung und bietet Dateimanager mit Verzeichnissen an, darunter auch die vorinstallierten Programme (oben bereits erwähnt). <br>
Die Benützung des Terminals ist etwas schwieriger, da dies gewisse Linux und deren Befehl Kentnisse voraussetzt. Die Shell interpretiert die Kommandos als Programmaufrufe und führt diese aus. Breits die ersten Unix Betriebssysteme hatten eine Shell "Oberfläche". Dabei gibt es einfache Texteditoren wie Nano oder Vim, womit man Textdateien, unter der Shell Oberfläche erstellen kann. 

### 2.5.1 Choosing an Operating System
Windows ist eines der verbreitesten, meistgenutzten und kostenpflichtiges Betriebssystemen. Ursprünglich war es eine von Microsoft entwickelte grafische Benutzeroberfläche, welche später zu einem eigenständigem Betriebssystem wurde. 
OSX ist der früehere Namen von MacOS, und bezeichnet das Betriebssystem für Mac-Computer von Apple. Es wurde auf der Grundlage von BSD Unix unter Darwin gebildet. <br>
In der Kategorie Sicherheit und Preis, liegt Linux weit vorne gefolgt von MacOS. Dafür ist der Nachteil beim Hardware Support und Software Versorgung bei Linux grösser, als bei Windows. Die Benutzerfreundlichkeit spielt ebenfalls eine wichtige Rolle, hier ist die Bedienung bei MacOS am einfachsten, wobei Windows einfacher zu erlernen und benutzen ist und durch die weite Verbreitung auch grösseres Interesse bei der Mehrheit findet. Bei Linux ist da mehr Erfahrung notwendig.  

### 2.5.2 Distribution Lifecycle Management
Bei Linux werden sehr häufig Komponenten Dritter integriert. Da Teile dieser Komponenten über die Produktlebenszeit hinweg Performance-Optimierungen oder Security Fixes erhalten, ist sehr hoch und daher ist eine kontinuierliche Pflege notwendig. Die Entwicklung eines auf Linux basierenden Produkts die Anpassung des Betriebssystemkerns, sowie das Zusammenstellen, Konfigurieren und reproduzierbare Paketieren als Gesamtsystem. Die lange Projekthistorie, eine große Entwicklergemeinde und viele Nutzer aus unterschiedlichen Anwendungsgebieten garantieren auch langfristig eine umfangreiche Pflege und Weiterentwicklung, wie z.B. das Debian-LTS-Projekt. Es stellt sicher, dass alle Debian Releases für mindestens 5 Jahre gepflegt werden. Darunter befinden sich auch Kernelrelease, welche sogenannte Stable-Versionen enthalten, die kritische Fehlerbehebungen zur Verfügung stellen. Bei der Produktpflege wird häufig vernachlässigt oder vergessen, dass auch die verwendeten Werkzeuge über die Produktlebenszeit gewartet werden müssen. 

### 2.5.3 Hardware
* Das Motherboard oder Hauptplatine ist der Grundbaustein eines Computers. Er beinhaltet den Sockel für die CPU, Steckplätze für Speicherbausteine und Erweiterungskarten wie Grafik-, Sound- und Netzwerkkarten sowie Bausteine, die die Komponenten miteinander verbinden.
* Der Prozessor ist die zentrale Recheneinheit, welche alle ihm übergebenen Befehle abarbeitet. Bekannte Prozessorhersteller sind Intel und AMD. 
* Der Power Supply ist zuständig für die notwendige Stromzufuhr. 
* Unter den optischen Laufwerke, werden z.B. CD's und DVD's verstanden, welche Daten lesen oder schreiben können. 
* Peripheriegeräte sind interne oder externe Komponenten/Geräte, welche zur Ein-/Ausgabe von Daten oder Befehlen in die Zentraleinheit dienen. 
* Partitionen oder Datenträger sind ein Teil der Festplatte, welche wichtige Dateien enthält. Dabei wird zwischen physischen, logischen und erweiterten Partitionen unterschieden. 
* Unter /dev/sd* sind die SATA und SCSI Festplatten zu finden
* Treiber sind Programme, welche für die Interaktion / Kommunikation zwischen Software und Hardware zuständig ist.
<br>
<br>
<br>

## 3. Fahrplan 
Der Fahrplan ist wie folgt aufgegliedert: 



| Datum: |	behandelte Unterrichtsinhalte: |	Gewichtung: |
| ------------- | ------------- | ------------- |
|15.05.19 |	Installation SW, Einrichten Linux VM <br>  1.1 Linux Evolution and Popular Operating Systems <br>  1.3 Open Source Software and Licensing  |   2 + 2 |
|22.05.19 |	2.1 Command Line Basics <br> 2.3 Using Directories and Listing Files <br> 2.4 Creating, Moving and Deleting Files |	2 + 3 + 2|
|29.05.19 |	3.2 Searching and Extracting Data from Files <br> 3.3 Turning Commands into a Script |	3 + 4 |
| 05.06.19 |	4.4 Your Computer on the Network |	2 |
| 12.06.19 | 702.1 Container Usage - Studium |	- |
|19.06.19 |	702.1 Container Usage - Umsetzung |	7 (14)|
| 26.06.19 |	LB1 Theoretische Prüfung und Abschluss LB2 |	-  |
|03.07.19 	|Sommersporttage |	- |
|   |Total Punkte |	24 (31) ! |

<br>
<br>

## 4. Lernprozess / Reflexion
Durch dieses Modul konnte ich viel Grundlegendes über Linux lernen und mein Memory bezüglich der Linux Befehle auffrischen. Vieles über den Aufbau von Linux und den damit zusammenhängenden Lizenzen, wusste ich nicht. Für die Zukunft waren diese und weiter Informationen, welche gesammelt wurden, sicherlich sehr hilfreich. Einen gewissen Umgang mit den Linux Befehlen hatte ich bereits, konnte aber viel Neue hinzufügen und ausprobieren. Das praktische Austesten auf der virtuellen Maschine nebst der Theorie, hat mir am meisten Spass gemacht. 


### 4.1 Command Line Basics
Ein separates Dokument mit den Basic Commands und entsprechenden Beschreibungen wird getestet, festgehalten und verlinkt.  
Link: https://github.com/SherinParankeymalil/myE010/blob/master/Wichtige%20CMD.docx








