# Events
## Definition
"An event is something to which a running program (a process) needs to respond, but which occurs outside the program, at an *unpredictable* time." [PLP, S. 434]

## Typische Beispiele:
- GUI: Mausklicks, Tastatureingaben
- Asynchrone Ein-/Ausgabe: Netzwerkzugriffe
-> alles typische Browser Beispiele und damit sehr prägend für JavaScript
[so]

## Synchron / Blocking
Was wäre wenn Funktionsaufrufe/IO synchron/blocking wären?
- -> in Single-Thread Umgebungen wie JavaScript Runtime (?) unerwünscht
- <Synchronen/blockierenden Beispielcode, der Meldung provoziert>
- Alternative: Asynchrone/nicht-blockierende Ausführung und Aufruf eines Handlers, sobald Operation abgeschlossen
[so]

## Callback Funktionen
- Grundidee: Handler-Funktion, die ausgeführt wird, sobald Event eingetreten ist
- das Laufzeitsystem wird somit "zurückgerufen"
[so]

## Event Implementierungsstrategien
### "Spontane" Subroutinen-Aufrufe:
klassisches Beispiel: Unix Signals <Figure 8.7, PLP, S. 435>
[PLP S. 434 ff.]
### Thread-basierte Handler
<TODO>
[PLP S. 436 ff.]

## Event-Loop
