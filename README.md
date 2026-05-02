# HTML-FUCKUP
 (Tutorial/s)

 # **0. Die zwei Grundformen von HTML‑Elementen**

**1. Paariges Element (mit Inhalt)**  
<element> ... </element>

**2. Unpaariges Element (ohne Inhalt)**  
<element>


# **1. Die zwei Grundformen von HTML‑Elementen (erweitert)**

**1. Paarige Elemente:**  
<tag attribut="wert">Inhalt</tag>

**2. Unpaarige Elemente:**  
<tag attribut="wert">


# **2. Was du bei BEIDEN Formen lernen kannst (universelle Mechanismen)**

• **Tagname**  
• **Attribute**  
• **Attributwerte**  
• **Globale Attribute**  
• **Event-Attribute**  
• **DOM-Verhalten**  
• **Kategorien** (Block, Inline, Flow, Phrasing, Interactive)  
• **Inhaltstypen** (Text, HTML, Phrasing Content, Flow Content)  
• **Parsing-Regeln**  
• **Verschachtelungsregeln**  


# **3. Was du speziell bei paarigen Elementen lernen kannst**

• **Inhaltstypen** (Text, HTML, andere Elemente)  
• **Verschachtelung** (welche Elemente dürfen in welchen stehen)  
• **Semantik** (z. B. <h1> = Überschrift, <p> = Absatz)  
• **DOM-Struktur** (Parent, Child, Sibling)  
• **Rendering-Regeln** (Block vs Inline)  
• **CSS-Interaktion** (display, margin, padding, etc.)

**Beispiele:**  
<div class="box">Text</div>  
<p id="intro">Hallo</p>  
<h1 data-level="1">Titel</h1>


# **4. Was du speziell bei unpaarigen Elementen lernen kannst**

• **Void-Element-Regeln** (kein End-Tag erlaubt)  
• **Attribut-basierte Steuerung** (z. B. <img src="...">)  
• **Selbstschließende Syntax** (optional)  
• **Browser-Parsing ohne Inhalt**

**Beispiele:**  
<br>  
<img src="bild.png" alt="Beschreibung">  
<meta charset="utf-8">  
<input type="text" placeholder="Name">


# **5. Die universellen Attribute (für ALLE Elemente)**

**id**  
**class**  
**style**  
**title**  
**lang**  
**dir**  
**hidden**  
**tabindex**  
**accesskey**  
**draggable**  
**contenteditable**  
**spellcheck**  
**data-***  

**Beispiele:**  
<div id="box" class="red" data-info="123"></div>  
<br class="spacer">  
<img src="x.png" draggable="false">


# **6. Die universellen Event‑Attribute (für ALLE Elemente)**

**onclick**  
**ondblclick**  
**onmouseover**  
**onmouseout**  
**onchange**  
**oninput**  
**onfocus**  
**onblur**  
**onkeydown**  
**onkeyup**  
**onload**

**Beispiele:**  
<h1 onclick="alert('Hi')">Titel</h1>  
<input oninput="console.log(this.value)">  
<img src="x.png" onload="init()">


# **7. Die universellen Strukturregeln**

• **Jedes Element hat einen Tag-Namen**  
• **Jedes Element kann Attribute haben**  
• **Jedes Element ist ein DOM-Knoten**  
• **Jedes Element hat eine Kategorie** (Flow, Phrasing, etc.)  
• **Jedes Element hat erlaubte Eltern**  
• **Jedes Element hat erlaubte Kinder** (außer Void)  
• **Jedes Element hat CSS-Display-Standardwerte**  


# **8. Kurzfassung der Meta-Ebene**

1. **Tagname**  
2. **Attribute**  
3. **Globale Attribute**  
4. **Event-Attribute**  
5. **DOM-Struktur**  
6. **Kategorien**  
7. **Inhaltstypen**  
8. **Verschachtelungsregeln**  
9. **Parsing-Regeln**  
10. **Rendering-Regeln**  


# **9. Alle paarigen HTML‑Elemente (<...>...</...>)**

