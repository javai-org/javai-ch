---
title: "Compliance und KI prägen den Swiss Testing Day 2026"
date: 2026-03-26
description: "Der Swiss Testing Day 2026 stellte KI-Compliance und nicht-deterministisches Testen ins Zentrum. Referenten aus Banken, Governance und Software-Engineering diskutierten eine gemeinsame Herausforderung."
summary: "Der Swiss Testing Day 2026 machte eines deutlich: Compliance und KI sind keine getrennten Gespräche mehr. Von Bertrand Meyers Keynote über Software-Verifikation bis zum herausragenden Vortrag darüber, warum KI für Compliance nutzlos — und gleichzeitig unverzichtbar — ist, zeigte die Konferenz, dass das Testen nicht-deterministischer Systeme die zentrale Herausforderung für Qualitätsfachleute von heute darstellt."
featured_image: "images/bertrand-meyer.jpg"
featured_image_alt: "Bertrand Meyer am Swiss Testing Day 2026"
featured_image_caption: "Software Correctness Authority Bertrand Meyer"
---

Der Swiss Testing Day 2026, am 26. März in Zürich durchgeführt, brachte Tester, Quality Engineers und Compliance-Fachleute zusammen — für einen Tag voller Vorträge und Panels, die sich überwiegend mit einer Frage befassten: Was passiert, wenn KI in Systeme einzieht, die zuverlässig, überprüfbar und korrekt sein müssen?

## Software-Korrektheit trifft auf Nicht-Determinismus

Die Eröffnungs-Keynote von Bertrand Meyer — Pionier des Design-by-Contract und der Programmiersprache Eiffel — gab den Ton an. Meyer behandelte ein breites Themenspektrum, kehrte aber immer wieder zum zentralen Gedanken zurück: den Beweis, dass Software das tut, was sie verspricht. Grosse Sprachmodelle (LLMs) mit ihrem inhärenten Nicht-Determinismus haben diese Herausforderung verschärft, nicht vereinfacht.

Meyer betonte, dass die Leistung stochastischer Features — insbesondere LLMs — *gemessen* werden muss, weil ein einfaches Bestanden/Nicht-bestanden nicht ausreicht. Allerdings ging er nicht im Detail darauf ein, *wie* solche Systeme zu messen sind, sondern bekräftigte seine langjährige Überzeugung, dass Korrektheit von Grund auf in die Software eingebaut werden muss.

Er schloss mit einer optimistischen Note: Qualifizierte Software-Ingenieure werden weiterhin gebraucht, auch wenn sich ihre Werkzeuge verändern. Generierter Code muss nach wie vor verifiziert werden, und das menschliche Verständnis des Codes bleibt unverzichtbar.

## Teststrategie ist keine Liste von Zielen

Iosif Itkin forderte das Publikum auf, sorgfältig darüber nachzudenken, was Teststrategie tatsächlich bedeutet — und was nicht. Es ist keine Zielliste. Es ist auch nicht dasselbe wie Qualitätssicherung, die eine grundlegend andere Denkweise erfordert.

Unter häufigem Bezug auf das Buch *Good Strategy/Bad Strategy* lieferte Itkin eine wertvolle Erinnerung: Organisationen, die es mit KI ernst meinen, müssen ihre Teststrategie bewusst gestalten und nicht dem Zufall überlassen.

## Agentisches Testen liefert bereits Ergebnisse im Bankensektor

Ein Team aus dem Schweizer Bankensektor präsentierte «Avalon», ein agentenbasiertes System zur Generierung synthetischer Testdaten. Obwohl der Vortrag schnell in Produktdetails überging, war die Kernbotschaft klar: Es handelt sich um eine ausgeklügelte agentische Anwendung, die bereits messbare Produktivitätsgewinne liefert. Das System arbeitet transparent und zeigt LLM-Interaktionen und Tool-Aufrufe in Echtzeit über die Benutzeroberfläche an.

## Der Compliance-Vortrag des Tages

Der herausragende Beitrag war Nick Gushchins *Why AI Is Useless for Compliance …and Why You Still Need It*. Gushchin, ein AI Transformation Manager, präsentierte einen strukturierten Ansatz zum KI-Risikomanagement mittels einer Wahrscheinlichkeits-Auswirkungs-Matrix — ein bewährtes Framework, dessen Bedeutung im Zeitalter der KI nicht geringer ist, wie er betonte.

Seine zentrale Frage — wie die Dimension «Wahrscheinlichkeit» bei nicht-deterministischen Systemen zu quantifizieren ist — trifft genau die Herausforderung, die probabilistische Testframeworks adressieren wollen. Es war der erste Vortrag an der Konferenz, der das Problem des Testens von Systemen mit inhärent variablen Ausgaben explizit ansprach.

Kein Hype, kein Herumgerede — nur praktische, fundierte Orientierung für alle, die für Testen und Zuverlässigkeit in KI-gestützten Umgebungen verantwortlich sind.

## Qualität definieren in einem gefährlichen Jahrzehnt

Das Nachmittagspanel brachte Bertrand Meyer, Elmar Jürgens und Marcel Gygli zusammen, moderiert von Anne-Lea Marte, um eine täuschend einfache Frage zu diskutieren: Wie definieren wir Qualität in einer Welt, in der Systeme lernen?

