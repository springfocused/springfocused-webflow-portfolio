
# springfocused™ — Portfolio Website, Rabih Haj-Hassan (IM5)

## Persönliche Reflexion

Das Erstellen meiner Website empfand ich insgesamt als sehr wertvoll, aber auch als herausfordernd.  
Ich habe viele Stunden damit verbracht, einzelne Probleme zu lösen, Bugs zu beheben oder Situationen zu bewältigen, in denen plötzlich ganze Mechaniken nicht mehr so funktionierten, wie ich es geplant hatte.

Mein grösstes Learning aus diesem Projekt ist die **Bedeutung einer sauberen Planung**.  
Ich hatte von Beginn an eine recht klare Vorstellung von der Mechanik, der Farbwelt und der Typografie meiner Website, habe es jedoch versäumt, diese Ideen vorgängig beispielsweise in Figma als strukturierten Entwurf festzuhalten. Das rächte sich im späteren Verlauf des Projekts deutlich.

Sobald das Grundgerüst stand, wurde die Frage nach dem **richtigen Inhalt** zentral:  
Welche Elemente braucht die Seite wirklich? Wo machen Bilder Sinn? Wie gross, wie positioniert, wie gewichtet?  
Da diese Entscheidungen nicht frühzeitig konzeptionell festgelegt wurden, verlor sich die Kontinuität stellenweise, und Anpassungen wurden zunehmend mühsam.

Zusätzlich führte das fehlende Namenskonzept für Klassen, Container und Abstände zu einem strukturellen Chaos.  
Ich konnte mir während der Entwicklung erlauben, mehrere Tage am Stück an der Website zu arbeiten. Mit zeitlichem Abstand wäre es sehr schwierig gewesen, einzelne Blöcke oder Layout-Entscheidungen wiederzufinden oder nachzuvollziehen.

Trotz dieser Schwierigkeiten bin ich mit dem aktuellen Stand der Website insgesamt zufrieden.  
Das Projekt hat mir klar aufgezeigt, wie wichtig Organisation, saubere Benennung und vorgängige Planung sind – insbesondere bei komplexeren Layout- und Scroll-Mechaniken.

Die Website ist bewusst **noch nicht abgeschlossen**.  
Der Call-to-Action zur Kontaktaufnahme ist aktuell schwach ausgeprägt, und auch inhaltlich gibt es Optimierungspotenzial. Für die Abgabe im Rahmen von IM5 soll dieser Stand jedoch genügen. Ich plane, die Website weiterzuentwickeln und strukturell zu verfeinern.

Ich bin mir bewusst, dass die Website nicht mit WordPress umgesetzt wurde, obwohl dies Teil der Aufgabenstellung war. Diese Entscheidung wird weiter unten begründet. Für Rückfragen oder eine genauere Erklärung einzelner Schritte stehe ich jederzeit zur Verfügung.

---

## Projektübersicht

Dieses Repository dokumentiert die Portfolio-Website von **Rabih Haj-Hassan (springfocused™)**.  
Die Website dient der Präsentation meiner Arbeit als Creative Producer mit Fokus auf Fotografie, Videografie und Storytelling.

Primär handelt es sich um eine **Personal-Brand-Website**, die potenziellen Kund:innen ermöglicht, sich ein Bild meiner Arbeitsweise, meiner Projekte und meiner gestalterischen Haltung zu machen. Sekundär dient die Website bestehenden Kund:innen als Anlaufstelle, um beispielsweise Galerien wiederzufinden.

Die Nutzung der Website erfolgt überwiegend unterstützend, da die meisten Anfragen über Social Media oder persönliche Empfehlungen entstehen. Dennoch war das Projekt eine gute Gelegenheit, im Rahmen von IM5 eine professionelle Website umzusetzen.

---

## Ziel des Projekts

- Aufbau einer seriösen, professionellen Online-Präsenz
- Klare Darstellung meiner Leistungen als Freelancer
- Präsentation ausgewählter Arbeiten und Referenzen zur Vertrauensbildung
- Bereitstellung einer zentralen Kontaktmöglichkeit
- Umsetzung eines technisch und gestalterisch anspruchsvollen Webprojekts

---

## Seitenstruktur & Aufbau

Die Website ist als **Onepager** umgesetzt und besteht aus folgenden Sektionen:

- Hero (Showreel)
- What I Do
- Conception
- Production
- Work
- Behind the Scenes (BTS)
- References
- Contact

In der Desktop-Version wird die Seite horizontal gescrollt, angelehnt an eine filmische Erzählweise.  
Eine dynamische Label-Leiste (Labels) sowie eine kontextabhängig hervorgehobene Navigation unterstützen die Orientierung innerhalb der Seite.

Für Tablet- und Mobile-Ansichten wurde bewusst auf angepasste Mechaniken gesetzt, um die Bedienbarkeit und Verständlichkeit sicherzustellen.

---

## Technologie & Umsetzung

- **Webflow** für Layout, Struktur, Interaktionen und Publishing
-  **HTML / CSS / JavaScript**
- Exportierter Code zur Dokumentation über **GitHub**

Der Webflow-Code wurde exportiert und im Repository abgelegt.  
Ein automatischer Versionsverlauf wie bei einer klassischen Codebase ist aufgrund der Plattform nicht möglich.

---

## Projektverlauf & Prozessdokumentation

Der Entwicklungsprozess der Website erfolgte über mehrere Wochen hinweg.  
Dabei wurden unterschiedliche technische Ansätze getestet, verworfen und neu bewertet. Der zeitliche Verlauf lässt sich grob wie folgt zusammenfassen:

