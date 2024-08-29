# Einleitung

## Span-Tag:

Ein Span ist ein HTML Element, dass innerhalb anderer Elemente genutzt werden kann um einen Textteil zu selektieren.
Der Span-Tag an sich hat keinerlei Auswirkungen und eignet sich daher gut um spezielle Textstellen hervorzuheben.

### Beispiel Span:

```html
<p>Das ist ein <span style="color:red">Beispiel</span>!</p>
```

<p>Das ist ein <span style="color:red">Beispiel</span>!</p>
<hr>

## Div-Tag:

Ein Div ist ein Block-Element (siehe README-HTML.md). Dieser Container kann andere Elemente beinhalten um diese zu Gruppieren. Stell dir einen Container einfach wie eine Box vor, die mehrere Elemente beinhalten können.

### Beispiel:

```html
<div style="background-color: #ccc; color: red;">
  <h2>Willkommen im BigBrother Container</h2>
  <p>Ich bin ein Teil dieses Divs</p>
  <p>Egal wo ihr hingeht, ich folge euch!</p>
</div>
```

<div style="background-color: #ccc; color: red;">
  <h2>Willkommen im BigBrother Container</h2>
  <p>Ich bin ein Teil dieses Divs</p>
  <p>Egal wo ihr hingeht, ich folge euch!</p>
</div>

## Padding und Margin:

Margin und Padding sind grob gesagt Angaben für Abstände. Padding verwendet man für innere Abstände während Margin für Äußere Abstände verwendet wird.
Das Bedeutet, dass Padding den Abstand zwischen dem Inhalt und dem Rand eures Elementes bestimmt, während Margin den Abstand zwischen den einzelnen Elementen bestimmt.

### Beispiel Margin:

```html
<div style="border: solid red; margin-bottom: 30px">
  <p>Mein Text</p>
</div>
<div style="border: solid blue;">
  <p>Mein Text</p>
</div>
```

<div style="border: solid red;  margin-bottom: 30px">
    <p style="border: solid 1px #ccc">Mein Text</p>
</div>
<div style="border: solid blue; padding-top: 10px;">
    <p style="border: solid 1px #ccc">Mein Text</p>
</div>

[margin](https://www.w3schools.com/css/css_margin.asp)

### Beispiel Padding:

```html
<div style="border: solid red; padding-bottom: 30px">
  <p>Mein Text</p>
</div>
<div style="border: solid blue;">
  <p>Mein Text</p>
</div>
```

<div style="border: solid red;  padding-bottom: 30px">
    <p style="border: solid 1px #ccc">Mein Text</p>
</div>
<div style="border: solid blue;">
    <p style="border: solid 1px #ccc">Mein Text</p>
</div>

[padding](https://www.w3schools.com/css/css_padding.asp)

## Aufgaben

1. Erstelle 2 `div` Container mit `Lorem` Text.
2. Gebe dem `div` eine `border` von `2px` in schwarz.
3. Versuche nun den Text mit Padding zu zentrieren
4. Sorge nun dafür, dass zwischen den beiden div Containern 10px Abstand (`margin`) ist.
5. Versuche Aufgabe 4 mit nur einem Befehl umzusetzen, siehe dazu in die Dokumentation (Link in Beispiel Margin)
