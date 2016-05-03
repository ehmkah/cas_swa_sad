# SAD - Online Ticketing System

#Buildstatus
Zur Zeit ist der Build: ![logo](https://api.travis-ci.org/ehmkah/cas_swa_sad.svg)

#Installationsanleitung

* https://github.com/ehmkah/cas_swa_sad  - enthält den aktuellen Stand unseres SADs
* http://asciidoctor.org/docs/asciidoc-syntax-quick-reference - Eine Anleitung zu Asciidoc
* erstellen eines PDFs aus den Dateien 
  * Installation JDK8 - http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html (brauchen wir später auch für den Prototypen)
  * Installation Gradle -  http://gradle.org/gradle-download/ (Ist eine Art "Make" für Java)
  * Installation GIT - https://git-scm.com/downloads (VersionsverwaltungsSystem)
  * im Terminal eingeben: `git clone https://github.com/ehmkah/cas_swa_sad`
  * im Terminal eingeben: `cd cas_swa_sad`
  * im Terminal eingeben: `<YOUR_INSTALLATION_PFAD>/bin/gradle generate`
  * das fertige pdf und html sollte sich in `sad/build/asciidoc/pdf` bzw. `sad/build/asciidoc/html5` befinden 


# Kurzpräsentation 
* Asciidoctor images unter src/docs/asciidoc/images (in asciidocDateien, werden diese dann von dort angezogen)
* neue Dateien mit eigenen Kapiteln möglich, bittte mit _ damit dafür keine eigenen Dokumente generiert werden

# mini git aneleitung

* Neue Datei zum Repository hinzufügen `git add <filename>`
* Alle geänderten Dateien commiten `git commit -a -m "message"`
* Alle änderungen remote verfügbar machen `git push origin HEAD`
* Lokales Repository aktualisiert `git pull`
