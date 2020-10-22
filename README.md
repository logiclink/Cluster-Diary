# Bekämpfung von Superspreading während der COVID-19-Pandemie
Mittlerweile haben wir Herbst 2020 und die Infektionszahlen mit SARS-CoV-2 in Europa gehen steil nach oben. Haupttreiber der Infektionen sind Superspreading-Ereignisse<sup>[1](#f1)</sup>, die sich aus der Überdispersion der Corona-Infektionen ergeben. Die bisherigen Eindämmungsmaßnahmen, wie die AHA-Regeln<sup>[2](#f2)</sup> (Abstand, Hygiene und Atemschutzmasken), haben im Sommer für ein geringes Infektionsaufkommen gesorgt. Diese Maßnahmen scheinen jetzt im Herbst nicht mehr auszureichen und die täglichen Infektionszahlen steigen rapide an.

Bereits im Sommer war ein solches diffus steigendes Infektionsgeschehen für den Herbst absehbar<sup>[3](#f3)</sup>, dass sich aus der Perkolation<sup>[4](#f4)</sup> von Superspreading-Ereignissen ergibt und für ein exponentielles Wachstum der Infektionszahlen sorgt. Kontakt- und Reiseverbote reduzieren zwar die Wahrscheinlichkeit der direkten Infektion zwischen Personen, unterbrechen jedoch nicht die Kette der treibenden Superspreading-Ereignisse, sofern diese Ereignisse nicht durch Kontaktverbote explizit verhindert werden. Das Verbot solcher Ereignisse im öffentlichen und privaten Raum käme jedoch einem landesweiten Lockdown gleich. Dagegen würden eine gezielte Nachverfolgung von Superspreading-Ereignissen vorhandene Ressourcen auf die treibenden Infektionsereignisse der Pandemie konzentrieren und so einen Lockdown weiter hinauszögern.

Zur Nachverfolgung von Superspreading-Ereignissen wäre ein individuelles Kontakttagebuch sehr hilfreich und wurde von Prof. Dr. Drosten bereits Anfang August in einem Gastbeitrag der Zeit<sup>[3](#f3)</sup> vorgeschlagen. In diesem Tagebuch sollten alle Ereignisse mit Datum dokumentiert werden, die möglicherweise ein Superspreading-Ereignis sein könnten.

## Superspreading-Ereignisse
Für ein Superspreading-Ereignis müssen zwei Dinge zusammenkommen: Eine größere Gruppe von Personen in einem Innenraum, möglichst ohne Maske, die eine hohe und möglichst tiefe Atmung haben. Als Zweites muss ein Infizierter mit einer hohen Viruslast in dieser Gruppe anwesend sein.

Beispiele für potentielle Superspreading-Ereignisse sind z.B. Essen mit Freunden, Familienfeiern, Restaurant- oder Café-Besuche im privaten Bereich. In der Freizeit können dies Sport-Kurse, Fitness-Studiobesuche, Skat-, Kegel- oder Bowling-Runden, sowie Volkshochschulkurse sein. Ebenso kann es bei einem Friseur oder bei Meetings und in der Kantine zu potentiellen Superspreading-Ereignissen kommen. Auch außerhalb von Innenräumen kommt es schon mal zu Situationen mit Gedränge. Ebenso können kritische Situationen im privaten Pkw, in Bussen, Bahnen und im Flugverkehr auftreten.

## Cluster-Tagebuch

Ziel eines Cluster-Tagebuchs ist die Dokumentation genau dieser Ereignisse<sup>[5](#f5)</sup>. Da erst im Nachhinein bekannt wird, ob ein Infizierter anwesend war, sollten in einem Cluster-Tagebuch mögliche Superspreading-Ereignisse und ihrer Teilnehmer dokumentiert werden. Es ist daher nicht notwendig alle Kontakte eines Tages in einem solchen Tagebuch zu hinterlegen. Zusätzlich können alle Kontakte aus dem gleichen Haushalt und tägliche Kontakte am Arbeitsplatz entfallen, da diese schnell aus dem Gedächtnis aufgelistet werden können.

Nach dem Bekanntwerden einer Infektion kann dann das Cluster-Tagebuch des Betreffenden verwendet werden, um potentielle Superspreading-Ereignisse im infektiösen Zeitraum zu identifizieren und die betreffenden Personen zu isolieren. Dies kann z.B. durch die örtlichen Gesundheitsämter erfolgen, wenn Sie das Cluster-Tagebuch des Infizierten auswerten.

![Superspreading-Ereigniss und infizierte Personen](https://raw.githubusercontent.com/logiclink/Cluster-Diary/main/Cluster-Infektionen.svg?sanitize=true)
<p style="text-align: center;"><sup>Superspreading-Ereigniss und infizierte Personen</sup></p>

Es wäre sehr sinnvoll, ein solches Tagebuch elektronisch zu führen, da dann manuelle Kontaktdaten nicht mühsam entziffert werden müssten und die Daten transportabel sind, um sie z.B. einem Gesundheitsamt schnell per Mail zur Verfügung zu stellen. Neben Telefonnummern sollten auch E-Mail-Adressen zur einfacheren Kontaktaufnahme vermerkt werden.

Eine kurze Marktanalyse brachte leider keine brauchbare Software für diesen Zweck hervor. Die CORONA Warn-App des RKI ist auf eine Einzelkontaktverfolgung ausgelegt und kann keine Superspreading-Ereignisse erkennen. Manuelle Erfassung, wie Sie z.B. [coronika](https://www.coronika.app/) für Android oder [Cluster Diary](https://apps.apple.com/de/app/cluster-diary/id1535388491) für iOS bieten, sind entweder nicht auf allen Plattformen erhältlich oder für eine Beurteilung von Superspreading-Ereignissen zu einfach gestrickt.

## Cluster-Tagebuch als Excel-Datei
Da die Entwicklung einer App recht aufwendig ist und ein Tagebuch für Superspreading-Ereignisse möglichst schnell zur Verfügung stehen sollte, haben wir uns für eine einfache Excel-Liste entschieden, dies Sie hier auf [Github](https://github.com/logiclink/Cluster-Diary) in der [neuesten Version](https://github.com/logiclink/Cluster-Diary/raw/main/Cluster-Tagebuch.xlsx) finden.

Neben dem Datum und einer Textbeschreibung wird ein mögliches Superspreading-Ereignis anhand von Dauer, getragener Maske, Innenraum, Abstand zu anderen Personen, Tätigkeit, Lüftung und vorhandener Kontaktliste charakterisiert. Dabei haben wir am Kontaktmanagement<sup>[6](#f6)</sup> des RKI orientiert.

Zu jedem möglichen Superspreading-Ereignis können ein oder mehrere Kontakte mit Telefonnummer und E-Mail-Adresse hinterlegt werden. Im Zweifelsfall reicht hier auch ein allgemeiner Kontakt von dem aus dann eine Kontaktliste angefordert werden kann.
Das Führen eines solchen Cluster-Tagebuchs ist immer noch Arbeit. Allerdings hat mich das Nachtragen einer Woche gerade mal 10 Minuten gekostet. Wenn die Excel-Liste auf einem Cloud-Verzeichnis liegt können Ereignisse auch über Smartphone überall nachgetragen werden. Der Datenschutz kann z.B. über eine Verschlüsselung mit [Boxcryptor](https://www.boxcryptor.com/de/) gewährleistet werden.

Fragen oder Anregungen zur Excel-Datei, neue Beispiele für Superspreading-Ereignisse und weitere Ergänzungen können Sie mir entweder direkt [zumailen](mailto://info@logiclink.de) oder als [Eintrag](https://github.com/logiclink/Cluster-Diary/issues) bei Github hinterlassen.

<b><i>Es liegt an uns, ob wir uns die Mühe machen, SARS-CoV-2 die Stirn zu bieten!</i></b>

<a name="f1">1.</a> Mehr zu Superspreading unter https://de.wikipedia.org/wiki/Superspreading <br/>
<a name="f2">2.</a> AHA Regeln siehe https://www.infektionsschutz.de/coronavirus/alltag-in-zeiten-von-corona.html  <br/>
<a name="f3">3.</a> https://www.zeit.de/2020/33/corona-zweite-welle-eindaemmung-massnahmen-christian-drosten/komplettansicht  <br/>
<a name="f4">4.</a> Weitere Informationen zur Perkolation unter https://de.wikipedia.org/wiki/Perkolationstheorie  <br/>
<a name="f5">5.</a> CORONAVIRUS-Update Folge 54 https://www.ndr.de/nachrichten/info/coronaskript222.pdf  <br/>
<a name="f6">6.</a> Ausführliche Informationen zum Kontaktmanagement des RKI finden Sie hier https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Kontaktperson/Management.html