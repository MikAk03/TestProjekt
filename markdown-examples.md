
# Markdown-Erweiterungsbeispiele

Diese Seite demonstriert einige der integrierten Markdown-Erweiterungen, die von VitePress bereitgestellt werden.

## Syntax-Hervorhebung

VitePress bietet Syntax-Hervorhebung mit [Shiki](https://github.com/shikijs/shiki), einschließlich zusätzlicher Funktionen wie Zeilenhervorhebung:

**Eingabe**

````
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**Ausgabe**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

## Benutzerdefinierte Container

**Eingabe**

```md
::: info
Das ist eine Infobox.
:::

::: tip
Das ist ein Tipp.
:::

::: warning
Das ist eine Warnung.
:::

::: danger
Das ist eine gefährliche Warnung.
:::

::: details
Das ist ein Detailblock.
:::
```

**Ausgabe**

::: info
Das ist eine Infobox.
:::

::: tip
Das ist ein Tipp.
:::

::: warning
Das ist eine Warnung.
:::

::: danger
Das ist eine gefährliche Warnung.
:::

::: details
Das ist ein Detailblock.
:::

## Diagramme

VitePress unterstützt auch die Einbindung von Diagrammen mit [Mermaid](https://mermaid-js.github.io/mermaid/).

**Eingabe**

````
```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```
````

**Ausgabe**

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```

## Task-Listen

Markdown unterstützt auch Task-Listen, die nützlich für To-Do-Listen und Aufgabenverfolgung sind.

**Eingabe**

```md
- [x] Aufgabe 1
- [ ] Aufgabe 2
- [ ] Aufgabe 3
```

**Ausgabe**

- [x] Aufgabe 1
- [ ] Aufgabe 2
- [ ] Aufgabe 3

## Emojis

Emojis können einfach in Markdown-Dokumente eingefügt werden, um sie lebendiger zu gestalten.

**Eingabe**

```md
Hier sind einige Emojis: 🎉 🚀 🌟
```

**Ausgabe**

Hier sind einige Emojis: 🎉 🚀 🌟

## Tabellen

Markdown unterstützt auch Tabellen, die nützlich sind, um Daten in einem strukturierten Format darzustellen.

**Eingabe**

```md
| Name     | Alter | Beruf       |
|----------|-------|-------------|
| Alice    | 30    | Ingenieurin |
| Bob      | 25    | Designer    |
| Charlie  | 35    | Lehrer      |
```

**Ausgabe**

| Name     | Alter | Beruf       |
|----------|-------|-------------|
| Alice    | 30    | Ingenieurin |
| Bob      | 25    | Designer    |
| Charlie  | 35    | Lehrer      |

## Mehr

Schauen Sie sich die Dokumentation für die [vollständige Liste der Markdown-Erweiterungen](https://vitepress.dev/guide/markdown) an.