**a**  
**abbr**  
**address**  
**article**  
**aside**  
**audio**  
**b**  
**bdi**  
**bdo**  
**blockquote**  
**body**  
**button**  
**canvas**  
**caption**  
**cite**  
**code**  
**colgroup**  
**data**  
**datalist**  
**dd**  
**del**  
**details**  
**dfn**  
**dialog**  
**div**  
**dl**  
**dt**  
**em**  
**fieldset**  
**figcaption**  
**figure**  
**footer**  
**form**  
**h1**  
**h2**  
**h3**  
**h4**  
**h5**  
**h6**  
**head**  
**header**  
**html**  
**i**  
**iframe**  
**ins**  
**kbd**  
**label**  
**legend**  
**li**  
**main**  
**map**  
**mark**  
**menu**  
**meter**  
**nav**  
**noscript**  
**object**  
**ol**  
**optgroup**  
**option**  
**output**  
**p**  
**picture**  
**pre**  
**progress**  
**q**  
**rp**  
**rt**  
**ruby**  
**s**  
**samp**  
**script**  
**section**  
**select**  
**small**  
**span**  
**strong**  
**style**  
**sub**  
**summary**  
**sup**  
**table**  
**tbody**  
**td**  
**template**  
**textarea**  
**tfoot**  
**th**  
**thead**  
**time**  
**title**  
**tr**  
**u**  
**ul**  
**var**  
**video**  


# **10. Alle unpaarigen HTML‑Elemente (<...>)**

**area**  
**base**  
**br**  
**col**  
**embed**  
**hr**  
**img**  
**input**  
**link**  
**meta**  
**param**  
**source**  
**track**  
**wbr**

---

# 1. Die zwei Grundformen von HTML‑Elementen

1. **Tagname:** `<element>` ist der Platzhalter für jeden gültigen HTML‑Tagnamen.  
2. **Attribute:** Grundform ohne Attribute, reine Struktur: `<element>…</element>` und `<element>`.  
3. **Globale Attribute:** Denkbar, aber in der Minimalform noch nicht eingesetzt.  
4. **Event‑Attribute:** Noch nicht sichtbar, aber an jedem `<element>` möglich (`onclick`, …).  
5. **DOM‑Struktur:** Paarig = Knoten mit Inhalt; unpaarig = Knoten ohne Inhalt.  
6. **Kategorien:** Beide Formen können beliebigen Kategorien angehören (Block, Inline, …).  
7. **Inhaltstypen:** Nur die paarige Form kann Inhalt tragen (`…`‑Bereich).  
8. **Verschachtelungsregeln:** Nur relevant für die paarige Form (welche Kinder im `…` erlaubt sind).  
9. **Parsing‑Regeln:** Parser erkennt Start‑ und End‑Tag bzw. einzelnes Tag als Knoten.  
10. **Rendering‑Regeln:** Paarige Elemente erzeugen Boxen mit Inhalt, unpaarige nur ihren Effekt (z. B. Zeilenumbruch).

---

# 2. Die erweiterten Grundformen (mit Attributen)

1. **Tagname:** `<tag>` steht für einen konkreten Namen wie `div`, `p`, `img`.  
2. **Attribute:** Syntax: `<tag attribut="wert">…</tag>` bzw. `<tag attribut="wert">`.  
3. **Globale Attribute:** Jedes `tag` kann `id`, `class`, `style`, `data-*` usw. tragen.  
4. **Event‑Attribute:** Jedes `tag` kann `onclick`, `oninput`, … enthalten.  
5. **DOM‑Struktur:** Attribute verändern Eigenschaften des Knotens, nicht seine Existenz.  
6. **Kategorien:** Unabhängig von Attributen bleibt die Kategorie des Elements gleich.  
7. **Inhaltstypen:** Attribute beeinflussen Inhalt nicht direkt, nur Interpretation (z. B. `type` bei `<input>`).  
8. **Verschachtelungsregeln:** Attribute ändern die erlaubten Kinder nicht.  
9. **Parsing‑Regeln:** Parser liest Tagname, dann Attributliste, dann ggf. Inhalt.  
10. **Rendering‑Regeln:** Attribute steuern Darstellung/Verhalten (z. B. `hidden`, `style`, `src`, `href`).

---

# 3. Universelle Mechanismen aller HTML‑Elemente

