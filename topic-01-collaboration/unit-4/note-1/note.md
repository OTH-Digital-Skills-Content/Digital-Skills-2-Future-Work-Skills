---
order: 3

icon:
  type: fluent:notepad-28-regular
  color: orange
---

Note Challenge (4/5)

Aufgaben

[toc]

Ist es nicht toll, einen Eintrag auf einer Todo-Liste abzuhaken? Wir schauen uns nun zunächst ganz simple Tools an, die gar nicht viel mehr können als eine Todo-Liste, die ihr auf einen Zettel schreibt. Und dann gehen wir zu komplexeren Tools über, die auch in Unternehmen eingesetzt werden, um komplexe Aufgaben zu managen, sie an die zuständigen Personen zu verteilen und um den Fortschritt der Aufgaben zu tracken.

Ein ganz simples Aufgaben-Tool ist Microsoft To-Do. Es läuft im Browser und es gibt Apps für Android und iOS. Ähnliche Tools sind Todoist, Remember the Milk, Things, und so weiter. 

Bei Microsoft To-Do könnt ihr zunächst verschiedene Listen anlegen, z. B. für jede Vorlesung eine Liste oder aber auch eine Liste für alle Vorlesungen auf einmal. Und innerhalb einer Liste könnt ihr Aufgaben eintragen, erledigte Aufgaben abhaken und Aufgaben editieren. Komplexere Aufgaben lassen sich in einzelne Schritte unterteilen. Das sind also quasi Unteraufgaben, die es zunächst zu erledigen gilt, damit schlussendlich der Task als Gesamtes als erledigt markiert werden kann. Zu jeder Aufgabe lässt sich optional ein Fälligkeitsdatum setzen und man kann sich sogar per Push-Benachrichtigung erinnern lassen. Praktisch ist die Funktion “Mein Tag”. Schaut euch einfach früh morgens an, welche Aufgaben ihr heute bearbeiten wollt, fügt sie zu “Mein Tag” hinzu und setzt euch als Tagesziel, ebendiese Aufgaben bis zum Abend zu erledigen. Microsoft To-Do lässt sich auch mit mehreren Personen nutzen. Dazu könnt ihr eine Liste an andere Personen teilen, die dann die gleichen Aufgaben sehen und erledigen können und sie können auch neue Aufgaben anlegen.

Ein Eintrag in einer Todo-Liste hat im Prinzip nur zwei mögliche Status: unerledigt oder erledigt. In der Praxis werden in der Regel aber noch weitere Zusände benötigt: Mach ich irgendwann später, vorher muss erst noch XY gemacht werden, ist gerade in Arbeit, und so weiter. Hier sprechen wir nun nicht mehr von einfachen ToDos, sondern vom sogenannten Issue Tracking. Ein Issue ist eine Angelegenheit, ein Fall. Oft nennt man es auch: ein Ticket. Sagen wir mal, ihr ruft beim Paketdienst an, weil ein Paket nicht angekommen ist. Dann machen die ein Ticket auf. Dieses Ticket hat vielleicht den Status “offen”. Nun kommt eine anderere Mitarbeiterin, die sich um dieses Ticket kümmern möchte. Dann weist sie sich selbst das Ticket zu und setzt den Status auf “In Bearbeitung”. Nun kann sie auch wieder weitere Unter-Tickets aufmachen für Dinge, die sie oder jemand anderes erledigen muss, damit letztendlich das Haupt-Ticket abgeschlossen werden kann, und das verlorengeganene Paket hoffentlich wieder auftaucht. Bei solchen Support-Anfragen kommen Issue-Tracking-Systeme häufig zum Einsatz, aber auch in der Software-Entwicklung, wenn es darum geht, ein neues Feature zu implementieren oder Bugs zu fixen.

Das hier ist Trello. Genau wie Confluence und Jira - zu Jira kommen wir gleich - ist es von der Firma Atlassian. Trello lässt sich in der Basisversion kostenlos nutzen. Für jeden Zustand, den ein Ticket annehmen kann, legen wir eine Spalte an. Wir haben hier die Spalten Backlog, In Progress, For Review und Done. Im Backlog sind Aufgaben, die man zwar schon auf dem Schirm hat, aber noch niemand hat sich darum gekümmert. Wenn wir uns nun einer Aufgabe widmen wollen, schieben wir sie in die Spalte "In Progress". In der Regel verwendet man Trello im Team, man sieht also, wer gerade was macht und wer für was zuständig ist. Jeder kann auch Aufgaben kommentieren und man kann sich per E-Mail benachrichtigen lassen, wenn man selbst für eine Aufgabe zugewiesen wurde oder wenn sich an einer Aufgabe etwas getan hat. Der Zustand "For Review" heißt im Prinzip, dass die Aufgabe abgeschlossen ist. Nun soll nochmal jemand anderes über Resultat drüberschauen und das finale Okay geben oder man diskutiert gemeinsam die Lösung. Das erfolgt meist in virtuellen, hybriden oder on-site-Meetings, bei denen jeder seine erfüllten Aufgaben dem Team oder dem Vorgesetzten vorstellt und darüber diskutiert werden kann.

