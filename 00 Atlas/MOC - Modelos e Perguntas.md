---
tags:
  - universo-organismo
  - universo-organismo/moc
tipo: moc
escala: mapa
estado: vivo
---

# MOC - Modelos e Perguntas

Parent:: [[Atlas - Universo como Organismo]]
Children:: [[Axiomas da Hipótese]], [[Arquitetura de Escalas]], [[Tabela de Correspondências]], [[Glossário Universo-Organismo]], [[Limites Científicos]], [[Experimentos de Pensamento]], [[Perguntas Abertas]], [[Diário de Investigação]]
Friends:: [[MOC - Conceitos]], [[MOC - Analogias]]

## Modelo

- [[Axiomas da Hipótese]]
- [[Arquitetura de Escalas]]
- [[Tabela de Correspondências]]
- [[Glossário Universo-Organismo]]

## Investigação

- [[Limites Científicos]]
- [[Experimentos de Pensamento]]
- [[Perguntas Abertas]]
- [[Diário de Investigação]]

## Consulta

```dataview
TABLE tipo, estado
FROM #universo-organismo
WHERE contains(file.folder, "Modelos") OR contains(file.folder, "Perguntas")
SORT file.name ASC
```
