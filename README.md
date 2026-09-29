Dampfphasenlötanlage Einweisung
===============================

:warning: __Work in Progress. Noch nicht auf der Webseite posten__ :warning:

Einweisung des [FAU FabLab](https://fablab.fau.de) für die Dampfphasenlötanlage VaporPhase One (siehe [Löten](https://fablab.fau.de/tool/elektronikmessen-loeten-etc/loeten/)).

Inhalt
------

- Grundlagen: warum Dampfphasenlöten, Vergleich mit anderen Lötverfahren
- Sicherheitshinweise zum Wärmeübertragungsmedium Galden (Verbrennung, Rutschgefahr, Zersetzung bei Überhitzung)
- Geeignete Bauteile, Bestücken, Vorbereitung der Anlage (Kühlwasser, Füllstand, Einstellungen)
- Lötvorgang, Checkliste für den Ablauf, Wartung für Betreuer

Download
--------

Die neueste Version aus [GitHub](https://github.com/fau-fablab/dampfphasenloetanlage-einweisung) ist als PDF abrufbar:

- [Einweisung](https://brain.fablab.fau.de/build/dampfphasenloetanlage-einweisung/Einweisung_Dampfphasenloetanlage.pdf)
- [Einweisungsliste](https://brain.fablab.fau.de/build/dampfphasenloetanlage-einweisung/Einweisungsliste_Dampfphasenloetanlage.pdf)

Außerdem baut eine GitHub Action die PDFs bei jedem Push. Auf dem Hauptbranch entsteht dabei ein
[Release](https://github.com/fau-fablab/dampfphasenloetanlage-einweisung/releases) mit Datums-Version (`vJJJJ.MM.TT`) und den PDFs.

Auschecken und bauen
--------------------

```bash
git clone --recursive git@github.com:fau-fablab/dampfphasenloetanlage-einweisung.git
cd dampfphasenloetanlage-einweisung
make
```

Die PDFs landen in `output/`. Layout, Kopf- und Fußzeile und das Logo des FAU FabLab (mit
FAU-Schriftzug) kommen aus dem Untermodul [fablab-document](https://github.com/fau-fablab/fablab-document),
das Logo wiederum aus dessen Untermodul [logo](https://github.com/fau-fablab/logo). Bei einem bestehenden
Klon die Untermodule mit `git submodule update --init --recursive` laden.

Technische Details zum Buildserver: [fau-fablab/buildserver](https://github.com/fau-fablab/buildserver)

[![Build Status](https://brain.fablab.fau.de/build/dampfphasenloetanlage-einweisung/status.svg)](https://brain.fablab.fau.de/build/dampfphasenloetanlage-einweisung/)
[![TODOs](https://brain.fablab.fau.de/build/dampfphasenloetanlage-einweisung/status-todos.svg)](https://brain.fablab.fau.de/build/dampfphasenloetanlage-einweisung/)
[![PDF bauen](https://github.com/fau-fablab/dampfphasenloetanlage-einweisung/actions/workflows/pdf.yml/badge.svg)](https://github.com/fau-fablab/dampfphasenloetanlage-einweisung/actions/workflows/pdf.yml)

Lizenz
------

[![Lizenz: CC BY-SA 3.0](https://licensebuttons.net/l/by-sa/3.0/de/88x31.png)</br>CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)