Es gibt viele Issue-Tracking-Tools: Trello, Asana, ClickUp, usw. Die meisten stellen die Aufgaben in Spalten dar, die von links nach rechts ihren Zustand ändern. Natürlich kann auch mal ein Ticket wieder nach links wandern, beispielsweise von “For Review” zurück in die “In Progress”-Spalte, weil doch noch nicht alles abgeschlossen war. 

Ein solches Tools, um Tickets je nach Status in Spalten zu organisieren, wird auch oft Kanban-Board genannt. Das geht natürlich auch analog, zum Beispiel mit Magnet-Tafeln oder Haftnotizen. Wenn ich eine Aufgabe bearbeiten möchte, schnappe ich mir das entspechende PostIt und wenn ich sie erledigt habe, klebe ich es in die Spalte “For Review”. 

In einigen Unternehmen kommen Tools wie Atlassian Jira zum Einsatz. Auch dieses Tool managet Tickets, ist aber noch deutlich komplexer und bietet jede Menge mehr Funktionen. Beispielsweise gibt es Integrationen in andere Tools, z. B. kann automatisch ein Ticket erstellt werden, wenn eine E-Mail eintrifft. Das Ticket-System antwortet auch auf diese E-Mail, sodass der Kunde gar nichts davon mitbekommt, dass im Hintergrund ein Ticket-System eingesetzt wird. In Jira können Tickets Unter-Tickets haben, sie können mit anderen Tickets verlinkt werden und es gibt sogar unterschiedliche Arten von Verlinkungen: Ein Ticket wurde von einem anderen Ticket verursacht, ist ähnlich zu dem, ein Ticket kann erst bearbeitet werden, wenn das andere abgeschlossen ist, usw. Tickets haben auch hier wieder Zustände. Das kann wieder so etwas simples sein wie: “Open”, “In Progress” oder “Done”, aber so etwas wie: “Paket ist wieder aufgetaucht” oder “Paket ist verschollen”. Jira-Tickets können unterschiedliche Typen haben und je nach Typ gibt es unterschiedliche Eigenschaften und Status-Workflows.

Schließen wir das Video ab mit den beiden Tools GitHub und GitLab. Git ist eine sogenannte Versionsverwaltung. Wenn man Software entwickelt oder allgemeiner, wenn man an Dateien arbeitet, kann man den Programmcode bzw. die Dateien in ein sogenanntes Git-Repository einchecken. Andere Personen können sich dann selbst wieder auf den neusten Stand bringen, ebenfalls Änderungen einpflegen und so gemeinsam an den gleichen Daten arbeiten. Git verwaltet die komplette Historie, sodass Änderungen leicht nachvollzogen und auch bei Bedarf wieder rückgängig gemacht werden können.

Die berühmtesten Anwendungen, um ein privates oder öffentliches Git-Repository komfortabel zu managen, sind GitHub und GitLab. GitLab kann man sich auf einem eigenen Server selbst installieren, GitHub ist ein Cloud-Dienst, den man in einer kostenlosen aber auch in einer Bezahlvariante nutzen kann. Auf GitHub findet man viele öffentliche Open-Source-Software-Projekte. Öffnet man ein Repository, sieht man die URL, um das Repository zu clonen, also um es auszuchecken:

```c
git clone git@github.com:jschildgen/monster-park.git
```

Wenn man selbst nicht der Eigentümer oder Mitbearbeiter des Repositories ist, kann man die Daten zwar auschecken, sie sehen und auch lokal bearbeiten, aber man kann keine Änderungen ins Repository zurückschreiben.

GitHub und GitLab haben einen eingebauen Issue-Tracker. Jeder kann dort Issues anlegen, beispielsweise um Bugs und Probleme zu melden. Issues können kommentiert werden, um eine Diskussion zu führen und Issues haben einen Zustand: Open oder Closed.