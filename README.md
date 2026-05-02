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
