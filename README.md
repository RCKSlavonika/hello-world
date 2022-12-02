# Git u nastavi

Na konferenciji u Splitu održano je predavanje i radionica na temu Git-a u nastavi. 

## Učenici vole Git

Kako natjerati učenike da koriste Git?

## Dijgrami u Markdownu

Jednostavan primjer dijagrama: 

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

Prvi primjer "cjevovoda": 

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
