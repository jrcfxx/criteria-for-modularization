# Critérios para Modularização de Software

Este repositório reúne materiais de estudo sobre modularização de sistemas, com foco no artigo clássico de David L. Parnas, **"On the Criteria To Be Used in Decomposing Systems into Modules" (1972)**.

A ideia central é estudar por que **modularização não deve ser feita apenas pelo fluxo de processamento**, mas sim pelo princípio de **ocultação de informação** (*information hiding*): cada módulo deve esconder decisões de projeto que podem mudar no futuro.

---

## Objetivo deste repositório

Este espaço foi organizado para apoiar estudos acadêmicos em Engenharia de Software, principalmente para:

- compreender os fundamentos de modularização;
- relacionar teoria clássica com práticas modernas;
- desenvolver leitura crítica de artigos técnicos;
- servir de base para resenhas, seminários e discussões em sala.

---

## Materiais disponíveis neste repositório

- `Criteria-for-Modularization.pdf`  
  Artigo original de D. L. Parnas (texto-base do estudo).

- `ResenhaCrítica-Parnas.pdf`  
  Resenha crítica em português, com análise contextual e discussão de limitações.

---

## Assunto em foco: modularização com critério

No artigo, Parnas compara duas formas de decompor um sistema:

- uma decomposição tradicional, orientada por etapas do processamento;
- uma decomposição orientada por decisões de projeto que devem ficar encapsuladas.

O argumento principal é que a segunda abordagem tende a melhorar:

- **manutenibilidade** (mudanças com impacto localizado);
- **compreensão** do sistema;
- **desenvolvimento independente** entre partes do software.

Ao mesmo tempo, o autor também alerta para **trade-offs de eficiência**, mostrando que boas fronteiras de módulo precisam ser acompanhadas de implementação adequada.

---

## Conceitos-chave para revisar

- modularidade;
- acoplamento e coesão;
- encapsulamento e interface;
- custo de mudança;
- responsabilidade por módulo;
- trade-offs entre flexibilidade e desempenho.

---

## Materiais complementares recomendados

Para aprofundar além do artigo do Parnas:

- **Code Complete** (Steve McConnell) - qualidade de design e organização de código;
- **Clean Architecture** (Robert C. Martin) - fronteiras arquiteturais e independência de camadas;
- **Designing Data-Intensive Applications** (Martin Kleppmann) - trade-offs reais em sistemas modernos;
- conteúdos sobre **Domain-Driven Design** e **arquitetura hexagonal** para expandir a discussão de limites de módulos.

---

## Perguntas-guia para leitura crítica

Use estas perguntas ao estudar o artigo:

- O exemplo KWIC é suficiente para generalizar as conclusões?
- Quais decisões de projeto estão realmente “escondidas” em cada decomposição?
- Como o princípio de Parnas se comporta em sistemas distribuídos modernos?
- Quais custos surgem quando modularizamos demais?
- O texto é conceitualmente forte, mas onde faltam evidências empíricas?