Die Antworten gingen sofort auseinander. Gygli definierte Qualität danach, ob Nutzer bekommen, was sie brauchen. Jürgens widersprach: für einfache Software vielleicht — aber geschäftskritische Systeme verlangen mehr. Meyer vertrat die breiteste Sicht und bestand darauf, dass Qualität mehrdimensional ist, in den Augen aller Stakeholder liegt und über die Zeit aufrechterhalten werden muss.

Beim Thema Geschwindigkeit schlugen die Panelteilnehmer vorsichtige Töne an. Jürgens warnte vor einem Zielkonflikt, wenn Code-Generierung die Testgenerierung überholt. Gygli stellte eine schärfere Frage: Wenn 90 % des generierten Codes korrekt sind, aber die verbleibenden 10 % extrem schwer zu testen oder zu debuggen, könnte der scheinbare Geschwindigkeitsgewinn eine Illusion sein.

Die Diskussion wurde beim Thema Verantwortung pointierter. Wenn KI-Systeme Schaden verursachen, wer ist rechenschaftspflichtig? Jürgens war eindeutig: diejenigen, die die Software erstellt haben. Meyer warnte, dass sowohl KI-Hype als auch KI-Verleugnung gefährlich sind und dass Entscheidungsträger sich zu leicht von Begeisterung mitreissen lassen. Alle drei waren sich einig, dass Bildung und Regulierung unerlässlich sind, um menschliche Sicherheitsmechanismen aufrechtzuerhalten.

Auf die Frage, was in der Branche Unsinn ist, hielten die Panelteilnehmer nicht zurück. Meyer kritisierte es, Agenten die Kontrolle zu geben und Menschen als Backup einzusetzen. Gygli nahm Vibe Coding ins Visier. Jürgens bezeichnete die meisten Produktivitätsmessungsansätze als bedeutungslos.

Was sie sich für die Zukunft wünschen, darauf konvergierten die Panelteilnehmer bei der Regulierung. Gygli forderte nutzbare Regulierung, die widerspiegelt, was die Gesellschaft tatsächlich braucht. Meyer — mit dem Scherz «Amerika innoviert, China kopiert, Europa reguliert» — äusserte Hoffnung auf mehr mathematische Beweise im Testen. Jürgens hoffte, dass Meyer recht hat, merkte aber an, dass formale Methoden in der Praxis begrenzt bleiben.

## Wenn generierter Code nicht getestet werden kann

Jonas Hermansson teilte einen offenen Erfahrungsbericht über die vollständige Softwareentwicklung mit KI-Agenten. Sein Team setzt mittlerweile mehrere Agententeams mit unterschiedlichen Rollen ein — Frontend, Backend, Datenbank — und hat doppelt so viele Test-Agenten wie Entwicklungs-Agenten im Einsatz.

Die Erkenntnisse waren hart erarbeitet. Frühe Experimente mit Vibe-codiertem Code produzierten Lösungen, die praktisch nicht testbar waren. Ein generiertes Login-Feature enthielt einen Fehler, der auf eine mehrdeutige Anforderung zurückzuführen war. Ein QA-Wrapper, der die Absicht von den Anforderungen bis zum Endprodukt testete, übersah dennoch Nebenläufigkeitsfehler. Am Ende führte das Team manuelles Testen als letzte Plausibilitätsprüfung wieder ein — teuer, aber notwendig.

Die vielleicht überraschendste Erkenntnis: Hermanssons Team wartet Code überhaupt nicht mehr. Wenn etwas geändert werden muss, wird der Code von Grund auf neu generiert. Ein radikaler Arbeitsablauf, der ebenso viele Fragen aufwirft wie er beantwortet.

## Die Abschluss-Keynote: ein Aufruf zu statistischem Denken

Robert Sabourin — Akademiker und erfahrener Testing-Praktiker — hielt eine Abschluss-Keynote, die den unterschwelligen Alarmton der Konferenz als Chance umformulierte. Er griff den Gefahrenton auf, den die Organisatoren bewusst gewählt hatten, und konterte mit einer positiven Botschaft über die geschäftlichen Möglichkeiten, die sich aus dem Testen KI-gestützter Systeme ergeben.

{{< figure src="images/test-oracle.jpeg" alt="Folie über probabilistische Testorakel aus Robert Sabourins Abschluss-Keynote" caption="Robert Sabourin on the need for experiments and probabilistic testing" >}}

Am bedeutsamsten für die Themen dieser Konferenz war Sabourins explizites Plädoyer für probabilistisches Testen. Er forderte Tester auf, ein statistisches Denken zu entwickeln, und argumentierte, dass stochastische Dienste probabilistisch getestet werden müssen — nicht mit den binären Bestanden/Nicht-bestanden-Urteilen aus der deterministischen Software. Es war ein passender Abschluss eines Tages, der diese Idee wiederholt umkreist hatte, ohne sie immer direkt beim Namen zu nennen.

## Der rote Faden

Über das gesamte Tagesprogramm hinweg war ein gemeinsamer Faden unverkennbar: Die Testbranche ringt mit Systemen, die sich nicht zweimal gleich verhalten. Traditionelles Bestanden/Nicht-bestanden-Testen wurde für deterministische Software gebaut. Die heute eingesetzten Systeme — von LLM-gesteuerten Agenten bis zur Erkennung synthetischer Medien — erfordern neue Ansätze: statistische Messung, probabilistische Garantien und Governance-Rahmenwerke, die mit Unsicherheit umgehen können.

Der Swiss Testing Day 2026 zeigte, dass die Branche dies weiss. Die Frage ist nun, wie schnell die Werkzeuge und Praktiken nachziehen werden.