1. **Tagname:** Jedes Element wird über seinen Tagnamen identifiziert.  
2. **Attribute:** Jedes Element kann eine Liste von Attributen besitzen.  
3. **Globale Attribute:** Einheitlicher Satz, der für alle Elemente gültig ist.  
4. **Event‑Attribute:** Einheitlicher Mechanismus, um Ereignisse an jedem Element zu binden.  
5. **DOM‑Struktur:** Alle Elemente sind Knoten im DOM‑Baum mit Eltern, Kindern, Geschwistern.  
6. **Kategorien:** Jedes Element gehört zu einer oder mehreren Inhaltskategorien.  
7. **Inhaltstypen:** Jedes Element definiert, welche Inhalte es enthalten darf.  
8. **Verschachtelungsregeln:** Regeln bestimmen, welche Elemente in welchen erlaubt sind.  
9. **Parsing‑Regeln:** Einheitliche Regeln, wie Tags in DOM‑Knoten übersetzt werden.  
10. **Rendering‑Regeln:** Browser leiten aus Kategorie und Standard‑CSS die Darstellung ab.

---

# 4. Mechanismen paariger Elemente

1. **Tagname:** Paarige Elemente haben immer `<tag>` und `</tag>`.  
2. **Attribute:** Attribute stehen im Start‑Tag und beeinflussen das gesamte Element.  
3. **Globale Attribute:** Können immer im Start‑Tag verwendet werden.  
4. **Event‑Attribute:** Binden Verhalten an das gesamte Element und seinen Inhalt.  
5. **DOM‑Struktur:** Start‑Tag erzeugt Knoten, End‑Tag schließt ihn; Inhalt wird Kind dieses Knotens.  
6. **Kategorien:** Paarige Elemente können z. B. Flow, Phrasing, Sectioning, … sein.  
7. **Inhaltstypen:** Definieren, welche Kinder im Inneren erlaubt sind (Text, Inline, Block, …).  
8. **Verschachtelungsregeln:** Bestimmen, welche Elemente in welchen Kontexten gültig sind.  
9. **Parsing‑Regeln:** Parser hält einen offenen Stack von Start‑Tags und schließt beim End‑Tag.  
10. **Rendering‑Regeln:** Paarige Elemente erzeugen visuelle Container mit Inhalt (Box‑Modell).

---

# 5. Mechanismen unpaariger Elemente

1. **Tagname:** Unpaarige Elemente haben nur ein `<tag>` ohne `</tag>`.  
2. **Attribute:** Alle Steuerung erfolgt über Attribute im einzigen Tag.  
3. **Globale Attribute:** Auch hier vollständig nutzbar (`id`, `class`, …).  
4. **Event‑Attribute:** Ereignisse können direkt am unpaarigen Element hängen (`<img onload="…">`).  
5. **DOM‑Struktur:** Ein einzelner Knoten ohne Kinder (Void‑Element).  
6. **Kategorien:** Meist Phrasing/Embedded/Metadata, je nach Elementtyp.  
7. **Inhaltstypen:** Kein eigener Inhalt erlaubt; nur Attribute.  
8. **Verschachtelungsregeln:** Bestimmen, wo das Element stehen darf (z. B. im Flow‑Content).  
9. **Parsing‑Regeln:** Parser erzeugt sofort einen abgeschlossenen Knoten ohne weiteren Inhalt.  
10. **Rendering‑Regeln:** Wirkung ist direkt (z. B. Bild, Zeilenumbruch, Meta‑Info), keine Innenstruktur.

---

# 6. Universelle Attribute

1. **Tagname:** Unabhängig vom Tagnamen sind globale Attribute verfügbar.  
2. **Attribute:** `id`, `class`, `style`, `title`, `lang`, `dir`, `hidden`, `tabindex`, …  
3. **Globale Attribute:** Einheitlicher Satz, der für alle Elemente gilt.  
4. **Event‑Attribute:** Zählen funktional zu den Attributen, sind aber verhaltensbezogen.  
5. **DOM‑Struktur:** Attribute verändern Eigenschaften des Knotens (z. B. Identität, Stil, Rolle).  
6. **Kategorien:** Attribute ändern die Kategorie nicht, können aber semantische Rolle beeinflussen (ARIA).  
7. **Inhaltstypen:** Attribute beeinflussen Inhalt indirekt (z. B. `contenteditable`).  
8. **Verschachtelungsregeln:** Attribute ändern die erlaubte Verschachtelung nicht.  
9. **Parsing‑Regeln:** Einheitliche Syntax: `name="wert"`; Reihenfolge beliebig.  
10. **Rendering‑Regeln:** Viele Attribute wirken direkt auf Darstellung/Interaktion (`hidden`, `style`, `class`).

---

# 7. Universelle Event‑Attribute

