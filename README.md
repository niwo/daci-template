# Entscheidungen nach DACI

Wir nutzen den hier dokumentierten Entscheidungsfindungsprozess nach DACI, um wichtige Entscheide zu fällen.

## Warum brauchen wir Entscheidungsfindungsprozess?

Nicht-, schlecht- oder nicht nachvollziehbare Entscheidungen führen zu Konfusion und unnötigen Disskussionen die wir vermeiden wollen.  

Folgende **Ziele** verfolgen wir mit dem einheitlichen Vorgehen:

- **Nachvollziehbarkeit**: Entscheide sind auch für Teammembers die nicht in den Prozess involviert waren nachvollziehbar.
- **Transparenz**: Teammembers sind über wichtige Entscheide informiert
- **Qualität**: Durch den Prozess nehmen wir uns die nötige Zeit, um wichtige Entscheidungen im Team zu treffen.
  Dadurch können wir die Qualität und damit auch die **Akzeptanz** von Entscheidungen erhöhen.

## An welchem Vorgehensmodell orientieren wir uns?

Der Entscheidungsfindungsprozess orientiert sich an den Prinzipien des [DACI](https://www.atlassian.com/team-playbook/plays/daci) Frameworks.

Das [Open Decision Frameworks](https://github.com/red-hat-people-team/open-decision-framework/blob/v1.0.1/Open_Decision_Framework-community.pdf) von Red Hat beschreibt sehr gut,
was die Vorteile eines offene und transparenten Entscheidungsprozess sind.

Die Markdownvorlagen ist stark an die "Architectural Decision Records" aus dem [MDN](https://github.com/mdn/mdn/tree/master/ADRs) (Mozilla Developer Network) Projekt angelehnt.

## Wie kann ich eine neue Entscheidung vorschlagen?

1. Erstelle ein neues File mit dem Name in der Form `JAHR-MONAT-TAG-Entscheidungstitel`

2. Kopiere den Inhalt des [Templates](000-TEMPLATE.md) in das neue File.

3. Fülle die Vorlage mit den Details zu deinem vogeschlagenen Entscheid aus.

4. Erstelle einen Pull Request (PR) für das neue Entscheidungsfile und beteilige dich an allfälligen Diskussionen rund um den PR.

5. Das File kann, während der PR offen ist, angepasst und verbessert werden und muss nicht von Anfang an vollständig sein.  

## Wie werden eingegebene Entscheide angenommen oder abgelehnt?

- Wir setzen das DACI Framework für die Entscheidungsfindung ein, welches voraussetzt, dass Du die *Driver*, *Approver*, *Consultants* und die *Informed* Rollen für die Entscheidung bestimmst.

- Wenn Du das Entscheidungsdokument erstellst, ist es wahrscheinlich, dass Du selbst der **Driver** bist, der die Nachvorschungen anstellt und die Entscheidung treibt.

- Der **Approver** ist typischerweise eine Einzelperson die die nötige Erfahrung hat und berechtigt ist, die Entscheidung zu fällen.
  Wenn möglich ändert der *Aprover* selbst den Status des Entscheids von "Vorgeschlagen" auf "Angenommen" oder "Abgelehnt" und merged der PR.

- Das C in DACI steht für **Consultants** (oder Beteiligte oder Mitautoren). Dies sollte eine kleine Gruppe von Personen sein,
  die beim Vorschlag mitgearbeitet haben oder konsultiert wurden.
  Die "Consultants" sind auch die Personen die daran interessiert sein werden den PR zu kommentieren.

- Das I in DACI steht für **Informed**, die Leute die nicht direkt in die Entscheidungsfindung involviert, aber informiert werden müssen, sobald die Entscheidung gefällt wurde.
