# Inspeção do NFR Framework

A verificação do [NFR Framework](https://github.com/Marcosatc147/req2024.1-Moovit/blob/main/docs/Modelagem/NFR-Framework.md) foi realizada por meio de uma inspeção detalhada utilizando o método de checklist. A inspeção seguiu critérios específicos para avaliar a clareza, consistência e viabilidade das abstrações e relações representadas no Softgoal Interdependency Graph (SIG). A seguir, é apresentado o checklist utilizado, uma tabela de avaliação dos diagramas inspecionados e uma lista dos principais problemas encontrados durante a análise.

---

## Checklist para Verificação dos Diagramas

1. Os softgoals estão nomeados de maneira clara e adequada?  
2. Os softgoals estão diretamente vinculados aos critérios de qualidade relevantes?  
3. As operacionalizações estão corretamente definidas e descrevem de forma clara como os softgoals serão implementados?  
4. As operacionalizações possuem impactos mensuráveis e podem ser implementadas de forma prática para atingir os softgoals?  
5. As argumentações justificam ou explicam decisões importantes?  
6. As classificações ('help', 'hurt', 'make', 'break') estão corretamente aplicadas para descrever as contribuições?  
7. As escolhas de contribuições ou operacionalizações são justificadas de forma explícita e lógica?  
8. As notações e símbolos utilizados no diagrama estão consistentes e de acordo com as convenções do SIG?  
9. O impacto de cada operacionalização está claramente representado, mostrando como contribui para os softgoals?  
10. Existe uma representação clara de como os requisitos funcionais impactam ou são impactados pelos softgoals?

---

## Tabela de Avaliação
Nesta tabela, um X indica que o diagrama atendeu completamente ao critério correspondente, enquanto um espaço em branco indica que o critério não foi atendido ou não foi adequadamente abordado.

| Diagrama | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| :---- | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: | :----: |
| [NFR001](https://github.com/Marcosatc147/req2024.1-Moovit/blob/main/docs/assets/NFR/NFR%20MoovitV1.png) | X | X |  |  |  | X |  | X |  |  |
| [NFR002](https://github.com/Marcosatc147/req2024.1-Moovit/blob/main/docs/assets/NFR/NFR%20%20MoovitV1-2.png) | X | X | X |  |  | X |  | X |  |  |
| [NFR003](https://github.com/Marcosatc147/req2024.1-Moovit/blob/main/docs/assets/NFR/NFR%20MoovitV2.jpg) | X | X | X | X |  | X |  | X |  |  |
| [NFR004](https://github.com/Marcosatc147/req2024.1-Moovit/blob/main/docs/assets/NFR/NFR%20MoovitV3.jpg) | X | X | X | X |  | X | X | X | X |  |

---

## Problemas Encontrados

- Algumas operacionalizações não estão claramente definidas, faltando mais informações sobre como elas serão implementadas para atingir os softgoals.
- A avaliação prática do impacto das operacionalizações nos softgoals é dificultada pela falta de clareza sobre como esse impacto será medido.
- Não há uma representação clara de como os requisitos funcionais impactam ou são impactados pelos softgoals, o que compromete a análise de interdependências.

| Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito) e [Marcos Castilhos](https://github.com/Marcosatc147)|1ª   |08/09/2024|