1. **Tagname:** Jedes Element kann Event‑Attribute tragen, unabhängig vom Namen.  
2. **Attribute:** `onclick`, `oninput`, `onload`, `onfocus`, … sind spezielle Attribute.  
3. **Globale Attribute:** Event‑Attribute sind quasi „globale Verhaltens‑Attribute“.  
4. **Event‑Attribute:** Binden JavaScript‑Code an Ereignisse des Elements.  
5. **DOM‑Struktur:** Ereignisse propagieren im DOM (Capturing/Bubbling).  
6. **Kategorien:** Bestimmen, welche Events typischerweise auftreten (z. B. `oninput` bei Formularen).  
7. **Inhaltstypen:** Ereignisse können vom Inhalt ausgelöst werden (z. B. Klick auf Text im Element).  
8. **Verschachtelungsregeln:** Ereignisse können von Kind‑Elementen nach oben „blubbern“.  
9. **Parsing‑Regeln:** Event‑Attribute werden wie normale Attribute geparst, Inhalt ist JS‑Code.  
10. **Rendering‑Regeln:** Beeinflussen Darstellung nur indirekt (z. B. durch JS‑Klassenwechsel).

---

# 8. Universelle Strukturregeln

1. **Tagname:** Bestimmt Position und Rolle im DOM‑Baum.  
2. **Attribute:** Können Struktur annotieren (z. B. `id` für Anker, `role` für Semantik).  
3. **Globale Attribute:** Unterstützen Struktur (z. B. `hidden` blendet Knoten aus).  
4. **Event‑Attribute:** Interaktion mit der Struktur (z. B. Klick öffnet/klappt Bereiche).  
5. **DOM‑Struktur:** Eltern‑/Kind‑Beziehungen, Geschwister, Dokumentwurzel (`<html>`).  
6. **Kategorien:** Steuern, wo ein Element im Flow stehen darf.  
7. **Inhaltstypen:** Definieren, welche Kinder strukturell erlaubt sind.  
8. **Verschachtelungsregeln:** Verhindern ungültige Strukturen (z. B. `<p>` darf kein `<div>` enthalten).  
9. **Parsing‑Regeln:** Reparaturregeln des Browsers bei fehlerhafter Struktur.  
10. **Rendering‑Regeln:** Struktur bestimmt Layout‑Fluss, Block‑/Inline‑Verhalten, Hierarchie.

---

# 9. Meta‑Ebene der HTML‑Struktur

1. **Tagname:** Abstrakte Sicht: Tagnamen sind nur Symbole für Rollen im Dokument.  
2. **Attribute:** Metadaten, Steuerung, Semantik, Verhalten – alles über Attribute kodierbar.  
3. **Globale Attribute:** Einheitliche Meta‑Schicht über allen Elementen.  
4. **Event‑Attribute:** Verknüpfen Struktur mit Verhalten (DOM + JS).  
5. **DOM‑Struktur:** HTML als Baummodell, Grundlage für jede weitere Verarbeitung.  
6. **Kategorien:** Meta‑Klassifikation von Elementen (Flow, Phrasing, Sectioning, …).  
7. **Inhaltstypen:** Meta‑Definition, welche Inhalte wo erlaubt sind.  
8. **Verschachtelungsregeln:** Formale Grammatik der Dokumentstruktur.  
9. **Parsing‑Regeln:** Übergang von Text (HTML‑Quellcode) zu Baum (DOM).  
10. **Rendering‑Regeln:** Übergang von Baum zu visueller/akustischer Darstellung.

---

# 10. Alle paarigen und unpaarigen HTML‑Elemente

1. **Tagname:** Konkrete Liste aller Tagnamen (paarig und unpaarig).  
2. **Attribute:** Jedes dieser Elemente kann Attribute tragen, viele haben spezielle Attribute.  
3. **Globale Attribute:** Für alle auf der Liste gültig.  
4. **Event‑Attribute:** Für alle auf der Liste nutzbar.  
5. **DOM‑Struktur:** Paarige Elemente = Knoten mit Inhalt; unpaarige = Knoten ohne Kinder.  
6. **Kategorien:** Jedes Element gehört zu bestimmten Kategorien (z. B. `a` = phrasing/interactive).  
7. **Inhaltstypen:** Paarige Elemente definieren erlaubte Kinder; unpaarige haben keine.  
8. **Verschachtelungsregeln:** Bestimmen, wo jedes Element stehen darf (z. B. `<li>` nur in `<ul>/<ol>`).  
9. **Parsing‑Regeln:** Spezielle Regeln für manche Elemente (z. B. `<table>`, `<script>`, `<style>`).  
10. **Rendering‑Regeln:** Jedes Element hat Standard‑CSS (z. B. `display:block` für `<div>`, `inline` für `<span>`).