- **23.10.2025**  
  Erster Versuch, die Website mit WordPress aufzusetzen.  
  In diesem Zusammenhang traten früh Probleme beim Domain-Transfer von Namecheap (dort war meine Domain angelegt gewesen) zu Hostpoint auf, da Hosting und Domain bewusst am selben Ort gebündelt werden sollten.

- **26.10.2025**  
  Erfolgreicher Abschluss des Domain-Transfers und Installation von WordPress auf dem Hostpoint-Server.

- **10.11.–13.11.2025**  
  Erstellung eines Child-Themes basierend auf dem Theme *Recluse*.  
  Aufbau der Seite mit Elementor sowie mehreren Plugins gemäss Schulempfehlung.  
  Mehrere Versuche, die gewünschte horizontale Scroll-Mechanik umzusetzen, führten jedoch zu keinem zufriedenstellenden Resultat.  
  Die bestehende Theme-Struktur erwies sich als einschränkend und erforderte zahlreiche Umgehungslösungen.  
  In dieser Phase wurde auch ein GitHub-Repository erstellt und erste technische Grundlagen (Plugins, Sicherheit, Struktur) umgesetzt.

- **01.01.2026**  
  Fortsetzungsversuch mit WordPress.  
  Aufgrund zunehmender Frustration und mangelnder gestalterischer Kontrolle entschied ich mich, alternative Tools zu evaluieren.  
  Erste Tests und Versuche von Webflow.

- **02.01.2026**  
  Bewusste Entscheidung, das Projekt nicht weiter in WordPress zu verfolgen.  
  Umstieg auf Webflow, erneuter Domain-Transfer und Aufbau eines neuen Onepagers mit horizontaler Scroll-Mechanik.

- **03.01.2026**  
  Umsetzung der Navigationslogik inklusive Label-Raster, interaktiver Navbar und visueller Hervorhebung der jeweils aktiven Sektion.

- **04.01.2026**  
  Erstellung eines kleinen Styleguides in Milanote (Logo, Farben, Typografie), um visuelle Entscheidungen zu konsolidieren.

- **05.01.2026**  
  Responsive Anpassungen:  
  Umstellung der Scroll-Mechanik von horizontal (Desktop) auf vertikal (Tablet & Mobile), inklusive Optimierung der Nutzerführung.

- **06.01.2026**  
  Erstellung der Privacy Policy sowie Integration eines Cookie-Hinweises.  
  Erstellung und Einbindung des Favicons.

- **07.01.2026**  
  Inhaltliche Arbeit an den einzelnen Sektionen der Website.  
  Verfassen von Texten für Inhalte sowie SEO-relevante Metadaten.

- **08.01.2026**  
  Schnitt eines kurzen Showreels aus bestehendem Videomaterial für die Hero-Sektion.  
  Vereinheitlichung und Aufbereitung von Kundenlogos in Photoshop.  
  Veröffentlichung der Website sowie Anbindung an die Google Search Console und Einreichung der Sitemap.

- **09.01.2026**  
  Ergänzung weiterer Bilder, Verlinkung von Projekten, Feinjustierung des Layouts und Erweiterung von Hover- und Interaktionseffekten.  
  Zusätzliche Optimierungen für Responsive-Ansichten.

---

## Begründung: WordPress → Webflow

Die ursprüngliche Aufgabenstellung sah vor, die Website entweder vollständig selbst zu programmieren oder mit WordPress umzusetzen.  
Ich habe zu Beginn versucht, mit WordPress zu arbeiten und verfüge über grundlegende Erfahrung damit. Nach mehreren Ansätzen entschied ich mich jedoch bewusst für Webflow.

Die Hauptgründe dafür waren:

- **Volle gestalterische Kontrolle** ohne gegen ein bestehendes Theme oder Child-Theme arbeiten zu müssen
- Die geplante **horizontale Scroll-Mechanik** wäre in WordPress nur mit erheblichem Zusatzaufwand oder Plugins umsetzbar gewesen
- Ich wollte **nicht für jede Funktion ein Plugin einsetzen**, um Abhängigkeiten, Wartungsaufwand und Komplexität zu reduzieren
- Webflow ermöglichte mir, Struktur und Layout visuell präzise zu steuern, ohne den Überblick über verschachtelte Container und Divs zu verlieren
- Als visuell denkender Mensch konnte ich Änderungen unmittelbar sehen und iterativ weiterentwickeln
- Die Website-Struktur und das finale Layout wurden zwar technisch (HTML/CSS-Denken) erarbeitet, jedoch effizient über die Webflow-Oberfläche umgesetzt

Mir ist bewusst, dass Webflow nicht explizit Teil der Aufgabenstellung war.  
Ich bin jedoch der Überzeugung, dass die erlernten Kompetenzen – Strukturdenken, Layout-Logik, Responsive Design, SEO-Grundlagen, Datenschutz, technische Umsetzung – mindestens gleichwertig, wenn nicht vertiefter, angewendet wurden als mit WordPress.

---

## SEO & Indexierung

- Individuelle Meta Titles und Meta Descriptions
- Open-Graph-Tags für Social Sharing
- Saubere Seitenstruktur (Onepager)
- Automatisch generierte Sitemap
- Google Search Console angebunden
- Sitemap eingereicht und Indexierung manuell angestossen

---

## Datenschutz & Cookies

Die Website verwendet ausschliesslich **technisch notwendige Cookies**.  
Es werden keine Analyse-, Marketing- oder Tracking-Tools eingesetzt.

Transparenz wird über:
- eine Privacy Policy
- einen minimalen Cookie-Hinweis

gewährleistet.  
Ein komplexes Consent-Management-System wurde bewusst nicht implementiert, da es im aktuellen Setup nicht erforderlich ist.

---
