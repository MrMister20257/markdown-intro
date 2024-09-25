# Cheat Sheet für Markdown
---
<br>

# Überschriften

| Befehl | Effekt|
|--------|-------|
|`#`     | <h1> Überschrift H1 </h1> |
|`##`     | <h2> Überschrift H2 </h2> |
|`###`     | <h3> Überschrift H3 </h3> |
|`####`     | <h4> Überschrift H4 </h4> |
|`#####`     | <h5> Überschrift H5 </h5> |
|`######`     | <h6> Überschrift H6 </h6> |

---
<br>

# Text-Formatierung


| Befehl | Effekt|
|--------|-------|
|`**TEXT**` | **TEXT** |
|`*TEXT*`   | *TEXT* |
|`~~TEXT~~` | ~~TEXT~~  |

---
<br>

# Listen

<table>
  <tr>
    <th>Sortierte Liste</th>
    <th>Effekt</th>
  </tr>
  <tr>
    <td>
        <code>1.</code><br>
        <code>2.</code><br>
        <code>3.</code><br>
    </td>
    <td>1. TEXT<br>
                    2. TEXT<br>
                    3. TEXT</td>
  </tr>
</table>
<table>
  <tr>
     <th>Unsortierte Liste</th>
     <th>Effekt</th>
  </tr>
  <tr>
    <td>       
        <code>-</code><br>
        <code>-</code><br>
        <code>-</code><br>
    </td>
    <td>
        <li> TEXT
        <li> TEXT
        <li> TEXT
    </td>
  </tr>
</table>

---
<br>

# Links

| Befehl | Effekt|
|--------|-------|
|`[LINKNAME](LINKADRESSE)` | [Google](https://google.de/) |
|`![Alternativer Text](Bildlink)`   | ![ALternativer Text](/google.png) |

---
<br>

# Tabellen


<table>
  <tr>
    <th>Befehl</th>
    <th>Effekt</th>
  </tr>
  <tr>
    <td>
        <code>| Spalte A | Spalte B |</code><br>
        <code>|----------|----------|</code><br>
        <code>| Zeile 1  | Zeile 2  |</code><br>
    </td>
    <td>
        <table>
            <tr>
                <th>Spalte A</th>
                <th>Spalte B</th>
            </tr>
            <tr>
                <th>Zeile 1</th>
                <th>Zeile 2</th>
        </table>
    </td>
  </tr>
</table>

---
<br>

# ToDo-Listen

- [x] = `- [x]`
- [ ] = `- [ ]` 