# 1. Die zwei Grundformen von HTML‑Elementen

HTML besteht aus nur zwei fundamentalen Elementformen.  
Diese beiden Formen bestimmen alles: Struktur, Inhalt, Verhalten und Parsing.

## 1.1 Paarige Elemente
Syntax:
<element> … </element>

Ein paariges Element:
- besitzt einen Start‑Tag  
- besitzt einen End‑Tag  
- kann Inhalt enthalten  
- bildet einen vollständigen DOM‑Knoten mit Kindern

Beispiele: <div>, <p>, <h1>, <span>, <section>

## 1.2 Unpaarige Elemente
Syntax:
<element>

Ein unpaariges Element:
- besitzt keinen End‑Tag  
- kann keinen Inhalt enthalten  
- ist ein sofort abgeschlossener DOM‑Knoten

Beispiele: <br>, <img>, <meta>, <input>

## Tabelle: Vergleich der beiden Grundformen
| Eigenschaft | Paarig | Unpaarig |
|------------|--------|----------|
| Start‑Tag | ✔ | ✔ |
| End‑Tag | ✔ | ✘ |
| Inhalt möglich | ✔ | ✘ |
| DOM‑Kinder | ✔ | ✘ |
| Parsing‑Verhalten | Stack‑basiert | sofort abgeschlossen |

Diese beiden Formen bilden die Grundlage für alle weiteren Kapitel.


# 2. Die erweiterten Grundformen (mit Attributen)

HTML‑Elemente können Attribute besitzen, die Verhalten, Darstellung oder Bedeutung steuern.

## 2.1 Paarige Elemente mit Attributen
<tag attribut="wert">Inhalt</tag>

Attribute:
- modifizieren das Element  
- definieren Metadaten  
- steuern Verhalten (z. B. onclick)  
- steuern Darstellung (z. B. class, style)

## 2.2 Unpaarige Elemente mit Attributen
<tag attribut="wert">

Attribute sind hier besonders wichtig, weil:
- kein Inhalt existiert  
- alle Informationen im Tag selbst stehen müssen

## Tabelle: Attributverhalten
| Elementtyp | Attribute | Inhalt | Beispiel |
|------------|-----------|--------|----------|
| Paarig | ✔ | ✔ | <p id="x">Hallo</p> |
| Unpaarig | ✔ | ✘ | <img src="bild.png"> |


# 3. Universelle Mechanismen aller HTML‑Elemente

Diese Mechanismen gelten für jedes Element, egal ob paarig oder unpaarig.

## Mechanismen
- **Tagname**: definiert die Rolle  
- **Attribute**: modifizieren Verhalten  
- **Globale Attribute**: überall gültig  
- **Event‑Attribute**: Interaktion  
- **DOM‑Verhalten**: Knotenstruktur  
- **Kategorien**: Flow, Phrasing, Interactive …  
- **Inhaltstypen**: Text, HTML, Phrasing Content …  
- **Parsing‑Regeln**: wie der Browser liest  
- **Verschachtelungsregeln**: was darf wo stehen

## Matrix: Universelle Mechanismen
| Mechanismus | Bedeutung |
|-------------|-----------|
| Tagname | Identität des Elements |
| Attribute | Konfiguration |
| Globale Attribute | universelle Steuerung |
| Events | Interaktion |
| DOM | Struktur |
| Kategorien | semantische Einordnung |
| Inhaltstypen | erlaubte Kinder |
| Verschachtelung | Strukturregeln |
| Parsing | Browserlogik |


# 4. Mechanismen paariger Elemente

Paarige Elemente sind die strukturelle Basis von HTML.

## Eigenschaften
- besitzen Inhalt  
- definieren Container  
- bestimmen Dokumentstruktur  
- erlauben komplexe Verschachtelung

## Beispiele
<div class="box">Text</div>  
<p id="intro">Hallo</p>  
<h1 data-level="1">Titel</h1>

