---
tags:
  - universo-organismo
  - universo-organismo/painel
tipo: painel
escala: meta
estado: vivo
---

# Painel Dataview - Hipótese Universo-Organismo

Parent:: [[Atlas - Universo como Organismo]]
Friends:: [[MOC - Conceitos]], [[MOC - Analogias]], [[MOC - Modelos e Perguntas]]

## Todas as notas da hipótese

```dataview
TABLE tipo, escala, estado
FROM #universo-organismo
SORT tipo ASC, file.name ASC
```

## Conceitos

```dataview
TABLE escala, estado
FROM #universo-organismo/conceito
SORT file.name ASC
```

## Analogias

```dataview
TABLE estado
FROM #universo-organismo/analogia
SORT file.name ASC
```

## Pontos que pedem desenvolvimento

```dataview
LIST
FROM #universo-organismo
WHERE estado = "rascunho" OR estado = "expandir"
SORT file.name ASC
```
