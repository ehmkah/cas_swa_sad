# SAD - Online Ticketing System

# Installationsanleitung

* https://github.com/ehmkah/cas_swa_sad  - enthält den aktuellen Stand unseres SADs, wenn Ihr mir Eure github-Namen schicken würdet, würde ich Euch Schreibrechte geben 
* http://asciidoctor.org/docs/asciidoc-syntax-quick-reference - Eine Anleitung zu Asciidoc
* erstellen eines PDFs aus den Dateien 
  * Installation JDK8 - http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html (brauchen wir später auch für den Prototypen)
  * Installation Gradle -  http://gradle.org/gradle-download/ (Ist eine Art "Make" für Java)
  * Installation GIT - https://git-scm.com/downloads (VersionsverwaltungsSystem)
  * im Terminal eingeben: `git clone https://github.com/ehmkah/cas_swa_sad`
  * im Terminal eingeben: `cd cas_swa_sad`
  * im Terminal eingeben: `<YOUR_INSTALLATION_PFAD>/bin/gradle generate`
  * das fertige pdf und html sollte sich in `sad/build/asciidoc/pdf` bzw. `sad/build/asciidoc/html5` befinden 


# Kurpräsentation 
** Asciidoctor images unter src/docs/asciidoc/images (in asciidocDateien, werden diese dann von dort angezogen)
** neue Dateien mit eigenen Kapiteln möglich, bittte mit _ damit dafür keine eigenen Dokumente generiert werden
** 