## Tabelle: Eigenschaften paariger Elemente
| Aspekt | Bedeutung |
|--------|-----------|
| Inhalt | Text/HTML möglich |
| DOM | Eltern + Kinder |
| Semantik | Überschrift, Absatz, Abschnitt |
| Rendering | Block/Inline |
| CSS | vollständige Kontrolle |


# 5. Mechanismen unpaariger Elemente

Unpaarige Elemente sind funktionale Einzelknoten.

## Eigenschaften
- kein Inhalt  
- sofort abgeschlossen  
- oft technische Funktion

## Beispiele
<br>  
<img src="bild.png" alt="Beschreibung">  
<meta charset="utf-8">  
<input type="text" placeholder="Name">

## Tabelle: Eigenschaften unpaariger Elemente
| Aspekt | Bedeutung |
|--------|-----------|
| Inhalt | ✘ |
| DOM | Einzelknoten |
| Funktion | Bild, Zeilenumbruch, Meta |
| Parsing | sofort abgeschlossen |


# 6. Universelle Attribute

Diese Attribute gelten für jedes Element.

Liste:
id, class, style, title, lang, dir, hidden, tabindex, accesskey, draggable, contenteditable, spellcheck, data-*

## Beispiele
<div id="box" class="red" data-info="123"></div>  
<br class="spacer">  
<img src="x.png" draggable="false">

## Tabelle: Globale Attribute
| Attribut | Zweck |
|----------|-------|
| id | eindeutige Identifikation |
| class | CSS‑Gruppierung |
| style | Inline‑CSS |
| data-* | eigene Daten |
| hidden | ausblenden |
| draggable | Ziehbar |


# 7. Universelle Event‑Attribute

Diese Attribute binden Verhalten an Ereignisse.

Liste:
onclick, ondblclick, onmouseover, onmouseout, onchange, oninput, onfocus, onblur, onkeydown, onkeyup, onload

## Beispiele
<h1 onclick="alert('Hi')">Titel</h1>  
<input oninput="console.log(this.value)">  
<img src="x.png" onload="init()">

## Tabelle: Event‑Attribute
| Event | Auslöser |
|--------|----------|
| onclick | Klick |
| oninput | Eingabe |
| onload | Laden |
| onfocus | Fokus |
| onkeydown | Taste |


# 8. Universelle Strukturregeln

Diese Regeln bestimmen, wie HTML aufgebaut sein darf.

## Regeln
- jedes Element hat einen Tag‑Namen  
- jedes Element kann Attribute haben  
- jedes Element ist ein DOM‑Knoten  
- jedes Element hat eine Kategorie  
- jedes Element hat erlaubte Eltern  
- jedes Element hat erlaubte Kinder  
- jedes Element hat Standard‑CSS‑Displaywerte

## Tabelle: Strukturregeln
| Regel | Bedeutung |
|--------|-----------|
| Kategorie | Flow/Phrasing |
| Eltern | erlaubte Container |
| Kinder | erlaubte Inhalte |
| Display | Block/Inline |


# 9. Meta‑Ebene der HTML‑Struktur

Diese Ebene beschreibt HTML als System.

## Bestandteile
- Tagname  
- Attribute  
- Globale Attribute  
- Events  
- DOM  
- Kategorien  
- Inhaltstypen  
- Verschachtelung  
- Parsing  
- Rendering

## Diagramm (ASCII)
HTML  
├── Struktur  
├── Mechanik  
├── Attribute  
├── Regeln  
└── Elemente


# 10. Alle HTML‑Elemente

## Paarige Elemente
```
a, abbr, address, article, aside, audio, b, bdi, bdo, blockquote, body, button, canvas, caption, cite, code, colgroup, data, datalist, dd, del, details, dfn, dialog, div, dl, dt, em, fieldset, figcaption, figure, footer, form, h1–h6, head, header, html, i, iframe, ins, kbd, label, legend, li, main, map, mark, menu, meter, nav, noscript, object, ol, optgroup, option, output, p, picture, pre, progress, q, rp, rt, ruby, s, samp, script, section, select, small, span, strong, style, sub, summary, sup, table, tbody, td, template, textarea, tfoot, th, thead, time, title, tr, u, ul, var, video
```
## Unpaarige Elemente
```
area, base, br, col, embed, hr, img, input, link, meta, param, source, track, wbr
```

## Tabelle: Elementtypen
| Typ | Beispiele | Inhalt |
|------|-----------|--------|
| Paarig | div, p, h1 | ✔ |
| Unpaarig | br, img, meta | ✘ |
