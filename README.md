# claudesearch
Prototyp für ein VuFind-basiertes Recherchesystem, das die eingegebenen Begriffe von einem LLM zu einem von zwei Suchtypen zuordnen lässt: Einer Known-Item-Suche, die über Kombinationen aus Nachnamen und Titelstichwörtern oder ID-Nummern identifziert wird, und thematische Anfragen. Je nach Ergebnis der Analyse werden unterschiedliche Parameter an VuFind übergeben.

Zusätzlich kann eine Checkbox ausgewählt werden, mit der zu dem eingegebenen Suchbegriff Grundlagenliteratur gefunden wird. Dafür wird der Suchbegriff kombiniert mit einer veroderten Menge an typischen Titelstichwörtern (Handbuch, Textbook, Einführung...)

Entwickelt mit Cursor.

Demo unter: https://youtu.be/keNoyD0pskY

Realisiert über eine VuFind-API nach diesem Schema
https://github.com/vufind-org/vufind/blob/dev/config/vufind/SearchApiRecordFields.yaml

LLM: claude-3-opus-20240229 über Anthropic
VuFind-Index: HCU Testing (nur intern bei eWW)

Credits:
Für Inspiration: 
Ralf Stockmann: https://github.com/rstockm

Für Geduld sowie moralische & technische Unterstützung: 
Johannes Schultze: https://github.com/jschultze
