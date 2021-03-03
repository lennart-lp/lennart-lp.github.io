# Lennart LP-Webseite
`https://lennart-lp.github.io`

[Klicke hier, um zur Webseite zu gelangen](https://lennart-lp.github.io)

## Die Lennart LP Webseite besteht vor allem aus diesen Seiten:
* [Links zu Social Media Kanälen](https://lennart-lp.github.io/links.html)
* [PC-Konfigurations Tipps](https://lennart-lp.github.io/pc-konfigurationen.html)
* [PC-Komponenten Erklärungen](https://lennart-lp.github.io/pc-erklaerungen.html)
* [Lennart LP Setup](https://lennart-lp.github.io/setup.html)

## Rollen

* Autor: Lennart
* Hauptentwickler: Luca
* Entwickler: Lennart
* Planung und Organisation: Luca

(C) Lennart LP 2021

## Dateihierarchie

* *Alle Hauptseiten*
* pc-konfigurationen
  * *Alle PC-Konfigurationen*
* a
  * img
     * *Alle Bilder*
  * fls
    * ical
      * *Alle iCal-Dateien*  
    * pdf
      * *Alle PDF-Dateien*  

## Dateiennamensschema

Allgemein: Umlaute werden ausgeschrieben. Daten werden im Format YYYY-MM-DD geschrieben. Wiederholende Dateien werden `YYYY-MM-DD_##`genannt, um eine sortierte Auflistung zu gewährleisten.

HTML-Seiten werden kleingeschrieben. Leerzeichen werden durch Minusse ersetzt:
`beispiel-html-seite.html `

Dateinamen können großgeschrieben werden. Leerzeichen werden durch Minusse ersetzt:
`Beispiel-Bild.webP`

Ordnernamen werden kleingeschrieben. Leerzeichen werden durch Minusse ersetzt:
`/beispiel-ordner`

Dateienordnernamen werden kleingeschrieben und abgekürzt:
`/fldr`

Interne Dateien oder Ordner und Testdateien werden in Camel Case geschrieben. Es gibt keine Wortabgrenzungen. Vor und nach dem Namen kommt ein Unterstrich:
`_testBeispielHTMLSeite_.html`

## Dateien

### Webseiten:

Webseiten werden in HTML (`.html`) geschrieben. Das Design wird in CSS (`.css`) geschrieben. 

### Bilder

Bilder werden in webP (`.webP`) oder JPEG (`.jpeg`) gespeichert. Teiltransparente Bilder werden in PNG (`.png`) gespeichert.

Zu vermeiden sind GIF (`.gif`) und HEIC (`.heic`), sowie andere Formate. 

Vorsicht: Manche Browser und Browserversionen unterstützen webP nicht. 

### Kalenderereignisse

Kalenderereignisse werden im iCalendar-Format (`.ical`) verfasst. Benutze [diese](https://ical.marudot.com) Webseite.

## CSS-Klassenbenennung

CSS-Klassen werden kleingeschrieben. Leerzeichen werden durch Minusse ersetzt. Die Klassen sollten sich im Singular auf eine Entität beziehen, anstatt im Plural alle Objekte zu bezeichnen: `main list-item`

Falsch wären: `main-content List list-items`

Individuelle Klassen sollten auf Minusse, beziehungsweise auf mehrere Wörter verzichten. Mehrwörtige Klassen sollten nur für Child-Parent-Beziehungen benutzt werden, d.h. ein Parent vererbt einem Child den ganzen Klassennamen, das Child fügt am Ende eine Objektbezeichnung hinzu. Beispiel:
* `list`
  * `list-item`
    * `list-item-image`
    * `list-item-title`
    * `list-item-text` 
