# MindTheGap: A Jornada do Estudante Global

> **Unidade Curricular:** Gamificação e Narrativas Interativas e Desenvolvimento Web Front | TDW (ESMAD)
> **Tema Selecionado:** Percurso Académico e Saúde Mental[span_0](start_span)[span_0](end_span)  
> **Estado Atual:** Fase 1 Concluída (Game Design Document & Arquitetura de Conceito)

---

## 📌 Visão Geral do Projeto

O **MindTheGap** é uma experiência web pedagógica, lúdica e sustentável desenvolvida para simular o desafio de gerir o sucesso académico, a saúde mental e o suporte social no ensino superior contemporâneo[span_1](start_span)[span_1](end_span). 

A aplicação coloca o utilizador no papel de um estudante que precisa de equilibrar prazos críticos de trabalhos, projetos de grupo e a vida profissional ao longo de um semestre, enfrentando dilemas diários que impactam diretamente a sua energia e resiliência psicológica[span_2](start_span)[span_2](end_span).

---

## 🎯 Objetivos do Sistema

O projeto foca-se em três pilares pedagógicos fundamentais:
* **Promover o Equilíbrio:** Evitar ciclos de exaustão e *burnout* causados pela exigência extrema de produtividade académica[span_3](start_span)[span_3](end_span).
* **Literacia de Gestão de Tempo:** Ensinar a balancear o estudo individual com o trabalho colaborativo e o descanso estratégico[span_4](start_span)[span_4](end_span).
* **Consciencialização:** Demonstrar que ações isoladas (como ignorar prazos ou negligenciar o descanso) geram consequências severas a médio e longo prazo[span_5](start_span)[span_5](end_span).

---

## 👥 Personas e Públicos-Alvo

O sistema foi desenhado para diferentes perfis de jogadores/utilizadores[span_6](start_span)[span_6](end_span):
* **Ana (A Perfecionista Exausta - *Achiever / Player*):** Focada em maximizar o desempenho académico, obter notas máximas e desbloquear insígnias rapidamente[span_7](start_span)[span_7](end_span).
* **Lucas (O Trabalhador Full-Time / Sobrecarregado - *Free Spirit / Philanthropist*):** Focado em gerir a autonomia, equilibrar a vida profissional/pessoal com os estudos e apoiar a rede colaborativa[span_8](start_span)[span_8](end_span).

---

## 🎮 Mecânicas e Dinâmicas (Framework 6D)

A experiência utiliza mecânicas inspiradas na Teoria da Autodeterminação (SDT) para manter o envolvimento[span_9](start_span)[span_9](end_span):
* **Autonomia:** Liberdade total para escolher abordagens de estudo, colaboração ou pausas[span_10](start_span)[span_10](end_span).
* **Competência:** Feedback quantitativo em tempo real através de barras de progresso (Desempenho e Saúde Mental)[span_11](start_span)[span_11](end_span).
* **Relacionamento:** Impacto das decisões de entreajuda com os colegas de grupo[span_12](start_span)[span_12](end_span).
* **Efeito de "Névoa Mental":** Mecânica de alerta visual ativada automaticamente quando a saúde mental do estudante desce abaixo de um nível crítico[span_13](start_span)[span_13](end_span)[span_14](start_span)[span_14](end_span).

---

## 🛠️ Arquitetura Técnica Planeada (Fase 2)

Embora esta primeira entrega foque o planeamento estratégico e o GDD, a arquitetura técnica já se encontra definida para a implementação em **Vue.js** e **Pinia**:
* **Store Global (Pinia):** Gestão de variáveis de estado como `desempenhoAcademico`, `saudeMental`, `unlockedBadges` e estados de alerta (`mentalFogActive`)[span_15](start_span)[span_15](end_span).
* **Camada Narrativa:** Consumo dinâmico de árvores de decisão estruturadas em formato JSON[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span).

---

## 📁 Documentação e Links

* **Game Design Document (GDD - Parte 1):** Disponível no repositório (`docs/GDD_MindTheGap_Entrega01.pdf`).
* **Quadro de Organização:** Gerenciado via Notion (https://app.notion.com/p/alicealfredo/MindTheGap-3f4077f67258807b8499f96b3204d3f9).
