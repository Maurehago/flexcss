# Zeilen und Spalten

Spalten ohne Breitenangabe passen sich an die Länge vom Text an

<f-row>
    <f-item color-s><p>Spalte 1</p></f-item>
    <f-item color-s2><p>Spalte 2</p></f-item>
    <f-item color-s><p>Spalte 3</p></f-item>
</f-row>

```html
<f-row>
    <f-item><p>Spalte 1</p></f-item>
    <f-item><p>Spalte 2</p></f-item>
    <f-item><p>Spalte 3</p></f-item>
</f-row>
```

## w-fit
Mit **w-fit** Passt sich eine Spalte an die verbleibende Breite an.

<f-row>
    <f-item color-s><p>Spalte 1</p></f-item>
    <f-item w-fit color-s2><p>Spalte 2</p></f-item>
    <f-item color-s><p>Spalte 3</p></f-item>
</f-row>

```html
<f-row>
    <f-item><p>Spalte 1</p></f-item>
    <f-item w-fit><p>Spalte 2</p></f-item>
    <f-item><p>Spalte 3</p></f-item>
</f-row>
```

Wird **w-fit** bei allen Spalten angegeben, so teilen sich diese den vorhandenen Platz auf. [ pa-t]

<f-row>
    <f-item w-fit color-s><p>Spalte 1</p></f-item>
    <f-item w-fit color-s2><p>Spalte 2</p></f-item>
    <f-item w-fit color-s><p>Spalte 3</p></f-item>
</f-row>

```html
<f-row>
    <f-item w-fit><p>Spalte 1</p></f-item>
    <f-item w-fit><p>Spalte 2</p></f-item>
    <f-item w-fit><p>Spalte 3</p></f-item>
</f-row>
```
