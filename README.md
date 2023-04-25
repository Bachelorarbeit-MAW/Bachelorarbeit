# Bachelorarbeit

Voraussetzung:     JRE 8

Ausführen der JAR in der Konsole: java -jar Bachelorarbeit.jar

Parameter:  -h -> Hilfe
             <Sequenzdateipfad> <-maw|-lw> <-dna|-abc>

-> Sequenzdatei muss im (Multi-) FASTA-Format vorliegen

Falls -dna als Parameter verwendet wird, werden alle Zeichen, die nicht A,C,G,T entsprechen, durch eine zufällige Base ersetzt.



Im Fall der Distanzmatrix wird das Ergebnis in einer Datei mit dem Namen result.phylip gespeichert.
Im Fall der MAW wird das das Ergebnis in einer Datei mit dem Namen  result.txt gespeichert.
Die Datei wird in dem selben Verzeichnis erzeugt, in dem sich auch die JAR befindet.
