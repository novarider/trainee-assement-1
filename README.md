# Trainingsaufgaben
Versuche bitte folgende Trainingsaufgaben zu lösen. 

Beachte dabei folgendes:
- Fragen bei denen du die Wahlmöglichkeit hast zwischen verschiedenen Varianten der Umsetzung sind mit Absicht so gestellt. Versuche dabei einfach begründen zu können wieso du es so umgesetzt hast bzw. welchen Vorteil du siehst.
- Es ist nicht schlimm wenn du nicht alle Aufgaben in der Zeit lösen kannst. Du solltest allerdings die Aufgaben die du lösen konntest verstanden haben und deinen Lösungsweg auch erklären und aufzeigen können!
- Falls du nicht weiter kommst oder etwas unklar ist, kannst du deinen Betreuer um Hilfe bitten!

## Aufgabe 1

Erstelle eine Angular Komponente die einen Action Button anzeigt und füge sie der App Komponente hinzu.
 - Der Button soll als weißes '+' in einem gelben Kreis dargestellt werden.
 - Der Kreis soll einen Durchmesser von 20px haben.
 - Die Komponente soll folgenden Selector verwenden: 'action-button'

![Button Preview](https://cdn.jsdelivr.net/gh/novarider/trainee-assement-1@master/src/assets/actionButton.png)

### Hilfreiches

- https://angular.io/guide/component-overview
- https://www.w3schools.com/html/
- https://www.w3schools.com/css/

## Aufgabe 2

Erstelle ein Formular in der App Komponente in dem zwei Werte eingetragen werden können:
- Ein Textfeld in dem der Name eingetragen werden kann.
- Ein Nummernfeld in dem man das Alter eintragen kann.

Das Formular soll einen Speichern Button und einen Reset Button besitzen.
- Mit dem Speichern Button werden die eingegebenen Werte gespeichert.
- Mit dem Reset Button wird das Formular zurückgesetzt (Alle Werte gelöscht)

### Hilfreiches

- https://angular.io/guide/reactive-forms
- https://www.w3schools.com/html/html_forms.asp


## Aufgabe 3

Erstelle einen Service der die Daten aus dem Formular speichert und verwaltet.
- Es soll eine Methode geben den bestehenden Daten einen Datensatz hinzufügt.
- Es soll eine Methode geben die gespeicherte Daten retouniert.

### Hilfreiches

- https://angular.io/tutorial/toh-pt4
- https://angular.io/guide/dependency-injection

## Aufgabe 4

Die Daten die im Service aus Aufgabe 3 gespeichert sind sollen in einer Liste angezeigt werden.
Das Design der Liste ist dir überlassen es müssen nur **alle** Daten angezeigt werden.

### Hilfreiches
- https://angular.io/tutorial/toh-pt2

## Aufgabe 5

Versuche in dieser Aufgabe Daten von einem REST Interface abzuholen und in einer SelectBox anzuzeigen.
Erstelle eine eigene Komponente die das abholen der Daten und die anzeige der Select Box übernimmt.

### Hilfreiches
- https://angular.io/guide/http
- http://restcountries.eu/
- https://www.w3schools.com/tags/tag_select.asp

## Aufgabe 6

Verwende nun Angular Routing in deiner Anwendung. Jedes Listenelement aus Aufgabe 4 soll auf eine eigene Komponente verlinken.

Die angezeigte Komponente soll sich ausgehend von einem Identifier in der URL (Route Parameter) die restlichen Daten aus dem Service von Aufgabe 3 holen und anzeigen.

Du kannst das verhalten testen in dem du zwei Personen einträgst, wenn du auf Person 1 klickst zeigt die Komponente die Daten von Person 1 an. Beim Klick auf Person 2 soll das selbe für Person 2 geschehen.

### Hilfreiches
- https://angular.io/guide/router
- https://codecraft.tv/courses/angular/routing/parameterised-routes/


## Aufgabe 7

Füge der soeben erstellten Komponente die Select Box aus Aufgabe 6 und einen Speichern Button hinzu.
Beim Klick auf Speichern soll das ausgewählte Land zu der Person hinzu gespeichert werden.

- Zeige die Länder information nur in der Detailseite an.
- Verwende dafür nicht ein Reactive Form sondern ein Template Driven Form.

### Hilfreiches

- https://angular.io/guide/forms

## Aufgabe 8

Erweitere die Anwendung um ein Feature das den Local Storage des Browsers nützt. Beim neuladen der Seite sollen die Daten die eingegeben wurden erhalten bleiben. Schreibe die Daten dafür in den LocalStorage und lade sie beim starten der Angular Anwendung aus dem LocalStorage, damit sie wieder angezeigt werden können.

### Hilfreiches

- https://www.w3schools.com/html/html5_webstorage.asp

## Aufgabe 9

Verlinke nun den Action Button aus Aufgabe 1 mit dem Formular aus Aufgabe 2.
Dabei soll das Formular normalerweise nicht angezeigt werden. Wenn allerdings auf den Button geklickt wird, erscheint auch das Formular mit dem Reset und Speichern Button.
Wenn auf Speichern oder Reset geklickt wird soll nach dem Speichern das Formular wieder verschwinden.

### Hilfreiches

- https://angular.io/guide/built-in-directives#adding-or-removing-an-element-with-ngif
